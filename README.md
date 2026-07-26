# 🎯 Broken Glass — Shooting Gallery

**[▶ Play it live](https://haidersharif-9.github.io/BrokenGlass-shooting-game/)**

A fast-paced, arcade-style shooting gallery game built entirely in a single HTML file — no frameworks, no dependencies, no build step. Aim, fire, and survive as bottles, cans, hearts, and the occasional bomb come flying at you from every direction, across an endlessly escalating set of levels.

> ⚠️ **Setup note:** for the live link above to load the game itself (instead of this README), the main file needs to be named `index.html` at the repo root. See [How to Run](#-how-to-run) if you're running it locally instead.

## 🎮 About

You're standing in a shifting gallery of alleys, boardwalks, night markets, rain-soaked lots, foggy harbors, and blizzards — and things keep getting thrown at you. Shoot the right targets, dodge the wrong ones, and chase your own best score.

- 🍾 **Bottles** — common, worth +1 bullet
- 🥫 **Cans** — rarer, smaller, worth +2 bullets
- ❤️ **Hearts** — restore health, no penalty if missed
- 💣 **Bombs** — shoot one and you just waste the bullet (no score); miss one and it still hurts you
- 👑 **Boss targets** — a big bonus target appears every 5th level

Every shot costs a bullet whether you hit or miss, so precision matters more than spam. Chain hits together to build a combo multiplier, survive long enough to level up (full reload, tougher speed, a new scene and weather), and try to beat your own personal best.

## ✨ Features

- 🎯 Real-time canvas-based aiming and shooting, with mouse **and** touch support for mobile
- 🥤 Five target types with distinct risk/reward behavior (bottles, cans, hearts, bombs, boss crates)
- 🔥 Combo system with a live score multiplier
- 📈 Progressive leveling — more bullets, faster targets, harder thresholds each level
- 🌆 A generated city skyline backdrop, with six rotating weather/scene themes (including rain and snow particle effects)
- 💥 Glass-shatter, can-crumple, and spark particle effects on every hit, plus screen shake on damage
- 🔊 Fully synthesized sound effects via the Web Audio API — gunfire, shatter, crumple, heal chime, level-up fanfare, and a heartbeat cue when health runs low (no audio files needed)
- ⏸️ Pause menu, plus adjustable **volume** and **Easy / Normal / Hard** difficulty settings
- 🧭 A one-time "tap here" tutorial hint for first-time players
- 🏆 A personal best-runs leaderboard and a score trend graph, saved locally per device
- 📊 An all-time stats screen — total shots fired, accuracy %, best combo, total playtime
- 🔁 A "reset progress" option if you want a clean slate
- 📱 Fully responsive — plays on desktop and mobile browsers alike

## 🛠️ Built With

- HTML5 & CSS3
- Vanilla JavaScript
- HTML5 Canvas API (rendering, particles, weather)
- Web Audio API (all sound effects, synthesized — no audio files)
- `localStorage` (personal best scores, stats, and settings persistence)

## 🚀 How to Run

**Play online:** just open the [live link](https://haidersharif-9.github.io/BrokenGlass-shooting-game/) — nothing to install.

**Run locally:**
1. Clone or download this repository
2. Open `index.html` in any modern browser
3. Click **Start Game** and go

No build step, no server, no external dependencies.

## 📸 Screenshots

*Add gameplay screenshots here.*

## 👨‍💻 Developer

**Haider Sharif**

Built as a personal project to practice real-time canvas rendering, game-feel design (combo systems, difficulty curves, hit timing), procedural audio, and browser-based game architecture from scratch.

---

⭐ If you enjoyed this project, consider giving it a star on GitHub!
