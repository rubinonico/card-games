# AGENTS.md — card games

Three self-contained browser games. **Vanilla HTML/CSS/JS, zero dependencies, zero build step.** Each file
is a complete, playable game — open it in a browser and it runs.

## Files

| File | What it is |
|---|---|
| `index.html` | Landing page linking the three |
| `five-column-poker.html` | Five-Column Chinese Poker, 1-swap variant — hand evaluation and scoring across five columns |
| `holdem-scratch.html` | Hold'em Hotstreak — scratch-and-match, Texas Hold'em themed. First build |
| `holdem-scratch-B.html` | Hold'em Hotstreak v2 — second build of the same game |

## Rules

1. **No dependencies, no framework, no bundler.** This is the point of the repo: a stranger can view-source
   and read the whole thing. Do not introduce React, a package.json, or a build step.
2. **Each game must run from `file://`.** No fetch, no module imports that need a server.
3. **The v1/v2 pair stays.** `holdem-scratch-B.html` is kept as a second build, not a replacement — the
   diff between them is the artifact.

## Related

The same three files also live under the portfolio site (`Career/portfolio/`, `gaming.html` is the index
there). If a game changes, both copies change or the repo starts lying about what it ships.
