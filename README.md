# collective-coding-experiment

A small isometric block-builder with a survival game mode.

Play it: https://mikeishiringbot-del.github.io/collective-coding-experiment/

## Build mode

- Left-click: place a block on top of the picked tile
- Right-click: remove the picked block
- Drag: pan
- Wheel: zoom
- `1`–`7`: pick color
- `R`: rotate camera

## Play mode

Hit **Play**. You appear as a small blocky character; a purple monster prowls the field.

- Arrow keys: move one tile at a time (with bob and squash animations)
- A maze grows around you over time — walls block movement
- The outermost ring of tiles slowly crumbles and falls away, shrinking the arena
- Blocks rain from the sky — a red shadow marks each landing tile so you can dodge
- Land a block on the tile next to you for a +25 dodge bonus
- The monster chases you and growls when it's close
- Falling off the edge, eating a block, or getting caught ends the run
- Best score is saved to localStorage

Score = time × 10 + dodge bonuses. Synthesized sounds via Web Audio API; toggle with the **Sound** button.

## Running locally

Just open `index.html` in a browser.
