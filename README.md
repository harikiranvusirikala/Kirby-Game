# Kirby like Platformer Game made with TypeScript + Kaboom.js

Live at [https://harikiranvusirikala.github.io/Kirby-Game/](https://harikiranvusirikala.github.io/Kirby-Game/).


Controls for the demo :

- Arrow keys for movement
- Z key for jumping
- X key for inhaling enemies and for shooting once inhaled.

## Files and purpose:

- constants.ts - for constants
- entities.ts - contain the logic for our players, our mobs, enemies etc
- kaboomCtx.ts - to initialize kaboom library and export it's context
- main.ts - entry point of our project
- state.ts - to hold the global state of the game (eg: useful to know when to move on to next scene)
- utils.ts - related to making the map
