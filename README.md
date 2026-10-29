# swimming.rayanupadhyay.com

A quiet horror walk through endless tiled pool rooms. The pool is open. It has always been open.

**Live:** [swimming.rayanupadhyay.com](https://swimming.rayanupadhyay.com)

## Features

- First-person rooms of white tile, shallow water and humming lights, built around you as you walk, so they never end
- The same layout every visit: the rooms are always where you left them
- Deep ends you can swim across and dive into, with muffled sound and murky light underwater
- Small things that happen while you wander: lights that flicker or go out, splashes that aren't yours, short lines of text, and a figure at the end of the hall that doesn't like being looked at
- An exit, eventually, if you walk far enough
- Sound made live in the browser: fluorescent hum, lapping water, drips and a long tiled echo
- Works on phones: left thumb to walk, drag to look, hold the dive button in deep water. On a computer: WASD, mouse, and hold space to dive

## Tech

A single `index.html` with three.js r128 from cdnjs and the Web Audio API, no build step and no image files: the tile, water ripple and sign textures are all drawn in code. Each room is merged into a few meshes so it runs smoothly on phones. Hosted on Vercel.
