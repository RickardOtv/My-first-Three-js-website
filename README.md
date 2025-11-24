# 🌙 My First Three.js Website

A simple 3D website I made while learning Three.js. It's basically a space scene with a textured moon!

## What is this?

This project is me experimenting with Three.js and 3D graphics on the web. It covers the basics like setting up a scene, adding objects, textures, lighting, and making things spin around.

## Files

```
My-first-Three-js-website/
├── index.html       # Main HTML file
├── style.css        # Styling
├── main.js          # Three.js magic happens here
├── counter.js       # Extra JS utility
├── moon.jpg         # Moon texture
├── normal.jpg       # Normal map for the moon
├── space.jpg        # Space background
├── package.json     # NPM stuff
└── package-lock.json
```

## Tech

- Three.js
- Vanilla JavaScript
- HTML & CSS

## How to run it

1. Clone it:
```bash
git clone https://github.com/RickardOtv/My-first-Three-js-website.git
```

2. Either open `index.html` directly in your browser, or run a local server:
```bash
npx serve
```

3. You should see a space scene with a spinning moon!

## TODO

- OrbitControls so you can move the camera around
- Import actual 3D models (GLTF/OBJ)
- Shadows and better lighting
- Different shapes (torus, custom geometry)
- Post-processing effects like bloom

## If something's broken

- **Black screen?** — Check camera position, lights, or renderer setup
- **Textures not showing?** — You probably need to run a local server instead of opening the file directly
- **Can't see objects?** — They might be behind the camera or outside the view

## Author

[@RickardOtv](https://github.com/RickardOtv)
