# Print Size Studio — Offline & GitHub Pages

A static print-size calculator that runs in a modern browser. The application has no external JavaScript, CDN, font, or network dependencies.

## Offline use

1. Download and extract this folder.
2. Open `index.html` in Chrome, Edge, Firefox, or another modern browser.
3. Upload a JPG, JPEG, or PNG file.
4. Choose the output unit and adjust the width, height, or custom scale.

Image processing and calculations happen locally in your browser. Your artwork is not uploaded to a server. The calculator uses the DPI value shown in the app (300 by default) to estimate physical dimensions from image pixels.

**Offline format support:** JPG, JPEG, and PNG. PDF and TIFF are not included in this offline edition because their reader libraries are not bundled.

## GitHub Pages hosting

1. Create a GitHub repository.
2. Upload `index.html`, `README.md`, and `.nojekyll` to the repository root.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/(root)`, then save.

The same `index.html` works when opened directly from your computer and when hosted on GitHub Pages. No build step or installation is needed.
