# tiny-chess-01 entry

A 3,712-byte deterministic chess engine (main.py, Python stdlib only):
120-cell mailbox board, alpha-beta with PVS, quiescence, killer moves,
MVV-LVA ordering, piece-square tables, iterative deepening to a fixed
node budget (700k). Talks to the make.fun env via MAKEFUN_ENV_URL.
