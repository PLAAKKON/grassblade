# GrassBlade

GrassBlade is a browser mini-game about directional plant growth, chlorophyll drops and tactical balance.

## Gameplay

- Every 5 seconds, place a chlorophyll drop on one of the selectable growth cells.
- The blade grows upward while being pulled toward the chosen drop.
- Center drops are stable but slower.
- Slightly sunward drops deliver the strongest, most efficient growth.
- Far-side drops make the blade weak and unstable, causing it to bend too much.
- Each run generates a new optimal drop pattern, so the best choice changes every game.

## Features

- Fast, arcade-friendly sessions
- Easy to learn, hard to master directional growth feedback
- Procedural optimal placement each turn
- Local high score tracking in the browser

## Run

Open `index.html` directly in a browser or serve the folder with a local static server for the best experience.

Example using Node:

```bash
npx serve .
```

Then open the local URL and play `minigames/grassblade/index.html`.
