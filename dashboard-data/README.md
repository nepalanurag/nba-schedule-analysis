# Dashboard data: NBA Schedule Analysis

Results from `nba-schedule-analysis.Rmd` (analysis done in R; this repo's
`.ipynb` is the story write-up). The source CSVs are proprietary and not in the
repo; values below are the analysis's reported answers.

## Files

- `answers.json` — the headline answers: Q1 (26 4-in-6 stretches in OKC's draft
  schedule), Q2 (25.1 per season on average, per-82 adjusted), Q3 (most CHA
  28.1, fewest NYK 22.2), Q5 (BKN defensive eFG% 54.3% overall, 53.5% vs tired
  opponents, 2023-24), Q9 (schedule worth +0.71 wins for MIL, -1.03 for DEN over
  2019-20 to 2023-24).
- `b2b_trend.csv` — average back-to-back games per team per season (per-82
  adjusted) at the seasons called out in the write-up. Columns: `season`,
  `avg_b2b_per_82`, `approx` (true: values are as-reported approximations from
  the trend plot, not re-digitized points).

Headline: schedule effects are small next to team quality (under two wins
separating the luckiest and unluckiest schedules over five seasons), and
back-to-backs fell by a third from 2014 to 2019 before the pandemic season.
