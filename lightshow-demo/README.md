# 3D Light Show Demo

A dazzling visual experience featuring dynamic colored lights, bloom effects, and interactive camera controls.

## Features

- Reflective icosahedron mesh in the center
- Multiple point lights with vibrant colors orbiting around the mesh
- Bloom/glow post-processing for intense light effects
- OrbitControls for intuitive camera interaction
- Responsive design: resizes with your browser window

## How to Run

### Option A: HTTP Server

```bash
cd lightshow-demo
python3 -m http.server 8002 --bind 0.0.0.0
```

Open your browser at http://localhost:8002 to view the light show.

### Option B: Offline Mode

Simply open `index.html` in your browser—no server required.

Enjoy the show!

## GUI Controls

The top-right controls panel (powered by lil-gui) allows you to:

- **Bloom Threshold**: Set the minimum brightness level that triggers the bloom effect.  
- **Bloom Strength**: Adjust the intensity of the glow around bright areas.  
- **Bloom Radius**: Control the radius or spread of the bloom blur.  
- **Number of Lights**: Change how many colored point lights orbit the mesh (0–20).  
- **Rotation Speed**: Speed up or slow down the mesh's rotation.  
- **Metalness** and **Roughness**: Tweak the reflective material properties of the mesh.  
