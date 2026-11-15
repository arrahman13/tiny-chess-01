# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/arrahman13/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/arrahman13/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A deterministic chess engine in a single 3,958-byte `main.py`: the file unpacks an lzma-packed payload at startup (packing is allowed by the rules) into a negamax alpha-beta engine with PVS, a transposition table, quiescence search, null-move pruning, LMR, check extensions, killer/history ordering, and piece-square tables with endgame king/pawn tables. Fixed 55,000 nodes per move — no clocks, no randomness, no model calls. Kit practice instances scored Elo 1,654 / 1,451 / 1,279 against a house baseline of 1,364 / 1,451 / 1,279.

## Run it

```sh
python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=pb4k2c9b&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
