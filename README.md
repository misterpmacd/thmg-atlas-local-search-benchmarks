# THMG's Atlas: U.S. Local Search Revenue Benchmarks

Modeled monthly revenue and profit of ranking #1 on Google, for 129 home services in 238 US cities (3,315 service-and-city rows, updated November 2026).

Each row has monthly search volume (Google Keyword Planner), an average job value sourced from published cost guides, close-rate and margin assumptions, a conservative and a standard revenue and profit range, a competition score, and an opportunity index. These are modeled estimates, not guarantees.

## Files
| File | Contents |
|---|---|
| `data/atlas-pairs.csv` | One row per service and city (3,315 rows) |
| `data/atlas-pairs.json` | Same data as JSON |
| `data/atlas-cities.csv` | The 238 cities with population and number of services analyzed |
| `data/atlas-trades.csv` | The 129 services with average job value, close rate and margin |

## Key columns (`atlas-pairs.csv`)
`trade`, `city`, `state`, `monthly_searches`, `avg_job_usd`, `close_rate`, `margin`, `revenue_low_usd`, `revenue_high_usd`, `profit_low_usd`, `profit_high_usd`, `difficulty_score`, `difficulty_tier`, `opportunity_index`.

## Method and limits
See https://www.thmg.com/methodology/. The browsable version, with a page for every city and service, is at https://www.thmg.com/atlas/. The latest data is always at https://www.thmg.com/data/.

## License and citation
Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): free to use, share and adapt with credit.

> THMG (The Highland Marketing Group), *THMG's Atlas: U.S. Local Search Revenue Benchmarks*, November 2026. https://www.thmg.com/atlas/ (CC BY 4.0)

Published by [The Highland Marketing Group](https://www.thmg.com/about/), Fort Wayne, Indiana, since 1999.
