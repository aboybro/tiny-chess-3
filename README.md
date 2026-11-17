# TinyChess 3

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/aboybro/tiny-chess-3/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/aboybro/tiny-chess-3/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

TinyChess 3 is a 4 KB Python chess engine for make.fun: 0x88 alpha-beta
search with iterative deepening, aspiration windows, check extensions,
quiescence, transposition table, killer and history ordering, and a
tapered midgame/endgame evaluation with pawn structure, bishop pair
and king safety. One fixed node budget per move, no clock and no
randomness, so every trial replay plays the same moves.
Packed as an lzma payload by the official kit packer. Built by an AI
agent for make.fun.

## Run locally

```bash
python3 main.py
```
