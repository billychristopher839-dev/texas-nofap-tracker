# Texas: Road to #1 — Governor's Habit Ledger

A single-file, Texas-themed NoFap streak tracker. You play the Governor of Texas: every clean day you log establishes the next of the state's 254 real counties, in the exact order Texas created them (1836–1921), each with its own county seat, founding year, and a short story. Reach 254 clean days and Texas is ranked #1 in the nation for governance.

## Rules
- Log once a day: **Held the line** (clean) or **Report a setback**.
- Streak milestones: 7d +5 · 14d +10 · 30d +20 · 45d +25 · 60d +30 · 90d +60 (and +60 for every further 90).
- A setback costs **−3 points** and resets the streak — founded counties are never taken back.
- Day 254 (Kenedy County, 1921) ends the game in victory.

## Features
- Interactive SVG county map of Texas: unlocked counties fill in by historical era; tap any county for its story.
- Tabs: Office (daily log), State Map, County Registry, Progress (weekly strip + monthly calendar with backfill editing), Guide & Support.
- Onboarding: name, personal oath, term start date.
- Editable: change profile, undo today, backfill/clear any past day, export/import save, full reset.
- Storage: `window.storage` → `localStorage` → in-memory fallback, so it works on claude.ai, GitHub Pages, and plain `file://`.
- Fully self-contained: Texas flag, state seal, county map, and all 254 county facts are embedded. No external requests.

## Deploy to GitHub Pages
1. Put `index.html` and `.nojekyll` in the repo root (or a folder).
2. Settings → Pages → deploy from branch.
3. Hard-refresh (⌘⇧R) after updates.
