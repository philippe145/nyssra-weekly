# NYS Weekly Alpine Ski Racing Analysis

New York State Ski Racing Association slalom and giant slalom results, analyzed race by race. Racers are shown by first name only; an anonymous code links each racer's results across races.

Live page: https://philippe145.github.io/nyssra-weekly/

- **Race reports**: % behind the winner for every finisher, run 1 vs run 2 ranks and gaps, run-2 movers.
- **Club ranking**: 60% speed index (run winner's time / racer's time x 100, average of each club's best three per run) + 40% finish rate, by age group (U14, U16-U18) and gender.
- **Spotlight racers** and a Hunter vs Windham comparison.
- **Courses**: vertical drop and course name per race where the timing report publishes them.

## Data
`data/races.json` holds one record per race and gender with every racer's run times, from live-timing.com and vola.ussalivetiming.com; West council races and one slalom come from AdminSkiRacing official tables (totals only). A weekly update adds new races each Monday from January 2027.

All figures are computed in the page from the stored results.
