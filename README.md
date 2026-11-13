Discipline by Design Dashboard (web version)
Static files only. No backend, no accounts, no analytics, no outside requests.
Open index.html directly, or upload this whole folder to any static host (GitHub Pages, Netlify, Cloudflare Pages).
Data is stored only in the visitor's browser (localStorage). Export/Import on "Your data" moves it between devices.
Offline/home-screen install works when served over https (service worker sw.js). When opened as a local file it still works, just without install.
Files: index.html, styles.css, app.js (UI), logic.js (calculations, same rules as the .xlsx), maya.js (example data), manifest.webmanifest, sw.js, icons/.
When you change any file after publishing, bump CACHE in sw.js (dbd-discipline-v1 -> v2) so phones pick up the update.
© 2026 Nathan Hansen. A companion to Discipline by Design. For personal use.
