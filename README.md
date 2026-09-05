# Manoj K — Portfolio

Single-file static site (`index.html`), no build step, no dependencies beyond two Google Fonts.

## Host it on GitHub Pages

1. Create a new repo — name it exactly `Manojk0302.github.io` if you want it at the root domain (`https://manojk0302.github.io`), or any name if you're fine with a project URL (`https://manojk0302.github.io/repo-name`).
2. Put `index.html` and `Manoj_K_Resume.pdf` in the repo root and push:
   ```
   git init
   git add index.html Manoj_K_Resume.pdf README.md
   git commit -m "Portfolio site"
   git branch -M main
   git remote add origin https://github.com/Manojk0302/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Source → Deploy from a branch → main / (root)** → Save.
4. Your site goes live at the URL GitHub shows on that same Pages settings screen (usually within a minute).

## Editing later

- All content is plain HTML in `index.html` — projects are under `<!-- SHEET 02 — SYSTEMS / PROJECTS -->`, the skills table under `SHEET 03`, and so on.
- Keep `Manoj_K_Resume.pdf` filename as-is (or update the link in the hero section if you rename it).
- Swap the GitHub link/handle across the file if it ever changes.
