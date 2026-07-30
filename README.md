# STONESTEP

A 3D volumetric block-puzzle. You're a knight in a torchlit dungeon: **push**, **pull**, and **climb** rune-etched stone blocks to build your way up to the glowing exit.

- **Arrows / WASD** — move (relative to the camera)
- **Q / E** — turn the camera 90°
- **Shift + direction** — pull a block
- **Z** — undo · **R** — restart

The puzzle is a true 3D grid with gravity — push a block into open space and it falls. Reach the exit to descend.

## Run locally

It's a single static file. Serve the folder any way you like, e.g.:

```bash
python -m http.server 5788
```

Then open `http://localhost:5788/`.

Built with [Three.js](https://threejs.org/).
