# Moonlight Factory

CMPM 120 Platformer implementation.

## Important

This repo expects Phaser at:

```txt
lib/phaser.js
```

I did not include Phaser in this zip. Put your own `phaser.js` there.

## Scenes

```txt
src/scenes/Load.js
src/scenes/Platformer.js
```

## Current map setup

The uploaded `first_orbit.tmj` only had a `Platforms` tile layer.
This starter version converts it into:

```txt
assets/tilemaps/first_orbit.json
```

and adds object layers:

```txt
Spawn
Collision
Collectibles
Hazards
Exit
```

The `Platforms` layer is visual only. The real collision comes from the `Collision` object layer.
