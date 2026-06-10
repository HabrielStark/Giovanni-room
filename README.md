# Giovanni's Room — An Interactive Journey

A short, first-person 3D exploration game based on James Baldwin's novel *Giovanni's Room* (1956). You play as David and walk through five scenes of his memory — the house in the south of France, his father's living room, Guillaume's bar, Giovanni's room, and Hella's return — talking to the novel's characters, making dialogue choices, and collecting ten evidence cards that tie the story to its central theme: **Identity / Self-Expression**. A full playthrough takes about 5–10 minutes.

## How to run

No build step. Serve this folder with any static server and open it in desktop Chrome:

```
npx serve .          # or: python3 -m http.server
```

Then open the printed local address (e.g. http://localhost:3000 or http://localhost:8000). An internet connection is required (Three.js is loaded from a CDN).

## Controls

| Action | Key |
| --- | --- |
| Move | WASD or Arrow keys |
| Look | Mouse (click the screen to lock the cursor) |
| Interact | E (when a prompt is shown) |
| Continue dialogue | Click or E |
| Pause / journal | Esc |

## Note for the teacher

The ten collectible evidence cards are faithful **paraphrases** with accurate Part/Chapter attribution to the novel (Part One, Chapters 1–3; Part Two, Chapters 1–5). The citation field uses `Baldwin, p. ___` so the exact page can be filled from the physical class copy before submission. An in-game **For the Teacher** screen summarizes how the game covers the characters, plot, central conflict, theme, citations, and interactivity.
