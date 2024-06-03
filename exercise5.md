# JSONQuery Exercise 5 Educom Traineeship

`jq '[
  group_by(.continent)[] |
  {
    continent: .[0].continent,
    population_2022: (map(.population_2022) | add),
    population_1970: (map(.population_1970) | add)
  }
] | map({
  continent: .continent,
  population_growth: ((.population_2022 - .population_1970) / .population_1970 * 100)
})' < world-population.json`

```yaml
[
  {
    "continent": "Africa",
    "population_growth_percentage": 290.4099050397682
  },
  {
    "continent": "Asia",
    "population_growth_percentage": 120.12072490122634
  },
  {
    "continent": "Europe",
    "population_growth_percentage": 13.29781319128484
  },
  {
    "continent": "North America",
    "population_growth_percentage": 90.30763415983597
  },
  {
    "continent": "Oceania",
    "population_growth_percentage": 131.20087144582698
  },
  {
    "continent": "South America",
    "population_growth_percentage": 126.39183549303002
  }
]
```
