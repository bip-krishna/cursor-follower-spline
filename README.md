# Cursor Follower · Spline

An interactive 3D page that loads a hosted Spline scene through the `<spline-viewer>` web component. Move the pointer around the scene to see its cursor response.

[Live demo](https://bip-krishna.github.io/cursor-follower-spline/) · [Quick start](#quick-start)

## Quick start

Run this from the repository root with Python 3 installed.

```bash
python3 -m http.server 8000
```

Open [localhost:8000](http://localhost:8000).

The browser needs internet access to load the viewer and hosted scene. Change the scene URL in [`index.html`](index.html) or adjust the surrounding layout in [`style.css`](style.css).
