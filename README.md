# StoicFocus Landing Page

Static landing page for StoicFocus.

## Live site (GitHub Pages)

1. Make the repo public on GitHub.
2. In the repo: **Settings → Pages**.
3. **Source**: Deploy from a branch.
4. **Branch**: `main` (or `master`) / **Folder**: `/ (root)`.
5. Save. The site will be published at `https://<your-username>.github.io/<repo-name>/`.

## Local preview

```bash
npm install
npm run dev
```

Then open `http://localhost:3030`.

## Structure

- `index.html` — main page
- `styles.css` — styles
- `assets/` — images and other static files

## Notes

- This is a static site. No build step is required for GitHub Pages.
- `node_modules/` is ignored; install deps locally for the preview server.
