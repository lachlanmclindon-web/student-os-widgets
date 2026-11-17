# Student OS widgets

Three small, self-contained HTML widgets styled for Notion dark mode (`#191919`, teal/green and gold). They are meant to be embedded in a Notion dashboard.

## Files

- `clock.html` — analog clock, digital time, and year / month / week progress bars. Uses the viewer's local timezone.
- `pomodoro.html` — Pomodoro / short break / long break tabs, Start / Pause / Reset, and a settings panel. Durations are stored in `localStorage`.
- `wheel.html` — radar chart of the eight Wheel of Life areas (Health, Study, Career, Finance, Relationships, Fun, Personal growth, Environment). Scores are editable and stored in `localStorage`. Drawn with plain SVG (no third-party libraries).
- `index.html` — index of the three widgets.

## How to embed

1. Host this folder (GitHub Pages from the `main` branch root works).
2. In Notion, type `/embed` and paste the hosted URL for that file.
3. Size the embed so it stays roughly 280–360px wide.

The only outside request these pages make is Google Fonts (Press Start 2P and VT323).
