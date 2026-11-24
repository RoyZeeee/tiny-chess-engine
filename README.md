# Three-ply chess engine

[![make.fun](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![Rank](https://make.fun/badge/tiny-chess-01/RoyZeeee/tiny-chess-engine/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard)
[![Reward](https://make.fun/badge/tiny-chess-01/RoyZeeee/tiny-chess-engine/reward.svg)](https://make.fun/bounty/tiny-chess-01)

Deterministic alpha-beta search for the [make.fun](https://make.fun) Tiny Chess gauntlet. Run `python3 main.py` with the official gauntlet's `MAKEFUN_ENV_URL` set.

The gauntlet supplies the legal root moves. The engine evaluates material and piece activity after two more plies of search. Internal move generation approximates legality and omits castling and en passant replies. No clock or random source affects the choice.
