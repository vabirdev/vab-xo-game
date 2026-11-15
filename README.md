# VAB XO Game

A responsive Tic-Tac-Toe (XO) game built with **HTML, CSS, and vanilla JavaScript**, featuring local two-player mode and an AI opponent with three difficulty levels.

Created by **Vali Asghari Bakhtavar**  
Website: <https://vab-dev.ir>

## Features

- **Play against the computer** or **play locally with two players** on the same device.
- **Three AI difficulty levels:**
  - **Easy:** makes mostly random moves, with occasional winning moves.
  - **Medium:** uses a depth-limited search to look ahead and respond to tactical threats.
  - **Hard:** uses full-depth Minimax with Alpha-Beta pruning. In standard Tic-Tac-Toe, optimal play cannot lose.
- Custom player names.
- Scoreboard for X wins, O wins, and draws.
- Scores persist in the browser using `localStorage`.
- New game, undo move, and sound toggle.
- Responsive layout for desktop and mobile screens.
- VAB Dev logo embedded in the standalone HTML file.
- Microsoft Fluent 2-inspired visual styling.

## Getting started

No build tools, package manager, or server are required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Choose **Vs. Computer** or **Two Players**.
4. If playing against the computer, choose Easy, Medium, or Hard.

## Project structure

```text
vab-xo-game/
├── index.html   # Complete game: HTML, CSS, JavaScript, and embedded logo
└── README.md    # Project documentation
```

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Browser Local Storage
- Minimax algorithm with Alpha-Beta pruning for Hard AI

## AI difficulty notes

| Level | Strategy |
| --- | --- |
| Easy | Random legal moves, with occasional immediate wins |
| Medium | Depth-limited search for tactical and positional decisions |
| Hard | Full-depth Minimax search with Alpha-Beta pruning |

## Customization

You can edit `index.html` to change the interface, colors, player defaults, game behavior, or AI settings. The game is intentionally kept in one file so it is easy to run and host.

## License

No license has been specified yet. Add a `LICENSE` file before presenting this project as open source under a particular license.

---

Made with care by **Vali Asghari Bakhtavar** · <https://vab-dev.ir>
