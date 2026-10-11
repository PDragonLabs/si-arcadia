# SI Arcadia — Matrix Invaders

A fully playable browser-based arcade game inspired by classic Space Invaders, reimagined with a green phosphor Matrix digital-rain aesthetic and a pyramid defender base.

Created from a retro arcade cabinet image featuring falling code, invader formations, scores, lives, and an "INSERT COIN" prompt.

## Play Instantly

**GitHub Pages (recommended):**
1. Go to the repo **Settings → Pages**
2. Source: Deploy from a branch → `main` → `/ (root)`
3. Save and wait ~1 minute
4. Play at: https://pdragonlabs.github.io/si-arcadia/

Or simply open `index.html` in any modern browser.

## Controls

| Action | Keys / Input |
|--------|--------------|
| Move | ← → Arrow keys or A / D |
| Shoot | Space, ↑ Arrow, or Click |
| Start / Restart | Enter or Click (on attract / game over) |
| Mouse | Soft steering when moving the mouse |

## Features

- Falling Matrix digital rain background
- Wireframe pyramid player with glowing laser
- 5×11 invader grid with animated pixel-style sprites (3 types)
- Classic arcade UI: SCORE, HI-SCORE (persisted), LIVES (pyramid icons), CREDITS, LEVEL
- Attract / Insert Coin screen matching the original image vibe
- Progressive levels (speed increases)
- Particle explosions and simple Web Audio beeps
- CRT scanline overlay and green glow effects
- 16:9 canvas that scales responsively
- Works offline — single HTML file, no dependencies

## How It Works

Pure vanilla JavaScript + HTML5 Canvas. No build step, no frameworks.

- **Attract mode** shows a static formation + demo laser while Matrix rain falls.
- **Playing** : invaders march side-to-side and drop, shoot back, and speed up as they advance or numbers thin.
- Clear a wave → next level. Lose all lives or let invaders reach the bottom → game over.
- High score is saved in `localStorage`.

## Credits & Origin

Recreated by Grok from an image of a Matrix-styled Space Invaders cabinet screen (pyramid base, green everything, classic HUD).

Original image concept and game request by PDragonLabs.

Enjoy defending the pyramid. Insert coin. 🐍
