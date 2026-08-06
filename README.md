# havidtech.github.io

Two small, self-contained, no-build web tools hosted on one GitHub Pages site:

- **Budget Tracker** — `index.html` (site root) — personal budgeting: categories,
  expenses, and funds, saved in the browser via `localStorage`.
- **Eye Rest** — `eye-rest.html` — a 20-20-20 timer for healthy eyes while doing
  screen work: every ~20 minutes it reminds you to look ~20 ft (6 m) away for ~20
  seconds, with a full-screen break prompt, a blink pacer, and optional chime /
  desktop notifications.

Both tools link to each other and each stores its own data locally (`bt_*` and
`er_*` keys), so they never collide.
