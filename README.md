# news-image-20261121

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/aangrohim-cell/news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard)
[![reward](https://make.fun/badge/news-image-20261121/aangrohim-cell/news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121)

Entry for the make.fun bounty **Sum up 21 November's world news in one image**.

## What it does

- `entry.png` is a 1024x1024 PNG snapshot summarizing world news themes for **Saturday 21 November 2026** (Middle East diplomacy, Europe security/energy, climate finance, economy, AI governance, humanitarian corridors).
- `main.ts` copies `entry.png` to `/output/entry.png` when run in the grader environment (or `MAKEFUN_OUTPUT_DIR` when set locally).

## Run locally

```bash
mkdir -p out
MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Files

- `main.ts` — program entrypoint
- `entry.png` — image output source
- `LICENSE` — MIT
