# spellzlol.github.io

Static documentation site for internal guides.

## Published URLs

| Page | URL |
|------|-----|
| Docs index | https://spellzlol.github.io/docs/ |
| Barks System guide | https://spellzlol.github.io/docs/barks-system-guide.html |

## Adding a page

1. Add a self-contained `.html` file under `docs/`.
2. Link it from `docs/index.html`.
3. Commit and push to `main`.

## GitHub Pages setup

This repo is a user site (`spellzlol.github.io`). Pages must deploy from the **repository root**, not the `/docs` folder setting in GitHub.

1. Open [repository Settings → Pages](https://github.com/Spellzlol/spellzlol.github.io/settings/pages).
2. **Build and deployment → Source:** Deploy from a branch.
3. **Branch:** `main` / **`/ (root)`** (not `/docs`).
4. Save. The site is usually live within 1–2 minutes.

Files in the repo's `docs/` folder are served at `https://spellzlol.github.io/docs/...`.

## Local preview

Open any file directly in a browser, or serve the repo root:

```powershell
python -m http.server 8080
```

Then visit http://localhost:8080/docs/barks-system-guide.html
