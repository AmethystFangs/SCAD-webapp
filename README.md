# SCAD Param Viewer
Personal OpenSCAD viewer for Android: open a .scad (or .zip with includes), tweak Customizer parameters, render, orbit, export STL. No editor.
Uses OpenSCAD's WASM build (Manifold backend). GPL-2.0-or-later applies to the OpenSCAD binary; if you share this, publish source and don't call it "OpenSCAD".

## Deploy (one time)
1. Create a GitHub repo, upload everything in this folder (keep `.github/`), commit to `main`.
2. Repo Settings -> Pages -> Source: **GitHub Actions**.
3. Actions tab -> wait for "Deploy" to go green (it downloads the WASM for you).
4. Open `https://<you>.github.io/<repo>/` in Chrome on Android -> menu -> Add to Home screen.
