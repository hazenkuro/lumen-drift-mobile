# Lumen Drift — Mobile

A neon arcade game: steer the light-skiff, collect star shards, dodge void mines and storm shards, reach 1,200 points to open the Aurora Gate.

Play it here: https://hazenkuro.github.io/lumen-drift-mobile/

This is the mobile-fixed build of Lumen Drift (originally a make.fun best-game-01 entry):

- One uniform scale + letterboxed field, so the ship's drawn position is exactly its collision position on any screen shape (the original scaled X and Y separately, so the collider did not match the player on non-16:9 screens).
- Touch controls: drag to steer, on-screen DASH and pause buttons, no-zoom viewport, rotate-to-landscape hint.
- Crisp rendering on hi-DPI phone screens.

Controls: Arrows / WASD, mouse or drag to steer — Space, click or DASH to dash — P pauses, R restarts, M mutes.

Single self-contained file (`index.html`, no network dependencies). The multi-file source lives in the author's workspace.
