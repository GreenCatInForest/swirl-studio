# Swirl Studio

Draw thick, multi-color swirl lines and export them as ready-to-use React components.

- **Pen**: click to add points, drag to move, click the line to insert, double-click to delete.
- **Sketch**: drag freehand; the stroke turns into editable points.
- **Export**: name the component, copy the code, save it as `src/components/<Name>.tsx`.

It's a single static `index.html` with no build step. Every push to `main` deploys it to GitHub Pages through `.github/workflows/deploy.yml`.
