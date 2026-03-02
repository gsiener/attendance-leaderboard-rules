# Attendance Leaderboard

A point-based attendance tracking system for a HS ultimate team. The README.md is the entire product — it defines the rules, point values, and definitions. It deploys to GitHub Pages via Jekyll on push to main.

## Project structure

- `README.md` — The rules document. This is the only content file.
- `.github/workflows/pages.yml` — GitHub Pages deployment (Jekyll).
- `.claude/turbocommit.json` — Turbocommit is enabled; changes auto-commit after each turn.

## Conventions

- Push directly to `main`. There are no branches or PRs.
- Keep the README concise and readable by players and parents. Avoid jargon.
- Point values and bonuses are defined in the table in README.md. Bonuses stack.
- When updating rules, keep the point table, definitions, and "Why" section in sync.
