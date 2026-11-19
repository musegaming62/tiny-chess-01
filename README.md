# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/musegaming62/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/musegaming62/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4,096-byte chess engine in a single `main.py`: an lzma + base85 payload unpacking a 0x88-board negamax engine (alpha-beta + PVS, transposition table with incremental Zobrist hashing, killer moves, MVV-LVA ordering, quiescence over captures, promotions and check replies, fixed 100,000 nodes per move — fully deterministic, no clock, no randomness). Speaks the env protocol (UCI over HTTP) at `MAKEFUN_ENV_URL`. Python 3.13, standard library only.

## Run it

```sh
python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=qpvh92a1&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
