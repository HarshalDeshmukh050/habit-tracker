# Grove — Habit Tracker 🌱

A single-file habit tracker with a GitHub-style heatmap per habit, streak tracking, and a growth glyph (🫘 → 🌱 → 🌾 → 🌿 → 🌳) that evolves as your streak grows. Categories match the "Notes app" style (All / Work / Study / Personal / Idea / Other). Data is saved in the browser via `localStorage` — no backend needed.

## How to deploy on GitHub Pages

1. Create a new repo on GitHub (e.g. `habit-tracker`).
2. Upload `index.html` to the repo root (drag-and-drop on GitHub, or `git add`/`commit`/`push`).
3. Go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
5. Save — GitHub gives you a URL like `https://harshaldeshmukh050.github.io/habit-tracker/` within a minute or two.

## Notes
- Everything (habits, dates, theme) is stored per-browser via `localStorage`, so it won't sync across devices — that's a good next feature if you want to extend it (e.g. with a small backend or GitHub Gist sync).
- Click any cell in a habit's heatmap to toggle that day done/not done — including past days, in case you forget to log same-day.
- Dark mode toggle in the top right.
