# THE LAST NIGHT — 3D Forest Horror

A browser-based low-poly survival horror game built with Three.js. Playable on desktop and mobile.

## Play locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Internet is required to load Three.js from jsDelivr.

For the best local development experience, run a small web server:
- Python: `python -m http.server 8000`
- Visit `http://localhost:8000`

## Controls
- **PC:** WASD / arrow keys to move, mouse to look, Shift to sprint, F to toggle flashlight.
- **Mobile:** left virtual joystick to move, drag the right side to look, flashlight button to toggle.

## Objective
Find all three glowing totems, then reach the gate at the far end of the forest. Avoid the tall creature stalking between the trees.

## Publish with GitHub Pages
1. Create a new public GitHub repository (for example, `the-last-night`).
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then Save.
6. Wait for GitHub Pages to publish. Your game URL will be shown in the Pages section.

## Notes
- No build step is required.
- Three.js is loaded from a CDN, so players need an internet connection.
- This is a playable prototype. Art, audio, pathfinding, and touch sensitivity can be expanded in future versions.
