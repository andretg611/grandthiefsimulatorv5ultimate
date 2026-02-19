# grandthiefsimulatorv5ultimate

A browser-based **HTML5 + Three.js open-world crime sandbox prototype** inspired by GTA-style gameplay loops.

## Play on GitHub Pages
After you push this repository to GitHub, the included workflow auto-deploys the site from the `main` branch.

```text
https://<your-github-username>.github.io/grandthiefsimulatorv5ultimate/
```

### One-time GitHub Pages setup
1. Push this code to a GitHub repository.
2. In GitHub, open **Settings → Pages**.
3. Ensure **Source** is set to **GitHub Actions**.
4. Push to `main` (or run the workflow manually under **Actions**).

## Prototype upgrades in this version
- Pointer lock mouse-look start screen.
- Better lighting/material polish + gradient sky shader.
- Improved vehicle handling with proper idle, reverse, drag, steering behavior.
- Armed on-foot combat loop (shooting, ammo, reload behavior).
- Traffic awareness (cars stop for player in front), plus multi-car collision response.
- Active police spawning and pursuit behavior tied to wanted level.

## Controls
- `WASD`: move / drive
- `Shift`: sprint (on foot)
- `E`: enter / exit nearby vehicle
- `Mouse`: look (while pointer-locked)
- `Left Click`: fire weapon (on foot)
- `R`: reload
- `Space`: handbrake (driving)
- `C`: cinematic camera
- `F`: provoke / increase wanted level

## Run locally
```bash
python3 -m http.server 4173
```
Then open `http://localhost:4173`.

## Notes
This is an original prototype and **not an official GTA product**.
