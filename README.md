# Canoply Template (Static Mirror)

This repository contains a static, offline mirror of the Webflow site “Canoply.” It was downloaded for local viewing/testing so you can browse the pages and assets without relying on the live site.

## Structure
- site/ — All mirrored files (HTML, CSS, JS, images, fonts). The entry page is:
  - site/canoply-template.webflow.io/index.html

## Run locally
You can serve the site locally to avoid browser restrictions on file URLs.

- With Python (Windows PowerShell):
  1. python -m http.server 5500 --directory "site"
  2. Open http://localhost:5500/canoply-template.webflow.io/index.html

## Notes
- This is an offline/static copy; forms and other dynamic features may not function locally.
- Asset paths were rewritten during mirroring; JS and CSS are stored under site/cdn.prod.website-files.com and other vendor folders.
- Content belongs to the original owner. Use this mirror for personal/testing purposes unless you have rights to reuse the content.

## Deploy (optional)
You can host the static copy via GitHub Pages:
1. Push to the main branch (already done).
2. In the repository settings, enable Pages for the main branch (root).
3. Visit the Pages URL and navigate to /site/canoply-template.webflow.io/index.html.

## License
This repository only contains a mirrored website for local testing. No license for the mirrored content is implied. Respect the original author’s terms.
