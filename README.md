# Arcade

A collection of small browser arcade games, each in its own directory.

## Breakout

[Game source](breakout/) — a two-level Breakout game in Atlético Madrid red, white, and navy, with scores, three lives, and synthesized crowd and milestone sounds.

- Use **Left / Right arrows** to start, move, and restart. The ball serves automatically.
- Clear both levels to win. Your best score is saved in your browser.
- Type **A, S, D** during play to leave one brick needing one hit in the current level.
- Audio starts after interaction; Spanish goal speech depends on browser speech support.

## Play locally

No dependencies or build step required. From the repository root:

```sh
python3 -m http.server 5173 --bind 127.0.0.1
```

Open <http://127.0.0.1:5173/breakout/>. Add future games in separate top-level directories.
