# Fit Dock Pilates — Wooden Reformer 3D Viewer

A static, English-language 3D product viewer for GitHub Pages.

## Files
- `index.html`: the complete website
- `reformer.glb`: 3D CAD geometry
- `fit-dock-logo.png`: Fit Dock Pilates branding
- `.nojekyll`: GitHub Pages setting

## Publish
Copy all files to the root of your GitHub repository. Commit, push to the `main` branch, and enable **Settings → Pages → Deploy from a branch → main / (root)**. Wait for the Pages workflow to succeed. Refresh with Ctrl+Shift+R.

## Notes
- The viewer loads Three.js from jsDelivr, so internet access is required.
- The GLB is publicly downloadable from any public website; do not publish proprietary geometry unless you intend to share it.
- Material appearance is conceptual and can be improved later.
