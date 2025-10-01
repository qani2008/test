# Demiri Builder Ltd — Static Site

This is a single-page static website ready for GitHub Pages.

## How to publish on GitHub Pages

1. Create a new repo on GitHub, e.g. `demiribuilder.github.io` (recommended for a user/org site), or any repo name for a project site.
2. Upload all files from this folder to the root of that repo.
3. Enable Pages:
   - Go to **Settings → Pages**.
   - **Source**: select `Deploy from a branch`.
   - **Branch**: choose `main` (or `master`) and `/ (root)`.
4. Wait ~1 minute and visit the URL shown in the Pages panel.
   - If the repo is `demiribuilder.github.io`, your site will be live at `https://demiribuilder.github.io/`.
5. (Optional) Add a custom domain later via **Settings → Pages** and create DNS `A`/`ALIAS`/`CNAME` records with your domain provider.

## Editing contact email
In `index.html`, the contact form uses a `mailto:` link. Replace `info@demiribuilder.co.uk` with your real inbox if needed.

## Files
- `index.html` — main site (HTML, inline CSS and JS)
- `404.html` — friendly not-found page
- `robots.txt`, `sitemap.xml` — basic SEO files
- `.nojekyll` — disables Jekyll processing on Pages
- `assets/*` — favicon, logo, and social preview image

## License
MIT — see `LICENSE`.
