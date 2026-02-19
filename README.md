# grandthiefsimulatorv5ultimate

A browser-based **HTML5 + Three.js open-world crime sandbox prototype** inspired by GTA-style gameplay loops.

## Play on GitHub Pages
After you push this repository to GitHub, the included workflow auto-deploys the site from the `main` branch.

Your live URL will be:

```text
https://<your-github-username>.github.io/grandthiefsimulatorv5ultimate/
```

### One-time GitHub Pages setup
1. Push this code to a GitHub repository.
2. In GitHub, open **Settings → Pages**.
3. Ensure **Source** is set to **GitHub Actions**.
4. Push to `main` (or run the workflow manually under **Actions**).

## Features
- 3D city grid with roads, buildings, trees, and fog distance.
- On-foot character movement with sprinting.
- Enter/exit vehicles and drive with arcade handling.
- Ambient AI traffic cars roaming the map.
- Wanted level system and “chaos action” to escalate police heat.
- Minimap + HUD (mode, speed, stars, cash).
- Third-person and cinematic camera toggle.

## Controls
- `WASD`: move / drive
- `Shift`: sprint
- `Space`: handbrake
- `E`: enter/exit nearby vehicle
- `F`: chaos action (+cash, +wanted)
- `C`: cinematic camera
- Hold mouse button + move mouse: look around

## Run locally
Because this project uses ES modules, run from a local server:

```bash
python3 -m http.server 4173
```

Then open:

```text
http://localhost:4173
```

## Notes
This is an original prototype and **not an official GTA product**.
