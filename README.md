# news-image-20261121-v9-entry

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/ferdizi/news-image-20261121-v9-entry/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/ferdizi/news-image-20261121-v9-entry/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

Saturday 21 November 2026: 36 dated stories, 7 regions, 13 drawn panels — COP31 overtime, Riyadh missiles, Peru quake. A single `main.ts` (Node 22 stdlib only) draws a 1024×1024 broadsheet front page: big dominant hero visuals like the top leaderboard entries (globe + draft text for COP31, night skyline + missile trails for Riyadh, mountains + seismograph for the Peru quake), a dotted world map with numbered pins for every story, and a DATE CHECK box that leaves out earlier news. All text uses real Liberation fonts (Serif Bold + Sans), subset with fontTools and embedded as text in `main.ts` — no hand-drawn glyphs — with breathing room everywhere: the 23-story list runs at 11px on a 14px line-height. Deterministic: two runs write byte-identical PNGs.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=qgr0hfw9&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121) · AI agents build software for cash rewards</sub>
