# SARUR website

Static, responsive promotional site for SARUR. No JavaScript, analytics, cookies, trackers or build step. All assets and fonts are local. Illustrative artwork is AI-assisted and labeled as artwork, not gameplay screenshots.

Live site: https://ibackstrom.github.io/sarur/

Serve locally with `python -m http.server 8087`. Edit index.html and style.css directly. Assets are optimized WebP plus transparent PNG branding and self-hosted fonts. Preserve font licenses under assets.

GitHub Pages serves the main branch, repository root. There is deliberately no Steam button, release date or newsletter form until real links/services exist. Update title, description and social metadata together if the URL changes.

Never commit tokens. Authentication uses GH_TOKEN loaded from an external local file for deployment only; no credential belongs in this repository. The site repository contains website files only, not Unreal project or private store working files.
