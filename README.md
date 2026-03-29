# ☠ Duel Grid ⚡
### A gothic-themed Tic-Tac-Toe battle game — pure HTML, CSS & JS

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen?style=flat-square)

---

## Overview

**Duel Grid** is a stylish, feature-rich Tic-Tac-Toe game built with zero dependencies — just a single HTML file. Two players go head-to-head using ☠ Skull vs ⚡ Lightning symbols across three distinct board themes, with match history tracking, animated win effects, and a cinematic dark aesthetic.

---

## Features

- **Player Name Entry** — A modal prompts both players to enter their names before the game starts
- **3 Board Styles** — Switch between Abyss (purple neon), Ember (orange fire), and Crystal (frosted glass) at any time
- **Custom Symbols** — ☠ Skull for Player 1, ⚡ Lightning Bolt for Player 2 — no boring X's and O's
- **Hover Effects** — Cells glow, scale, and light up on hover, themed to the active board style
- **Transparent Borders** — All borders use rgba and backdrop-filter blur for a glassmorphism feel
- **Win Animations** — Winning cells pulse, confetti erupts in the winner's color, and a dramatic overlay announces victory
- **Draw Detection** — Board shakes on a draw with its own overlay
- **Player Cards** — Live score cards (Wins / Draws / Losses) sit on each side of the board with a turn indicator
- **Match History Log** — Scrollable per-player history below the board, showing numbered results with color-coded badges
- **Fully Responsive** — Cards stack above the board on mobile screens
- **No Build Tools** — Open the file and play. That's it.

---

## Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/duel-grid.git

# Open in your browser
open tictactoe.html
```

No installs. No `npm install`. No config. Just open `tictactoe.html` in any modern browser.

---

## How to Play

1. Open `tictactoe.html` in a browser
2. Enter Player 1 and Player 2 names in the modal and click **Begin the Duel**
3. Players take turns clicking cells — ☠ goes first
4. First to get 3 in a row wins the round
5. Use **Next Round** to replay, or **New Game** to reset everything and re-enter names

---

## Board Styles

| Style | Theme | Border Effect |
|---|---|---|
| **Abyss** | Deep purple neon | Glowing purple rgba borders |
| **Ember** | Orange fire | Warm ember-toned borders |
| **Crystal** | Frosted glass | Backdrop-filter blur transparency |

---

## Tech Stack

| Layer | Choice |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, animations, backdrop-filter) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Cinzel Decorative, Cinzel, Rajdhani |
| Dependencies | None |

---

## File Structure

```
duel-grid/
└── tictactoe.html    # Entire game — markup, styles, and logic in one file
└── README.md
```

---

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge). Requires support for `backdrop-filter` for the Crystal style's glass effect — degrades gracefully in older browsers.

---

## License

MIT — free to use, fork, and modify.

---

> *"The grid remembers every duel. Do you?"*
