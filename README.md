# grandthiefsimulatorv5ultimate

A browser-based **HTML5 + Three.js open-world crime sandbox prototype** inspired by GTA-style gameplay loops.

## Play on GitHub Pages
After you push this repository to GitHub, the included workflow auto-deploys the site from `main`.

```text
https://<your-github-username>.github.io/grandthiefsimulatorv5ultimate/
```

## One-time GitHub Pages setup
1. Push this code to a GitHub repository.
2. Open **Settings → Pages**.
3. Set **Source** to **GitHub Actions**.
4. Push to `main` (or manually run workflow in **Actions**).

## New upgrades in this pass
- **NPC civilians** walking around the city.
- **Lane-following traffic patterns** (cars stay on roads and stop for player ahead).
- **Police escalation improvements**:
  - cruisers pursue by wanted level,
  - officers can deploy from cruisers,
  - on-foot police can fire at the player.
- **Enhanced visuals**:
  - improved lighting and tone mapping,
  - upgraded materials,
  - sun-glow sky shader and vignette pass.
- Better world feedback via expanded HUD (health + NPC counters).

## Controls
- `WASD`: move / drive
- `Shift`: sprint (on foot)
- `E`: enter / exit nearby vehicle
- `Mouse`: look (pointer-locked)
- `Left Click`: fire weapon (on foot)
- `R`: reload
- `Space`: handbrake (driving)
- `C`: cinematic camera
- `F`: provoke / increase wanted level

## Run locally
```bash
python3 -m http.server 4173
```
Then open:

```text
http://localhost:4173
```

## Notes
This is an original prototype and **not an official GTA product**.
