# Forge

A manual-entry progressive overload tracker for a 4-day split (Push / Pull / Legs / Shoulders).

Built for Dylan Beaumont · True Forge Fitness.

## What it does

You type your own reps and weights every session. Nothing is calculated for you, so the app can never suggest a weight that does not exist on the machine in front of you.

- **Ghost numbers** — every input carries last session's figures as a placeholder, and a box above each exercise shows what you did and when. Tap the tick on a blank set to accept it unchanged.
- **Levels** — each exercise sits on a level. Tap *Level up* and the app explains which step you are on: more reps at the same weight, or back to your lower reps at a heavier weight. It pre-fills the numbers and you edit any of them before confirming.
- **Ratings** — Easy / Just right / Hard feed a recommendation on each card and inside the level-up screen.
- **Stall detection** — any exercise sitting on the same level for four or more sessions gets flagged, because that is where progressive overload quietly stops.
- **Week tracking** — a strip shows which of the four days are done and what is next. Close a week and the counter advances.
- **Back-dating** — walked out and forgot to log? Pick the day you actually trained.
- **Rest timer** — 2 minutes by default, in the bottom bar, auto-starts when you tick a set.
- **Bodyweight** — log it, chart it, with a weigh-in reminder on your chosen day.
- **History** — full session log, per-exercise history, printable report, CSV export, JSON backup and restore.

## Progression rule

Rep ranges run 10, 8, 6 with a bonus 6. When 10/8/6/6 goes well at a given weight, keep the weight and move to 12/10/8/6. Once that is comfortable, return to 10/8/6/6 and shift every set up one weight: drop the first weight used, start at the second, and add a new top weight.

## Data

Everything is stored in your browser's local storage on the device you use it on. Nothing is sent anywhere and there is no account. That also means clearing site data or changing phone loses it, so the app reminds you to back up every five sessions. Backups download as JSON and restore from the History tab or Settings.

## Running it

Open `index.html`. No build step, no dependencies, one file.
