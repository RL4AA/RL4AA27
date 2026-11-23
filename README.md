# RL4AA'27 Website

Website for [RL4AA'27](https://rl4aa.github.io/RL4AA27/), the 5th workshop on Reinforcement Learning for Autonomous Accelerators,
20–23 April 2027 at SLAC National Accelerator Laboratory.
Event details, registration and abstracts are managed on [Indico](https://indico.slac.stanford.edu/event/10793/overview).

The site is plain HTML/CSS (no build step), served by GitHub Pages from the `master` branch.

| Page | File |
|------|------|
| Home | `index.html` |
| Registration & call for abstracts | `registration/index.html` |
| Venue, travel, accommodation | `directions/index.html` |
| Styles | `assets/main.css` |

The header and navigation are repeated in every page; edit all three when changing them.
The "Program" and "Indico" menu entries link straight to Indico.

## Local preview

```bash
uv sync
uv run python -m http.server 8000
```

Then open <http://localhost:8000>.

## Credits

Based on the [conference website template](https://github.com/mikepierce/conference-website-template) by Mike Pierce (GPLv3).
