# Nana Adu‑Abankro — Portfolio

This repo is ready for GitHub Pages. It includes:

- `index.html` (single-file React + Tailwind portfolio)
- `files/resume.pdf` (replace with your actual resume)
- `files/10.5-matplotlib.ipynb` (replace with your notebook)
- `.nojekyll`

## Quick edit
Open `index.html` and update these fields at the top of the file:
```js
PROFILE.links.linkedin = "https://www.linkedin.com/in/...";
PROFILE.links.github   = "https://github.com/...";
PROFILE.links.kaggle   = "https://kaggle.com/...";
PROFILE.links.resume   = "files/resume.pdf";
PROFILE.tableauViewsUrl = "YOUR_TABLEAU_VIEWS_URL";
PROFILE.tableauOpenUrl  = "YOUR_TABLEAU_OPEN_URL";
```
You can also change the notebook paths in `PROFILE.notebook` if needed.

## Local preview
- VS Code + Live Server → Go Live
- Or: `python -m http.server 5500` then open http://localhost:5500

## Deploy to GitHub Pages
1. Create a new repo (e.g., `portfolio`).
2. Upload the contents of this folder (or push via Git).
3. In GitHub → **Settings → Pages**:
   - **Source:** Deploy from a branch
   - **Branch:** main (or master) / root
4. Wait 1–2 minutes for the site to appear.

Generated 2025-08-12.
