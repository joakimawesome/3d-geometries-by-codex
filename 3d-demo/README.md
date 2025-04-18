# 3D Demo – Fancy Moving Geometries

This demo uses Three.js to render and animate multiple 3D geometries in real time:

- Rotating box, sphere, and torus knot  
- Orbit controls (drag to rotate, scroll to zoom)  
- Responsive viewport and dynamic resize handling  
- Ambient and directional lighting  
- Grid helper as a floor reference

How to run:

1. Open a terminal and `cd` into this folder:
   ```
   cd 3d-demo
   ```
2. Start a simple HTTP server:
   ```
   python3 -m http.server 8000 --bind 0.0.0.0
   ```
3. In your browser, navigate to `http://localhost:8000` and enjoy the moving 3D geometries!