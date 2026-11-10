# SARUR website

Minimal, static SARUR page: one in-engine character image, title and short description. No generated promotional illustrations, decorative effects, JavaScript, analytics, cookies, trackers, web fonts or build step.

Live site: https://ibackstrom.github.io/sarur/

Serve locally with `python -m http.server 8087`. Edit index.html and style.css directly. The sole displayed image preserves its 16:9 source proportions using width: 100% and height: auto; there is no fixed-height container, crop or horizontal expansion.

Image source: `SARURPackage/Graphics/Gameplay/SARUR_Hero_Original_2560x1440.png`. The web version is a proportional 1920 × 1080 export of this in-engine reference, not a claim of the current gameplay camera. Social preview is a centered crop of the same source, never a nonuniform resize.

GitHub Pages serves the main branch, repository root. There is deliberately no Steam button, release date or newsletter form until real links/services exist. Update title, description and social metadata together if the URL changes.

Never commit tokens. Authentication uses GH_TOKEN loaded from an external local file for deployment only; no credential belongs in this repository. The site repository contains website files only, not Unreal project or private store working files.
