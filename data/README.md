# sources

## alcohol
https://ourworldindata.org/grapher/total-alcohol-consumption-per-capita-litres-of-pure-alcohol

## smoking
https://ourworldindata.org/grapher/share-of-adults-who-smoke

## gambling
https://www.statista.com/outlook/amo/gambling/worldwide/#revenue
- Gambling is split up into Sports Betting, Casinos & casino games, Lottery & bingo per country.
- By decision, we will use the maximum out of these three values; the statista visuals have some sort of "combined metric" that takes overlap into account, but no such column exists in the dataset, so to be safe, we use the maximum of these three gambling categories; semantically, something like 50% Sports Betting would mean "at least 50% user penetration" which is safer than making up a combined statistic.

# example processed schema

| Country (ID or name) | Earliest alcohol year | Alcohol in earliest year | Alcohol in 2020 | Earliest smoking year | Smoking in earliest year | Smoking in 2020 | Earliest gambling year | Gambling in earliest year | Gambling in 2020 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| USA | 2000 | | | 2000 | | | 2017 | | |
| South Sudan | 2011 | | | 2014 | | | 2017 | | |
