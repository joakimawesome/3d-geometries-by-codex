# 3D Geometries by Codex

A simple demo showcasing rotating 3D geometries rendered in the browser using Three.js.

## Features

- Rotating box, sphere, and torus knot
- Orbit controls (drag to rotate, scroll to zoom)
- Responsive viewport and dynamic resize handling
- Ambient and directional lighting
- Grid helper floor reference

## Getting Started

### Prerequisites

- A modern web browser with WebGL support
- (Optional) Python 3 for serving static files

### Running the Demo

```bash
# Clone the repository
git clone https://github.com/joakimawesome/3d-geometries-by-codex.git
cd 3d-geometries-by-codex/3d-demo

# Start a simple HTTP server
python3 -m http.server 8000 --bind 0.0.0.0
```

Then open your browser at http://localhost:8000 to view the demo.

## Repository Structure

- README.md           Project overview and instructions
- 3d-demo/            Contains the standalone HTML/JS demo
  - index.html        Demo page
  - README.md         Demo-specific instructions
