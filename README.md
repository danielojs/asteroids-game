# Asteroids Game

A pygame implementation of Asteroids built through Boot.dev assignments.

## Run

```bash
uv sync
uv run main.py
```

## Controls

- `A` / `Left Arrow`: rotate left
- `D` / `Right Arrow`: rotate right
- `W` / `Up Arrow`: move forward
- `S` / `Down Arrow`: move backward
- `Space`: shoot (rate-limited)

## Gameplay

- Asteroids spawn from screen edges.
- Shots destroy asteroids.
- Large and medium asteroids split into smaller/faster asteroids.
- Collision between player and asteroid ends the game.

## Logs

- `game_state.jsonl`: periodic game state snapshots
- `game_events.jsonl`: key events (hits, splits, etc.)
