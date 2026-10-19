# THE LAST SHIFT — PyroMania

A free, browser-playable retro low-poly psychological horror prototype built with Three.js.

## Play locally
Open `index.html` in a modern browser with an internet connection. The game loads Three.js from jsDelivr, so it needs internet access.

## Controls
- PC: WASD to move, mouse to look, Shift to run, F to toggle flashlight.
- Mobile: on-screen directional buttons to move, drag the right side of the screen to look, RUN and LIGHT buttons.
- Find all 3 fuses, then reach the red exit at the far end of the facility. Avoid the creature.

## Deploy to GitHub Pages
1. Create a **public** repository named `PyroMania-Game` on GitHub.
2. Upload the contents of this folder to the repository root (make sure `index.html` is at the root).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **GitHub Actions** as the source.
5. The workflow in `.github/workflows/pages.yml` deploys the game automatically after the files are pushed. Open **Actions** and wait for the Pages workflow to finish.
6. Your game URL will be `https://YOUR-GITHUB-USERNAME.github.io/PyroMania-Game/`.

## Notes
- No paid tools, backend, or API key required.
- This is an early playable prototype. Graphics are intentionally low-poly and atmospheric; all game code is in `index.html`.
