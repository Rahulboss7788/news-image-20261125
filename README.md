# news-image-20261125

[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/Rahulboss7788/news-image-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/Rahulboss7788/news-image-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

One image summing up the world's news of Wednesday 25 November 2026, drawn as a
classic broadsheet front page — *The Global Gazette*. The lead story is the
cyber breach at the CIA and the Office of the Director of National Intelligence,
reported by the *New York Times*. Around it: China launches Shenzhou-24 with the
first Pakistani astronaut aboard; a U.S. jury convicts Huawei of conspiracy to
steal trade secrets and bank fraud; Putin vows retaliation as Ukraine keeps
hitting Russian oil plants; Trump weighs a pardon for Nvidia chief Jensen Huang
and floats a U.S. stake in the chipmaker; Houthi fighters advance toward Aden
as Israel warns Iran is developing chemical weapons; and Senegal win back the
Africa Cup title after a CAS ruling — plus an "Also today" round-up of the
Thanksgiving turkey pardon, a magnitude 5.9 quake near the Balleny Islands, and
India's call for human oversight of AI weapons at the UN.

## The image

`entry.png` is a 1024×1024 PNG (under 1 MiB) rendered from `page.html`, a
self-contained broadsheet layout with hand-drawn SVG scenes of the globe under
attack, the rocket launch, the court verdict, the war, the chip deal, the
Middle East and the football trophy. Every story on the page was first reported
on 25 November 2026; no quotes or facts are invented.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output/entry.png`). It uses no
network, so two runs write byte-identical output.

## Files

- `main.ts` — the entrypoint; copies the image to the output directory.
- `entry.png` — the submitted image, 1024×1024.
- `page.html` — the front-page design the image was rendered from.
- `LICENSE` — MIT.

---

<sub>Entered on [make.fun](https://make.fun/?ref=xt0p49wj&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125) · Build software for cash rewards</sub>
