# The Architecture Journal

A responsive, static personal learning website about architecture, building construction, materials, and interior design.

## Files
- `index.html` — page content and structure
- `styles.css` — visual design and responsive layout
- `script.js` — navigation, material filters, and saved learning progress

## Preview locally
Open `index.html` in a modern browser. For a local development server, you can use VS Code's Live Server extension.

## Publish with GitHub Pages
1. Sign in to GitHub and create a new repository, for example `architecture-journal`.
2. Upload the contents of this folder to the repository root (not the parent folder).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. Wait for GitHub Pages to publish the site. The URL will usually be `https://YOUR-USERNAME.github.io/architecture-journal/`.

For a personal root website, name the repository `YOUR-USERNAME.github.io`.

## About the images
The earlier lesson images were visual reference previews inside the chat, not downloadable image files. This first website version therefore uses original CSS-based architectural illustrations and material swatches rather than pretending those previews are local assets. To add photographs, place licensed image files in an `assets/` folder and reference them from `index.html`. Prefer your own photographs or images with clear reuse permissions, and record attribution where required.

## Customisation
- Change the site name and text in `index.html`.
- Adjust colours, typography, spacing, and layout in `styles.css`.
- Add lessons as new sections or separate HTML pages.
- Learning progress is saved in the visitor's browser using local storage; it is not synchronised between devices.
