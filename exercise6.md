# JSONQuery Exercise 6 Educom Traineeship

With this command we have to fidget a bit with the data, namely replacing \t with commas. We do it this way to make importing to a spreadsheet program a lot easier, since most have trouble interpreting the escaped characters produced by `@csv`. We then also need to fix the line for the United States and do some number conversions but this is no large overhead.

`jq '["rank", "cca3", "country", "capital", "continent", "population_2022", "population_2020", "population_2015", "population_2010", "population_2000", "population_1990", "population_1980", "population_1970", "area_km2", "population_density", "population_growth_rate", "percentage_world_population"], (.[] | to_entries | map(.value)) | @tsv' < world-population.json > world-population.tsv
`

See `world-population.csv` for the results.
