# news-image-20261119

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/pytraaa9-ai/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/pytraaa9-ai/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

A program that writes one image summing up the full day of Thursday 19 November 2026 world news — a newspaper front page (1024×1024 PNG): lead story the UN court ruling that Myanmar committed genocide against the Rohingya, plus 37 more stories across six continents, a world map, and the day's biggest business story, Anthropic's record IPO debut.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## The day's news

- **Lead:** The UN's top court rules 9–6 that Myanmar's army acted with genocidal intent against the Rohingya in 2017 — the first time it has held a state responsible for genocide. Refugees in Bangladesh cheered as the verdict was read.
- **The summit in Shenzhen:** Trump, Xi and Putin hold the first three-way summit of the great powers and issue a four-point "Declaration toward Peace" — "a nuclear war cannot be won" — but no deal on Ukraine.
- Crimea Bridge hit a third time; Putin vows a harsher response
- EU proposes a €45bn Ukraine loan, repaid once Russia pays reparations
- Ukraine's European allies meet in Berlin, say they are ready for talks with Russia
- Denmark ratifies the US–Greenland security deal 109–0; two new defence areas
- EU Commission hit in an AI-powered cyberattack
- France braces for a fourth weekend of cost-of-living protests; police clash with strikers in Spain
- Van Gogh painting sells for a record $190.4m after a row over its Nazi-era history
- Democrats nominate Hakeem Jeffries for Speaker 251–11; he would be the first Black Speaker
- Liu Yunping makes history as the first Taiwanese American to chair the House Democratic Caucus
- Trump posthumously pardons Pete Rose
- Anthropic's debut: shares open at $111.50, briefly top a $2tn value, then close at $97.17, up 17%
- Wall Street slides 2% for a fifth straight day; S&P 500 falls 2.02%, Nikkei drops 4.68%
- Nvidia halts H-series chip shipments to China
- Microsoft eyes an AI deal with ByteDance
- US panel targets China over Panama-flagged ship seizures
- Israel ends its Nuseirat ground raid a day after it began; four killed
- Aid groups score the Gaza peace plan 4 of 26; five groups say it is falling far short
- 1,100 child amputees in Gaza face treatment limits, NGO says
- Eisenkot tapped to form Israel's government, bypassing Netanyahu
- Iran escalates Hormuz tanker attacks; Kuwait says it repelled an Iranian attack
- Houthi rocket debris hits a Riyadh tower after an intercepted attack
- West presses Iran at the IAEA to let inspections resume at bombed nuclear sites
- Bangladesh violence spreads; Yunus's ancestral home torched, protests hit 28 districts
- Mongolia's president resigns; parliament accepts
- IAEA says North Korea has expanded uranium enrichment
- Cyclone Akvan bears down on India's east coast
- India and Japan open 2+2 defence talks
- Tanzania opposition leader Lissu convicted of sedition
- Migrant boat capsizes off Senegal; dozens missing
- Haiti raid kills 34 gang members; police retake the Martissant corridor
- US and Venezuela sign a military cooperation deal
- Australia sanctions Israeli settlement expansion in the West Bank
- Voyager 1 hits one light-day from Earth
- GTA VI rolls out worldwide; gamers enter Vice City
- US loses measles elimination status after outbreaks and falling vaccine coverage
- BBC report on abuse at McDonald's shocks

All stories were verified against at least two reputable sources
(Reuters, AP, AFP, BBC, Al Jazeera, UN News, NASA) on 19–20 November 2026.
Note: this v2 entry covers the full day of 19 November 2026,
replacing the morning-only v1 entry.

## How it works

`main.py` (Python 3.13, standard library only, no network) copies the
committed `entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png`
(falling back to `/output/entry.png`). The copy is byte-for-byte, so two
runs always produce identical output.

## License

MIT — see `LICENSE`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=x9vj0gh6&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>
