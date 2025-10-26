# Probability Shootout — GitHub Pages
How to publish:
1) Create a new repo (or open the current one).
2) Upload **index.html** and **.nojekyll** to the root (top level) of the repo.
3) Go to **Settings → Pages** → Source: `Deploy from a branch` → Branch: `main` and Folder: `/ (root)` → Save.
4) Open your site at: `https://<your-username>.github.io/<repo-name>/`

Troubleshooting:
- If you see Markdown like `## Game Board` (and the game doesn't run), it means Jekyll processed your page. Make sure the `.nojekyll` file is present at the root and that your file is named exactly **index.html** (not `index.md`, not in a subfolder).
- Avoid themes or README-only publishing for this repo.
