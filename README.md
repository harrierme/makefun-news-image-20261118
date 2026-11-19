# makefun-news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/harrierme/makefun-news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/harrierme/makefun-news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

`main.py` draws a one-page newspaper front page summing up 18 November 2026's world news in a single 1024x1024 image, rendered entirely with Python's standard library.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=szgskt7z&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>

## What it is

`main.py` (Python 3, standard library only) draws a one-page newspaper
front page — **"THE WORLD IN ONE DAY — WEDNESDAY, 18 NOVEMBER 2026"** —
and writes it to `/output/entry.png` (1024x1024 PNG, ~21 KB). It draws
everything itself: a 5x7 bitmap font, a tiny raster engine, and a
hand-rolled PNG encoder. No network, no third-party packages, no system
fonts. Two runs produce byte-identical output.

## The seven stories

All happened, or were first reported, on Wednesday 18 November 2026:

- **Lead — Shenzhen:** APEC opens; Xi Jinping meets Vladimir Putin; the
  first-ever Trump–Xi–Putin trilateral summit is set for Thursday. The
  Quad leaders also met in Manila.
- **Middle East:** US jets strike a Revolutionary Guards missile site on
  Qeshm Island; Iran fires at US bases in Kuwait and Bahrain.
- **Europe:** Ukraine strikes the Kerch (Crimea) Bridge a second day;
  part of the road span collapses.
- **United States:** Democrat Mary Peltola wins Alaska's Senate seat;
  Democrats take a 56–44 Senate majority.
- **Health:** The US loses measles-free status after 26 years; the DR
  Congo Ebola outbreak passes 11,000 cases.
- **Space:** Voyager 1 passes one light-day from Earth, about 16 billion
  miles out — a first for any human-made object.
- **Climate:** COP31 climate talks open in Antalya, Turkey.

`entry.png` in this repository is the exact image the program produces,
committed for reference.

## License

MIT — see `LICENSE`.
