# tiny-chess-01

A chess engine in 4 KB of Python, built for the make.fun tiny-chess-01
competition ("strongest chess engine in 4 KB of Python").

`main.py` (4,084 bytes) is a self-contained engine: alpha-beta + PVS search
with quiescence, a transposition table, and a tapered PeSTO-style evaluation,
packed with lzma. It plays over the competition's HTTP env protocol and never
resigns. Local practice Elo vs the house gauntlet: ~1500-1600.

License: MIT.
