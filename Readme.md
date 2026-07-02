#  Tower Stack

A browser-based block-stacking game built with **Three.js**. Stack moving blocks as precisely as possible — every block you place gets sliced down to only the overlapping part, so accuracy is everything. Land one perfectly and you keep the full size (and get a little "Perfect!" bonus).

##  How to Play

- Click / tap anywhere, or press **Spacebar**, to drop the moving block.
- Each block only keeps the part that overlaps with the block below it.
- Land a block close enough to a perfect match and you get a **"Perfect!"** bonus with no size loss.
- Miss completely (zero overlap) and it's game over.
- The game speeds up as your tower grows.

## Features

- Smooth 3D stacking gameplay powered by Three.js
- Dynamic camera that follows the tower as it grows
- Procedurally generated block colors
- Persistent **high score**, saved locally in your browser
- Sound effects (placing, perfect landings, misses) generated with the Web Audio API — no audio files needed
- Mute toggle with your preference remembered between visits
- Fully responsive — works on desktop and mobile (mouse, touch, and keyboard input all supported)
- "New Best!" indicator when you beat your high score

## Tech Stack

- [Three.js](https://threejs.org/) — 3D rendering
- [GSAP (TweenMax)](https://greensock.com/gsap/) — animations
- [Font Awesome](https://fontawesome.com/) — icons
- Vanilla JavaScript, HTML, and CSS — no build tools or frameworks required

## Notes

- High scores and sound preference are stored in your browser's `localStorage`, so they're specific to each browser/device.
- No backend or external API is required — everything runs client-side.

##  License

Feel free to use, modify, and share.