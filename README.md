# EPUB Reader — iPhone PWA

This is a static web app. EPUB files chosen using the file picker are read in your browser; no EPUB data is uploaded to the site. Only the app shell is cached for offline launching; EPUB files are **not** saved for reopening. Reading position is stored locally and you must select the EPUB again after a relaunch.

## Publish with GitHub Pages

1. Create a **public** GitHub repository called `epub-reader`.
2. Upload all files from this folder to the repository root (`index.html`, `sw.js`, `manifest.webmanifest`, `icon-180.png`, `icon-192.png`, `icon-512.png`).
3. Go to Settings > Pages > Build and deployment > Deploy from a branch > `main` > `/ (root)` > Save.
4. Open `https://YOUR_LOGIN.github.io/epub-reader/` in **Safari** on the iPhone.
5. Share > Add to Home Screen > Open as Web App (if shown) > Add.
6. Open the new icon once while connected to the internet to allow the app shell to be cached.

Note: This repository is public and **includes only code and icons**, not your EPUB books. The native EPUB file picker requires a user action. The app uses native browser `DecompressionStream('deflate-raw')`; older browser versions may not support it. The app is not a native iOS App Store app.
