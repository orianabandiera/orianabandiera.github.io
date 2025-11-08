# GitHub Pages quick start

This repo is ready to serve a single-page site from the repository root.

## Deploy
1. Create a new repo on GitHub, e.g. `username/username.github.io` **or** any repo name.
2. Upload the files in this zip to the repo root.
3. In **Settings → Pages**, set:
   - Source: **Deploy from a branch**
   - Branch: **main** / **root**
4. Your site will be live at:
   - `https://username.github.io` (if the repo is `username.github.io`), or
   - `https://username.github.io/reponame` (for any other repo).

## Add your assets
- Replace `headshot.jpg` with your own image (same filename).
- Replace `cv.pdf` with your CV (same filename).

## Optional
- To avoid Jekyll processing, `.nojekyll` is included.
- For a custom domain, add a `CNAME` file with your domain (e.g., `www.example.org`) and point DNS to GitHub Pages.
