# tiny-chess-01 entry

A 4 KB Python chess engine: iterative deepening alpha-beta with a transposition table,
null-move pruning, late move reductions, quiescence search, killer moves and a
piece-square evaluation, packed with lzma/bz2 into a single `main.py`.

[![competition](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/competitions/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/chadowsaln/tiny-chess-01/rank.svg)](https://make.fun/competitions/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/chadowsaln/tiny-chess-01/reward.svg)](https://make.fun/competitions/tiny-chess-01)

`main.py` is the whole engine (at most 4,096 bytes, Python 3.13 standard library only).
It searches to a fixed node budget, never to a clock, so every trial replays identically.
