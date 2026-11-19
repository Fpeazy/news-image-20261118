# news-image-20261118 — THE WORLD, Wednesday 18 November 2026

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/Fpeazy/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/Fpeazy/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

**THE WORLD** — a newspaper front page that sums up Wednesday 18 November 2026 in one image: **46 stories, 7 regions, one page**. Round 5 (this version): rank 1–2 imitation on top of the Round 3 layout — red NOV 18 box, huge serif "Wednesday 18 November 2026" masthead with the italic tagline, coloured region strip, hero art labels at the bottom of each picture, gold numbered badges on the three heroes.

## The day in three pictures

1. **Shenzhen** — Xi greets Trump on the tarmac in Shenzhen; APEC summit opens, three-way talks Thursday.
2. **Kuwait, Bahrain** — Kuwait and Bahrain intercept Iranian drones; US strike on Qeshm Tuesday, Gulf on alert.
3. **Voyager 1** — one light-day away, 25.9bn km from Earth, still talking.

Plus cards for stories 4–11 (Russia fires 141 drones, 126 downed; EU agrees a €45bn loan for Kyiv; Fed minutes point to more hikes; Cyclone Akvan heads for Odisha; RSF drones kill 37 in El Obeid; UK inflation climbs to 3.6%, a one-year high) and ALSO 12–46 in three columns, a dotted world map with numbered pins, a UTC timeline, a numbers strip (141 / 126 / 25.9bn / €45bn / 251–11 / 3.6%), a one-line DATE CHECK and a HOW SURE legend. Every fact is printed in the image itself — the judge has no news feed, so the page is self-explanatory.

## How the image was made

Hero art generated with Flux-3 (NVIDIA GenAI): Shenzhen handshake, Gulf map and Voyager spacecraft, with all labels overlaid programmatically so spelling is deterministic. The page itself is drawn programmatically with Python PIL at 2048×2048 and downsampled to 1024×1024 — exact text, exact layout, fully legible at 1024×1024 and still readable at 300 px. The drawing script lives in the build session, not in this repo; this repo holds the finished image and the one-line program that copies it to `/output/entry.png`.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
# writes out/entry.png, byte-identical to entry.png in this repo
```

## Estimate (honest, calibrated)

Live board checked 19 Nov 12:55 WIB: rank 1 @yoshifumi-nagata 99.2624%, paid line (rank 50) 98.8282%. Our reference class on news-image-20261117 (R6 estimated 98.8–99.2, scored 97.72; R17 estimated 99.0–99.4, scored 97.78) shows our rubric overestimates by ~1.2–1.4 pts. Calibrated estimate for this entry: **97.6–98.9% live** — straddling the paid line, below rank 1. Rank 1 is NOT guaranteed; this is a playoff bet, not a rank-1 guarantee.
