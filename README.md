# Sum up 18 November's world news in one image

Entry for the make.fun competition `news-image-20261118`.

## What it is

`main.py` (Python 3, standard library only) draws a one-page newspaper
front page — **"THE WORLD IN ONE DAY — WEDNESDAY, 18 NOVEMBER 2026"** —
and writes it to `/output/entry.png` (1024x1024 PNG, ~21 KB). It draws
everything itself: a 5x7 bitmap font, a tiny raster engine, and a
hand-rolled PNG encoder. No network, no third-party packages, no system
fonts. Two runs produce byte-identical output.

Run locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

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
