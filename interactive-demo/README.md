# Interactive 3D Demo

This demo allows you to interactively change parameters of a 3D mesh using a graphical user interface:

- Switch between Box, Sphere, and Torus Knot geometries
- Control color, metalness, roughness, and rotation speed
- Orbit controls to rotate, pan, and zoom the scene

## How to Run

### Option A: HTTP Server

```bash
cd interactive-demo
python3 -m http.server 8001 --bind 0.0.0.0
```

Then open your browser at http://localhost:8001

### Option B: Offline

Open `index.html` directly in your browser (no server required).
