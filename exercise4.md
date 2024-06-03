`jq '[
  group_by(.continent)[] |
  {
    continent: .[0].continent,
    population_2022: (map(.population_2022) | add)
  }
] as $continents |
($continents | map(.population_2022) | add) as $world_population |
$continents | map({
  continent: .continent,
  world_population_percentage: (.population_2022 / $world_population * 100)
})' < world-population.json`

```yaml
[
  {
    "continent": "Africa",
    "world_population_percentage": 17.893603711292595
  },
  {
    "continent": "Asia",
    "world_population_percentage": 59.21408121127158
  },
  {
    "continent": "Europe",
    "world_population_percentage": 9.320319091529134
  },
  {
    "continent": "North America",
    "world_population_percentage": 7.528722428374607
  },
  {
    "continent": "Oceania",
    "world_population_percentage": 0.5648591608481732
  },
  {
    "continent": "South America",
    "world_population_percentage": 5.478414396683904
  }
]
```
```
