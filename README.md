# เลี้ยงกาแฟผู้พัฒนา (โดเนท)

!["Alt text"](https://warathepj.github.io/js-ai-gallery/public/image/promptpay-20.png)

# Three.js Particle System Visualization

A dynamic 3D visualization of particles using Three.js, featuring a system of bouncing spherical particles with random motion.

## Features

- 500 spherical particles with random motion
- Particle collision boundaries
- Orbital camera controls
- Responsive design
- Axis helper for orientation- Dynamic lighting (ambient and point light)

## Setup

Simply open `index.html` in a modern web browser. No build process required.

## Dependencies

- Three.js (r128)
- OrbitControls.js

## Controls

- Left click + drag: Rotate camera- Right click + drag: Pan
- Scroll wheel: Zoom in/out

## Technical Details

- Particles move with random velocities in 3D space- Boundary checking prevents particles
  from moving beyond ±30 units
- Camera positioned at (25, 25, 25) for optimal viewing
- Responsive window resizing support

## License

MIT
