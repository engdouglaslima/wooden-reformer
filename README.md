# Fit Dock Pilates — Wooden Reformer 3D Viewer

Static website for GitHub Pages. All site content is in English.

## Deployment
1. Copy `index.html`, `reformer.glb`, `fit-dock-logo.png`, `.nojekyll`, and `README.md` to the repository root.
2. Commit and push the changes to your `main` branch.
3. Enable GitHub Pages from `main` / `(root)` in repository settings.
4. Refresh the published page with Ctrl + Shift + R after deployment.

## Camera and canvas correction
The WebGL canvas is explicitly styled to occupy 100% of its container in CSS pixels. This is essential because the renderer uses a high device pixel ratio for sharp rendering; without CSS dimensions the drawing buffer can make the canvas larger than the viewport, moving the visible model toward the bottom-right.
