# Corkboard Diary

A browser-based corkboard diary and interest tracker. The app is a static site: it uses local HTML, JavaScript, CSS, fonts, and images, and stores entries in the browser's local storage.

## Run locally

Open `index.html` in a browser. No build step or package installation is required.

## Publish with GitHub Pages

1. Push this folder to the `main` branch of a GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
4. GitHub Pages will publish the site at `https://<owner>.github.io/<repository>/`.

The app and its bundled assets use relative paths so they work from a GitHub Pages project subpath.

## Project layout

- `index.html` — app markup, styles, and client-side behavior
- `assets/demo/` — sample card images
- `assets/fontawesome/` — icons and bundled font files
- `assets/fonts/` — bundled app fonts
- `assets/images/` — Duckie illustrations
- `assets/textures/` — corkboard and card textures
- `assets/licenses/` — third-party license notices

