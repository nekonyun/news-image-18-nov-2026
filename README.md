# news-image-18-nov-2026

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/nekonyun/news-image-18-nov-2026/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/nekonyun/news-image-18-nov-2026/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

The World in One Day — Wednesday 18 November 2026. Entry for the make.fun bounty
[news-image-20261118](https://make.fun/bounty/news-image-20261118):
one image summing up the world's news of Wednesday 18 November 2026.

## The image

A newspaper front page, drawn as a web page and screenshotted to
`entry.png` (1024×1024, PNG):

- **Masthead:** THE WORLD IN ONE DAY — WEDNESDAY · 18 NOVEMBER 2026
- **Four lead stories:** Iran strikes U.S. radar in Bahrain; Ukraine hits the
  Crimea Bridge for a second day; Trump lands in Manila for Quad talks ahead
  of APEC; Nvidia revenue doubles to $115.84bn in its first results since
  CEO Jensen Huang was ousted.
- **Also today:** Dhoni's IPL retirement, India's record 10th SAFF title,
  Cyclone Akvan, Voyager 1 nearing one light-day from Earth, UK sanctions on
  8 firms, and the Canada–China trade deal extension.

Every fact in the image comes from news first reported on 18 November 2026.
The four panels use flat hand-drawn vector art (radar and drone, suspension
bridge, airliner over a skyline, chip and bars) so every label stays crisp —
no AI-generated imagery, no garbled text. The design is a red-and-black
broadsheet system: the Gulf story leads as an inverted black panel, each
headline carries one red signal word, stories are numbered 01–04, and
ALSO TODAY runs as a black band over a faint newsprint grain.

## How it was built

`page.html` holds the front page (HTML/CSS with inline SVG art) and
`shot/shot.mjs` renders it with headless Chromium at exactly
1024×1024. The shipped `entry.png` is that render. (The build sources
live outside this repository; only the rendered image ships here.)

## The program

`main.ts` (Node 22, standard library only) copies `entry.png` to
`/output/entry.png` (or `$MAKEFUN_OUTPUT_DIR`). It runs with no network.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see `LICENSE`.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
