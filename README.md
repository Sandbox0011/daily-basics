# Daily basics

A one-habit-at-a-time daily tracker. Starts with a single habit and unlocks the next only when the current one is sticking (about 10 of the last 14 days).

Habits, in order:

1. Up on time (wake-up target)
2. Planned session done (BJJ, kettlebells, or a planned rest day)
3. Food logged (in MyFitnessPal / MacroFactor)
4. Step target hit

## My week

A weekly schedule lives in the same page, under the 14-day grid. Add the fixed parts of a normal week (work, training, morning routine) and it shows the free gaps, both as a week map and per day.

- Tap a block to edit, move or delete it. Tap a dashed "Free" gap to plan something into it.
- When adding, pick several days at once for anything that repeats.
- Free gaps (30+ minutes) are counted between the **Wake-up time** and **Bedtime** in Targets, so set those to match your real day.
- It's included in Export / Import, and the most recently edited copy wins when merging.

## Running it

It's a single static `index.html` with no build step. Open it in a browser, or host it free with GitHub Pages:
Settings → Pages → Source: "Deploy from a branch" → `main` / root.

## Data

When hosted outside claude.ai, data is saved in the browser's localStorage, so it stays on that one device and browser. Clearing site data wipes it.
