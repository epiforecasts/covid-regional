# covid-regional

> **Archived.** No longer maintained; last updated July 2020. It depends on the retired `EpiNow` and `NCoVUtils` packages and on national data sources as published at the time.

Results store for the subnational Rt estimates for Brazil, Germany, India, Italy, the United Kingdom and the United States shown on the epiforecasts COVID-19 website, held as a submodule of epiforecasts/covid. It was started afresh in June 2020; earlier results are in epiforecasts/covid-regional-archive. Later estimates are in epiforecasts/covid-rt-estimates.

- `update_nowcasts.sh`: updates the shared reporting delay (`update_delay.R`, saved as `delays.rds`) and runs each country's `update_nowcasts.R`.
- `<country>/regional/`: per-region estimates and plots.
- `<country>/regional-summary/`: country summary tables, plots and `rt.csv`.
- `<country>/data/`: region codes and boundary files for the maps.
