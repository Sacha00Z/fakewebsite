# fakewebsite

[![Live demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue)](https://sacha00z.github.io/fakewebsite/) [![License](https://img.shields.io/github/license/sacha00z/fakewebsite)](LICENSE) [![Last commit](https://img.shields.io/github/last-commit/sacha00z/fakewebsite)](https://github.com/sacha00z/fakewebsite/commits/main) [![Open issues](https://img.shields.io/github/issues/sacha00z/fakewebsite)](https://github.com/sacha00z/fakewebsite/issues)

Tiny static demo site that hosts links to external resources, such as iForms. As an initial implementation, it contains one link, but the intention is to create a series of "Cards" that link to different business scenarios.

## Quick start
- Just navigate to [https://sacha00z.github.io/fakewebsite/](https://sacha00z.github.io/fakewebsite/)

## Testing Changes Locally
- Requirements: `python3` (for a local preview), a browser, and Git.
- Serve locally (from the repo root):

```bash
python3 -m http.server 8000
# open http://localhost:8000 in your browser
```

The site is purely static: edit `index.html`, `style.css`, and images in the `images/` folder.

## Developing in VS Code

- Open the project folder in VS Code: `File → Open Folder...` and choose this repo.
- Recommended extensions: *Prettier* (formatting), *EditorConfig*, and *Live Server* (optional quick preview).
- Use the built-in Terminal (`View → Terminal`) to run the quick-start server above.
- Git in VS Code: use the Source Control pane to stage, commit, and push changes.

Helpful VS Code workflow:

1. Create a feature branch: `git checkout -b feature/short-description`
2. Make small, focused commits.
3. Push: `git push -u origin feature/short-description`
4. Open a Pull Request on GitHub and request a review.

## GitHub / Contribution guidelines

- Branch naming: `feature/*`, `fix/*`, or `chore/*`.
- Keep changes small and include a short descriptive commit message.
- Use relative image paths (place images into the `images/` folder).
- When adding new markup or styles, try to keep styles scoped to `style.css` and follow the existing simple patterns.

## Project structure

- `index.html` — main page
- `style.css` — site styles
- `images/` — static images used by the page
- `LICENSE` — project license

## Notes

- This repo intentionally has no build system. If you want to introduce one (tooling, bundlers, or generators for image galleries), open an issue first so we can agree on scope.


