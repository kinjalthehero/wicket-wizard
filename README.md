**Live App: [https://kinjalthehero.github.io/wicket-wizard/](https://kinjalthehero.github.io/wicket-wizard/)**

# Wicket Wizard - Cricket Umpire Scoreboard

A fast, mobile-friendly scoreboard web app for cricket umpires. Track runs, balls, overs, and wickets in real time during a live match.

## Features

- **Run Counter** — Large display with +1, +4, and +6 buttons for quick scoring, plus a -1 undo
- **Ball & Over Tracking** — Automatic over rollover every 6 balls (displayed as `2.3` = 2 overs, 3 balls)
- **Wicket Tracker** — Track wickets fallen, capped at 10
- **Persistent State** — Score, overs, and wickets survive browser refresh via localStorage
- **Reset** — One-tap reset with confirmation dialog
- **Mobile First** — Large touch targets, no zoom, works great on phones
- **Dark Theme** — Muted glassmorphism design, easy to read outdoors

## Usage

Open the app at **[https://kinjalthehero.github.io/wicket-wizard/](https://kinjalthehero.github.io/wicket-wizard/)** on any browser or mobile device.

To run locally, open `index.html` in any browser. No build step, no dependencies, no backend.

### Controls

| Button | Action |
|--------|--------|
| **+1** | Add one run to the total |
| **+4** | Add four runs (boundary) |
| **+6** | Add six runs (six) |
| **-1** (runs) | Remove one run |
| **+ Ball** | Record a ball bowled |
| **-1** (ball) | Undo last ball |
| **+ Wicket** | Record a wicket fallen |
| **-1** (wicket) | Undo last wicket |
| **RESET MATCH** | Clear everything (with confirmation) |

## Deployment

This is a single static HTML file. Deploy anywhere:

- **GitHub Pages** — Push and enable in repo Settings → Pages
- **Netlify** — Drag and drop the folder
- **Vercel** — Connect the repo
- **Cloudflare Pages** — Connect or drag and drop

## Tech

Single `index.html` with embedded CSS and JavaScript. Zero dependencies.

## Author

Developed by Kinjal Mistry — kinjalthehero@gmail.com

## License

MIT
