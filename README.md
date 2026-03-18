# Labeling Game

A retro-styled web game where you race against the clock to label objects in procedurally generated pixel art scenes.

## How It Works

You have **60 seconds** to identify and draw bounding boxes around objects in a series of abstract pixel art images. Each scene contains 2–4 randomly generated shapes — blobs, crystals, stars, rings, and more — rendered on an HTML5 canvas. Draw a box around each object, submit, and move on to the next image.

## Scoring

Labels are scored based on how accurately your box overlaps the true object (Intersection over Union). Each object is worth up to 100 points scaled by accuracy. At the end you receive a grade from S (1500+ points) down to D.

## Game Modes

- **Manual Mode** — Draw all bounding boxes yourself by click-and-drag.
- **AI Assist Mode** — AI pre-generates bounding boxes that you can adjust before submitting.

## Controls

| Input | Action |
|---|---|
| Click & drag | Draw a bounding box |
| Enter | Submit current image |
| Ctrl+Z / Z | Undo last box |
| Escape | Clear all boxes |
| A | AI Assist (in AI mode) |

Touch input is also supported.

## Running

Open `index.html` in any modern browser. The entire game is a single self-contained HTML file with no dependencies.

## License

MIT
