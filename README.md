# GitHub Pages — Ready-to-Publish Starter

This repo is pre-wired to deploy from **main** using GitHub Actions.

## 30‑second setup

1. Create a **public** repo on GitHub (any name).  
2. Upload these files (or `git push` the folder).  
3. Go to **Settings → Pages** and ensure the source is **GitHub Actions** (it auto-detects from this workflow).  
4. Push changes to `main` → the Action runs → your public URL appears in the workflow summary.

## How to use

- Replace `index.html` with your app.  
- Keep `404.html` if you're building a single‑page app (React/Vite/Vanilla router) so deep links work.  
- Every push to `main` redeploys.

## Want a Vite/React build instead?

- Swap this workflow for a build one that runs `npm ci && npm run build` and uploads `dist/`.
- In Vite project sites (not username.github.io root), set `base: '/<repo>/'` in `vite.config`.

