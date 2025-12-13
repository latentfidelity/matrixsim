# matrixsim — Coding Agent Notes

## What this is
A single-page Three.js simulation in `index.html` using ES modules via an import map (Three.js + addons from `unpkg.com`).

## Run
- Serve over HTTP:
  - From the parent folder: `python -m http.server 8000`
  - Open `http://localhost:8000/matrixsim/`

## Conventions
- Keep everything in `index.html` (no bundler).
- Keep CDN versions pinned; update the import map and addon paths together.
- Prefer performance-friendly changes (avoid per-frame allocations; keep interaction smooth).

