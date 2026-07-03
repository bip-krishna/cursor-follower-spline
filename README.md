# Cursor Follower Spline

A minimal HTML page embedding a **Spline 3D scene** using the `<spline-viewer>` web component. The 3D model follows cursor interaction via Spline's built-in event system.

## Tech Stack

- Spline Viewer (`@splinetool/viewer`)
- Vanilla HTML / CSS

## Setup

```bash
git clone https://github.com/bip-krishna/cursor-follower-spline.git
cd cursor-follower-spline
# Serve locally (CORS requires a server)
python3 -m http.server 8000
```

Open `http://localhost:8000` to view the 3D scene.
