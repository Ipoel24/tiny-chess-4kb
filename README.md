# Tiny Chess Engine (≤4 KB)

Python chess engine for the [make.fun tiny-chess-01](https://make.fun/bounty/tiny-chess-01) bounty.

- Alpha-beta + quiescence + null-move pruning + killer moves
- Piece-square tables
- Fixed node budget (~80k)
- Pure stdlib, deterministic
- Packed main.py: 2795 bytes (lzma+base64)

Target: ≥1900 Elo on the house gauntlet (practice).

## Run

```bash
MAKEFUN_ENV_URL=... python main.py
```

MIT License.
