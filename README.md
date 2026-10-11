# Fit Dock Pilates — Wooden Reformer 3D Viewer

## Color correction update

- Preserves all 589 CAD geometry pieces and the original four color families.
- Decodes 8-bit sRGB vertex colors into linear space before Three.js lighting (addresses washed-out material colors).
- Uses neutral tone mapping and balanced studio lighting.
- Keeps solid surfaces, working zoom, camera positioning and the English-only interface.

## Publish

Replace `index.html` in your existing GitHub repository, then commit, push and refresh with Ctrl+Shift+R. No need to replace `reformer.glb` or `fit-dock-logo.png`.

The source STEP does not contain photographic textures, so realistic wood grain or fabric would require separate material/texture work.
