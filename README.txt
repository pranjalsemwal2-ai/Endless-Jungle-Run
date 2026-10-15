ENDLESS JUNGLE RUN — PWA / OFFLINE BUILD

FILES
- index.html: game code and interface
- manifest.json: installable app metadata
- service-worker.js: caches the game for offline use
- icon.svg, icon-192.png, icon-512.png: app icons

IMPORTANT
A service worker will NOT work when you open index.html as a file:// URL.
For installation and offline caching, publish this folder to an HTTPS website such as GitHub Pages.

SETUP
1. Upload all four files to the same folder in a GitHub repository.
2. Enable GitHub Pages for the repository (Settings > Pages > Deploy from a branch).
3. Open the published HTTPS URL on Android Chrome.
4. Wait for the game to load fully once, then use Chrome menu > Install app or Add to Home screen.
5. Open the installed game once, then test with airplane mode enabled.

After changing files and publishing updates, reload the game online once so the new offline cache can install.
