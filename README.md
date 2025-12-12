# Accomplishment Cake (NYAP Colors) — GitHub Pages

This folder is ready to deploy to **GitHub Pages** as a static site.

## Quick Deploy (Web UI)
1. Create a new **public** repository (e.g., `accomplishment-cake`).
2. Upload all files from this folder to the repository **root**.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
5. Set **Branch** to `main` and **Folder** to `/root`.
6. Click **Save** — GitHub will publish your site at:
   `https://<your-username>.github.io/accomplishment-cake/`

## Deploy via Git (CLI)
```bash
mkdir accomplishment-cake && cd accomplishment-cake
# Copy site contents here
git init
git add .
git commit -m "Accomplishment Cake initial publish"
git branch -M main
# Replace USER/REPO
git remote add origin https://github.com/USER/accomplishment-cake.git
git push -u origin main
```

Enable Pages: **Settings → Pages → Source: Deploy from a branch** (main / root).

## Notes
- NYAP colors are set under `:root` in `index.html`.
- No logo is used; header shows only the title.
- Features: add notes, click to celebrate (sound + confetti), drag to reposition, export/import JSON.
