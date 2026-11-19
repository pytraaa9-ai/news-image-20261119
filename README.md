# news-image-20261119

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/pytraaa9-ai/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/pytraaa9-ai/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

A program that writes one image summing up Thursday 19 November 2026 world news — a newspaper front page (1024×1024 PNG): lead story the first Trump–Xi–Putin trilateral at APEC in Shenzhen, plus 32 more stories across six continents, a world map, and the day's biggest business story, Anthropic's record $81.3bn IPO.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## The day's news

- **Lead:** Trump, Xi and Putin meet in Shenzhen — the first trilateral of the three leaders opens at APEC; nuclear arms, Ukraine, Iran and trade on the table; Xi hugged Trump on arrival; Putin sees "big potential benefit".
- Crimea Bridge hit a third time this week; traffic halted
- EU proposes a €45bn Ukraine loan, repaid once Russia pays reparations
- Russian arrested for spying on US defence firm Palantir over Ukraine support
- France braces for a fourth weekend of cost-of-living protests; police clash with strikers in Spain
- Van Gogh painting sells for a record $190.4m after a row over its Nazi-era history
- Democrats nominate Hakeem Jeffries for Speaker 251–11; he would be the first Black Speaker
- Anthropic's IPO raises a record $81.3bn at $83 a share; trading starts today as ANT
- US senators warn AI-enabled cyber threats are outpacing defences
- Fed minutes point to more rate hikes
- Nvidia halts H-series chip shipments to China
- Liu Yunping makes history as the first Taiwanese American to chair the House Democratic Caucus
- US panel targets China over Panama-flagged ship seizures
- Microsoft eyes an AI deal with ByteDance
- Eisenkot tapped to form Israel's government, bypassing Netanyahu
- Four nations demand Gaza aid access as floods worsen
- Israeli tanks cross the Gaza ceasefire line in a rare ground raid
- Saudi Arabia says the danger has passed in three southern cities
- US–Iran exchanges grind on around the Gulf; oil eases
- 1,100 child amputees in Gaza face treatment limits, NGO says
- Canada recalibrates its China ties
- India and Japan open 2+2 defence talks
- Cyclone Akvan bears down on India's east coast
- Myanmar faces a historic genocide verdict at the UN court
- GTA VI rolls out worldwide; gamers enter Vice City
- Australia sanctions Israeli settlement expansion in the West Bank
- India's Congress presses Modi on inflation
- US details $12bn in Venezuelan oil and mineral revenue
- Bukele hails a raid on a Haiti gang leader's home
- Voyager 1 hits one light-day from Earth
- Pew: Islam on track to be the world's largest religion by 2035
- World COPD Day spotlights early diagnosis
- BBC report on abuse at McDonald's shocks

All stories were verified against at least two reputable sources
(Reuters, AP, AFP, Al Jazeera, UN News, NASA) on 19 November 2026.
Note: this v1 entry covers overnight and morning news of 19 November
2026; afternoon and evening developments go into a full-day v2.

## How it works

`main.py` (Python 3.13, standard library only, no network) copies the
committed `entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png`
(falling back to `/output/entry.png`). The copy is byte-for-byte, so two
runs always produce identical output.

## License

MIT — see `LICENSE`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=x9vj0gh6&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>
