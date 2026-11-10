# GMChess puzzle packs

Extra puzzles the GMChess app can download (Puzzles → puzzle rating card → **More**):
`pack-1000.json`, `pack-2000.json`, `pack-5000.json`. There are 8,000 different puzzles, none of them in the app's bundled set.

Source: the [Lichess open puzzle database](https://database.lichess.org/#puzzles) (CC0).
Built by `mobile/scripts/build-puzzle-packs.py` in the app repo.
Format: `{ "sets": [theme…], "p": [[id, fen, uciMoves, rating, [setIndex…]], …] }`, the same as the app's `assets/puzzles/lichess.json`.
