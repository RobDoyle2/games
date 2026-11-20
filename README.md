# games

A collection of small browser games. Each game lives in its own folder with its own `index.html` and runs on its own, with no build step.

| Game | Folder | Notes |
|------|--------|-------|
| 🕷️ Spider Takedown | [`spider-takedown/`](spider-takedown/) | 3D first-person spider game, 1–5 players (keyboard, controller, touch). Needs internet for three.js and the font. |
| 🔍 Spot the Difference | [`spot-the-difference/`](spot-the-difference/) | Kids' game: tap the 10 differences between two pictures. Six settings (countryside, under the sea, outer space, farm, beach, city) and three difficulty levels, picked at random each time, with people and speech bubbles. Needs internet for the font. |
| 🏠 Build a Home | [`build-a-home/`](build-a-home/) | Buy a run-down house, fix up the outside and every room, play jobs for coins, then sell it with a stamp. Make your own builder. Needs internet for the fonts. Saves progress under `build-a-home-v1`. |

## Adding a game
Make a new folder with an `index.html`, add a card for it on the front page (`index.html` in the main folder, there's a comment showing how), use relative paths, and give its saved data (localStorage) its own prefix so games don't overwrite each other. Spider Takedown uses `st_`.

## Playing on GitHub Pages
The front page (`index.html`) is the colourful game picker for kids; this README is just notes for grown-ups.

Turn on Pages for the `main` branch (Settings → Pages), then open `https://robdoyle2.github.io/games/spider-takedown/`.
