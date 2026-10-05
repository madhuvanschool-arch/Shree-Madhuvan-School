# Shree Madhuvan School Website

Static website (plain HTML/CSS/JS, no build step).

## Files
- `index.html` – the whole website
- `assets/img/` – all images (photos, logo, icons)
- `404.html` – not-found page
- `_headers` – Cloudflare Pages caching and security headers
- `robots.txt`, `.nojekyll`, `.gitignore`

## Deploy on Cloudflare Pages (via GitHub)
1. Push this folder to a GitHub repository (root of the repo = these files).
2. Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git.
3. Select the repository. Framework preset: **None**. Build command: *(leave empty)*. Build output directory: `/`.
4. Save and Deploy. Add your custom domain under the project's Custom domains tab.

## Deploy on GitHub Pages (optional)
Repo → Settings → Pages → Source: Deploy from branch → `main` / root.

## Updating
Edit files, commit and push. Cloudflare redeploys automatically.
