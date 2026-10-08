# Manhattan Corner Dice 🎲

**Roll for a completely random corner of Manhattan — and go visit it.**

### ▶️ [Try the live demo](https://asrvstv5.github.io/manhattan-corner-dice/)

No landmarks. No iconic spots. No bias. Every real corner has exactly the same chance of coming up.

[![Live demo](https://img.shields.io/badge/demo-live-brightgreen)](https://asrvstv5.github.io/manhattan-corner-dice/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Single file](https://img.shields.io/badge/single%20file-HTML-blue)](#run-it)

## How it works

Rolling a random street and a random avenue independently would invent corners that don't exist (like 200th & 1st Ave). So instead, this builds a pool of **1,694 real Manhattan intersections** — every street × avenue crossing that actually exists, using each avenue's real street range (1st Ave only goes to ~127th, Amsterdam goes to 184th, Avenue A–D only exist in the East Village, and so on) — and picks uniformly at random from that pool.

Each roll shows:

- The corner, street-sign style
- A rough neighborhood label
- **Open in Maps** — drops you straight to the corner
- **Copy corner** — for sharing where the dice sent you
- A session-only history of your recent rolls

## Use it on your phone

Open the [live demo](https://asrvstv5.github.io/manhattan-corner-dice/) in your phone browser, then:

- **iPhone:** Share → Add to Home Screen
- **Android:** Menu (⋮) → Add to Home screen / Install app

It works in light and dark mode and needs no build step, no server, and no accounts — it's a single self-contained HTML file.

## Run it

Just open `index.html` in any browser. That's it.

Or serve it locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Why?

Manhattan is a grid, which makes it one of the few cities you can explore completely at random and always end up *somewhere real*. Most of the city is corners nobody ever deliberately visits. This is a way to go see them.

## Ideas welcome

Want to add another city's grid, track visited corners, or avoid repeats until you've seen them all? Check the [issues](https://github.com/asrvstv5/manhattan-corner-dice/issues) — especially anything labeled `good first issue` — or read [CONTRIBUTING.md](CONTRIBUTING.md). It's one HTML file; if you can edit a list, you can contribute.

## License

MIT — see [LICENSE](LICENSE).

Built by Amitesh Srivastava with Muse (Spark).
