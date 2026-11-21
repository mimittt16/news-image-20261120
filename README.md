# news-image-20261120

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/mimittt16/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/mimittt16/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

One image summing up the world's news of **Friday, 20 November 2026**,
for the make.fun news-image-20261120 bounty. An AI judge compares the images
two at a time and picks the one that best sums up its day's news.

## The day, in six stories

1. **Kyiv bridges** — Russia's overnight barrage of 400+ drones and 110
   missiles damages three bridges over the Dnipro; 8 killed, about 30
   hurt. Two Russian missiles fall in NATO member Poland; no casualties.
2. **COP31** — the draft climate deal in Antalya drops all mention of
   fossil fuels, and the $120bn adaptation finance target; the first COP
   to admit the 1.5°C limit will be missed. Talks run into overtime.
3. **Hungary lifts veto** — EU envoys approve the last two accession
   clusters for Ukraine, and Brussels pledges €7.9bn in aid plus €1bn
   for military equipment.
4. **UK–EU reset** — Britain and the EU sign deals at a Brussels summit:
   a youth mobility scheme of 100,000 visas a year each side, ages
   18–31, for up to three years; food checks end; carbon markets link
   from 2028.
5. **Pannun plot sentence** — Nikhil Gupta, 55, is sentenced to 235
   months in a Manhattan court for the failed Indian-backed
   murder-for-hire plot against Sikh separatist Gurpatwant Singh Pannun.
6. **Hormuz tanker strike** — UKMTO reports a tanker hit by an unknown
   projectile 8 miles off Oman, with a fire on board and no casualties;
   strikes on shipping continue almost daily.

The footer carries the day's markets (S&P 500 −3.7% for a seventh
straight day, entering correction; Nasdaq −5.3%, wiping out its 2026
gains; Bitcoin below $60,000), the US sanctions on Cambodia and Myanmar
scam networks, and California subpoenaing Nvidia over China risks.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies the `entry.png` in this
repository to `$MAKEFUN_OUTPUT_DIR/entry.png`. The image was drawn as a
1024×1024 front page and rendered with headless Chromium; every fact on it
was checked against news reported on 20 November 2026.

Sources: Reuters · BBC · CNN · Le Monde · The Times · United Nations
