# THE LAST NIGHT — 3D Forest Horror (Version 2)

A low-poly, browser-based survival horror prototype built with Three.js. Playable on desktop and mobile.

## Version 2 features
- Stateful monster behavior: patrol, investigate sprinting/noise, and hunt when it spots the player.
- Procedural atmospheric wind, footsteps, flashlight clicks, totem chimes, heartbeat tension, and jumpscare audio (Web Audio).
- Screen-shaking monster jumpscare on capture.
- Two abandoned ranger shacks and broken fence landmarks.
- Three glowing totems, flashlight battery, sprint stamina, and escape gate.
- Responsive touch joystick and touch-look controls.

## Run locally
Open `index.html` in a modern browser, or run `python -m http.server 8000` and visit `http://localhost:8000`.
Internet is required for the Three.js CDN.

## Controls
- **PC:** WASD / arrows to move, mouse to look, Shift to sprint, F to toggle flashlight.
- **Mobile:** left virtual joystick to move, drag the right side to look, flashlight button to toggle.

## Objective
Find all three glowing totems and reach the gate at the far end of the forest. Avoid the tall creature stalking between the trees.

## Publish with GitHub Pages
1. Create a public GitHub repository, e.g. `the-last-night`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, select **main** and **/(root)**, then Save.
5. GitHub Pages will show your public game URL when deployment finishes.

No build step is required. This is still a prototype: advanced navmesh pathfinding, custom authored models, and recorded voice/audio assets can be added in a later release.
