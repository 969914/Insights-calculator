SLICK INSIGHT EARNINGS CALCULATOR - PWA SOURCE

Files:
- index.html: application HTML, CSS and JavaScript
- manifest.json: installable app metadata
- sw.js: offline cache/service worker
- icon.svg: app icon

MOBILE INSTALL (Android):
1. Upload all four files to a public HTTPS host. GitHub Pages is a free option.
2. Open the hosted URL in Chrome on your Android phone.
3. Open Chrome menu (three dots) and tap "Install app" or "Add to Home screen".
4. Confirm. The calculator will appear on your home screen.

IMPORTANT:
- Do not open index.html from a file:// URL if you want PWA installation/offline caching.
- Saved match data uses localStorage in that browser on that device. It does not automatically sync to other devices. Export CSV backups regularly.
- To publish on GitHub Pages: create a repository, upload these files to the repository root, then Settings > Pages > deploy from branch > main / root. Wait for the HTTPS URL to become available.
