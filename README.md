# games

A collection of small browser games. Each game lives in its own folder with its own `index.html` and runs on its own, with no build step.

| Game | Folder | Notes |
|------|--------|-------|
| 🕷️ Spider Takedown | [`spider-takedown/`](spider-takedown/) | 3D first-person spider game, 1–5 players (keyboard, controller, touch). Needs internet for three.js and the font. |
| 🔍 Spot the Difference | [`spot-the-difference/`](spot-the-difference/) | Kids' game: tap the 10 differences between two pictures. New random scene every time, with people and speech bubbles. Needs internet for the font. |

## Adding a game
Make a new folder with an `index.html`, use relative paths, and give its saved data (localStorage) its own prefix so games don't overwrite each other. Spider Takedown uses `st_`.

## Playing on GitHub Pages
Turn on Pages for the `main` branch (Settings → Pages), then open `https://robdoyle2.github.io/games/spider-takedown/`.
