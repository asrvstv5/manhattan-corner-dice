# Contributing

Thanks for wanting to help people get lost on purpose.

This project is deliberately tiny: **one self-contained `index.html`**, no build step, no dependencies, no server. Please keep it that way.

## Easy places to start

- **Fix a corner.** If the dice sends you somewhere that doesn't exist, is misnamed, or isn't publicly reachable, open an issue with the corner it gave you. The intersection pool lives near the top of the script in `index.html` — each avenue lists the street range where it actually exists.
- **Improve a range.** Avenue start/end streets are approximations. A PR that corrects a range (with a source, e.g. a map) is very welcome.
- **Add a city.** Another grid city (Chicago, Barcelona's Eixample, Buenos Aires…) mostly means adding its own avenue/range table and neighborhood labels.

## Making a change

1. Fork the repo and make your change in `index.html`.
2. Open the file in a browser and roll a few dozen times. Check that every result is a real corner, that Maps links work, and that light/dark mode both look right.
3. Open a pull request describing what changed and how you tested it.

## Ground rules

- No dependencies, build tools, or frameworks — vanilla HTML/CSS/JS only.
- No tracking, analytics, accounts, or cookies. Roll history is session-only, on purpose.
- Every corner must be real. If you're not sure an intersection exists, leave it out.
