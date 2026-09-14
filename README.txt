SS13 PWA package

Upload these files to the ROOT of the GitHub repository SS13-report:
- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png

After GitHub Pages redeploys, open:
https://cgdfry.github.io/SS13-report/

Then Chrome should offer: Install app / Установить приложение.

The service worker caches the app shell for offline launch.
User data remains local in browser/PWA storage.
Before replacing an older live version, create a full backup inside SS13.
