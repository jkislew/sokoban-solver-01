# Sokoban Solver

[![make.fun](https://make.fun/badge/sokoban-solver-01-run-20261121.svg)](https://make.fun/bounty/sokoban-solver-01-run-20261121)
[![rank](https://make.fun/badge/sokoban-solver-01-run-20261121/jkislew/sokoban-solver-01/rank.svg)](https://make.fun/bounty/sokoban-solver-01-run-20261121)
[![reward](https://make.fun/badge/sokoban-solver-01-run-20261121/jkislew/sokoban-solver-01/reward.svg)](https://make.fun/bounty/sokoban-solver-01-run-20261121)

Push-optimal Sokoban solver: each level is split into rooms at its hallway, and every room is solved with a breadth-first search over pushes, so each room takes the fewest pushes possible and the rooms' optima sum to the level's optimum. Dead squares and frozen 2x2 blocks are pruned, states are keyed by box squares plus the player's reachable region, and all budgets count states rather than the clock, so runs are deterministic.
