# SARUR website

Royal, minimalist SARUR landing page: full-screen in-engine background, authentic gold wordmark and fine framing, short premise, two real gameplay clips and collapsible estimated PC requirements. No generated promotional illustrations, JavaScript, analytics, cookies, trackers, web fonts or build step. The full About This Game description belongs to the documentation pack, not this site.

Live site: https://ibackstrom.github.io/sarur/

Serve locally with `python -m http.server 8087`. Edit index.html and style.css directly. The full-screen background uses object-fit: cover: it crops proportionally, never stretches. Logos retain intrinsic proportions; videos stay 16:9. Videos have native controls and do not autoplay.

Image source: `SARURPackage/Graphics/Gameplay/SARUR_Hero_Original_2560x1440.png`. The web version is a proportional 1920 × 1080 export of this in-engine reference, not a claim of the current gameplay camera. Social preview is a centered crop of the same source, never a nonuniform resize.

Gameplay clips come from `2026-11-10 07-47-58.mp4`: stone carry/release at 01:24–01:29 and melee combat at 02:38–02:44. Clips show actual footage; no enemy kill is implied. They use silent H.264 MP4 rather than large GIFs to keep the page lightweight. GIF exports and full-size combat/throw screenshots are retained in the SteamStore package.

GitHub Pages serves the main branch, repository root. There is deliberately no Steam button, release date or newsletter form until real links/services exist. Update title, description and social metadata together if the URL changes.

Never commit tokens. Authentication uses GH_TOKEN loaded from an external local file for deployment only; no credential belongs in this repository. The site repository contains website files only, not Unreal project or private store working files.
