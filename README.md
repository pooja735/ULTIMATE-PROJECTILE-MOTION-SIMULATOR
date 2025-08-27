# Ultimate Projectile Motion Simulator

A modern single-page web app to visualize projectile motion. Runs locally in any modern browser.

## Features
- Professional, responsive UI with clear sections
- Adjustable launch: Angle, Speed, Height
- Environment: Gravity (Earth, Moon, Mars)
- Display: Time scale slider, Grid toggle
- Actions: Start, Pause/Resume, Reset
- Tools: Optimize Angle (no-drag), Export CSV of trajectory
- Smooth animation with numerical integration

## Quick Start
1. Open `index.html` in Chrome, Edge, or Firefox.
2. Set Angle, Speed, Height, and Gravity.
3. Optionally adjust Time scale and toggle Grid.
4. Click Start.

## Controls
- Angle (°): Launch angle
- Speed (m/s): Initial speed
- Height (m): Launch height above ground
- Gravity: Celestial body (sets g)
- Time scale: Slow down/speed up animation
- Show grid: Toggle background grid
- Optimize Angle: Suggests angle maximizing range (no drag)
- Export CSV: Downloads `trajectory.csv` with columns `t,x,y,vx,vy`

## Notes
- Current build models gravity-only motion (no wind/drag/target)
- View auto-scales to keep the full trajectory visible

## Files
- `index.html` — UI, styles, and simulation logic
- `README.md` — This document

## License
MIT
