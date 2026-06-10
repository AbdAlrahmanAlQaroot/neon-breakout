# Neon Shuffle

8 arcade games. One life. The game switches on you **without warning**.

**Play it:** https://abdalrahmanalqaroot.github.io/neon-breakout/

## How it works

You pick a difficulty and get thrown into a random game. Every few seconds — you never
know exactly when — the game freezes and shuffles you into a different one, exactly where
you left it. Die in **any** game and the whole run is over. One shared score across all eight.

## The games

| Game | You... | Die when... |
|---|---|---|
| BREAKOUT | bounce a ball into bricks (power-ups, explosive + steel bricks) | the last ball falls |
| FLAPPY | flap through neon pipes | you hit a pipe or the ground |
| SNAKE | eat, grow, steer | you hit a wall or yourself |
| DODGE | weave through falling asteroids | one hits you |
| PONG | out-rally a tracking AI | the ball gets past you |
| RUNNER | jump spikes, duck under bars | you clip anything |
| STACK | drop sliding blocks on the tower (auto-drops if you stall) | you miss the stack |
| INVADERS | strafe + autofire at marching aliens | they shoot you or reach you |

## Difficulty

- **EASY** — slower games, lazy switches (8–14s), ×1 score
- **NORMAL** — fair speeds, 4–9s switches with occasional ambushes, ×1.5 score
- **HARD** — 1.3× game speed, tiny paddles, near-perfect pong AI, 2.5–6s switches,
  40% chance of a ~1.5s ambush switch, ×2.5 score

High scores are saved per difficulty in your browser.

## Controls

Mouse / touch / arrows / WASD move things. Tap or Space jumps, flaps, launches, and drops.
Snake turns with arrows, or tap the left/right half of the screen. `P` pause, `M` mute.

Getting shuffled in mid-disaster would be unfair, so every game grants a small mercy on
entry (clearing projectiles about to hit you, auto-turning a doomed snake, etc).

## Run locally

Open `index.html` in a browser. No build, no dependencies, one file.
