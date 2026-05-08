# Wicket Wizard - Cricket Umpire Scoreboard

A fast, mobile-friendly scoreboard web app for cricket umpires. Track runs, balls, and overs in real time during a live match.

## Features

- **Run Counter** — Large display with +1 and -1 buttons for quick scoring
- **Ball & Over Tracking** — Automatic over rollover every 6 balls (displayed as `2.3` = 2 overs, 3 balls)
- **Persistent State** — Score survives browser refresh via localStorage
- **Reset** — One-tap reset with confirmation dialog
- **Mobile First** — Large touch targets, no zoom, works great on phones
- **Dark Neon Theme** — Glassmorphism design, easy to read outdoors

## Usage

Open `index.html` in any browser. No build step, no dependencies, no backend.

### Controls

| Button | Action |
|--------|--------|
| **+1 Run** | Add one run to the total |
| **-1** (small) | Remove one run |
| **+ Ball** | Record a ball bowled |
| **-1** (small) | Undo last ball |
| **RESET MATCH** | Clear everything (with confirmation) |

## Deployment

This is a single static HTML file. Deploy anywhere:

- **GitHub Pages** — Push and enable in repo Settings → Pages
- **Netlify** — Drag and drop the folder
- **Vercel** — Connect the repo
- **Cloudflare Pages** — Connect or drag and drop

## Tech

Single `index.html` with embedded CSS and JavaScript. Zero dependencies.

## License

MIT
