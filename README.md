# Alyssa's Hogwarts Learning Games 🦉

Hogwarts-themed learning games for Alyssa's Grade 7 (Ontario) work: weekly spelling lists plus math.

**Play:** https://nick-seward.github.io/alyssa-games/

| Week / Subject | Game | Folder |
|------|------|--------|
| 5 | Word Search | [`week-5-word-search/`](week-5-word-search/) |
| 6 | Word Scramble | [`week-6-word-scramble/`](week-6-word-scramble/) |
| 7 | Guess the Word | [`week-7-guess-the-word/`](week-7-guess-the-word/) |
| Math | Slope Explorer (rise over run) | [`math-slope-explorer/`](math-slope-explorer/) |

Each game is a single self-contained `index.html` with no dependencies.

## Adding a new game
1. Create a folder such as `week-8-<game-name>/` or `math-<topic>/` with an `index.html`.
2. Add an entry to the end of the `GAMES` list near the bottom of the root `index.html` (newest shows first). Use `week: N` for a spelling week, or `label: "Math"` for a subject.
