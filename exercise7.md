# JSONQuery Exercise 7 Educom Traineeship

`jq '.[] | {country: .country, rank: .rank, cca3: .cca3, capital: .capital, continent: .continent, population: [{year: 2022, population:.population_2022}, {year: 2020, population: .population_2020}, {year: 2015, population: .population_2015}, {year: 2010, population: .population_2010}, {year: 2000, population: .population_2000}, {year: 1990, population: .population_1990}, {year: 1980, population: .population_1980}, {year: 1970, population: .population_1970}], area_km2: .area_km2, population_density: .population_density, population_growth_rate: .population_growth_rate, percentage_world_population: .percentage_world_population}' < world-population.json`

```yaml
{
  "country": "Afghanistan",
  "rank": 36,
  "cca3": "AFG",
  "capital": "Kabul",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 41128771
    },
    {
      "year": 2020,
      "population": 38972230
    },
    {
      "year": 2015,
      "population": 33753499
    },
    {
      "year": 2010,
      "population": 28189672
    },
    {
      "year": 2000,
      "population": 19542982
    },
    {
      "year": 1990,
      "population": 10694796
    },
    {
      "year": 1980,
      "population": 12486631
    },
    {
      "year": 1970,
      "population": 10752971
    }
  ],
  "area_km2": 652230,
  "population_density": 63.0587,
  "population_growth_rate": 1.0257,
  "percentage_world_population": 0.52
}
{
  "country": "Albania",
  "rank": 138,
  "cca3": "ALB",
  "capital": "Tirana",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 2842321
    },
    {
      "year": 2020,
      "population": 2866849
    },
    {
      "year": 2015,
      "population": 2882481
    },
    {
      "year": 2010,
      "population": 2913399
    },
    {
      "year": 2000,
      "population": 3182021
    },
    {
      "year": 1990,
      "population": 3295066
    },
    {
      "year": 1980,
      "population": 2941651
    },
    {
      "year": 1970,
      "population": 2324731
    }
  ],
  "area_km2": 28748,
  "population_density": 98.8702,
  "population_growth_rate": 0.9957,
  "percentage_world_population": 0.04
}
{
  "country": "Algeria",
  "rank": 34,
  "cca3": "DZA",
  "capital": "Algiers",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 44903225
    },
    {
      "year": 2020,
      "population": 43451666
    },
    {
      "year": 2015,
      "population": 39543154
    },
    {
      "year": 2010,
      "population": 35856344
    },
    {
      "year": 2000,
      "population": 30774621
    },
    {
      "year": 1990,
      "population": 25518074
    },
    {
      "year": 1980,
      "population": 18739378
    },
    {
      "year": 1970,
      "population": 13795915
    }
  ],
  "area_km2": 2381741,
  "population_density": 18.8531,
  "population_growth_rate": 1.0164,
  "percentage_world_population": 0.56
}
{
  "country": "American Samoa",
  "rank": 213,
  "cca3": "ASM",
  "capital": "Pago Pago",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 44273
    },
    {
      "year": 2020,
      "population": 46189
    },
    {
      "year": 2015,
      "population": 51368
    },
    {
      "year": 2010,
      "population": 54849
    },
    {
      "year": 2000,
      "population": 58230
    },
    {
      "year": 1990,
      "population": 47818
    },
    {
      "year": 1980,
      "population": 32886
    },
    {
      "year": 1970,
      "population": 27075
    }
  ],
  "area_km2": 199,
  "population_density": 222.4774,
  "population_growth_rate": 0.9831,
  "percentage_world_population": 0
}
{
  "country": "Andorra",
  "rank": 203,
  "cca3": "AND",
  "capital": "Andorra la Vella",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 79824
    },
    {
      "year": 2020,
      "population": 77700
    },
    {
      "year": 2015,
      "population": 71746
    },
    {
      "year": 2010,
      "population": 71519
    },
    {
      "year": 2000,
      "population": 66097
    },
    {
      "year": 1990,
      "population": 53569
    },
    {
      "year": 1980,
      "population": 35611
    },
    {
      "year": 1970,
      "population": 19860
    }
  ],
  "area_km2": 468,
  "population_density": 170.5641,
  "population_growth_rate": 1.01,
  "percentage_world_population": 0
}
{
  "country": "Angola",
  "rank": 42,
  "cca3": "AGO",
  "capital": "Luanda",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 35588987
    },
    {
      "year": 2020,
      "population": 33428485
    },
    {
      "year": 2015,
      "population": 28127721
    },
    {
      "year": 2010,
      "population": 23364185
    },
    {
      "year": 2000,
      "population": 16394062
    },
    {
      "year": 1990,
      "population": 11828638
    },
    {
      "year": 1980,
      "population": 8330047
    },
    {
      "year": 1970,
      "population": 6029700
    }
  ],
  "area_km2": 1246700,
  "population_density": 28.5466,
  "population_growth_rate": 1.0315,
  "percentage_world_population": 0.45
}
{
  "country": "Anguilla",
  "rank": 224,
  "cca3": "AIA",
  "capital": "The Valley",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 15857
    },
    {
      "year": 2020,
      "population": 15585
    },
    {
      "year": 2015,
      "population": 14525
    },
    {
      "year": 2010,
      "population": 13172
    },
    {
      "year": 2000,
      "population": 11047
    },
    {
      "year": 1990,
      "population": 8316
    },
    {
      "year": 1980,
      "population": 6560
    },
    {
      "year": 1970,
      "population": 6283
    }
  ],
  "area_km2": 91,
  "population_density": 174.2527,
  "population_growth_rate": 1.0066,
  "percentage_world_population": 0
}
{
  "country": "Antigua and Barbuda",
  "rank": 201,
  "cca3": "ATG",
  "capital": "Saint John’s",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 93763
    },
    {
      "year": 2020,
      "population": 92664
    },
    {
      "year": 2015,
      "population": 89941
    },
    {
      "year": 2010,
      "population": 85695
    },
    {
      "year": 2000,
      "population": 75055
    },
    {
      "year": 1990,
      "population": 63328
    },
    {
      "year": 1980,
      "population": 64888
    },
    {
      "year": 1970,
      "population": 64516
    }
  ],
  "area_km2": 442,
  "population_density": 212.1335,
  "population_growth_rate": 1.0058,
  "percentage_world_population": 0
}
{
  "country": "Argentina",
  "rank": 33,
  "cca3": "ARG",
  "capital": "Buenos Aires",
  "continent": "South America",
  "population": [
    {
      "year": 2022,
      "population": 45510318
    },
    {
      "year": 2020,
      "population": 45036032
    },
    {
      "year": 2015,
      "population": 43257065
    },
    {
      "year": 2010,
      "population": 41100123
    },
    {
      "year": 2000,
      "population": 37070774
    },
    {
      "year": 1990,
      "population": 32637657
    },
    {
      "year": 1980,
      "population": 28024803
    },
    {
      "year": 1970,
      "population": 23842803
    }
  ],
  "area_km2": 2780400,
  "population_density": 16.3683,
  "population_growth_rate": 1.0052,
  "percentage_world_population": 0.57
}
{
  "country": "Armenia",
  "rank": 140,
  "cca3": "ARM",
  "capital": "Yerevan",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 2780469
    },
    {
      "year": 2020,
      "population": 2805608
    },
    {
      "year": 2015,
      "population": 2878595
    },
    {
      "year": 2010,
      "population": 2946293
    },
    {
      "year": 2000,
      "population": 3168523
    },
    {
      "year": 1990,
      "population": 3556539
    },
    {
      "year": 1980,
      "population": 3135123
    },
    {
      "year": 1970,
      "population": 2534377
    }
  ],
  "area_km2": 29743,
  "population_density": 93.4831,
  "population_growth_rate": 0.9962,
  "percentage_world_population": 0.03
}
{
  "country": "Aruba",
  "rank": 198,
  "cca3": "ABW",
  "capital": "Oranjestad",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 106445
    },
    {
      "year": 2020,
      "population": 106585
    },
    {
      "year": 2015,
      "population": 104257
    },
    {
      "year": 2010,
      "population": 100341
    },
    {
      "year": 2000,
      "population": 89101
    },
    {
      "year": 1990,
      "population": 65712
    },
    {
      "year": 1980,
      "population": 62267
    },
    {
      "year": 1970,
      "population": 59106
    }
  ],
  "area_km2": 180,
  "population_density": 591.3611,
  "population_growth_rate": 0.9991,
  "percentage_world_population": 0
}
{
  "country": "Australia",
  "rank": 55,
  "cca3": "AUS",
  "capital": "Canberra",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 26177413
    },
    {
      "year": 2020,
      "population": 25670051
    },
    {
      "year": 2015,
      "population": 23820236
    },
    {
      "year": 2010,
      "population": 22019168
    },
    {
      "year": 2000,
      "population": 19017963
    },
    {
      "year": 1990,
      "population": 17048003
    },
    {
      "year": 1980,
      "population": 14706322
    },
    {
      "year": 1970,
      "population": 12595034
    }
  ],
  "area_km2": 7692024,
  "population_density": 3.4032,
  "population_growth_rate": 1.0099,
  "percentage_world_population": 0.33
}
{
  "country": "Austria",
  "rank": 99,
  "cca3": "AUT",
  "capital": "Vienna",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 8939617
    },
    {
      "year": 2020,
      "population": 8907777
    },
    {
      "year": 2015,
      "population": 8642421
    },
    {
      "year": 2010,
      "population": 8362829
    },
    {
      "year": 2000,
      "population": 8010428
    },
    {
      "year": 1990,
      "population": 7678729
    },
    {
      "year": 1980,
      "population": 7547561
    },
    {
      "year": 1970,
      "population": 7465301
    }
  ],
  "area_km2": 83871,
  "population_density": 106.5877,
  "population_growth_rate": 1.002,
  "percentage_world_population": 0.11
}
{
  "country": "Azerbaijan",
  "rank": 91,
  "cca3": "AZE",
  "capital": "Baku",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 10358074
    },
    {
      "year": 2020,
      "population": 10284951
    },
    {
      "year": 2015,
      "population": 9863480
    },
    {
      "year": 2010,
      "population": 9237202
    },
    {
      "year": 2000,
      "population": 8190337
    },
    {
      "year": 1990,
      "population": 7427836
    },
    {
      "year": 1980,
      "population": 6383060
    },
    {
      "year": 1970,
      "population": 5425317
    }
  ],
  "area_km2": 86600,
  "population_density": 119.6082,
  "population_growth_rate": 1.0044,
  "percentage_world_population": 0.13
}
{
  "country": "Bahamas",
  "rank": 176,
  "cca3": "BHS",
  "capital": "Nassau",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 409984
    },
    {
      "year": 2020,
      "population": 406471
    },
    {
      "year": 2015,
      "population": 392697
    },
    {
      "year": 2010,
      "population": 373272
    },
    {
      "year": 2000,
      "population": 325014
    },
    {
      "year": 1990,
      "population": 270679
    },
    {
      "year": 1980,
      "population": 223752
    },
    {
      "year": 1970,
      "population": 179129
    }
  ],
  "area_km2": 13943,
  "population_density": 29.4043,
  "population_growth_rate": 1.0051,
  "percentage_world_population": 0.01
}
{
  "country": "Bahrain",
  "rank": 154,
  "cca3": "BHR",
  "capital": "Manama",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 1472233
    },
    {
      "year": 2020,
      "population": 1477469
    },
    {
      "year": 2015,
      "population": 1362142
    },
    {
      "year": 2010,
      "population": 1213645
    },
    {
      "year": 2000,
      "population": 711442
    },
    {
      "year": 1990,
      "population": 517418
    },
    {
      "year": 1980,
      "population": 362595
    },
    {
      "year": 1970,
      "population": 222555
    }
  ],
  "area_km2": 765,
  "population_density": 1924.4876,
  "population_growth_rate": 1.0061,
  "percentage_world_population": 0.02
}
{
  "country": "Bangladesh",
  "rank": 8,
  "cca3": "BGD",
  "capital": "Dhaka",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 171186372
    },
    {
      "year": 2020,
      "population": 167420951
    },
    {
      "year": 2015,
      "population": 157830000
    },
    {
      "year": 2010,
      "population": 148391139
    },
    {
      "year": 2000,
      "population": 129193327
    },
    {
      "year": 1990,
      "population": 107147651
    },
    {
      "year": 1980,
      "population": 83929765
    },
    {
      "year": 1970,
      "population": 67541860
    }
  ],
  "area_km2": 147570,
  "population_density": 1160.035,
  "population_growth_rate": 1.0108,
  "percentage_world_population": 2.15
}
{
  "country": "Barbados",
  "rank": 186,
  "cca3": "BRB",
  "capital": "Bridgetown",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 281635
    },
    {
      "year": 2020,
      "population": 280693
    },
    {
      "year": 2015,
      "population": 278083
    },
    {
      "year": 2010,
      "population": 274711
    },
    {
      "year": 2000,
      "population": 264657
    },
    {
      "year": 1990,
      "population": 258868
    },
    {
      "year": 1980,
      "population": 253575
    },
    {
      "year": 1970,
      "population": 241397
    }
  ],
  "area_km2": 430,
  "population_density": 654.9651,
  "population_growth_rate": 1.0015,
  "percentage_world_population": 0
}
{
  "country": "Belarus",
  "rank": 96,
  "cca3": "BLR",
  "capital": "Minsk",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 9534954
    },
    {
      "year": 2020,
      "population": 9633740
    },
    {
      "year": 2015,
      "population": 9700609
    },
    {
      "year": 2010,
      "population": 9731427
    },
    {
      "year": 2000,
      "population": 10256483
    },
    {
      "year": 1990,
      "population": 10428525
    },
    {
      "year": 1980,
      "population": 9817257
    },
    {
      "year": 1970,
      "population": 9170786
    }
  ],
  "area_km2": 207600,
  "population_density": 45.9295,
  "population_growth_rate": 0.9955,
  "percentage_world_population": 0.12
}
{
  "country": "Belgium",
  "rank": 81,
  "cca3": "BEL",
  "capital": "Brussels",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 11655930
    },
    {
      "year": 2020,
      "population": 11561717
    },
    {
      "year": 2015,
      "population": 11248303
    },
    {
      "year": 2010,
      "population": 10877947
    },
    {
      "year": 2000,
      "population": 10264343
    },
    {
      "year": 1990,
      "population": 9959560
    },
    {
      "year": 1980,
      "population": 9828986
    },
    {
      "year": 1970,
      "population": 9629376
    }
  ],
  "area_km2": 30528,
  "population_density": 381.8111,
  "population_growth_rate": 1.0038,
  "percentage_world_population": 0.15
}
{
  "country": "Belize",
  "rank": 177,
  "cca3": "BLZ",
  "capital": "Belmopan",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 405272
    },
    {
      "year": 2020,
      "population": 394921
    },
    {
      "year": 2015,
      "population": 359871
    },
    {
      "year": 2010,
      "population": 322106
    },
    {
      "year": 2000,
      "population": 240406
    },
    {
      "year": 1990,
      "population": 182589
    },
    {
      "year": 1980,
      "population": 145133
    },
    {
      "year": 1970,
      "population": 120905
    }
  ],
  "area_km2": 22966,
  "population_density": 17.6466,
  "population_growth_rate": 1.0131,
  "percentage_world_population": 0.01
}
{
  "country": "Benin",
  "rank": 77,
  "cca3": "BEN",
  "capital": "Porto-Novo",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 13352864
    },
    {
      "year": 2020,
      "population": 12643123
    },
    {
      "year": 2015,
      "population": 10932783
    },
    {
      "year": 2010,
      "population": 9445710
    },
    {
      "year": 2000,
      "population": 6998023
    },
    {
      "year": 1990,
      "population": 5133419
    },
    {
      "year": 1980,
      "population": 3833939
    },
    {
      "year": 1970,
      "population": 3023443
    }
  ],
  "area_km2": 112622,
  "population_density": 118.5635,
  "population_growth_rate": 1.0274,
  "percentage_world_population": 0.17
}
{
  "country": "Bermuda",
  "rank": 206,
  "cca3": "BMU",
  "capital": "Hamilton",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 64184
    },
    {
      "year": 2020,
      "population": 64031
    },
    {
      "year": 2015,
      "population": 63144
    },
    {
      "year": 2010,
      "population": 63447
    },
    {
      "year": 2000,
      "population": 61371
    },
    {
      "year": 1990,
      "population": 57470
    },
    {
      "year": 1980,
      "population": 53565
    },
    {
      "year": 1970,
      "population": 52019
    }
  ],
  "area_km2": 54,
  "population_density": 1188.5926,
  "population_growth_rate": 1,
  "percentage_world_population": 0
}
{
  "country": "Bhutan",
  "rank": 165,
  "cca3": "BTN",
  "capital": "Thimphu",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 782455
    },
    {
      "year": 2020,
      "population": 772506
    },
    {
      "year": 2015,
      "population": 743274
    },
    {
      "year": 2010,
      "population": 705516
    },
    {
      "year": 2000,
      "population": 587207
    },
    {
      "year": 1990,
      "population": 558442
    },
    {
      "year": 1980,
      "population": 415257
    },
    {
      "year": 1970,
      "population": 298894
    }
  ],
  "area_km2": 38394,
  "population_density": 20.3796,
  "population_growth_rate": 1.0064,
  "percentage_world_population": 0.01
}
{
  "country": "Bolivia",
  "rank": 80,
  "cca3": "BOL",
  "capital": "Sucre",
  "continent": "South America",
  "population": [
    {
      "year": 2022,
      "population": 12224110
    },
    {
      "year": 2020,
      "population": 11936162
    },
    {
      "year": 2015,
      "population": 11090085
    },
    {
      "year": 2010,
      "population": 10223270
    },
    {
      "year": 2000,
      "population": 8592656
    },
    {
      "year": 1990,
      "population": 7096194
    },
    {
      "year": 1980,
      "population": 5736088
    },
    {
      "year": 1970,
      "population": 4585693
    }
  ],
  "area_km2": 1098581,
  "population_density": 11.1272,
  "population_growth_rate": 1.012,
  "percentage_world_population": 0.15
}
{
  "country": "Bosnia and Herzegovina",
  "rank": 137,
  "cca3": "BIH",
  "capital": "Sarajevo",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 3233526
    },
    {
      "year": 2020,
      "population": 3318407
    },
    {
      "year": 2015,
      "population": 3524324
    },
    {
      "year": 2010,
      "population": 3811088
    },
    {
      "year": 2000,
      "population": 4179350
    },
    {
      "year": 1990,
      "population": 4494310
    },
    {
      "year": 1980,
      "population": 4199820
    },
    {
      "year": 1970,
      "population": 3815561
    }
  ],
  "area_km2": 51209,
  "population_density": 63.1437,
  "population_growth_rate": 0.9886,
  "percentage_world_population": 0.04
}
{
  "country": "Botswana",
  "rank": 144,
  "cca3": "BWA",
  "capital": "Gaborone",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 2630296
    },
    {
      "year": 2020,
      "population": 2546402
    },
    {
      "year": 2015,
      "population": 2305171
    },
    {
      "year": 2010,
      "population": 2091664
    },
    {
      "year": 2000,
      "population": 1726985
    },
    {
      "year": 1990,
      "population": 1341474
    },
    {
      "year": 1980,
      "population": 938578
    },
    {
      "year": 1970,
      "population": 592244
    }
  ],
  "area_km2": 582000,
  "population_density": 4.5194,
  "population_growth_rate": 1.0162,
  "percentage_world_population": 0.03
}
{
  "country": "Brazil",
  "rank": 7,
  "cca3": "BRA",
  "capital": "Brasilia",
  "continent": "South America",
  "population": [
    {
      "year": 2022,
      "population": 215313498
    },
    {
      "year": 2020,
      "population": 213196304
    },
    {
      "year": 2015,
      "population": 205188205
    },
    {
      "year": 2010,
      "population": 196353492
    },
    {
      "year": 2000,
      "population": 175873720
    },
    {
      "year": 1990,
      "population": 150706446
    },
    {
      "year": 1980,
      "population": 122288383
    },
    {
      "year": 1970,
      "population": 96369875
    }
  ],
  "area_km2": 8515767,
  "population_density": 25.2841,
  "population_growth_rate": 1.0046,
  "percentage_world_population": 2.7
}
{
  "country": "British Virgin Islands",
  "rank": 221,
  "cca3": "VGB",
  "capital": "Road Town",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 31305
    },
    {
      "year": 2020,
      "population": 30910
    },
    {
      "year": 2015,
      "population": 29366
    },
    {
      "year": 2010,
      "population": 27556
    },
    {
      "year": 2000,
      "population": 20104
    },
    {
      "year": 1990,
      "population": 15617
    },
    {
      "year": 1980,
      "population": 11109
    },
    {
      "year": 1970,
      "population": 9581
    }
  ],
  "area_km2": 151,
  "population_density": 207.3179,
  "population_growth_rate": 1.0059,
  "percentage_world_population": 0
}
{
  "country": "Brunei",
  "rank": 175,
  "cca3": "BRN",
  "capital": "Bandar Seri Begawan",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 449002
    },
    {
      "year": 2020,
      "population": 441725
    },
    {
      "year": 2015,
      "population": 421437
    },
    {
      "year": 2010,
      "population": 396053
    },
    {
      "year": 2000,
      "population": 333926
    },
    {
      "year": 1990,
      "population": 261928
    },
    {
      "year": 1980,
      "population": 187921
    },
    {
      "year": 1970,
      "population": 133343
    }
  ],
  "area_km2": 5765,
  "population_density": 77.8841,
  "population_growth_rate": 1.0081,
  "percentage_world_population": 0.01
}
{
  "country": "Bulgaria",
  "rank": 108,
  "cca3": "BGR",
  "capital": "Sofia",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 6781953
    },
    {
      "year": 2020,
      "population": 6979175
    },
    {
      "year": 2015,
      "population": 7309253
    },
    {
      "year": 2010,
      "population": 7592273
    },
    {
      "year": 2000,
      "population": 8097691
    },
    {
      "year": 1990,
      "population": 8767778
    },
    {
      "year": 1980,
      "population": 8980606
    },
    {
      "year": 1970,
      "population": 8582950
    }
  ],
  "area_km2": 110879,
  "population_density": 61.1654,
  "population_growth_rate": 0.9849,
  "percentage_world_population": 0.09
}
{
  "country": "Burkina Faso",
  "rank": 58,
  "cca3": "BFA",
  "capital": "Ouagadougou",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 22673762
    },
    {
      "year": 2020,
      "population": 21522626
    },
    {
      "year": 2015,
      "population": 18718019
    },
    {
      "year": 2010,
      "population": 16116845
    },
    {
      "year": 2000,
      "population": 11882888
    },
    {
      "year": 1990,
      "population": 9131361
    },
    {
      "year": 1980,
      "population": 6932967
    },
    {
      "year": 1970,
      "population": 5611666
    }
  ],
  "area_km2": 272967,
  "population_density": 83.0641,
  "population_growth_rate": 1.0259,
  "percentage_world_population": 0.28
}
{
  "country": "Burundi",
  "rank": 78,
  "cca3": "BDI",
  "capital": "Bujumbura",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 12889576
    },
    {
      "year": 2020,
      "population": 12220227
    },
    {
      "year": 2015,
      "population": 10727148
    },
    {
      "year": 2010,
      "population": 9126605
    },
    {
      "year": 2000,
      "population": 6307659
    },
    {
      "year": 1990,
      "population": 5483793
    },
    {
      "year": 1980,
      "population": 4312834
    },
    {
      "year": 1970,
      "population": 3497834
    }
  ],
  "area_km2": 27834,
  "population_density": 463.0874,
  "population_growth_rate": 1.027,
  "percentage_world_population": 0.16
}
{
  "country": "Cambodia",
  "rank": 73,
  "cca3": "KHM",
  "capital": "Phnom Penh",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 16767842
    },
    {
      "year": 2020,
      "population": 16396860
    },
    {
      "year": 2015,
      "population": 15417523
    },
    {
      "year": 2010,
      "population": 14363532
    },
    {
      "year": 2000,
      "population": 12118841
    },
    {
      "year": 1990,
      "population": 8910808
    },
    {
      "year": 1980,
      "population": 6198959
    },
    {
      "year": 1970,
      "population": 6708525
    }
  ],
  "area_km2": 181035,
  "population_density": 92.6221,
  "population_growth_rate": 1.0108,
  "percentage_world_population": 0.21
}
{
  "country": "Cameroon",
  "rank": 53,
  "cca3": "CMR",
  "capital": "Yaounde",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 27914536
    },
    {
      "year": 2020,
      "population": 26491087
    },
    {
      "year": 2015,
      "population": 23012646
    },
    {
      "year": 2010,
      "population": 19878036
    },
    {
      "year": 2000,
      "population": 15091594
    },
    {
      "year": 1990,
      "population": 11430520
    },
    {
      "year": 1980,
      "population": 8519891
    },
    {
      "year": 1970,
      "population": 6452787
    }
  ],
  "area_km2": 475442,
  "population_density": 58.7128,
  "population_growth_rate": 1.0263,
  "percentage_world_population": 0.35
}
{
  "country": "Canada",
  "rank": 39,
  "cca3": "CAN",
  "capital": "Ottawa",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 38454327
    },
    {
      "year": 2020,
      "population": 37888705
    },
    {
      "year": 2015,
      "population": 35732126
    },
    {
      "year": 2010,
      "population": 33963412
    },
    {
      "year": 2000,
      "population": 30683313
    },
    {
      "year": 1990,
      "population": 27657204
    },
    {
      "year": 1980,
      "population": 24511510
    },
    {
      "year": 1970,
      "population": 21434577
    }
  ],
  "area_km2": 9984670,
  "population_density": 3.8513,
  "population_growth_rate": 1.0078,
  "percentage_world_population": 0.48
}
{
  "country": "Cape Verde",
  "rank": 171,
  "cca3": "CPV",
  "capital": "Praia",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 593149
    },
    {
      "year": 2020,
      "population": 582640
    },
    {
      "year": 2015,
      "population": 552166
    },
    {
      "year": 2010,
      "population": 521212
    },
    {
      "year": 2000,
      "population": 458251
    },
    {
      "year": 1990,
      "population": 364563
    },
    {
      "year": 1980,
      "population": 317234
    },
    {
      "year": 1970,
      "population": 287262
    }
  ],
  "area_km2": 4033,
  "population_density": 147.0739,
  "population_growth_rate": 1.0089,
  "percentage_world_population": 0.01
}
{
  "country": "Cayman Islands",
  "rank": 205,
  "cca3": "CYM",
  "capital": "George Town",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 68706
    },
    {
      "year": 2020,
      "population": 67311
    },
    {
      "year": 2015,
      "population": 60911
    },
    {
      "year": 2010,
      "population": 54074
    },
    {
      "year": 2000,
      "population": 39658
    },
    {
      "year": 1990,
      "population": 26027
    },
    {
      "year": 1980,
      "population": 17100
    },
    {
      "year": 1970,
      "population": 10533
    }
  ],
  "area_km2": 264,
  "population_density": 260.25,
  "population_growth_rate": 1.0084,
  "percentage_world_population": 0
}
{
  "country": "Central African Republic",
  "rank": 117,
  "cca3": "CAF",
  "capital": "Bangui",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 5579144
    },
    {
      "year": 2020,
      "population": 5343020
    },
    {
      "year": 2015,
      "population": 4819333
    },
    {
      "year": 2010,
      "population": 4660067
    },
    {
      "year": 2000,
      "population": 3759170
    },
    {
      "year": 1990,
      "population": 2809221
    },
    {
      "year": 1980,
      "population": 2415276
    },
    {
      "year": 1970,
      "population": 2067356
    }
  ],
  "area_km2": 622984,
  "population_density": 8.9555,
  "population_growth_rate": 1.0224,
  "percentage_world_population": 0.07
}
{
  "country": "Chad",
  "rank": 69,
  "cca3": "TCD",
  "capital": "N'Djamena",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 17723315
    },
    {
      "year": 2020,
      "population": 16644701
    },
    {
      "year": 2015,
      "population": 14140274
    },
    {
      "year": 2010,
      "population": 11894727
    },
    {
      "year": 2000,
      "population": 8259137
    },
    {
      "year": 1990,
      "population": 5827069
    },
    {
      "year": 1980,
      "population": 4408230
    },
    {
      "year": 1970,
      "population": 3667394
    }
  ],
  "area_km2": 1284000,
  "population_density": 13.8032,
  "population_growth_rate": 1.0316,
  "percentage_world_population": 0.22
}
{
  "country": "Chile",
  "rank": 65,
  "cca3": "CHL",
  "capital": "Santiago",
  "continent": "South America",
  "population": [
    {
      "year": 2022,
      "population": 19603733
    },
    {
      "year": 2020,
      "population": 19300315
    },
    {
      "year": 2015,
      "population": 17870124
    },
    {
      "year": 2010,
      "population": 17004162
    },
    {
      "year": 2000,
      "population": 15351799
    },
    {
      "year": 1990,
      "population": 13342868
    },
    {
      "year": 1980,
      "population": 11469828
    },
    {
      "year": 1970,
      "population": 9820481
    }
  ],
  "area_km2": 756102,
  "population_density": 25.9274,
  "population_growth_rate": 1.0057,
  "percentage_world_population": 0.25
}
{
  "country": "China",
  "rank": 1,
  "cca3": "CHN",
  "capital": "Beijing",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 1425887337
    },
    {
      "year": 2020,
      "population": 1424929781
    },
    {
      "year": 2015,
      "population": 1393715448
    },
    {
      "year": 2010,
      "population": 1348191368
    },
    {
      "year": 2000,
      "population": 1264099069
    },
    {
      "year": 1990,
      "population": 1153704252
    },
    {
      "year": 1980,
      "population": 982372466
    },
    {
      "year": 1970,
      "population": 822534450
    }
  ],
  "area_km2": 9706961,
  "population_density": 146.8933,
  "population_growth_rate": 1,
  "percentage_world_population": 17.88
}
{
  "country": "Colombia",
  "rank": 28,
  "cca3": "COL",
  "capital": "Bogota",
  "continent": "South America",
  "population": [
    {
      "year": 2022,
      "population": 51874024
    },
    {
      "year": 2020,
      "population": 50930662
    },
    {
      "year": 2015,
      "population": 47119728
    },
    {
      "year": 2010,
      "population": 44816108
    },
    {
      "year": 2000,
      "population": 39215135
    },
    {
      "year": 1990,
      "population": 32601393
    },
    {
      "year": 1980,
      "population": 26176195
    },
    {
      "year": 1970,
      "population": 20905254
    }
  ],
  "area_km2": 1141748,
  "population_density": 45.4339,
  "population_growth_rate": 1.0069,
  "percentage_world_population": 0.65
}
{
  "country": "Comoros",
  "rank": 163,
  "cca3": "COM",
  "capital": "Moroni",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 836774
    },
    {
      "year": 2020,
      "population": 806166
    },
    {
      "year": 2015,
      "population": 730216
    },
    {
      "year": 2010,
      "population": 656024
    },
    {
      "year": 2000,
      "population": 536758
    },
    {
      "year": 1990,
      "population": 431119
    },
    {
      "year": 1980,
      "population": 328328
    },
    {
      "year": 1970,
      "population": 242351
    }
  ],
  "area_km2": 1862,
  "population_density": 449.3953,
  "population_growth_rate": 1.0184,
  "percentage_world_population": 0.01
}
{
  "country": "Cook Islands",
  "rank": 223,
  "cca3": "COK",
  "capital": "Avarua",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 17011
    },
    {
      "year": 2020,
      "population": 17029
    },
    {
      "year": 2015,
      "population": 17695
    },
    {
      "year": 2010,
      "population": 17212
    },
    {
      "year": 2000,
      "population": 15897
    },
    {
      "year": 1990,
      "population": 17123
    },
    {
      "year": 1980,
      "population": 17651
    },
    {
      "year": 1970,
      "population": 20470
    }
  ],
  "area_km2": 236,
  "population_density": 72.0805,
  "population_growth_rate": 1.0005,
  "percentage_world_population": 0
}
{
  "country": "Costa Rica",
  "rank": 124,
  "cca3": "CRI",
  "capital": "San José",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 5180829
    },
    {
      "year": 2020,
      "population": 5123105
    },
    {
      "year": 2015,
      "population": 4895242
    },
    {
      "year": 2010,
      "population": 4622252
    },
    {
      "year": 2000,
      "population": 3979193
    },
    {
      "year": 1990,
      "population": 3158253
    },
    {
      "year": 1980,
      "population": 2414303
    },
    {
      "year": 1970,
      "population": 1855697
    }
  ],
  "area_km2": 51100,
  "population_density": 101.3861,
  "population_growth_rate": 1.0052,
  "percentage_world_population": 0.06
}
{
  "country": "Croatia",
  "rank": 130,
  "cca3": "HRV",
  "capital": "Zagreb",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 4030358
    },
    {
      "year": 2020,
      "population": 4096868
    },
    {
      "year": 2015,
      "population": 4254815
    },
    {
      "year": 2010,
      "population": 4368682
    },
    {
      "year": 2000,
      "population": 4548434
    },
    {
      "year": 1990,
      "population": 4873707
    },
    {
      "year": 1980,
      "population": 4680144
    },
    {
      "year": 1970,
      "population": 4492638
    }
  ],
  "area_km2": 56594,
  "population_density": 71.2153,
  "population_growth_rate": 0.9927,
  "percentage_world_population": 0.05
}
{
  "country": "Cuba",
  "rank": 85,
  "cca3": "CUB",
  "capital": "Havana",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 11212191
    },
    {
      "year": 2020,
      "population": 11300698
    },
    {
      "year": 2015,
      "population": 11339894
    },
    {
      "year": 2010,
      "population": 11290417
    },
    {
      "year": 2000,
      "population": 11105791
    },
    {
      "year": 1990,
      "population": 10626680
    },
    {
      "year": 1980,
      "population": 9809107
    },
    {
      "year": 1970,
      "population": 8869636
    }
  ],
  "area_km2": 109884,
  "population_density": 102.0366,
  "population_growth_rate": 0.9961,
  "percentage_world_population": 0.14
}
{
  "country": "Curacao",
  "rank": 189,
  "cca3": "CUW",
  "capital": "Willemstad",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 191163
    },
    {
      "year": 2020,
      "population": 189288
    },
    {
      "year": 2015,
      "population": 169572
    },
    {
      "year": 2010,
      "population": 159380
    },
    {
      "year": 2000,
      "population": 141424
    },
    {
      "year": 1990,
      "population": 155446
    },
    {
      "year": 1980,
      "population": 156851
    },
    {
      "year": 1970,
      "population": 150385
    }
  ],
  "area_km2": 444,
  "population_density": 430.5473,
  "population_growth_rate": 1.0043,
  "percentage_world_population": 0
}
{
  "country": "Cyprus",
  "rank": 158,
  "cca3": "CYP",
  "capital": "Nicosia",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 1251488
    },
    {
      "year": 2020,
      "population": 1237537
    },
    {
      "year": 2015,
      "population": 1187280
    },
    {
      "year": 2010,
      "population": 1129686
    },
    {
      "year": 2000,
      "population": 948237
    },
    {
      "year": 1990,
      "population": 788500
    },
    {
      "year": 1980,
      "population": 679327
    },
    {
      "year": 1970,
      "population": 640804
    }
  ],
  "area_km2": 9251,
  "population_density": 135.2814,
  "population_growth_rate": 1.0059,
  "percentage_world_population": 0.02
}
{
  "country": "Czech Republic",
  "rank": 88,
  "cca3": "CZE",
  "capital": "Prague",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 10493986
    },
    {
      "year": 2020,
      "population": 10530953
    },
    {
      "year": 2015,
      "population": 10523798
    },
    {
      "year": 2010,
      "population": 10464749
    },
    {
      "year": 2000,
      "population": 10234710
    },
    {
      "year": 1990,
      "population": 10301192
    },
    {
      "year": 1980,
      "population": 10270060
    },
    {
      "year": 1970,
      "population": 9795744
    }
  ],
  "area_km2": 78865,
  "population_density": 133.0627,
  "population_growth_rate": 0.9984,
  "percentage_world_population": 0.13
}
{
  "country": "Denmark",
  "rank": 115,
  "cca3": "DNK",
  "capital": "Copenhagen",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 5882261
    },
    {
      "year": 2020,
      "population": 5825641
    },
    {
      "year": 2015,
      "population": 5677796
    },
    {
      "year": 2010,
      "population": 5550849
    },
    {
      "year": 2000,
      "population": 5340655
    },
    {
      "year": 1990,
      "population": 5144623
    },
    {
      "year": 1980,
      "population": 5125392
    },
    {
      "year": 1970,
      "population": 4922963
    }
  ],
  "area_km2": 43094,
  "population_density": 136.4984,
  "population_growth_rate": 1.0048,
  "percentage_world_population": 0.07
}
{
  "country": "Djibouti",
  "rank": 160,
  "cca3": "DJI",
  "capital": "Djibouti",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 1120849
    },
    {
      "year": 2020,
      "population": 1090156
    },
    {
      "year": 2015,
      "population": 1006259
    },
    {
      "year": 2010,
      "population": 919199
    },
    {
      "year": 2000,
      "population": 742033
    },
    {
      "year": 1990,
      "population": 577173
    },
    {
      "year": 1980,
      "population": 324121
    },
    {
      "year": 1970,
      "population": 144379
    }
  ],
  "area_km2": 23200,
  "population_density": 48.3125,
  "population_growth_rate": 1.0138,
  "percentage_world_population": 0.01
}
{
  "country": "Dominica",
  "rank": 204,
  "cca3": "DMA",
  "capital": "Roseau",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 72737
    },
    {
      "year": 2020,
      "population": 71995
    },
    {
      "year": 2015,
      "population": 70007
    },
    {
      "year": 2010,
      "population": 68755
    },
    {
      "year": 2000,
      "population": 68346
    },
    {
      "year": 1990,
      "population": 69481
    },
    {
      "year": 1980,
      "population": 72978
    },
    {
      "year": 1970,
      "population": 68895
    }
  ],
  "area_km2": 751,
  "population_density": 96.8535,
  "population_growth_rate": 1.0045,
  "percentage_world_population": 0
}
{
  "country": "Dominican Republic",
  "rank": 84,
  "cca3": "DOM",
  "capital": "Santo Domingo",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 11228821
    },
    {
      "year": 2020,
      "population": 10999664
    },
    {
      "year": 2015,
      "population": 10405832
    },
    {
      "year": 2010,
      "population": 9775755
    },
    {
      "year": 2000,
      "population": 8540791
    },
    {
      "year": 1990,
      "population": 7129004
    },
    {
      "year": 1980,
      "population": 5755800
    },
    {
      "year": 1970,
      "population": 4475871
    }
  ],
  "area_km2": 48671,
  "population_density": 230.7087,
  "population_growth_rate": 1.01,
  "percentage_world_population": 0.14
}
{
  "country": "DR Congo",
  "rank": 15,
  "cca3": "COD",
  "capital": "Kinshasa",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 99010212
    },
    {
      "year": 2020,
      "population": 92853164
    },
    {
      "year": 2015,
      "population": 78656904
    },
    {
      "year": 2010,
      "population": 66391257
    },
    {
      "year": 2000,
      "population": 48616317
    },
    {
      "year": 1990,
      "population": 35987541
    },
    {
      "year": 1980,
      "population": 26708686
    },
    {
      "year": 1970,
      "population": 20151733
    }
  ],
  "area_km2": 2344858,
  "population_density": 42.2244,
  "population_growth_rate": 1.0325,
  "percentage_world_population": 1.24
}
{
  "country": "Ecuador",
  "rank": 67,
  "cca3": "ECU",
  "capital": "Quito",
  "continent": "South America",
  "population": [
    {
      "year": 2022,
      "population": 18001000
    },
    {
      "year": 2020,
      "population": 17588595
    },
    {
      "year": 2015,
      "population": 16195902
    },
    {
      "year": 2010,
      "population": 14989585
    },
    {
      "year": 2000,
      "population": 12626507
    },
    {
      "year": 1990,
      "population": 10449837
    },
    {
      "year": 1980,
      "population": 8135845
    },
    {
      "year": 1970,
      "population": 6172215
    }
  ],
  "area_km2": 276841,
  "population_density": 65.0229,
  "population_growth_rate": 1.0114,
  "percentage_world_population": 0.23
}
{
  "country": "Egypt",
  "rank": 14,
  "cca3": "EGY",
  "capital": "Cairo",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 110990103
    },
    {
      "year": 2020,
      "population": 107465134
    },
    {
      "year": 2015,
      "population": 97723799
    },
    {
      "year": 2010,
      "population": 87252413
    },
    {
      "year": 2000,
      "population": 71371371
    },
    {
      "year": 1990,
      "population": 57214630
    },
    {
      "year": 1980,
      "population": 43748556
    },
    {
      "year": 1970,
      "population": 34781986
    }
  ],
  "area_km2": 1002450,
  "population_density": 110.7188,
  "population_growth_rate": 1.0158,
  "percentage_world_population": 1.39
}
{
  "country": "El Salvador",
  "rank": 112,
  "cca3": "SLV",
  "capital": "San Salvador",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 6336392
    },
    {
      "year": 2020,
      "population": 6292731
    },
    {
      "year": 2015,
      "population": 6231066
    },
    {
      "year": 2010,
      "population": 6114034
    },
    {
      "year": 2000,
      "population": 5958482
    },
    {
      "year": 1990,
      "population": 5367179
    },
    {
      "year": 1980,
      "population": 4508992
    },
    {
      "year": 1970,
      "population": 3619090
    }
  ],
  "area_km2": 21041,
  "population_density": 301.145,
  "population_growth_rate": 1.0035,
  "percentage_world_population": 0.08
}
{
  "country": "Equatorial Guinea",
  "rank": 152,
  "cca3": "GNQ",
  "capital": "Malabo",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 1674908
    },
    {
      "year": 2020,
      "population": 1596049
    },
    {
      "year": 2015,
      "population": 1346973
    },
    {
      "year": 2010,
      "population": 1094524
    },
    {
      "year": 2000,
      "population": 684977
    },
    {
      "year": 1990,
      "population": 465549
    },
    {
      "year": 1980,
      "population": 282509
    },
    {
      "year": 1970,
      "population": 316955
    }
  ],
  "area_km2": 28051,
  "population_density": 59.7094,
  "population_growth_rate": 1.0247,
  "percentage_world_population": 0.02
}
{
  "country": "Eritrea",
  "rank": 132,
  "cca3": "ERI",
  "capital": "Asmara",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 3684032
    },
    {
      "year": 2020,
      "population": 3555868
    },
    {
      "year": 2015,
      "population": 3340006
    },
    {
      "year": 2010,
      "population": 3147727
    },
    {
      "year": 2000,
      "population": 2392880
    },
    {
      "year": 1990,
      "population": 2149960
    },
    {
      "year": 1980,
      "population": 1657982
    },
    {
      "year": 1970,
      "population": 1272748
    }
  ],
  "area_km2": 117600,
  "population_density": 31.3268,
  "population_growth_rate": 1.0176,
  "percentage_world_population": 0.05
}
{
  "country": "Estonia",
  "rank": 156,
  "cca3": "EST",
  "capital": "Tallinn",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 1326062
    },
    {
      "year": 2020,
      "population": 1329444
    },
    {
      "year": 2015,
      "population": 1314657
    },
    {
      "year": 2010,
      "population": 1331535
    },
    {
      "year": 2000,
      "population": 1396877
    },
    {
      "year": 1990,
      "population": 1570674
    },
    {
      "year": 1980,
      "population": 1476983
    },
    {
      "year": 1970,
      "population": 1361999
    }
  ],
  "area_km2": 45227,
  "population_density": 29.3201,
  "population_growth_rate": 0.998,
  "percentage_world_population": 0.02
}
{
  "country": "Eswatini",
  "rank": 159,
  "cca3": "SWZ",
  "capital": "Mbabane",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 1201670
    },
    {
      "year": 2020,
      "population": 1180655
    },
    {
      "year": 2015,
      "population": 1133936
    },
    {
      "year": 2010,
      "population": 1099920
    },
    {
      "year": 2000,
      "population": 1030496
    },
    {
      "year": 1990,
      "population": 854011
    },
    {
      "year": 1980,
      "population": 598564
    },
    {
      "year": 1970,
      "population": 442865
    }
  ],
  "area_km2": 17364,
  "population_density": 69.2047,
  "population_growth_rate": 1.0079,
  "percentage_world_population": 0.02
}
{
  "country": "Ethiopia",
  "rank": 12,
  "cca3": "ETH",
  "capital": "Addis Ababa",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 123379924
    },
    {
      "year": 2020,
      "population": 117190911
    },
    {
      "year": 2015,
      "population": 102471895
    },
    {
      "year": 2010,
      "population": 89237791
    },
    {
      "year": 2000,
      "population": 67031867
    },
    {
      "year": 1990,
      "population": 47878073
    },
    {
      "year": 1980,
      "population": 34945469
    },
    {
      "year": 1970,
      "population": 28308246
    }
  ],
  "area_km2": 1104300,
  "population_density": 111.7268,
  "population_growth_rate": 1.0257,
  "percentage_world_population": 1.55
}
{
  "country": "Falkland Islands",
  "rank": 231,
  "cca3": "FLK",
  "capital": "Stanley",
  "continent": "South America",
  "population": [
    {
      "year": 2022,
      "population": 3780
    },
    {
      "year": 2020,
      "population": 3747
    },
    {
      "year": 2015,
      "population": 3408
    },
    {
      "year": 2010,
      "population": 3187
    },
    {
      "year": 2000,
      "population": 3080
    },
    {
      "year": 1990,
      "population": 2332
    },
    {
      "year": 1980,
      "population": 2240
    },
    {
      "year": 1970,
      "population": 2274
    }
  ],
  "area_km2": 12173,
  "population_density": 0.3105,
  "population_growth_rate": 1.0043,
  "percentage_world_population": 0
}
{
  "country": "Faroe Islands",
  "rank": 209,
  "cca3": "FRO",
  "capital": "Tórshavn",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 53090
    },
    {
      "year": 2020,
      "population": 52415
    },
    {
      "year": 2015,
      "population": 48816
    },
    {
      "year": 2010,
      "population": 48410
    },
    {
      "year": 2000,
      "population": 45660
    },
    {
      "year": 1990,
      "population": 47479
    },
    {
      "year": 1980,
      "population": 43054
    },
    {
      "year": 1970,
      "population": 38416
    }
  ],
  "area_km2": 1393,
  "population_density": 38.112,
  "population_growth_rate": 1.0038,
  "percentage_world_population": 0
}
{
  "country": "Fiji",
  "rank": 162,
  "cca3": "FJI",
  "capital": "Suva",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 929766
    },
    {
      "year": 2020,
      "population": 920422
    },
    {
      "year": 2015,
      "population": 917200
    },
    {
      "year": 2010,
      "population": 905169
    },
    {
      "year": 2000,
      "population": 832509
    },
    {
      "year": 1990,
      "population": 780430
    },
    {
      "year": 1980,
      "population": 644582
    },
    {
      "year": 1970,
      "population": 527634
    }
  ],
  "area_km2": 18272,
  "population_density": 50.8847,
  "population_growth_rate": 1.0056,
  "percentage_world_population": 0.01
}
{
  "country": "Finland",
  "rank": 118,
  "cca3": "FIN",
  "capital": "Helsinki",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 5540745
    },
    {
      "year": 2020,
      "population": 5529468
    },
    {
      "year": 2015,
      "population": 5479461
    },
    {
      "year": 2010,
      "population": 5363271
    },
    {
      "year": 2000,
      "population": 5176209
    },
    {
      "year": 1990,
      "population": 4986545
    },
    {
      "year": 1980,
      "population": 4779418
    },
    {
      "year": 1970,
      "population": 4606621
    }
  ],
  "area_km2": 338424,
  "population_density": 16.3722,
  "population_growth_rate": 1.0009,
  "percentage_world_population": 0.07
}
{
  "country": "France",
  "rank": 23,
  "cca3": "FRA",
  "capital": "Paris",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 64626628
    },
    {
      "year": 2020,
      "population": 64480053
    },
    {
      "year": 2015,
      "population": 63809769
    },
    {
      "year": 2010,
      "population": 62444567
    },
    {
      "year": 2000,
      "population": 58665453
    },
    {
      "year": 1990,
      "population": 56412897
    },
    {
      "year": 1980,
      "population": 53713830
    },
    {
      "year": 1970,
      "population": 50523586
    }
  ],
  "area_km2": 551695,
  "population_density": 117.1419,
  "population_growth_rate": 1.0015,
  "percentage_world_population": 0.81
}
{
  "country": "French Guiana",
  "rank": 184,
  "cca3": "GUF",
  "capital": "Cayenne",
  "continent": "South America",
  "population": [
    {
      "year": 2022,
      "population": 304557
    },
    {
      "year": 2020,
      "population": 290969
    },
    {
      "year": 2015,
      "population": 257026
    },
    {
      "year": 2010,
      "population": 228453
    },
    {
      "year": 2000,
      "population": 164351
    },
    {
      "year": 1990,
      "population": 113931
    },
    {
      "year": 1980,
      "population": 66825
    },
    {
      "year": 1970,
      "population": 46484
    }
  ],
  "area_km2": 83534,
  "population_density": 3.6459,
  "population_growth_rate": 1.0239,
  "percentage_world_population": 0
}
{
  "country": "French Polynesia",
  "rank": 183,
  "cca3": "PYF",
  "capital": "Papeete",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 306279
    },
    {
      "year": 2020,
      "population": 301920
    },
    {
      "year": 2015,
      "population": 291787
    },
    {
      "year": 2010,
      "population": 283788
    },
    {
      "year": 2000,
      "population": 250927
    },
    {
      "year": 1990,
      "population": 211089
    },
    {
      "year": 1980,
      "population": 163591
    },
    {
      "year": 1970,
      "population": 117891
    }
  ],
  "area_km2": 4167,
  "population_density": 73.5011,
  "population_growth_rate": 1.0074,
  "percentage_world_population": 0
}
{
  "country": "Gabon",
  "rank": 146,
  "cca3": "GAB",
  "capital": "Libreville",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 2388992
    },
    {
      "year": 2020,
      "population": 2292573
    },
    {
      "year": 2015,
      "population": 2028517
    },
    {
      "year": 2010,
      "population": 1711105
    },
    {
      "year": 2000,
      "population": 1272935
    },
    {
      "year": 1990,
      "population": 983028
    },
    {
      "year": 1980,
      "population": 749078
    },
    {
      "year": 1970,
      "population": 597192
    }
  ],
  "area_km2": 267668,
  "population_density": 8.9252,
  "population_growth_rate": 1.0204,
  "percentage_world_population": 0.03
}
{
  "country": "Gambia",
  "rank": 142,
  "cca3": "GMB",
  "capital": "Banjul",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 2705992
    },
    {
      "year": 2020,
      "population": 2573995
    },
    {
      "year": 2015,
      "population": 2253133
    },
    {
      "year": 2010,
      "population": 1937275
    },
    {
      "year": 2000,
      "population": 1437539
    },
    {
      "year": 1990,
      "population": 1040616
    },
    {
      "year": 1980,
      "population": 718586
    },
    {
      "year": 1970,
      "population": 528731
    }
  ],
  "area_km2": 10689,
  "population_density": 253.1567,
  "population_growth_rate": 1.025,
  "percentage_world_population": 0.03
}
{
  "country": "Georgia",
  "rank": 131,
  "cca3": "GEO",
  "capital": "Tbilisi",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 3744385
    },
    {
      "year": 2020,
      "population": 3765912
    },
    {
      "year": 2015,
      "population": 3771132
    },
    {
      "year": 2010,
      "population": 3836831
    },
    {
      "year": 2000,
      "population": 4265172
    },
    {
      "year": 1990,
      "population": 5391636
    },
    {
      "year": 1980,
      "population": 5145843
    },
    {
      "year": 1970,
      "population": 4800426
    }
  ],
  "area_km2": 69700,
  "population_density": 53.7214,
  "population_growth_rate": 0.9964,
  "percentage_world_population": 0.05
}
{
  "country": "Germany",
  "rank": 19,
  "cca3": "DEU",
  "capital": "Berlin",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 83369843
    },
    {
      "year": 2020,
      "population": 83328988
    },
    {
      "year": 2015,
      "population": 82073226
    },
    {
      "year": 2010,
      "population": 81325090
    },
    {
      "year": 2000,
      "population": 81551677
    },
    {
      "year": 1990,
      "population": 79370196
    },
    {
      "year": 1980,
      "population": 77786703
    },
    {
      "year": 1970,
      "population": 78294583
    }
  ],
  "area_km2": 357114,
  "population_density": 233.4544,
  "population_growth_rate": 0.9995,
  "percentage_world_population": 1.05
}
{
  "country": "Ghana",
  "rank": 47,
  "cca3": "GHA",
  "capital": "Accra",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 33475870
    },
    {
      "year": 2020,
      "population": 32180401
    },
    {
      "year": 2015,
      "population": 28870939
    },
    {
      "year": 2010,
      "population": 25574719
    },
    {
      "year": 2000,
      "population": 19665502
    },
    {
      "year": 1990,
      "population": 15446982
    },
    {
      "year": 1980,
      "population": 11865246
    },
    {
      "year": 1970,
      "population": 8861895
    }
  ],
  "area_km2": 238533,
  "population_density": 140.3406,
  "population_growth_rate": 1.0196,
  "percentage_world_population": 0.42
}
{
  "country": "Gibraltar",
  "rank": 219,
  "cca3": "GIB",
  "capital": "Gibraltar",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 32649
    },
    {
      "year": 2020,
      "population": 32709
    },
    {
      "year": 2015,
      "population": 32520
    },
    {
      "year": 2010,
      "population": 31262
    },
    {
      "year": 2000,
      "population": 27741
    },
    {
      "year": 1990,
      "population": 27317
    },
    {
      "year": 1980,
      "population": 28734
    },
    {
      "year": 1970,
      "population": 26685
    }
  ],
  "area_km2": 6,
  "population_density": 5441.5,
  "population_growth_rate": 0.9994,
  "percentage_world_population": 0
}
{
  "country": "Greece",
  "rank": 90,
  "cca3": "GRC",
  "capital": "Athens",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 10384971
    },
    {
      "year": 2020,
      "population": 10512232
    },
    {
      "year": 2015,
      "population": 10806641
    },
    {
      "year": 2010,
      "population": 11033783
    },
    {
      "year": 2000,
      "population": 11038109
    },
    {
      "year": 1990,
      "population": 10302255
    },
    {
      "year": 1980,
      "population": 9307148
    },
    {
      "year": 1970,
      "population": 8544873
    }
  ],
  "area_km2": 131990,
  "population_density": 78.68,
  "population_growth_rate": 0.9942,
  "percentage_world_population": 0.13
}
{
  "country": "Greenland",
  "rank": 208,
  "cca3": "GRL",
  "capital": "Nuuk",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 56466
    },
    {
      "year": 2020,
      "population": 56026
    },
    {
      "year": 2015,
      "population": 55895
    },
    {
      "year": 2010,
      "population": 56351
    },
    {
      "year": 2000,
      "population": 56184
    },
    {
      "year": 1990,
      "population": 55599
    },
    {
      "year": 1980,
      "population": 50106
    },
    {
      "year": 1970,
      "population": 45434
    }
  ],
  "area_km2": 2166086,
  "population_density": 0.0261,
  "population_growth_rate": 1.004,
  "percentage_world_population": 0
}
{
  "country": "Grenada",
  "rank": 193,
  "cca3": "GRD",
  "capital": "Saint George's",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 125438
    },
    {
      "year": 2020,
      "population": 123663
    },
    {
      "year": 2015,
      "population": 118980
    },
    {
      "year": 2010,
      "population": 114039
    },
    {
      "year": 2000,
      "population": 107432
    },
    {
      "year": 1990,
      "population": 99047
    },
    {
      "year": 1980,
      "population": 94838
    },
    {
      "year": 1970,
      "population": 98794
    }
  ],
  "area_km2": 344,
  "population_density": 364.6453,
  "population_growth_rate": 1.0066,
  "percentage_world_population": 0
}
{
  "country": "Guadeloupe",
  "rank": 178,
  "cca3": "GLP",
  "capital": "Basse-Terre",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 395752
    },
    {
      "year": 2020,
      "population": 395642
    },
    {
      "year": 2015,
      "population": 399089
    },
    {
      "year": 2010,
      "population": 403072
    },
    {
      "year": 2000,
      "population": 424067
    },
    {
      "year": 1990,
      "population": 391951
    },
    {
      "year": 1980,
      "population": 334234
    },
    {
      "year": 1970,
      "population": 318310
    }
  ],
  "area_km2": 1628,
  "population_density": 243.0909,
  "population_growth_rate": 0.9992,
  "percentage_world_population": 0
}
{
  "country": "Guam",
  "rank": 191,
  "cca3": "GUM",
  "capital": "Hagåtña",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 171774
    },
    {
      "year": 2020,
      "population": 169231
    },
    {
      "year": 2015,
      "population": 167978
    },
    {
      "year": 2010,
      "population": 164905
    },
    {
      "year": 2000,
      "population": 160188
    },
    {
      "year": 1990,
      "population": 138263
    },
    {
      "year": 1980,
      "population": 110286
    },
    {
      "year": 1970,
      "population": 88300
    }
  ],
  "area_km2": 549,
  "population_density": 312.8852,
  "population_growth_rate": 1.0073,
  "percentage_world_population": 0
}
{
  "country": "Guatemala",
  "rank": 68,
  "cca3": "GTM",
  "capital": "Guatemala City",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 17843908
    },
    {
      "year": 2020,
      "population": 17362718
    },
    {
      "year": 2015,
      "population": 16001107
    },
    {
      "year": 2010,
      "population": 14543121
    },
    {
      "year": 2000,
      "population": 11735894
    },
    {
      "year": 1990,
      "population": 9084780
    },
    {
      "year": 1980,
      "population": 6987767
    },
    {
      "year": 1970,
      "population": 5453208
    }
  ],
  "area_km2": 108889,
  "population_density": 163.8725,
  "population_growth_rate": 1.0134,
  "percentage_world_population": 0.22
}
{
  "country": "Guernsey",
  "rank": 207,
  "cca3": "GGY",
  "capital": "Saint Peter Port",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 63301
    },
    {
      "year": 2020,
      "population": 62794
    },
    {
      "year": 2015,
      "population": 61629
    },
    {
      "year": 2010,
      "population": 60782
    },
    {
      "year": 2000,
      "population": 59114
    },
    {
      "year": 1990,
      "population": 57727
    },
    {
      "year": 1980,
      "population": 52860
    },
    {
      "year": 1970,
      "population": 52656
    }
  ],
  "area_km2": 78,
  "population_density": 811.5513,
  "population_growth_rate": 1.0037,
  "percentage_world_population": 0
}
{
  "country": "Guinea",
  "rank": 75,
  "cca3": "GIN",
  "capital": "Conakry",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 13859341
    },
    {
      "year": 2020,
      "population": 13205153
    },
    {
      "year": 2015,
      "population": 11625998
    },
    {
      "year": 2010,
      "population": 10270728
    },
    {
      "year": 2000,
      "population": 8336967
    },
    {
      "year": 1990,
      "population": 6354145
    },
    {
      "year": 1980,
      "population": 4972609
    },
    {
      "year": 1970,
      "population": 4222374
    }
  ],
  "area_km2": 245857,
  "population_density": 56.3716,
  "population_growth_rate": 1.0242,
  "percentage_world_population": 0.17
}
{
  "country": "Guinea-Bissau",
  "rank": 149,
  "cca3": "GNB",
  "capital": "Bissau",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 2105566
    },
    {
      "year": 2020,
      "population": 2015828
    },
    {
      "year": 2015,
      "population": 1788919
    },
    {
      "year": 2010,
      "population": 1567220
    },
    {
      "year": 2000,
      "population": 1230849
    },
    {
      "year": 1990,
      "population": 973551
    },
    {
      "year": 1980,
      "population": 831462
    },
    {
      "year": 1970,
      "population": 591663
    }
  ],
  "area_km2": 36125,
  "population_density": 58.2856,
  "population_growth_rate": 1.0218,
  "percentage_world_population": 0.03
}
{
  "country": "Guyana",
  "rank": 164,
  "cca3": "GUY",
  "capital": "Georgetown",
  "continent": "South America",
  "population": [
    {
      "year": 2022,
      "population": 808726
    },
    {
      "year": 2020,
      "population": 797202
    },
    {
      "year": 2015,
      "population": 755031
    },
    {
      "year": 2010,
      "population": 747932
    },
    {
      "year": 2000,
      "population": 759051
    },
    {
      "year": 1990,
      "population": 747116
    },
    {
      "year": 1980,
      "population": 778176
    },
    {
      "year": 1970,
      "population": 705261
    }
  ],
  "area_km2": 214969,
  "population_density": 3.7621,
  "population_growth_rate": 1.0052,
  "percentage_world_population": 0.01
}
{
  "country": "Haiti",
  "rank": 82,
  "cca3": "HTI",
  "capital": "Port-au-Prince",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 11584996
    },
    {
      "year": 2020,
      "population": 11306801
    },
    {
      "year": 2015,
      "population": 10563757
    },
    {
      "year": 2010,
      "population": 9842880
    },
    {
      "year": 2000,
      "population": 8360225
    },
    {
      "year": 1990,
      "population": 6925331
    },
    {
      "year": 1980,
      "population": 5646676
    },
    {
      "year": 1970,
      "population": 4680812
    }
  ],
  "area_km2": 27750,
  "population_density": 417.4773,
  "population_growth_rate": 1.012,
  "percentage_world_population": 0.15
}
{
  "country": "Honduras",
  "rank": 89,
  "cca3": "HND",
  "capital": "Tegucigalpa",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 10432860
    },
    {
      "year": 2020,
      "population": 10121763
    },
    {
      "year": 2015,
      "population": 9294505
    },
    {
      "year": 2010,
      "population": 8450933
    },
    {
      "year": 2000,
      "population": 6656725
    },
    {
      "year": 1990,
      "population": 5053234
    },
    {
      "year": 1980,
      "population": 3777990
    },
    {
      "year": 1970,
      "population": 2782753
    }
  ],
  "area_km2": 112492,
  "population_density": 92.7431,
  "population_growth_rate": 1.015,
  "percentage_world_population": 0.13
}
{
  "country": "Hong Kong",
  "rank": 104,
  "cca3": "HKG",
  "capital": "Hong Kong",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 7488865
    },
    {
      "year": 2020,
      "population": 7500958
    },
    {
      "year": 2015,
      "population": 7399838
    },
    {
      "year": 2010,
      "population": 7132438
    },
    {
      "year": 2000,
      "population": 6731195
    },
    {
      "year": 1990,
      "population": 5838574
    },
    {
      "year": 1980,
      "population": 4978544
    },
    {
      "year": 1970,
      "population": 3955072
    }
  ],
  "area_km2": 1104,
  "population_density": 6783.3922,
  "population_growth_rate": 0.9992,
  "percentage_world_population": 0.09
}
{
  "country": "Hungary",
  "rank": 94,
  "cca3": "HUN",
  "capital": "Budapest",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 9967308
    },
    {
      "year": 2020,
      "population": 9750573
    },
    {
      "year": 2015,
      "population": 9844246
    },
    {
      "year": 2010,
      "population": 9986825
    },
    {
      "year": 2000,
      "population": 10202055
    },
    {
      "year": 1990,
      "population": 10375989
    },
    {
      "year": 1980,
      "population": 10698679
    },
    {
      "year": 1970,
      "population": 10315366
    }
  ],
  "area_km2": 93028,
  "population_density": 107.1431,
  "population_growth_rate": 1.0265,
  "percentage_world_population": 0.12
}
{
  "country": "Iceland",
  "rank": 179,
  "cca3": "ISL",
  "capital": "Reykjavík",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 372899
    },
    {
      "year": 2020,
      "population": 366669
    },
    {
      "year": 2015,
      "population": 331060
    },
    {
      "year": 2010,
      "population": 318333
    },
    {
      "year": 2000,
      "population": 281462
    },
    {
      "year": 1990,
      "population": 255019
    },
    {
      "year": 1980,
      "population": 228263
    },
    {
      "year": 1970,
      "population": 204468
    }
  ],
  "area_km2": 103000,
  "population_density": 3.6204,
  "population_growth_rate": 1.0069,
  "percentage_world_population": 0
}
{
  "country": "India",
  "rank": 2,
  "cca3": "IND",
  "capital": "New Delhi",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 1417173173
    },
    {
      "year": 2020,
      "population": 1396387127
    },
    {
      "year": 2015,
      "population": 1322866505
    },
    {
      "year": 2010,
      "population": 1240613620
    },
    {
      "year": 2000,
      "population": 1059633675
    },
    {
      "year": 1990,
      "population": 870452165
    },
    {
      "year": 1980,
      "population": 696828385
    },
    {
      "year": 1970,
      "population": 557501301
    }
  ],
  "area_km2": 3287590,
  "population_density": 431.0675,
  "population_growth_rate": 1.0068,
  "percentage_world_population": 17.77
}
{
  "country": "Indonesia",
  "rank": 4,
  "cca3": "IDN",
  "capital": "Jakarta",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 275501339
    },
    {
      "year": 2020,
      "population": 271857970
    },
    {
      "year": 2015,
      "population": 259091970
    },
    {
      "year": 2010,
      "population": 244016173
    },
    {
      "year": 2000,
      "population": 214072421
    },
    {
      "year": 1990,
      "population": 182159874
    },
    {
      "year": 1980,
      "population": 148177096
    },
    {
      "year": 1970,
      "population": 115228394
    }
  ],
  "area_km2": 1904569,
  "population_density": 144.6529,
  "population_growth_rate": 1.0064,
  "percentage_world_population": 3.45
}
{
  "country": "Iran",
  "rank": 17,
  "cca3": "IRN",
  "capital": "Tehran",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 88550570
    },
    {
      "year": 2020,
      "population": 87290193
    },
    {
      "year": 2015,
      "population": 81790841
    },
    {
      "year": 2010,
      "population": 75373855
    },
    {
      "year": 2000,
      "population": 65544383
    },
    {
      "year": 1990,
      "population": 55793629
    },
    {
      "year": 1980,
      "population": 38520664
    },
    {
      "year": 1970,
      "population": 28449705
    }
  ],
  "area_km2": 1648195,
  "population_density": 53.7258,
  "population_growth_rate": 1.0071,
  "percentage_world_population": 1.11
}
{
  "country": "Iraq",
  "rank": 35,
  "cca3": "IRQ",
  "capital": "Baghdad",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 44496122
    },
    {
      "year": 2020,
      "population": 42556984
    },
    {
      "year": 2015,
      "population": 37757813
    },
    {
      "year": 2010,
      "population": 31264875
    },
    {
      "year": 2000,
      "population": 24628858
    },
    {
      "year": 1990,
      "population": 17658381
    },
    {
      "year": 1980,
      "population": 13653369
    },
    {
      "year": 1970,
      "population": 9811347
    }
  ],
  "area_km2": 438317,
  "population_density": 101.5158,
  "population_growth_rate": 1.0221,
  "percentage_world_population": 0.56
}
{
  "country": "Ireland",
  "rank": 125,
  "cca3": "IRL",
  "capital": "Dublin",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 5023109
    },
    {
      "year": 2020,
      "population": 4946119
    },
    {
      "year": 2015,
      "population": 4665760
    },
    {
      "year": 2010,
      "population": 4524585
    },
    {
      "year": 2000,
      "population": 3768950
    },
    {
      "year": 1990,
      "population": 3485374
    },
    {
      "year": 1980,
      "population": 3391387
    },
    {
      "year": 1970,
      "population": 2937637
    }
  ],
  "area_km2": 70273,
  "population_density": 71.4799,
  "population_growth_rate": 1.0073,
  "percentage_world_population": 0.06
}
{
  "country": "Isle of Man",
  "rank": 202,
  "cca3": "IMN",
  "capital": "Douglas",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 84519
    },
    {
      "year": 2020,
      "population": 84046
    },
    {
      "year": 2015,
      "population": 83593
    },
    {
      "year": 2010,
      "population": 83828
    },
    {
      "year": 2000,
      "population": 75562
    },
    {
      "year": 1990,
      "population": 68865
    },
    {
      "year": 1980,
      "population": 64022
    },
    {
      "year": 1970,
      "population": 55298
    }
  ],
  "area_km2": 572,
  "population_density": 147.7605,
  "population_growth_rate": 1.003,
  "percentage_world_population": 0
}
{
  "country": "Israel",
  "rank": 98,
  "cca3": "ISR",
  "capital": "Jerusalem",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 9038309
    },
    {
      "year": 2020,
      "population": 8757489
    },
    {
      "year": 2015,
      "population": 8007778
    },
    {
      "year": 2010,
      "population": 7328445
    },
    {
      "year": 2000,
      "population": 6116958
    },
    {
      "year": 1990,
      "population": 4803254
    },
    {
      "year": 1980,
      "population": 3744608
    },
    {
      "year": 1970,
      "population": 2907307
    }
  ],
  "area_km2": 20770,
  "population_density": 435.1617,
  "population_growth_rate": 1.0155,
  "percentage_world_population": 0.11
}
{
  "country": "Italy",
  "rank": 25,
  "cca3": "ITA",
  "capital": "Rome",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 59037474
    },
    {
      "year": 2020,
      "population": 59500579
    },
    {
      "year": 2015,
      "population": 60232906
    },
    {
      "year": 2010,
      "population": 59822450
    },
    {
      "year": 2000,
      "population": 56966397
    },
    {
      "year": 1990,
      "population": 56756561
    },
    {
      "year": 1980,
      "population": 56329482
    },
    {
      "year": 1970,
      "population": 53324036
    }
  ],
  "area_km2": 301336,
  "population_density": 195.9191,
  "population_growth_rate": 0.9966,
  "percentage_world_population": 0.74
}
{
  "country": "Ivory Coast",
  "rank": 52,
  "cca3": "CIV",
  "capital": "Yamoussoukro",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 28160542
    },
    {
      "year": 2020,
      "population": 26811790
    },
    {
      "year": 2015,
      "population": 23596741
    },
    {
      "year": 2010,
      "population": 21120042
    },
    {
      "year": 2000,
      "population": 16799670
    },
    {
      "year": 1990,
      "population": 11910540
    },
    {
      "year": 1980,
      "population": 8303809
    },
    {
      "year": 1970,
      "population": 5477086
    }
  ],
  "area_km2": 322463,
  "population_density": 87.3295,
  "population_growth_rate": 1.0248,
  "percentage_world_population": 0.35
}
{
  "country": "Jamaica",
  "rank": 139,
  "cca3": "JAM",
  "capital": "Kingston",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 2827377
    },
    {
      "year": 2020,
      "population": 2820436
    },
    {
      "year": 2015,
      "population": 2794445
    },
    {
      "year": 2010,
      "population": 2733896
    },
    {
      "year": 2000,
      "population": 2612205
    },
    {
      "year": 1990,
      "population": 2392030
    },
    {
      "year": 1980,
      "population": 2135546
    },
    {
      "year": 1970,
      "population": 1859091
    }
  ],
  "area_km2": 10991,
  "population_density": 257.2447,
  "population_growth_rate": 0.9999,
  "percentage_world_population": 0.04
}
{
  "country": "Japan",
  "rank": 11,
  "cca3": "JPN",
  "capital": "Tokyo",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 123951692
    },
    {
      "year": 2020,
      "population": 125244761
    },
    {
      "year": 2015,
      "population": 127250933
    },
    {
      "year": 2010,
      "population": 128105431
    },
    {
      "year": 2000,
      "population": 126803861
    },
    {
      "year": 1990,
      "population": 123686321
    },
    {
      "year": 1980,
      "population": 117624196
    },
    {
      "year": 1970,
      "population": 105416839
    }
  ],
  "area_km2": 377930,
  "population_density": 327.9753,
  "population_growth_rate": 0.9947,
  "percentage_world_population": 1.55
}
{
  "country": "Jersey",
  "rank": 195,
  "cca3": "JEY",
  "capital": "Saint Helier",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 110778
    },
    {
      "year": 2020,
      "population": 108319
    },
    {
      "year": 2015,
      "population": 100561
    },
    {
      "year": 2010,
      "population": 96151
    },
    {
      "year": 2000,
      "population": 86192
    },
    {
      "year": 1990,
      "population": 82874
    },
    {
      "year": 1980,
      "population": 75124
    },
    {
      "year": 1970,
      "population": 68347
    }
  ],
  "area_km2": 116,
  "population_density": 954.9828,
  "population_growth_rate": 1.0106,
  "percentage_world_population": 0
}
{
  "country": "Jordan",
  "rank": 83,
  "cca3": "JOR",
  "capital": "Amman",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 11285869
    },
    {
      "year": 2020,
      "population": 10928721
    },
    {
      "year": 2015,
      "population": 9494246
    },
    {
      "year": 2010,
      "population": 6931258
    },
    {
      "year": 2000,
      "population": 5056174
    },
    {
      "year": 1990,
      "population": 3480587
    },
    {
      "year": 1980,
      "population": 2216903
    },
    {
      "year": 1970,
      "population": 1557374
    }
  ],
  "area_km2": 89342,
  "population_density": 126.3221,
  "population_growth_rate": 1.0123,
  "percentage_world_population": 0.14
}
{
  "country": "Kazakhstan",
  "rank": 66,
  "cca3": "KAZ",
  "capital": "Nursultan",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 19397998
    },
    {
      "year": 2020,
      "population": 18979243
    },
    {
      "year": 2015,
      "population": 17835909
    },
    {
      "year": 2010,
      "population": 16627837
    },
    {
      "year": 2000,
      "population": 15236253
    },
    {
      "year": 1990,
      "population": 16866563
    },
    {
      "year": 1980,
      "population": 14172710
    },
    {
      "year": 1970,
      "population": 12265305
    }
  ],
  "area_km2": 2724900,
  "population_density": 7.1188,
  "population_growth_rate": 1.0105,
  "percentage_world_population": 0.24
}
{
  "country": "Kenya",
  "rank": 27,
  "cca3": "KEN",
  "capital": "Nairobi",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 54027487
    },
    {
      "year": 2020,
      "population": 51985780
    },
    {
      "year": 2015,
      "population": 46851488
    },
    {
      "year": 2010,
      "population": 41517895
    },
    {
      "year": 2000,
      "population": 30851606
    },
    {
      "year": 1990,
      "population": 23162269
    },
    {
      "year": 1980,
      "population": 16187124
    },
    {
      "year": 1970,
      "population": 11473087
    }
  ],
  "area_km2": 580367,
  "population_density": 93.0919,
  "population_growth_rate": 1.0193,
  "percentage_world_population": 0.68
}
{
  "country": "Kiribati",
  "rank": 192,
  "cca3": "KIR",
  "capital": "Tarawa",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 131232
    },
    {
      "year": 2020,
      "population": 126463
    },
    {
      "year": 2015,
      "population": 116707
    },
    {
      "year": 2010,
      "population": 107995
    },
    {
      "year": 2000,
      "population": 88826
    },
    {
      "year": 1990,
      "population": 75124
    },
    {
      "year": 1980,
      "population": 60813
    },
    {
      "year": 1970,
      "population": 57437
    }
  ],
  "area_km2": 811,
  "population_density": 161.815,
  "population_growth_rate": 1.0183,
  "percentage_world_population": 0
}
{
  "country": "Kuwait",
  "rank": 129,
  "cca3": "KWT",
  "capital": "Kuwait City",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 4268873
    },
    {
      "year": 2020,
      "population": 4360444
    },
    {
      "year": 2015,
      "population": 3908743
    },
    {
      "year": 2010,
      "population": 2943356
    },
    {
      "year": 2000,
      "population": 1934901
    },
    {
      "year": 1990,
      "population": 1674938
    },
    {
      "year": 1980,
      "population": 1493870
    },
    {
      "year": 1970,
      "population": 802786
    }
  ],
  "area_km2": 17818,
  "population_density": 239.5821,
  "population_growth_rate": 1.0044,
  "percentage_world_population": 0.05
}
{
  "country": "Kyrgyzstan",
  "rank": 110,
  "cca3": "KGZ",
  "capital": "Bishkek",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 6630623
    },
    {
      "year": 2020,
      "population": 6424874
    },
    {
      "year": 2015,
      "population": 5914980
    },
    {
      "year": 2010,
      "population": 5483774
    },
    {
      "year": 2000,
      "population": 4935182
    },
    {
      "year": 1990,
      "population": 4394734
    },
    {
      "year": 1980,
      "population": 3691209
    },
    {
      "year": 1970,
      "population": 3016384
    }
  ],
  "area_km2": 199951,
  "population_density": 33.1612,
  "population_growth_rate": 1.0158,
  "percentage_world_population": 0.08
}
{
  "country": "Laos",
  "rank": 103,
  "cca3": "LAO",
  "capital": "Vientiane",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 7529475
    },
    {
      "year": 2020,
      "population": 7319399
    },
    {
      "year": 2015,
      "population": 6787419
    },
    {
      "year": 2010,
      "population": 6323418
    },
    {
      "year": 2000,
      "population": 5430853
    },
    {
      "year": 1990,
      "population": 4314443
    },
    {
      "year": 1980,
      "population": 3297519
    },
    {
      "year": 1970,
      "population": 2675283
    }
  ],
  "area_km2": 236800,
  "population_density": 31.7968,
  "population_growth_rate": 1.0141,
  "percentage_world_population": 0.09
}
{
  "country": "Latvia",
  "rank": 151,
  "cca3": "LVA",
  "capital": "Riga",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 1850651
    },
    {
      "year": 2020,
      "population": 1897052
    },
    {
      "year": 2015,
      "population": 1991955
    },
    {
      "year": 2010,
      "population": 2101530
    },
    {
      "year": 2000,
      "population": 2392530
    },
    {
      "year": 1990,
      "population": 2689391
    },
    {
      "year": 1980,
      "population": 2572037
    },
    {
      "year": 1970,
      "population": 2397414
    }
  ],
  "area_km2": 64559,
  "population_density": 28.666,
  "population_growth_rate": 0.9876,
  "percentage_world_population": 0.02
}
{
  "country": "Lebanon",
  "rank": 119,
  "cca3": "LBN",
  "capital": "Beirut",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 5489739
    },
    {
      "year": 2020,
      "population": 5662923
    },
    {
      "year": 2015,
      "population": 6398940
    },
    {
      "year": 2010,
      "population": 4995800
    },
    {
      "year": 2000,
      "population": 4320642
    },
    {
      "year": 1990,
      "population": 3593700
    },
    {
      "year": 1980,
      "population": 2963702
    },
    {
      "year": 1970,
      "population": 2381791
    }
  ],
  "area_km2": 10452,
  "population_density": 525.2334,
  "population_growth_rate": 0.9816,
  "percentage_world_population": 0.07
}
{
  "country": "Lesotho",
  "rank": 147,
  "cca3": "LSO",
  "capital": "Maseru",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 2305825
    },
    {
      "year": 2020,
      "population": 2254100
    },
    {
      "year": 2015,
      "population": 2118521
    },
    {
      "year": 2010,
      "population": 2022747
    },
    {
      "year": 2000,
      "population": 1998630
    },
    {
      "year": 1990,
      "population": 1798997
    },
    {
      "year": 1980,
      "population": 1407672
    },
    {
      "year": 1970,
      "population": 1023481
    }
  ],
  "area_km2": 30355,
  "population_density": 75.962,
  "population_growth_rate": 1.0107,
  "percentage_world_population": 0.03
}
{
  "country": "Liberia",
  "rank": 121,
  "cca3": "LBR",
  "capital": "Monrovia",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 5302681
    },
    {
      "year": 2020,
      "population": 5087584
    },
    {
      "year": 2015,
      "population": 4612329
    },
    {
      "year": 2010,
      "population": 4019956
    },
    {
      "year": 2000,
      "population": 2895224
    },
    {
      "year": 1990,
      "population": 2209731
    },
    {
      "year": 1980,
      "population": 1932169
    },
    {
      "year": 1970,
      "population": 1463563
    }
  ],
  "area_km2": 111369,
  "population_density": 47.6136,
  "population_growth_rate": 1.021,
  "percentage_world_population": 0.07
}
{
  "country": "Libya",
  "rank": 107,
  "cca3": "LBY",
  "capital": "Tripoli",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 6812341
    },
    {
      "year": 2020,
      "population": 6653942
    },
    {
      "year": 2015,
      "population": 6192235
    },
    {
      "year": 2010,
      "population": 6491988
    },
    {
      "year": 2000,
      "population": 5154790
    },
    {
      "year": 1990,
      "population": 4236983
    },
    {
      "year": 1980,
      "population": 2962720
    },
    {
      "year": 1970,
      "population": 1909177
    }
  ],
  "area_km2": 1759540,
  "population_density": 3.8717,
  "population_growth_rate": 1.0114,
  "percentage_world_population": 0.09
}
{
  "country": "Liechtenstein",
  "rank": 216,
  "cca3": "LIE",
  "capital": "Vaduz",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 39327
    },
    {
      "year": 2020,
      "population": 38756
    },
    {
      "year": 2015,
      "population": 37355
    },
    {
      "year": 2010,
      "population": 35926
    },
    {
      "year": 2000,
      "population": 33026
    },
    {
      "year": 1990,
      "population": 28765
    },
    {
      "year": 1980,
      "population": 25003
    },
    {
      "year": 1970,
      "population": 21089
    }
  ],
  "area_km2": 160,
  "population_density": 245.7937,
  "population_growth_rate": 1.0074,
  "percentage_world_population": 0
}
{
  "country": "Lithuania",
  "rank": 141,
  "cca3": "LTU",
  "capital": "Vilnius",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 2750055
    },
    {
      "year": 2020,
      "population": 2820267
    },
    {
      "year": 2015,
      "population": 2963765
    },
    {
      "year": 2010,
      "population": 3139019
    },
    {
      "year": 2000,
      "population": 3599637
    },
    {
      "year": 1990,
      "population": 3785847
    },
    {
      "year": 1980,
      "population": 3521206
    },
    {
      "year": 1970,
      "population": 3210147
    }
  ],
  "area_km2": 65300,
  "population_density": 42.1142,
  "population_growth_rate": 0.9869,
  "percentage_world_population": 0.03
}
{
  "country": "Luxembourg",
  "rank": 168,
  "cca3": "LUX",
  "capital": "Luxembourg",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 647599
    },
    {
      "year": 2020,
      "population": 630399
    },
    {
      "year": 2015,
      "population": 569408
    },
    {
      "year": 2010,
      "population": 507070
    },
    {
      "year": 2000,
      "population": 435628
    },
    {
      "year": 1990,
      "population": 381267
    },
    {
      "year": 1980,
      "population": 363741
    },
    {
      "year": 1970,
      "population": 339342
    }
  ],
  "area_km2": 2586,
  "population_density": 250.425,
  "population_growth_rate": 1.0129,
  "percentage_world_population": 0.01
}
{
  "country": "Macau",
  "rank": 167,
  "cca3": "MAC",
  "capital": "Concelho de Macau",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 695168
    },
    {
      "year": 2020,
      "population": 676283
    },
    {
      "year": 2015,
      "population": 615239
    },
    {
      "year": 2010,
      "population": 557297
    },
    {
      "year": 2000,
      "population": 431896
    },
    {
      "year": 1990,
      "population": 350227
    },
    {
      "year": 1980,
      "population": 245332
    },
    {
      "year": 1970,
      "population": 247284
    }
  ],
  "area_km2": 30,
  "population_density": 23172.2667,
  "population_growth_rate": 1.0125,
  "percentage_world_population": 0.01
}
{
  "country": "Madagascar",
  "rank": 50,
  "cca3": "MDG",
  "capital": "Antananarivo",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 29611714
    },
    {
      "year": 2020,
      "population": 28225177
    },
    {
      "year": 2015,
      "population": 24850912
    },
    {
      "year": 2010,
      "population": 21731053
    },
    {
      "year": 2000,
      "population": 16216431
    },
    {
      "year": 1990,
      "population": 11882762
    },
    {
      "year": 1980,
      "population": 8948162
    },
    {
      "year": 1970,
      "population": 6639751
    }
  ],
  "area_km2": 587041,
  "population_density": 50.4423,
  "population_growth_rate": 1.0241,
  "percentage_world_population": 0.37
}
{
  "country": "Malawi",
  "rank": 62,
  "cca3": "MWI",
  "capital": "Lilongwe",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 20405317
    },
    {
      "year": 2020,
      "population": 19377061
    },
    {
      "year": 2015,
      "population": 16938942
    },
    {
      "year": 2010,
      "population": 14718422
    },
    {
      "year": 2000,
      "population": 11229387
    },
    {
      "year": 1990,
      "population": 9539665
    },
    {
      "year": 1980,
      "population": 6267369
    },
    {
      "year": 1970,
      "population": 4625141
    }
  ],
  "area_km2": 118484,
  "population_density": 172.22,
  "population_growth_rate": 1.0259,
  "percentage_world_population": 0.26
}
{
  "country": "Malaysia",
  "rank": 45,
  "cca3": "MYS",
  "capital": "Kuala Lumpur",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 33938221
    },
    {
      "year": 2020,
      "population": 33199993
    },
    {
      "year": 2015,
      "population": 31068833
    },
    {
      "year": 2010,
      "population": 28717731
    },
    {
      "year": 2000,
      "population": 22945150
    },
    {
      "year": 1990,
      "population": 17517054
    },
    {
      "year": 1980,
      "population": 13215707
    },
    {
      "year": 1970,
      "population": 10306508
    }
  ],
  "area_km2": 330803,
  "population_density": 102.5934,
  "population_growth_rate": 1.0109,
  "percentage_world_population": 0.43
}
{
  "country": "Maldives",
  "rank": 174,
  "cca3": "MDV",
  "capital": "Malé",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 523787
    },
    {
      "year": 2020,
      "population": 514438
    },
    {
      "year": 2015,
      "population": 435582
    },
    {
      "year": 2010,
      "population": 361575
    },
    {
      "year": 2000,
      "population": 282507
    },
    {
      "year": 1990,
      "population": 224957
    },
    {
      "year": 1980,
      "population": 164887
    },
    {
      "year": 1970,
      "population": 123243
    }
  ],
  "area_km2": 300,
  "population_density": 1745.9567,
  "population_growth_rate": 1.0045,
  "percentage_world_population": 0.01
}
{
  "country": "Mali",
  "rank": 59,
  "cca3": "MLI",
  "capital": "Bamako",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 22593590
    },
    {
      "year": 2020,
      "population": 21224040
    },
    {
      "year": 2015,
      "population": 18112907
    },
    {
      "year": 2010,
      "population": 15529181
    },
    {
      "year": 2000,
      "population": 11239101
    },
    {
      "year": 1990,
      "population": 8945026
    },
    {
      "year": 1980,
      "population": 7372581
    },
    {
      "year": 1970,
      "population": 6153587
    }
  ],
  "area_km2": 1240192,
  "population_density": 18.2178,
  "population_growth_rate": 1.0314,
  "percentage_world_population": 0.28
}
{
  "country": "Malta",
  "rank": 173,
  "cca3": "MLT",
  "capital": "Valletta",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 533286
    },
    {
      "year": 2020,
      "population": 515357
    },
    {
      "year": 2015,
      "population": 456579
    },
    {
      "year": 2010,
      "population": 418755
    },
    {
      "year": 2000,
      "population": 399212
    },
    {
      "year": 1990,
      "population": 365392
    },
    {
      "year": 1980,
      "population": 333587
    },
    {
      "year": 1970,
      "population": 315414
    }
  ],
  "area_km2": 316,
  "population_density": 1687.6139,
  "population_growth_rate": 1.0124,
  "percentage_world_population": 0.01
}
{
  "country": "Marshall Islands",
  "rank": 215,
  "cca3": "MHL",
  "capital": "Majuro",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 41569
    },
    {
      "year": 2020,
      "population": 43413
    },
    {
      "year": 2015,
      "population": 49410
    },
    {
      "year": 2010,
      "population": 53416
    },
    {
      "year": 2000,
      "population": 54224
    },
    {
      "year": 1990,
      "population": 46047
    },
    {
      "year": 1980,
      "population": 31988
    },
    {
      "year": 1970,
      "population": 23969
    }
  ],
  "area_km2": 181,
  "population_density": 229.663,
  "population_growth_rate": 0.9886,
  "percentage_world_population": 0
}
{
  "country": "Martinique",
  "rank": 180,
  "cca3": "MTQ",
  "capital": "Fort-de-France",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 367507
    },
    {
      "year": 2020,
      "population": 370391
    },
    {
      "year": 2015,
      "population": 383515
    },
    {
      "year": 2010,
      "population": 392181
    },
    {
      "year": 2000,
      "population": 432543
    },
    {
      "year": 1990,
      "population": 374271
    },
    {
      "year": 1980,
      "population": 333786
    },
    {
      "year": 1970,
      "population": 326428
    }
  ],
  "area_km2": 1128,
  "population_density": 325.8041,
  "population_growth_rate": 0.9965,
  "percentage_world_population": 0
}
{
  "country": "Mauritania",
  "rank": 126,
  "cca3": "MRT",
  "capital": "Nouakchott",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 4736139
    },
    {
      "year": 2020,
      "population": 4498604
    },
    {
      "year": 2015,
      "population": 3946220
    },
    {
      "year": 2010,
      "population": 3419461
    },
    {
      "year": 2000,
      "population": 2695003
    },
    {
      "year": 1990,
      "population": 2006027
    },
    {
      "year": 1980,
      "population": 1506694
    },
    {
      "year": 1970,
      "population": 1122198
    }
  ],
  "area_km2": 1030700,
  "population_density": 4.5951,
  "population_growth_rate": 1.0263,
  "percentage_world_population": 0.06
}
{
  "country": "Mauritius",
  "rank": 157,
  "cca3": "MUS",
  "capital": "Port Louis",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 1299469
    },
    {
      "year": 2020,
      "population": 1297828
    },
    {
      "year": 2015,
      "population": 1293153
    },
    {
      "year": 2010,
      "population": 1283330
    },
    {
      "year": 2000,
      "population": 1215930
    },
    {
      "year": 1990,
      "population": 1090290
    },
    {
      "year": 1980,
      "population": 954865
    },
    {
      "year": 1970,
      "population": 830115
    }
  ],
  "area_km2": 2040,
  "population_density": 636.9946,
  "population_growth_rate": 1.0004,
  "percentage_world_population": 0.02
}
{
  "country": "Mayotte",
  "rank": 182,
  "cca3": "MYT",
  "capital": "Mamoudzou",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 326101
    },
    {
      "year": 2020,
      "population": 305587
    },
    {
      "year": 2015,
      "population": 249545
    },
    {
      "year": 2010,
      "population": 211786
    },
    {
      "year": 2000,
      "population": 159215
    },
    {
      "year": 1990,
      "population": 92659
    },
    {
      "year": 1980,
      "population": 52233
    },
    {
      "year": 1970,
      "population": 35383
    }
  ],
  "area_km2": 374,
  "population_density": 871.9278,
  "population_growth_rate": 1.0319,
  "percentage_world_population": 0
}
{
  "country": "Mexico",
  "rank": 10,
  "cca3": "MEX",
  "capital": "Mexico City",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 127504125
    },
    {
      "year": 2020,
      "population": 125998302
    },
    {
      "year": 2015,
      "population": 120149897
    },
    {
      "year": 2010,
      "population": 112532401
    },
    {
      "year": 2000,
      "population": 97873442
    },
    {
      "year": 1990,
      "population": 81720428
    },
    {
      "year": 1980,
      "population": 67705186
    },
    {
      "year": 1970,
      "population": 50289306
    }
  ],
  "area_km2": 1964375,
  "population_density": 64.9082,
  "population_growth_rate": 1.0063,
  "percentage_world_population": 1.6
}
{
  "country": "Micronesia",
  "rank": 194,
  "cca3": "FSM",
  "capital": "Palikir",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 114164
    },
    {
      "year": 2020,
      "population": 112106
    },
    {
      "year": 2015,
      "population": 109462
    },
    {
      "year": 2010,
      "population": 107588
    },
    {
      "year": 2000,
      "population": 111709
    },
    {
      "year": 1990,
      "population": 98603
    },
    {
      "year": 1980,
      "population": 76299
    },
    {
      "year": 1970,
      "population": 58989
    }
  ],
  "area_km2": 702,
  "population_density": 162.6268,
  "population_growth_rate": 1.0091,
  "percentage_world_population": 0
}
{
  "country": "Moldova",
  "rank": 135,
  "cca3": "MDA",
  "capital": "Chisinau",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 3272996
    },
    {
      "year": 2020,
      "population": 3084847
    },
    {
      "year": 2015,
      "population": 3277388
    },
    {
      "year": 2010,
      "population": 3678186
    },
    {
      "year": 2000,
      "population": 4251573
    },
    {
      "year": 1990,
      "population": 4480199
    },
    {
      "year": 1980,
      "population": 4103240
    },
    {
      "year": 1970,
      "population": 3711140
    }
  ],
  "area_km2": 33846,
  "population_density": 96.7026,
  "population_growth_rate": 1.0691,
  "percentage_world_population": 0.04
}
{
  "country": "Monaco",
  "rank": 217,
  "cca3": "MCO",
  "capital": "Monaco",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 36469
    },
    {
      "year": 2020,
      "population": 36922
    },
    {
      "year": 2015,
      "population": 36760
    },
    {
      "year": 2010,
      "population": 33178
    },
    {
      "year": 2000,
      "population": 32465
    },
    {
      "year": 1990,
      "population": 30329
    },
    {
      "year": 1980,
      "population": 27076
    },
    {
      "year": 1970,
      "population": 24270
    }
  ],
  "area_km2": 2,
  "population_density": 18234.5,
  "population_growth_rate": 0.9941,
  "percentage_world_population": 0
}
{
  "country": "Mongolia",
  "rank": 134,
  "cca3": "MNG",
  "capital": "Ulaanbaatar",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 3398366
    },
    {
      "year": 2020,
      "population": 3294335
    },
    {
      "year": 2015,
      "population": 2964749
    },
    {
      "year": 2010,
      "population": 2702520
    },
    {
      "year": 2000,
      "population": 2450979
    },
    {
      "year": 1990,
      "population": 2161433
    },
    {
      "year": 1980,
      "population": 1697780
    },
    {
      "year": 1970,
      "population": 1293880
    }
  ],
  "area_km2": 1564110,
  "population_density": 2.1727,
  "population_growth_rate": 1.0151,
  "percentage_world_population": 0.04
}
{
  "country": "Montenegro",
  "rank": 169,
  "cca3": "MNE",
  "capital": "Podgorica",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 627082
    },
    {
      "year": 2020,
      "population": 629048
    },
    {
      "year": 2015,
      "population": 633966
    },
    {
      "year": 2010,
      "population": 631044
    },
    {
      "year": 2000,
      "population": 633324
    },
    {
      "year": 1990,
      "population": 621442
    },
    {
      "year": 1980,
      "population": 589324
    },
    {
      "year": 1970,
      "population": 530268
    }
  ],
  "area_km2": 13812,
  "population_density": 45.4012,
  "population_growth_rate": 0.9988,
  "percentage_world_population": 0.01
}
{
  "country": "Montserrat",
  "rank": 230,
  "cca3": "MSR",
  "capital": "Brades",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 4390
    },
    {
      "year": 2020,
      "population": 4500
    },
    {
      "year": 2015,
      "population": 5059
    },
    {
      "year": 2010,
      "population": 4938
    },
    {
      "year": 2000,
      "population": 5138
    },
    {
      "year": 1990,
      "population": 10805
    },
    {
      "year": 1980,
      "population": 11452
    },
    {
      "year": 1970,
      "population": 11402
    }
  ],
  "area_km2": 102,
  "population_density": 43.0392,
  "population_growth_rate": 0.9939,
  "percentage_world_population": 0
}
{
  "country": "Morocco",
  "rank": 40,
  "cca3": "MAR",
  "capital": "Rabat",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 37457971
    },
    {
      "year": 2020,
      "population": 36688772
    },
    {
      "year": 2015,
      "population": 34680458
    },
    {
      "year": 2010,
      "population": 32464865
    },
    {
      "year": 2000,
      "population": 28554415
    },
    {
      "year": 1990,
      "population": 24570814
    },
    {
      "year": 1980,
      "population": 19678444
    },
    {
      "year": 1970,
      "population": 15274351
    }
  ],
  "area_km2": 446550,
  "population_density": 83.883,
  "population_growth_rate": 1.0103,
  "percentage_world_population": 0.47
}
{
  "country": "Mozambique",
  "rank": 48,
  "cca3": "MOZ",
  "capital": "Maputo",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 32969517
    },
    {
      "year": 2020,
      "population": 31178239
    },
    {
      "year": 2015,
      "population": 26843246
    },
    {
      "year": 2010,
      "population": 23073723
    },
    {
      "year": 2000,
      "population": 17768505
    },
    {
      "year": 1990,
      "population": 13303459
    },
    {
      "year": 1980,
      "population": 11413587
    },
    {
      "year": 1970,
      "population": 8411676
    }
  ],
  "area_km2": 801590,
  "population_density": 41.1302,
  "population_growth_rate": 1.0278,
  "percentage_world_population": 0.41
}
{
  "country": "Myanmar",
  "rank": 26,
  "cca3": "MMR",
  "capital": "Nay Pyi Taw",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 54179306
    },
    {
      "year": 2020,
      "population": 53423198
    },
    {
      "year": 2015,
      "population": 51483949
    },
    {
      "year": 2010,
      "population": 49390988
    },
    {
      "year": 2000,
      "population": 45538332
    },
    {
      "year": 1990,
      "population": 40099553
    },
    {
      "year": 1980,
      "population": 33465781
    },
    {
      "year": 1970,
      "population": 27284112
    }
  ],
  "area_km2": 676578,
  "population_density": 80.0784,
  "population_growth_rate": 1.0071,
  "percentage_world_population": 0.68
}
{
  "country": "Namibia",
  "rank": 145,
  "cca3": "NAM",
  "capital": "Windhoek",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 2567012
    },
    {
      "year": 2020,
      "population": 2489098
    },
    {
      "year": 2015,
      "population": 2282704
    },
    {
      "year": 2010,
      "population": 2099271
    },
    {
      "year": 2000,
      "population": 1819141
    },
    {
      "year": 1990,
      "population": 1369011
    },
    {
      "year": 1980,
      "population": 975994
    },
    {
      "year": 1970,
      "population": 754467
    }
  ],
  "area_km2": 825615,
  "population_density": 3.1092,
  "population_growth_rate": 1.0146,
  "percentage_world_population": 0.03
}
{
  "country": "Nauru",
  "rank": 225,
  "cca3": "NRU",
  "capital": "Yaren",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 12668
    },
    {
      "year": 2020,
      "population": 12315
    },
    {
      "year": 2015,
      "population": 11185
    },
    {
      "year": 2010,
      "population": 10241
    },
    {
      "year": 2000,
      "population": 10377
    },
    {
      "year": 1990,
      "population": 9598
    },
    {
      "year": 1980,
      "population": 7635
    },
    {
      "year": 1970,
      "population": 6663
    }
  ],
  "area_km2": 21,
  "population_density": 603.2381,
  "population_growth_rate": 1.0125,
  "percentage_world_population": 0
}
{
  "country": "Nepal",
  "rank": 49,
  "cca3": "NPL",
  "capital": "Kathmandu",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 30547580
    },
    {
      "year": 2020,
      "population": 29348627
    },
    {
      "year": 2015,
      "population": 27610325
    },
    {
      "year": 2010,
      "population": 27161567
    },
    {
      "year": 2000,
      "population": 24559500
    },
    {
      "year": 1990,
      "population": 19616530
    },
    {
      "year": 1980,
      "population": 15600442
    },
    {
      "year": 1970,
      "population": 12501285
    }
  ],
  "area_km2": 147181,
  "population_density": 207.5511,
  "population_growth_rate": 1.0171,
  "percentage_world_population": 0.38
}
{
  "country": "Netherlands",
  "rank": 71,
  "cca3": "NLD",
  "capital": "Amsterdam",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 17564014
    },
    {
      "year": 2020,
      "population": 17434557
    },
    {
      "year": 2015,
      "population": 17041107
    },
    {
      "year": 2010,
      "population": 16617116
    },
    {
      "year": 2000,
      "population": 15899135
    },
    {
      "year": 1990,
      "population": 14944548
    },
    {
      "year": 1980,
      "population": 14130387
    },
    {
      "year": 1970,
      "population": 13037686
    }
  ],
  "area_km2": 41850,
  "population_density": 419.6897,
  "population_growth_rate": 1.0036,
  "percentage_world_population": 0.22
}
{
  "country": "New Caledonia",
  "rank": 185,
  "cca3": "NCL",
  "capital": "Nouméa",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 289950
    },
    {
      "year": 2020,
      "population": 286403
    },
    {
      "year": 2015,
      "population": 283032
    },
    {
      "year": 2010,
      "population": 261426
    },
    {
      "year": 2000,
      "population": 221537
    },
    {
      "year": 1990,
      "population": 177264
    },
    {
      "year": 1980,
      "population": 148599
    },
    {
      "year": 1970,
      "population": 110982
    }
  ],
  "area_km2": 18575,
  "population_density": 15.6097,
  "population_growth_rate": 1.0075,
  "percentage_world_population": 0
}
{
  "country": "New Zealand",
  "rank": 123,
  "cca3": "NZL",
  "capital": "Wellington",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 5185288
    },
    {
      "year": 2020,
      "population": 5061133
    },
    {
      "year": 2015,
      "population": 4590590
    },
    {
      "year": 2010,
      "population": 4346338
    },
    {
      "year": 2000,
      "population": 3855266
    },
    {
      "year": 1990,
      "population": 3397389
    },
    {
      "year": 1980,
      "population": 3147168
    },
    {
      "year": 1970,
      "population": 2824061
    }
  ],
  "area_km2": 270467,
  "population_density": 19.1716,
  "population_growth_rate": 1.0108,
  "percentage_world_population": 0.07
}
{
  "country": "Nicaragua",
  "rank": 106,
  "cca3": "NIC",
  "capital": "Managua",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 6948392
    },
    {
      "year": 2020,
      "population": 6755895
    },
    {
      "year": 2015,
      "population": 6298598
    },
    {
      "year": 2010,
      "population": 5855734
    },
    {
      "year": 2000,
      "population": 5123222
    },
    {
      "year": 1990,
      "population": 4227820
    },
    {
      "year": 1980,
      "population": 3303309
    },
    {
      "year": 1970,
      "population": 2444767
    }
  ],
  "area_km2": 130373,
  "population_density": 53.2962,
  "population_growth_rate": 1.0143,
  "percentage_world_population": 0.09
}
{
  "country": "Niger",
  "rank": 54,
  "cca3": "NER",
  "capital": "Niamey",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 26207977
    },
    {
      "year": 2020,
      "population": 24333639
    },
    {
      "year": 2015,
      "population": 20128124
    },
    {
      "year": 2010,
      "population": 16647543
    },
    {
      "year": 2000,
      "population": 11622665
    },
    {
      "year": 1990,
      "population": 8370647
    },
    {
      "year": 1980,
      "population": 6173177
    },
    {
      "year": 1970,
      "population": 4669708
    }
  ],
  "area_km2": 1267000,
  "population_density": 20.6851,
  "population_growth_rate": 1.0378,
  "percentage_world_population": 0.33
}
{
  "country": "Nigeria",
  "rank": 6,
  "cca3": "NGA",
  "capital": "Abuja",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 218541212
    },
    {
      "year": 2020,
      "population": 208327405
    },
    {
      "year": 2015,
      "population": 183995785
    },
    {
      "year": 2010,
      "population": 160952853
    },
    {
      "year": 2000,
      "population": 122851984
    },
    {
      "year": 1990,
      "population": 95214257
    },
    {
      "year": 1980,
      "population": 72951439
    },
    {
      "year": 1970,
      "population": 55569264
    }
  ],
  "area_km2": 923768,
  "population_density": 236.5759,
  "population_growth_rate": 1.0241,
  "percentage_world_population": 2.74
}
{
  "country": "Niue",
  "rank": 232,
  "cca3": "NIU",
  "capital": "Alofi",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 1934
    },
    {
      "year": 2020,
      "population": 1942
    },
    {
      "year": 2015,
      "population": 1847
    },
    {
      "year": 2010,
      "population": 1812
    },
    {
      "year": 2000,
      "population": 2074
    },
    {
      "year": 1990,
      "population": 2533
    },
    {
      "year": 1980,
      "population": 3637
    },
    {
      "year": 1970,
      "population": 5185
    }
  ],
  "area_km2": 260,
  "population_density": 7.4385,
  "population_growth_rate": 0.9985,
  "percentage_world_population": 0
}
{
  "country": "North Korea",
  "rank": 56,
  "cca3": "PRK",
  "capital": "Pyongyang",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 26069416
    },
    {
      "year": 2020,
      "population": 25867467
    },
    {
      "year": 2015,
      "population": 25258015
    },
    {
      "year": 2010,
      "population": 24686435
    },
    {
      "year": 2000,
      "population": 23367059
    },
    {
      "year": 1990,
      "population": 20799523
    },
    {
      "year": 1980,
      "population": 17973650
    },
    {
      "year": 1970,
      "population": 14996879
    }
  ],
  "area_km2": 120538,
  "population_density": 216.2755,
  "population_growth_rate": 1.0038,
  "percentage_world_population": 0.33
}
{
  "country": "North Macedonia",
  "rank": 150,
  "cca3": "MKD",
  "capital": "Skopje",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 2093599
    },
    {
      "year": 2020,
      "population": 2111072
    },
    {
      "year": 2015,
      "population": 2107962
    },
    {
      "year": 2010,
      "population": 2093828
    },
    {
      "year": 2000,
      "population": 2037936
    },
    {
      "year": 1990,
      "population": 2044174
    },
    {
      "year": 1980,
      "population": 1907023
    },
    {
      "year": 1970,
      "population": 1656783
    }
  ],
  "area_km2": 25713,
  "population_density": 81.4218,
  "population_growth_rate": 0.9954,
  "percentage_world_population": 0.03
}
{
  "country": "Northern Mariana Islands",
  "rank": 210,
  "cca3": "NFK",
  "capital": "Saipan",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 49551
    },
    {
      "year": 2020,
      "population": 49587
    },
    {
      "year": 2015,
      "population": 51514
    },
    {
      "year": 2010,
      "population": 54087
    },
    {
      "year": 2000,
      "population": 80338
    },
    {
      "year": 1990,
      "population": 48002
    },
    {
      "year": 1980,
      "population": 17613
    },
    {
      "year": 1970,
      "population": 10143
    }
  ],
  "area_km2": 464,
  "population_density": 106.7909,
  "population_growth_rate": 1.0014,
  "percentage_world_population": 0
}
{
  "country": "Norway",
  "rank": 120,
  "cca3": "NOR",
  "capital": "Oslo",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 5434319
    },
    {
      "year": 2020,
      "population": 5379839
    },
    {
      "year": 2015,
      "population": 5190356
    },
    {
      "year": 2010,
      "population": 4889741
    },
    {
      "year": 2000,
      "population": 4491202
    },
    {
      "year": 1990,
      "population": 4241636
    },
    {
      "year": 1980,
      "population": 4085776
    },
    {
      "year": 1970,
      "population": 3875546
    }
  ],
  "area_km2": 323802,
  "population_density": 16.7828,
  "population_growth_rate": 1.0058,
  "percentage_world_population": 0.07
}
{
  "country": "Oman",
  "rank": 127,
  "cca3": "OMN",
  "capital": "Muscat",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 4576298
    },
    {
      "year": 2020,
      "population": 4543399
    },
    {
      "year": 2015,
      "population": 4191776
    },
    {
      "year": 2010,
      "population": 2881914
    },
    {
      "year": 2000,
      "population": 2344253
    },
    {
      "year": 1990,
      "population": 1804524
    },
    {
      "year": 1980,
      "population": 1017462
    },
    {
      "year": 1970,
      "population": 670693
    }
  ],
  "area_km2": 309500,
  "population_density": 14.7861,
  "population_growth_rate": 1.0123,
  "percentage_world_population": 0.06
}
{
  "country": "Pakistan",
  "rank": 5,
  "cca3": "PAK",
  "capital": "Islamabad",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 235824862
    },
    {
      "year": 2020,
      "population": 227196741
    },
    {
      "year": 2015,
      "population": 210969298
    },
    {
      "year": 2010,
      "population": 194454498
    },
    {
      "year": 2000,
      "population": 154369924
    },
    {
      "year": 1990,
      "population": 115414069
    },
    {
      "year": 1980,
      "population": 80624057
    },
    {
      "year": 1970,
      "population": 59290872
    }
  ],
  "area_km2": 881912,
  "population_density": 267.4018,
  "population_growth_rate": 1.0191,
  "percentage_world_population": 2.96
}
{
  "country": "Palau",
  "rank": 222,
  "cca3": "PLW",
  "capital": "Ngerulmud",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 18055
    },
    {
      "year": 2020,
      "population": 17972
    },
    {
      "year": 2015,
      "population": 17794
    },
    {
      "year": 2010,
      "population": 18540
    },
    {
      "year": 2000,
      "population": 19726
    },
    {
      "year": 1990,
      "population": 15293
    },
    {
      "year": 1980,
      "population": 12252
    },
    {
      "year": 1970,
      "population": 11366
    }
  ],
  "area_km2": 459,
  "population_density": 39.3355,
  "population_growth_rate": 1.0017,
  "percentage_world_population": 0
}
{
  "country": "Palestine",
  "rank": 122,
  "cca3": "PSE",
  "capital": "Ramallah",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 5250072
    },
    {
      "year": 2020,
      "population": 5019401
    },
    {
      "year": 2015,
      "population": 4484614
    },
    {
      "year": 2010,
      "population": 3992278
    },
    {
      "year": 2000,
      "population": 3139954
    },
    {
      "year": 1990,
      "population": 2124609
    },
    {
      "year": 1980,
      "population": 1453620
    },
    {
      "year": 1970,
      "population": 1118241
    }
  ],
  "area_km2": 6220,
  "population_density": 844.063,
  "population_growth_rate": 1.0227,
  "percentage_world_population": 0.07
}
{
  "country": "Panama",
  "rank": 128,
  "cca3": "PAN",
  "capital": "Panama City",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 4408581
    },
    {
      "year": 2020,
      "population": 4294396
    },
    {
      "year": 2015,
      "population": 3957099
    },
    {
      "year": 2010,
      "population": 3623617
    },
    {
      "year": 2000,
      "population": 3001731
    },
    {
      "year": 1990,
      "population": 2449968
    },
    {
      "year": 1980,
      "population": 1956987
    },
    {
      "year": 1970,
      "population": 1516188
    }
  ],
  "area_km2": 75417,
  "population_density": 58.4561,
  "population_growth_rate": 1.0132,
  "percentage_world_population": 0.06
}
{
  "country": "Papua New Guinea",
  "rank": 93,
  "cca3": "PNG",
  "capital": "Port Moresby",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 10142619
    },
    {
      "year": 2020,
      "population": 9749640
    },
    {
      "year": 2015,
      "population": 8682174
    },
    {
      "year": 2010,
      "population": 7583269
    },
    {
      "year": 2000,
      "population": 5508297
    },
    {
      "year": 1990,
      "population": 3864972
    },
    {
      "year": 1980,
      "population": 3104788
    },
    {
      "year": 1970,
      "population": 2489059
    }
  ],
  "area_km2": 462840,
  "population_density": 21.9139,
  "population_growth_rate": 1.0194,
  "percentage_world_population": 0.13
}
{
  "country": "Paraguay",
  "rank": 109,
  "cca3": "PRY",
  "capital": "Asunción",
  "continent": "South America",
  "population": [
    {
      "year": 2022,
      "population": 6780744
    },
    {
      "year": 2020,
      "population": 6618695
    },
    {
      "year": 2015,
      "population": 6177950
    },
    {
      "year": 2010,
      "population": 5768613
    },
    {
      "year": 2000,
      "population": 5123819
    },
    {
      "year": 1990,
      "population": 4059195
    },
    {
      "year": 1980,
      "population": 3078912
    },
    {
      "year": 1970,
      "population": 2408787
    }
  ],
  "area_km2": 406752,
  "population_density": 16.6705,
  "population_growth_rate": 1.0115,
  "percentage_world_population": 0.09
}
{
  "country": "Peru",
  "rank": 44,
  "cca3": "PER",
  "capital": "Lima",
  "continent": "South America",
  "population": [
    {
      "year": 2022,
      "population": 34049588
    },
    {
      "year": 2020,
      "population": 33304756
    },
    {
      "year": 2015,
      "population": 30711863
    },
    {
      "year": 2010,
      "population": 29229572
    },
    {
      "year": 2000,
      "population": 26654439
    },
    {
      "year": 1990,
      "population": 22109099
    },
    {
      "year": 1980,
      "population": 17492406
    },
    {
      "year": 1970,
      "population": 13562371
    }
  ],
  "area_km2": 1285216,
  "population_density": 26.4933,
  "population_growth_rate": 1.0099,
  "percentage_world_population": 0.43
}
{
  "country": "Philippines",
  "rank": 13,
  "cca3": "PHL",
  "capital": "Manila",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 115559009
    },
    {
      "year": 2020,
      "population": 112190977
    },
    {
      "year": 2015,
      "population": 103031365
    },
    {
      "year": 2010,
      "population": 94636700
    },
    {
      "year": 2000,
      "population": 77958223
    },
    {
      "year": 1990,
      "population": 61558898
    },
    {
      "year": 1980,
      "population": 48419546
    },
    {
      "year": 1970,
      "population": 37435586
    }
  ],
  "area_km2": 342353,
  "population_density": 337.5434,
  "population_growth_rate": 1.0147,
  "percentage_world_population": 1.45
}
{
  "country": "Poland",
  "rank": 37,
  "cca3": "POL",
  "capital": "Warsaw",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 39857145
    },
    {
      "year": 2020,
      "population": 38428366
    },
    {
      "year": 2015,
      "population": 38553146
    },
    {
      "year": 2010,
      "population": 38597353
    },
    {
      "year": 2000,
      "population": 38504431
    },
    {
      "year": 1990,
      "population": 38064255
    },
    {
      "year": 1980,
      "population": 35521429
    },
    {
      "year": 1970,
      "population": 32482943
    }
  ],
  "area_km2": 312679,
  "population_density": 127.4698,
  "population_growth_rate": 1.0404,
  "percentage_world_population": 0.5
}
{
  "country": "Portugal",
  "rank": 92,
  "cca3": "PRT",
  "capital": "Lisbon",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 10270865
    },
    {
      "year": 2020,
      "population": 10298192
    },
    {
      "year": 2015,
      "population": 10365435
    },
    {
      "year": 2010,
      "population": 10588401
    },
    {
      "year": 2000,
      "population": 10300626
    },
    {
      "year": 1990,
      "population": 10007346
    },
    {
      "year": 1980,
      "population": 9785252
    },
    {
      "year": 1970,
      "population": 8683631
    }
  ],
  "area_km2": 92090,
  "population_density": 111.5307,
  "population_growth_rate": 0.9981,
  "percentage_world_population": 0.13
}
{
  "country": "Puerto Rico",
  "rank": 136,
  "cca3": "PRI",
  "capital": "San Juan",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 3252407
    },
    {
      "year": 2020,
      "population": 3271564
    },
    {
      "year": 2015,
      "population": 3497335
    },
    {
      "year": 2010,
      "population": 3717922
    },
    {
      "year": 2000,
      "population": 3827108
    },
    {
      "year": 1990,
      "population": 3543776
    },
    {
      "year": 1980,
      "population": 3214568
    },
    {
      "year": 1970,
      "population": 2737619
    }
  ],
  "area_km2": 8870,
  "population_density": 366.675,
  "population_growth_rate": 0.9989,
  "percentage_world_population": 0.04
}
{
  "country": "Qatar",
  "rank": 143,
  "cca3": "QAT",
  "capital": "Doha",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 2695122
    },
    {
      "year": 2020,
      "population": 2760385
    },
    {
      "year": 2015,
      "population": 2414573
    },
    {
      "year": 2010,
      "population": 1713504
    },
    {
      "year": 2000,
      "population": 645937
    },
    {
      "year": 1990,
      "population": 441675
    },
    {
      "year": 1980,
      "population": 277450
    },
    {
      "year": 1970,
      "population": 118007
    }
  ],
  "area_km2": 11586,
  "population_density": 232.6189,
  "population_growth_rate": 1.0026,
  "percentage_world_population": 0.03
}
{
  "country": "Republic of the Congo",
  "rank": 114,
  "cca3": "COG",
  "capital": "Brazzaville",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 5970424
    },
    {
      "year": 2020,
      "population": 5702174
    },
    {
      "year": 2015,
      "population": 5064386
    },
    {
      "year": 2010,
      "population": 4437884
    },
    {
      "year": 2000,
      "population": 3134030
    },
    {
      "year": 1990,
      "population": 2385435
    },
    {
      "year": 1980,
      "population": 1829256
    },
    {
      "year": 1970,
      "population": 1396989
    }
  ],
  "area_km2": 342000,
  "population_density": 17.4574,
  "population_growth_rate": 1.0231,
  "percentage_world_population": 0.07
}
{
  "country": "Reunion",
  "rank": 161,
  "cca3": "REU",
  "capital": "Saint-Denis",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 974052
    },
    {
      "year": 2020,
      "population": 957822
    },
    {
      "year": 2015,
      "population": 922495
    },
    {
      "year": 2010,
      "population": 890130
    },
    {
      "year": 2000,
      "population": 785424
    },
    {
      "year": 1990,
      "population": 658992
    },
    {
      "year": 1980,
      "population": 551674
    },
    {
      "year": 1970,
      "population": 473925
    }
  ],
  "area_km2": 2511,
  "population_density": 387.914,
  "population_growth_rate": 1.0082,
  "percentage_world_population": 0.01
}
{
  "country": "Romania",
  "rank": 64,
  "cca3": "ROU",
  "capital": "Bucharest",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 19659267
    },
    {
      "year": 2020,
      "population": 19442038
    },
    {
      "year": 2015,
      "population": 19906079
    },
    {
      "year": 2010,
      "population": 20335211
    },
    {
      "year": 2000,
      "population": 21919876
    },
    {
      "year": 1990,
      "population": 22836234
    },
    {
      "year": 1980,
      "population": 22125224
    },
    {
      "year": 1970,
      "population": 19922618
    }
  ],
  "area_km2": 238391,
  "population_density": 82.4665,
  "population_growth_rate": 1.0171,
  "percentage_world_population": 0.25
}
{
  "country": "Russia",
  "rank": 9,
  "cca3": "RUS",
  "capital": "Moscow",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 144713314
    },
    {
      "year": 2020,
      "population": 145617329
    },
    {
      "year": 2015,
      "population": 144668389
    },
    {
      "year": 2010,
      "population": 143242599
    },
    {
      "year": 2000,
      "population": 146844839
    },
    {
      "year": 1990,
      "population": 148005704
    },
    {
      "year": 1980,
      "population": 138257420
    },
    {
      "year": 1970,
      "population": 130093010
    }
  ],
  "area_km2": 17098242,
  "population_density": 8.4636,
  "population_growth_rate": 0.9973,
  "percentage_world_population": 1.81
}
{
  "country": "Rwanda",
  "rank": 76,
  "cca3": "RWA",
  "capital": "Kigali",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 13776698
    },
    {
      "year": 2020,
      "population": 13146362
    },
    {
      "year": 2015,
      "population": 11642959
    },
    {
      "year": 2010,
      "population": 10309031
    },
    {
      "year": 2000,
      "population": 8109989
    },
    {
      "year": 1990,
      "population": 7319962
    },
    {
      "year": 1980,
      "population": 5247532
    },
    {
      "year": 1970,
      "population": 3896367
    }
  ],
  "area_km2": 26338,
  "population_density": 523.0731,
  "population_growth_rate": 1.0234,
  "percentage_world_population": 0.17
}
{
  "country": "Saint Barthelemy",
  "rank": 228,
  "cca3": "BLM",
  "capital": "Gustavia",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 10967
    },
    {
      "year": 2020,
      "population": 10681
    },
    {
      "year": 2015,
      "population": 9643
    },
    {
      "year": 2010,
      "population": 8988
    },
    {
      "year": 2000,
      "population": 7082
    },
    {
      "year": 1990,
      "population": 5168
    },
    {
      "year": 1980,
      "population": 2983
    },
    {
      "year": 1970,
      "population": 2417
    }
  ],
  "area_km2": 21,
  "population_density": 522.2381,
  "population_growth_rate": 1.0098,
  "percentage_world_population": 0
}
{
  "country": "Saint Kitts and Nevis",
  "rank": 211,
  "cca3": "KNA",
  "capital": "Basseterre",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 47657
    },
    {
      "year": 2020,
      "population": 47642
    },
    {
      "year": 2015,
      "population": 47790
    },
    {
      "year": 2010,
      "population": 47403
    },
    {
      "year": 2000,
      "population": 45461
    },
    {
      "year": 1990,
      "population": 40636
    },
    {
      "year": 1980,
      "population": 43097
    },
    {
      "year": 1970,
      "population": 44968
    }
  ],
  "area_km2": 261,
  "population_density": 182.5939,
  "population_growth_rate": 1.0011,
  "percentage_world_population": 0
}
{
  "country": "Saint Lucia",
  "rank": 190,
  "cca3": "LCA",
  "capital": "Castries",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 179857
    },
    {
      "year": 2020,
      "population": 179237
    },
    {
      "year": 2015,
      "population": 175623
    },
    {
      "year": 2010,
      "population": 170935
    },
    {
      "year": 2000,
      "population": 159500
    },
    {
      "year": 1990,
      "population": 142301
    },
    {
      "year": 1980,
      "population": 121633
    },
    {
      "year": 1970,
      "population": 103090
    }
  ],
  "area_km2": 616,
  "population_density": 291.9756,
  "population_growth_rate": 1.0011,
  "percentage_world_population": 0
}
{
  "country": "Saint Martin",
  "rank": 220,
  "cca3": "MAF",
  "capital": "Marigot",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 31791
    },
    {
      "year": 2020,
      "population": 32552
    },
    {
      "year": 2015,
      "population": 35020
    },
    {
      "year": 2010,
      "population": 36458
    },
    {
      "year": 2000,
      "population": 29610
    },
    {
      "year": 1990,
      "population": 28127
    },
    {
      "year": 1980,
      "population": 7776
    },
    {
      "year": 1970,
      "population": 5802
    }
  ],
  "area_km2": 53,
  "population_density": 599.8302,
  "population_growth_rate": 0.9951,
  "percentage_world_population": 0
}
{
  "country": "Saint Pierre and Miquelon",
  "rank": 229,
  "cca3": "SPM",
  "capital": "Saint-Pierre",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 5862
    },
    {
      "year": 2020,
      "population": 5906
    },
    {
      "year": 2015,
      "population": 5978
    },
    {
      "year": 2010,
      "population": 6052
    },
    {
      "year": 2000,
      "population": 6274
    },
    {
      "year": 1990,
      "population": 6324
    },
    {
      "year": 1980,
      "population": 6106
    },
    {
      "year": 1970,
      "population": 5537
    }
  ],
  "area_km2": 242,
  "population_density": 24.2231,
  "population_growth_rate": 0.9964,
  "percentage_world_population": 0
}
{
  "country": "Saint Vincent and the Grenadines",
  "rank": 199,
  "cca3": "VCT",
  "capital": "Kingstown",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 103948
    },
    {
      "year": 2020,
      "population": 104632
    },
    {
      "year": 2015,
      "population": 106482
    },
    {
      "year": 2010,
      "population": 109308
    },
    {
      "year": 2000,
      "population": 113813
    },
    {
      "year": 1990,
      "population": 112487
    },
    {
      "year": 1980,
      "population": 107480
    },
    {
      "year": 1970,
      "population": 98459
    }
  ],
  "area_km2": 389,
  "population_density": 267.2185,
  "population_growth_rate": 0.9963,
  "percentage_world_population": 0
}
{
  "country": "Samoa",
  "rank": 188,
  "cca3": "WSM",
  "capital": "Apia",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 222382
    },
    {
      "year": 2020,
      "population": 214929
    },
    {
      "year": 2015,
      "population": 203571
    },
    {
      "year": 2010,
      "population": 194672
    },
    {
      "year": 2000,
      "population": 184008
    },
    {
      "year": 1990,
      "population": 168186
    },
    {
      "year": 1980,
      "population": 164905
    },
    {
      "year": 1970,
      "population": 142771
    }
  ],
  "area_km2": 2842,
  "population_density": 78.2484,
  "population_growth_rate": 1.0165,
  "percentage_world_population": 0
}
{
  "country": "San Marino",
  "rank": 218,
  "cca3": "SMR",
  "capital": "San Marino",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 33660
    },
    {
      "year": 2020,
      "population": 34007
    },
    {
      "year": 2015,
      "population": 33570
    },
    {
      "year": 2010,
      "population": 31608
    },
    {
      "year": 2000,
      "population": 26823
    },
    {
      "year": 1990,
      "population": 23132
    },
    {
      "year": 1980,
      "population": 21346
    },
    {
      "year": 1970,
      "population": 18169
    }
  ],
  "area_km2": 61,
  "population_density": 551.8033,
  "population_growth_rate": 0.9975,
  "percentage_world_population": 0
}
{
  "country": "Sao Tome and Principe",
  "rank": 187,
  "cca3": "STP",
  "capital": "São Tomé",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 227380
    },
    {
      "year": 2020,
      "population": 218641
    },
    {
      "year": 2015,
      "population": 201124
    },
    {
      "year": 2010,
      "population": 182138
    },
    {
      "year": 2000,
      "population": 143714
    },
    {
      "year": 1990,
      "population": 120343
    },
    {
      "year": 1980,
      "population": 97210
    },
    {
      "year": 1970,
      "population": 77583
    }
  ],
  "area_km2": 964,
  "population_density": 235.8714,
  "population_growth_rate": 1.0192,
  "percentage_world_population": 0
}
{
  "country": "Saudi Arabia",
  "rank": 41,
  "cca3": "SAU",
  "capital": "Riyadh",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 36408820
    },
    {
      "year": 2020,
      "population": 35997107
    },
    {
      "year": 2015,
      "population": 32749848
    },
    {
      "year": 2010,
      "population": 29411929
    },
    {
      "year": 2000,
      "population": 21547390
    },
    {
      "year": 1990,
      "population": 16004763
    },
    {
      "year": 1980,
      "population": 10171710
    },
    {
      "year": 1970,
      "population": 6106191
    }
  ],
  "area_km2": 2149690,
  "population_density": 16.9368,
  "population_growth_rate": 1.0128,
  "percentage_world_population": 0.46
}
{
  "country": "Senegal",
  "rank": 72,
  "cca3": "SEN",
  "capital": "Dakar",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 17316449
    },
    {
      "year": 2020,
      "population": 16436119
    },
    {
      "year": 2015,
      "population": 14356181
    },
    {
      "year": 2010,
      "population": 12530121
    },
    {
      "year": 2000,
      "population": 9704287
    },
    {
      "year": 1990,
      "population": 7536001
    },
    {
      "year": 1980,
      "population": 5703869
    },
    {
      "year": 1970,
      "population": 4367744
    }
  ],
  "area_km2": 196722,
  "population_density": 88.025,
  "population_growth_rate": 1.0261,
  "percentage_world_population": 0.22
}
{
  "country": "Serbia",
  "rank": 105,
  "cca3": "SRB",
  "capital": "Belgrade",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 7221365
    },
    {
      "year": 2020,
      "population": 7358005
    },
    {
      "year": 2015,
      "population": 7519496
    },
    {
      "year": 2010,
      "population": 7653748
    },
    {
      "year": 2000,
      "population": 7935022
    },
    {
      "year": 1990,
      "population": 7987529
    },
    {
      "year": 1980,
      "population": 7777010
    },
    {
      "year": 1970,
      "population": 7193533
    }
  ],
  "area_km2": 88361,
  "population_density": 81.7257,
  "population_growth_rate": 0.9897,
  "percentage_world_population": 0.09
}
{
  "country": "Seychelles",
  "rank": 196,
  "cca3": "SYC",
  "capital": "Victoria",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 107118
    },
    {
      "year": 2020,
      "population": 105530
    },
    {
      "year": 2015,
      "population": 99240
    },
    {
      "year": 2010,
      "population": 92409
    },
    {
      "year": 2000,
      "population": 80060
    },
    {
      "year": 1990,
      "population": 71057
    },
    {
      "year": 1980,
      "population": 65290
    },
    {
      "year": 1970,
      "population": 54379
    }
  ],
  "area_km2": 452,
  "population_density": 236.9867,
  "population_growth_rate": 1.0061,
  "percentage_world_population": 0
}
{
  "country": "Sierra Leone",
  "rank": 102,
  "cca3": "SLE",
  "capital": "Freetown",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 8605718
    },
    {
      "year": 2020,
      "population": 8233969
    },
    {
      "year": 2015,
      "population": 7314773
    },
    {
      "year": 2010,
      "population": 6436698
    },
    {
      "year": 2000,
      "population": 4584067
    },
    {
      "year": 1990,
      "population": 4325388
    },
    {
      "year": 1980,
      "population": 3367477
    },
    {
      "year": 1970,
      "population": 2778557
    }
  ],
  "area_km2": 71740,
  "population_density": 119.957,
  "population_growth_rate": 1.022,
  "percentage_world_population": 0.11
}
{
  "country": "Singapore",
  "rank": 113,
  "cca3": "SGP",
  "capital": "Singapore",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 5975689
    },
    {
      "year": 2020,
      "population": 5909869
    },
    {
      "year": 2015,
      "population": 5650018
    },
    {
      "year": 2010,
      "population": 5163590
    },
    {
      "year": 2000,
      "population": 4053602
    },
    {
      "year": 1990,
      "population": 3022209
    },
    {
      "year": 1980,
      "population": 2400729
    },
    {
      "year": 1970,
      "population": 2061831
    }
  ],
  "area_km2": 710,
  "population_density": 8416.4634,
  "population_growth_rate": 1.0058,
  "percentage_world_population": 0.07
}
{
  "country": "Sint Maarten",
  "rank": 214,
  "cca3": "SXM",
  "capital": "Philipsburg",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 44175
    },
    {
      "year": 2020,
      "population": 43621
    },
    {
      "year": 2015,
      "population": 40205
    },
    {
      "year": 2010,
      "population": 33034
    },
    {
      "year": 2000,
      "population": 30489
    },
    {
      "year": 1990,
      "population": 27845
    },
    {
      "year": 1980,
      "population": 12243
    },
    {
      "year": 1970,
      "population": 6260
    }
  ],
  "area_km2": 34,
  "population_density": 1299.2647,
  "population_growth_rate": 1.003,
  "percentage_world_population": 0
}
{
  "country": "Slovakia",
  "rank": 116,
  "cca3": "SVK",
  "capital": "Bratislava",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 5643453
    },
    {
      "year": 2020,
      "population": 5456681
    },
    {
      "year": 2015,
      "population": 5424444
    },
    {
      "year": 2010,
      "population": 5396424
    },
    {
      "year": 2000,
      "population": 5376690
    },
    {
      "year": 1990,
      "population": 5261305
    },
    {
      "year": 1980,
      "population": 4973883
    },
    {
      "year": 1970,
      "population": 4522867
    }
  ],
  "area_km2": 49037,
  "population_density": 115.0856,
  "population_growth_rate": 1.0359,
  "percentage_world_population": 0.07
}
{
  "country": "Slovenia",
  "rank": 148,
  "cca3": "SVN",
  "capital": "Ljubljana",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 2119844
    },
    {
      "year": 2020,
      "population": 2117641
    },
    {
      "year": 2015,
      "population": 2080862
    },
    {
      "year": 2010,
      "population": 2057286
    },
    {
      "year": 2000,
      "population": 1984339
    },
    {
      "year": 1990,
      "population": 1986024
    },
    {
      "year": 1980,
      "population": 1901570
    },
    {
      "year": 1970,
      "population": 1741286
    }
  ],
  "area_km2": 20273,
  "population_density": 104.5649,
  "population_growth_rate": 1.0002,
  "percentage_world_population": 0.03
}
{
  "country": "Solomon Islands",
  "rank": 166,
  "cca3": "SLB",
  "capital": "Honiara",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 724273
    },
    {
      "year": 2020,
      "population": 691191
    },
    {
      "year": 2015,
      "population": 612660
    },
    {
      "year": 2010,
      "population": 540394
    },
    {
      "year": 2000,
      "population": 429978
    },
    {
      "year": 1990,
      "population": 324171
    },
    {
      "year": 1980,
      "population": 233668
    },
    {
      "year": 1970,
      "population": 172833
    }
  ],
  "area_km2": 28896,
  "population_density": 25.0648,
  "population_growth_rate": 1.0232,
  "percentage_world_population": 0.01
}
{
  "country": "Somalia",
  "rank": 70,
  "cca3": "SOM",
  "capital": "Mogadishu",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 17597511
    },
    {
      "year": 2020,
      "population": 16537016
    },
    {
      "year": 2015,
      "population": 13763906
    },
    {
      "year": 2010,
      "population": 12026649
    },
    {
      "year": 2000,
      "population": 8721465
    },
    {
      "year": 1990,
      "population": 6999096
    },
    {
      "year": 1980,
      "population": 5892224
    },
    {
      "year": 1970,
      "population": 3720977
    }
  ],
  "area_km2": 637657,
  "population_density": 27.5971,
  "population_growth_rate": 1.0312,
  "percentage_world_population": 0.22
}
{
  "country": "South Africa",
  "rank": 24,
  "cca3": "ZAF",
  "capital": "Pretoria",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 59893885
    },
    {
      "year": 2020,
      "population": 58801927
    },
    {
      "year": 2015,
      "population": 55876504
    },
    {
      "year": 2010,
      "population": 51784921
    },
    {
      "year": 2000,
      "population": 46813266
    },
    {
      "year": 1990,
      "population": 39877570
    },
    {
      "year": 1980,
      "population": 29463549
    },
    {
      "year": 1970,
      "population": 22368306
    }
  ],
  "area_km2": 1221037,
  "population_density": 49.0517,
  "population_growth_rate": 1.0084,
  "percentage_world_population": 0.75
}
{
  "country": "South Korea",
  "rank": 29,
  "cca3": "KOR",
  "capital": "Seoul",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 51815810
    },
    {
      "year": 2020,
      "population": 51844690
    },
    {
      "year": 2015,
      "population": 50994401
    },
    {
      "year": 2010,
      "population": 48813042
    },
    {
      "year": 2000,
      "population": 46788591
    },
    {
      "year": 1990,
      "population": 44120039
    },
    {
      "year": 1980,
      "population": 38170501
    },
    {
      "year": 1970,
      "population": 32601143
    }
  ],
  "area_km2": 100210,
  "population_density": 517.0722,
  "population_growth_rate": 0.9997,
  "percentage_world_population": 0.65
}
{
  "country": "South Sudan",
  "rank": 86,
  "cca3": "SSD",
  "capital": "Juba",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 10913164
    },
    {
      "year": 2020,
      "population": 10606227
    },
    {
      "year": 2015,
      "population": 11194299
    },
    {
      "year": 2010,
      "population": 9714419
    },
    {
      "year": 2000,
      "population": 6114440
    },
    {
      "year": 1990,
      "population": 4750817
    },
    {
      "year": 1980,
      "population": 4192011
    },
    {
      "year": 1970,
      "population": 3342410
    }
  ],
  "area_km2": 619745,
  "population_density": 17.6091,
  "population_growth_rate": 1.0153,
  "percentage_world_population": 0.14
}
{
  "country": "Spain",
  "rank": 30,
  "cca3": "ESP",
  "capital": "Madrid",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 47558630
    },
    {
      "year": 2020,
      "population": 47363807
    },
    {
      "year": 2015,
      "population": 46431342
    },
    {
      "year": 2010,
      "population": 46572772
    },
    {
      "year": 2000,
      "population": 40741651
    },
    {
      "year": 1990,
      "population": 38889889
    },
    {
      "year": 1980,
      "population": 37491666
    },
    {
      "year": 1970,
      "population": 33792617
    }
  ],
  "area_km2": 505992,
  "population_density": 93.9909,
  "population_growth_rate": 1.0015,
  "percentage_world_population": 0.6
}
{
  "country": "Sri Lanka",
  "rank": 61,
  "cca3": "LKA",
  "capital": "Colombo",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 21832143
    },
    {
      "year": 2020,
      "population": 21715079
    },
    {
      "year": 2015,
      "population": 21336697
    },
    {
      "year": 2010,
      "population": 20668557
    },
    {
      "year": 2000,
      "population": 18776371
    },
    {
      "year": 1990,
      "population": 17204094
    },
    {
      "year": 1980,
      "population": 14943645
    },
    {
      "year": 1970,
      "population": 12388769
    }
  ],
  "area_km2": 65610,
  "population_density": 332.7563,
  "population_growth_rate": 1.0027,
  "percentage_world_population": 0.27
}
{
  "country": "Sudan",
  "rank": 32,
  "cca3": "SDN",
  "capital": "Khartoum",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 46874204
    },
    {
      "year": 2020,
      "population": 44440486
    },
    {
      "year": 2015,
      "population": 38171178
    },
    {
      "year": 2010,
      "population": 33739933
    },
    {
      "year": 2000,
      "population": 26298773
    },
    {
      "year": 1990,
      "population": 21090886
    },
    {
      "year": 1980,
      "population": 16673586
    },
    {
      "year": 1970,
      "population": 11305206
    }
  ],
  "area_km2": 1886068,
  "population_density": 24.8529,
  "population_growth_rate": 1.0267,
  "percentage_world_population": 0.59
}
{
  "country": "Suriname",
  "rank": 170,
  "cca3": "SUR",
  "capital": "Paramaribo",
  "continent": "South America",
  "population": [
    {
      "year": 2022,
      "population": 618040
    },
    {
      "year": 2020,
      "population": 607065
    },
    {
      "year": 2015,
      "population": 575475
    },
    {
      "year": 2010,
      "population": 546080
    },
    {
      "year": 2000,
      "population": 478998
    },
    {
      "year": 1990,
      "population": 412756
    },
    {
      "year": 1980,
      "population": 375112
    },
    {
      "year": 1970,
      "population": 379918
    }
  ],
  "area_km2": 163820,
  "population_density": 3.7727,
  "population_growth_rate": 1.0082,
  "percentage_world_population": 0.01
}
{
  "country": "Sweden",
  "rank": 87,
  "cca3": "SWE",
  "capital": "Stockholm",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 10549347
    },
    {
      "year": 2020,
      "population": 10368969
    },
    {
      "year": 2015,
      "population": 9849349
    },
    {
      "year": 2010,
      "population": 9381729
    },
    {
      "year": 2000,
      "population": 8871043
    },
    {
      "year": 1990,
      "population": 8548406
    },
    {
      "year": 1980,
      "population": 8311763
    },
    {
      "year": 1970,
      "population": 8027702
    }
  ],
  "area_km2": 450295,
  "population_density": 23.4276,
  "population_growth_rate": 1.0079,
  "percentage_world_population": 0.13
}
{
  "country": "Switzerland",
  "rank": 101,
  "cca3": "CHE",
  "capital": "Bern",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 8740472
    },
    {
      "year": 2020,
      "population": 8638613
    },
    {
      "year": 2015,
      "population": 8281732
    },
    {
      "year": 2010,
      "population": 7822435
    },
    {
      "year": 2000,
      "population": 7182059
    },
    {
      "year": 1990,
      "population": 6711693
    },
    {
      "year": 1980,
      "population": 6319113
    },
    {
      "year": 1970,
      "population": 6181227
    }
  ],
  "area_km2": 41284,
  "population_density": 211.7157,
  "population_growth_rate": 1.0056,
  "percentage_world_population": 0.11
}
{
  "country": "Syria",
  "rank": 60,
  "cca3": "SYR",
  "capital": "Damascus",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 22125249
    },
    {
      "year": 2020,
      "population": 20772595
    },
    {
      "year": 2015,
      "population": 19205178
    },
    {
      "year": 2010,
      "population": 22337563
    },
    {
      "year": 2000,
      "population": 16307654
    },
    {
      "year": 1990,
      "population": 12408996
    },
    {
      "year": 1980,
      "population": 8898954
    },
    {
      "year": 1970,
      "population": 6319199
    }
  ],
  "area_km2": 185180,
  "population_density": 119.4797,
  "population_growth_rate": 1.0376,
  "percentage_world_population": 0.28
}
{
  "country": "Taiwan",
  "rank": 57,
  "cca3": "TWN",
  "capital": "Taipei",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 23893394
    },
    {
      "year": 2020,
      "population": 23821464
    },
    {
      "year": 2015,
      "population": 23512136
    },
    {
      "year": 2010,
      "population": 23083083
    },
    {
      "year": 2000,
      "population": 22194731
    },
    {
      "year": 1990,
      "population": 20586174
    },
    {
      "year": 1980,
      "population": 18100281
    },
    {
      "year": 1970,
      "population": 14957870
    }
  ],
  "area_km2": 36193,
  "population_density": 660.1662,
  "population_growth_rate": 1.0014,
  "percentage_world_population": 0.3
}
{
  "country": "Tajikistan",
  "rank": 95,
  "cca3": "TJK",
  "capital": "Dushanbe",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 9952787
    },
    {
      "year": 2020,
      "population": 9543207
    },
    {
      "year": 2015,
      "population": 8524063
    },
    {
      "year": 2010,
      "population": 7621779
    },
    {
      "year": 2000,
      "population": 6272998
    },
    {
      "year": 1990,
      "population": 5417860
    },
    {
      "year": 1980,
      "population": 4045965
    },
    {
      "year": 1970,
      "population": 2993019
    }
  ],
  "area_km2": 143100,
  "population_density": 69.5513,
  "population_growth_rate": 1.0208,
  "percentage_world_population": 0.12
}
{
  "country": "Tanzania",
  "rank": 22,
  "cca3": "TZA",
  "capital": "Dodoma",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 65497748
    },
    {
      "year": 2020,
      "population": 61704518
    },
    {
      "year": 2015,
      "population": 52542823
    },
    {
      "year": 2010,
      "population": 45110527
    },
    {
      "year": 2000,
      "population": 34463704
    },
    {
      "year": 1990,
      "population": 26206012
    },
    {
      "year": 1980,
      "population": 19297659
    },
    {
      "year": 1970,
      "population": 13618192
    }
  ],
  "area_km2": 945087,
  "population_density": 69.3034,
  "population_growth_rate": 1.03,
  "percentage_world_population": 0.82
}
{
  "country": "Thailand",
  "rank": 20,
  "cca3": "THA",
  "capital": "Bangkok",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 71697030
    },
    {
      "year": 2020,
      "population": 71475664
    },
    {
      "year": 2015,
      "population": 70294397
    },
    {
      "year": 2010,
      "population": 68270489
    },
    {
      "year": 2000,
      "population": 63066603
    },
    {
      "year": 1990,
      "population": 55228410
    },
    {
      "year": 1980,
      "population": 45737753
    },
    {
      "year": 1970,
      "population": 35791728
    }
  ],
  "area_km2": 513120,
  "population_density": 139.7276,
  "population_growth_rate": 1.0013,
  "percentage_world_population": 0.9
}
{
  "country": "Timor-Leste",
  "rank": 155,
  "cca3": "TLS",
  "capital": "Dili",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 1341296
    },
    {
      "year": 2020,
      "population": 1299995
    },
    {
      "year": 2015,
      "population": 1205813
    },
    {
      "year": 2010,
      "population": 1088486
    },
    {
      "year": 2000,
      "population": 878360
    },
    {
      "year": 1990,
      "population": 758106
    },
    {
      "year": 1980,
      "population": 642224
    },
    {
      "year": 1970,
      "population": 554021
    }
  ],
  "area_km2": 14874,
  "population_density": 90.1772,
  "population_growth_rate": 1.0154,
  "percentage_world_population": 0.02
}
{
  "country": "Togo",
  "rank": 100,
  "cca3": "TGO",
  "capital": "Lomé",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 8848699
    },
    {
      "year": 2020,
      "population": 8442580
    },
    {
      "year": 2015,
      "population": 7473229
    },
    {
      "year": 2010,
      "population": 6571855
    },
    {
      "year": 2000,
      "population": 5008035
    },
    {
      "year": 1990,
      "population": 3875947
    },
    {
      "year": 1980,
      "population": 2838110
    },
    {
      "year": 1970,
      "population": 2197383
    }
  ],
  "area_km2": 56785,
  "population_density": 155.8281,
  "population_growth_rate": 1.0236,
  "percentage_world_population": 0.11
}
{
  "country": "Tokelau",
  "rank": 233,
  "cca3": "TKL",
  "capital": "Nukunonu",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 1871
    },
    {
      "year": 2020,
      "population": 1827
    },
    {
      "year": 2015,
      "population": 1454
    },
    {
      "year": 2010,
      "population": 1367
    },
    {
      "year": 2000,
      "population": 1666
    },
    {
      "year": 1990,
      "population": 1669
    },
    {
      "year": 1980,
      "population": 1647
    },
    {
      "year": 1970,
      "population": 1714
    }
  ],
  "area_km2": 12,
  "population_density": 155.9167,
  "population_growth_rate": 1.0119,
  "percentage_world_population": 0
}
{
  "country": "Tonga",
  "rank": 197,
  "cca3": "TON",
  "capital": "Nuku‘alofa",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 106858
    },
    {
      "year": 2020,
      "population": 105254
    },
    {
      "year": 2015,
      "population": 106122
    },
    {
      "year": 2010,
      "population": 107383
    },
    {
      "year": 2000,
      "population": 102603
    },
    {
      "year": 1990,
      "population": 98727
    },
    {
      "year": 1980,
      "population": 96708
    },
    {
      "year": 1970,
      "population": 86484
    }
  ],
  "area_km2": 747,
  "population_density": 143.0495,
  "population_growth_rate": 1.0079,
  "percentage_world_population": 0
}
{
  "country": "Trinidad and Tobago",
  "rank": 153,
  "cca3": "TTO",
  "capital": "Port-of-Spain",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 1531044
    },
    {
      "year": 2020,
      "population": 1518147
    },
    {
      "year": 2015,
      "population": 1460177
    },
    {
      "year": 2010,
      "population": 1410296
    },
    {
      "year": 2000,
      "population": 1332203
    },
    {
      "year": 1990,
      "population": 1266518
    },
    {
      "year": 1980,
      "population": 1127852
    },
    {
      "year": 1970,
      "population": 988890
    }
  ],
  "area_km2": 5130,
  "population_density": 298.4491,
  "population_growth_rate": 1.0035,
  "percentage_world_population": 0.02
}
{
  "country": "Tunisia",
  "rank": 79,
  "cca3": "TUN",
  "capital": "Tunis",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 12356117
    },
    {
      "year": 2020,
      "population": 12161723
    },
    {
      "year": 2015,
      "population": 11557779
    },
    {
      "year": 2010,
      "population": 10895063
    },
    {
      "year": 2000,
      "population": 9893316
    },
    {
      "year": 1990,
      "population": 8440023
    },
    {
      "year": 1980,
      "population": 6578156
    },
    {
      "year": 1970,
      "population": 5047404
    }
  ],
  "area_km2": 163610,
  "population_density": 75.5218,
  "population_growth_rate": 1.0076,
  "percentage_world_population": 0.15
}
{
  "country": "Turkey",
  "rank": 18,
  "cca3": "TUR",
  "capital": "Ankara",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 85341241
    },
    {
      "year": 2020,
      "population": 84135428
    },
    {
      "year": 2015,
      "population": 79646178
    },
    {
      "year": 2010,
      "population": 73195345
    },
    {
      "year": 2000,
      "population": 64113547
    },
    {
      "year": 1990,
      "population": 54324142
    },
    {
      "year": 1980,
      "population": 44089069
    },
    {
      "year": 1970,
      "population": 35540990
    }
  ],
  "area_km2": 783562,
  "population_density": 108.9145,
  "population_growth_rate": 1.0067,
  "percentage_world_population": 1.07
}
{
  "country": "Turkmenistan",
  "rank": 111,
  "cca3": "TKM",
  "capital": "Ashgabat",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 6430770
    },
    {
      "year": 2020,
      "population": 6250438
    },
    {
      "year": 2015,
      "population": 5766431
    },
    {
      "year": 2010,
      "population": 5267970
    },
    {
      "year": 2000,
      "population": 4569132
    },
    {
      "year": 1990,
      "population": 3720278
    },
    {
      "year": 1980,
      "population": 2862903
    },
    {
      "year": 1970,
      "population": 2201432
    }
  ],
  "area_km2": 488100,
  "population_density": 13.1751,
  "population_growth_rate": 1.014,
  "percentage_world_population": 0.08
}
{
  "country": "Turks and Caicos Islands",
  "rank": 212,
  "cca3": "TCA",
  "capital": "Cockburn Town",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 45703
    },
    {
      "year": 2020,
      "population": 44276
    },
    {
      "year": 2015,
      "population": 36538
    },
    {
      "year": 2010,
      "population": 29726
    },
    {
      "year": 2000,
      "population": 18744
    },
    {
      "year": 1990,
      "population": 11709
    },
    {
      "year": 1980,
      "population": 7598
    },
    {
      "year": 1970,
      "population": 5665
    }
  ],
  "area_km2": 948,
  "population_density": 48.2099,
  "population_growth_rate": 1.0131,
  "percentage_world_population": 0
}
{
  "country": "Tuvalu",
  "rank": 227,
  "cca3": "TUV",
  "capital": "Funafuti",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 11312
    },
    {
      "year": 2020,
      "population": 11069
    },
    {
      "year": 2015,
      "population": 10877
    },
    {
      "year": 2010,
      "population": 10550
    },
    {
      "year": 2000,
      "population": 9638
    },
    {
      "year": 1990,
      "population": 9182
    },
    {
      "year": 1980,
      "population": 7731
    },
    {
      "year": 1970,
      "population": 5814
    }
  ],
  "area_km2": 26,
  "population_density": 435.0769,
  "population_growth_rate": 1.0096,
  "percentage_world_population": 0
}
{
  "country": "Uganda",
  "rank": 31,
  "cca3": "UGA",
  "capital": "Kampala",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 47249585
    },
    {
      "year": 2020,
      "population": 44404611
    },
    {
      "year": 2015,
      "population": 37477356
    },
    {
      "year": 2010,
      "population": 32341728
    },
    {
      "year": 2000,
      "population": 24020697
    },
    {
      "year": 1990,
      "population": 17586630
    },
    {
      "year": 1980,
      "population": 13284026
    },
    {
      "year": 1970,
      "population": 10317212
    }
  ],
  "area_km2": 241550,
  "population_density": 195.61,
  "population_growth_rate": 1.0304,
  "percentage_world_population": 0.59
}
{
  "country": "Ukraine",
  "rank": 38,
  "cca3": "UKR",
  "capital": "Kiev",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 39701739
    },
    {
      "year": 2020,
      "population": 43909666
    },
    {
      "year": 2015,
      "population": 44982564
    },
    {
      "year": 2010,
      "population": 45683020
    },
    {
      "year": 2000,
      "population": 48879755
    },
    {
      "year": 1990,
      "population": 51589817
    },
    {
      "year": 1980,
      "population": 49973920
    },
    {
      "year": 1970,
      "population": 47279086
    }
  ],
  "area_km2": 603500,
  "population_density": 65.7858,
  "population_growth_rate": 0.912,
  "percentage_world_population": 0.5
}
{
  "country": "United Arab Emirates",
  "rank": 97,
  "cca3": "ARE",
  "capital": "Abu Dhabi",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 9441129
    },
    {
      "year": 2020,
      "population": 9287289
    },
    {
      "year": 2015,
      "population": 8916899
    },
    {
      "year": 2010,
      "population": 8481771
    },
    {
      "year": 2000,
      "population": 3275333
    },
    {
      "year": 1990,
      "population": 1900151
    },
    {
      "year": 1980,
      "population": 1014048
    },
    {
      "year": 1970,
      "population": 298084
    }
  ],
  "area_km2": 83600,
  "population_density": 112.9322,
  "population_growth_rate": 1.0081,
  "percentage_world_population": 0.12
}
{
  "country": "United Kingdom",
  "rank": 21,
  "cca3": "GBR",
  "capital": "London",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 67508936
    },
    {
      "year": 2020,
      "population": 67059474
    },
    {
      "year": 2015,
      "population": 65224364
    },
    {
      "year": 2010,
      "population": 62760039
    },
    {
      "year": 2000,
      "population": 58850043
    },
    {
      "year": 1990,
      "population": 57210442
    },
    {
      "year": 1980,
      "population": 56326328
    },
    {
      "year": 1970,
      "population": 55650166
    }
  ],
  "area_km2": 242900,
  "population_density": 277.9289,
  "population_growth_rate": 1.0034,
  "percentage_world_population": 0.85
}
{
  "country": "United States",
  "rank": 3,
  "cca3": "USA",
  "capital": "Washington, D.C.",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 338289857
    },
    {
      "year": 2020,
      "population": 335942003
    },
    {
      "year": 2015,
      "population": 324607776
    },
    {
      "year": 2010,
      "population": 311182845
    },
    {
      "year": 2000,
      "population": 282398554
    },
    {
      "year": 1990,
      "population": 248083732
    },
    {
      "year": 1980,
      "population": 223140018
    },
    {
      "year": 1970,
      "population": 200328340
    }
  ],
  "area_km2": 9372610,
  "population_density": 36.0935,
  "population_growth_rate": 1.0038,
  "percentage_world_population": 4.24
}
{
  "country": "United States Virgin Islands",
  "rank": 200,
  "cca3": "VIR",
  "capital": "Charlotte Amalie",
  "continent": "North America",
  "population": [
    {
      "year": 2022,
      "population": 99465
    },
    {
      "year": 2020,
      "population": 100442
    },
    {
      "year": 2015,
      "population": 102803
    },
    {
      "year": 2010,
      "population": 106142
    },
    {
      "year": 2000,
      "population": 108185
    },
    {
      "year": 1990,
      "population": 100685
    },
    {
      "year": 1980,
      "population": 96640
    },
    {
      "year": 1970,
      "population": 63446
    }
  ],
  "area_km2": 347,
  "population_density": 286.6427,
  "population_growth_rate": 0.9937,
  "percentage_world_population": 0
}
{
  "country": "Uruguay",
  "rank": 133,
  "cca3": "URY",
  "capital": "Montevideo",
  "continent": "South America",
  "population": [
    {
      "year": 2022,
      "population": 3422794
    },
    {
      "year": 2020,
      "population": 3429086
    },
    {
      "year": 2015,
      "population": 3402818
    },
    {
      "year": 2010,
      "population": 3352651
    },
    {
      "year": 2000,
      "population": 3292224
    },
    {
      "year": 1990,
      "population": 3117012
    },
    {
      "year": 1980,
      "population": 2953750
    },
    {
      "year": 1970,
      "population": 2790265
    }
  ],
  "area_km2": 181034,
  "population_density": 18.9069,
  "population_growth_rate": 0.999,
  "percentage_world_population": 0.04
}
{
  "country": "Uzbekistan",
  "rank": 43,
  "cca3": "UZB",
  "capital": "Tashkent",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 34627652
    },
    {
      "year": 2020,
      "population": 33526656
    },
    {
      "year": 2015,
      "population": 30949417
    },
    {
      "year": 2010,
      "population": 28614227
    },
    {
      "year": 2000,
      "population": 24925554
    },
    {
      "year": 1990,
      "population": 20579100
    },
    {
      "year": 1980,
      "population": 15947129
    },
    {
      "year": 1970,
      "population": 12011361
    }
  ],
  "area_km2": 447400,
  "population_density": 77.3975,
  "population_growth_rate": 1.016,
  "percentage_world_population": 0.43
}
{
  "country": "Vanuatu",
  "rank": 181,
  "cca3": "VUT",
  "capital": "Port-Vila",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 326740
    },
    {
      "year": 2020,
      "population": 311685
    },
    {
      "year": 2015,
      "population": 276438
    },
    {
      "year": 2010,
      "population": 245453
    },
    {
      "year": 2000,
      "population": 192074
    },
    {
      "year": 1990,
      "population": 150882
    },
    {
      "year": 1980,
      "population": 118156
    },
    {
      "year": 1970,
      "population": 87019
    }
  ],
  "area_km2": 12189,
  "population_density": 26.8061,
  "population_growth_rate": 1.0238,
  "percentage_world_population": 0
}
{
  "country": "Vatican City",
  "rank": 234,
  "cca3": "VAT",
  "capital": "Vatican City",
  "continent": "Europe",
  "population": [
    {
      "year": 2022,
      "population": 510
    },
    {
      "year": 2020,
      "population": 520
    },
    {
      "year": 2015,
      "population": 564
    },
    {
      "year": 2010,
      "population": 596
    },
    {
      "year": 2000,
      "population": 651
    },
    {
      "year": 1990,
      "population": 700
    },
    {
      "year": 1980,
      "population": 733
    },
    {
      "year": 1970,
      "population": 752
    }
  ],
  "area_km2": 1,
  "population_density": 510,
  "population_growth_rate": 0.998,
  "percentage_world_population": 0
}
{
  "country": "Venezuela",
  "rank": 51,
  "cca3": "VEN",
  "capital": "Caracas",
  "continent": "South America",
  "population": [
    {
      "year": 2022,
      "population": 28301696
    },
    {
      "year": 2020,
      "population": 28490453
    },
    {
      "year": 2015,
      "population": 30529716
    },
    {
      "year": 2010,
      "population": 28715022
    },
    {
      "year": 2000,
      "population": 24427729
    },
    {
      "year": 1990,
      "population": 19750579
    },
    {
      "year": 1980,
      "population": 15210443
    },
    {
      "year": 1970,
      "population": 11355475
    }
  ],
  "area_km2": 916445,
  "population_density": 30.882,
  "population_growth_rate": 1.0036,
  "percentage_world_population": 0.35
}
{
  "country": "Vietnam",
  "rank": 16,
  "cca3": "VNM",
  "capital": "Hanoi",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 98186856
    },
    {
      "year": 2020,
      "population": 96648685
    },
    {
      "year": 2015,
      "population": 92191398
    },
    {
      "year": 2010,
      "population": 87411012
    },
    {
      "year": 2000,
      "population": 79001142
    },
    {
      "year": 1990,
      "population": 66912613
    },
    {
      "year": 1980,
      "population": 52968270
    },
    {
      "year": 1970,
      "population": 41928849
    }
  ],
  "area_km2": 331212,
  "population_density": 296.4472,
  "population_growth_rate": 1.0074,
  "percentage_world_population": 1.23
}
{
  "country": "Wallis and Futuna",
  "rank": 226,
  "cca3": "WLF",
  "capital": "Mata-Utu",
  "continent": "Oceania",
  "population": [
    {
      "year": 2022,
      "population": 11572
    },
    {
      "year": 2020,
      "population": 11655
    },
    {
      "year": 2015,
      "population": 12182
    },
    {
      "year": 2010,
      "population": 13142
    },
    {
      "year": 2000,
      "population": 14723
    },
    {
      "year": 1990,
      "population": 13454
    },
    {
      "year": 1980,
      "population": 11315
    },
    {
      "year": 1970,
      "population": 9377
    }
  ],
  "area_km2": 142,
  "population_density": 81.493,
  "population_growth_rate": 0.9953,
  "percentage_world_population": 0
}
{
  "country": "Western Sahara",
  "rank": 172,
  "cca3": "ESH",
  "capital": "El Aaiún",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 575986
    },
    {
      "year": 2020,
      "population": 556048
    },
    {
      "year": 2015,
      "population": 491824
    },
    {
      "year": 2010,
      "population": 413296
    },
    {
      "year": 2000,
      "population": 270375
    },
    {
      "year": 1990,
      "population": 178529
    },
    {
      "year": 1980,
      "population": 116775
    },
    {
      "year": 1970,
      "population": 76371
    }
  ],
  "area_km2": 266000,
  "population_density": 2.1654,
  "population_growth_rate": 1.0184,
  "percentage_world_population": 0.01
}
{
  "country": "Yemen",
  "rank": 46,
  "cca3": "YEM",
  "capital": "Sanaa",
  "continent": "Asia",
  "population": [
    {
      "year": 2022,
      "population": 33696614
    },
    {
      "year": 2020,
      "population": 32284046
    },
    {
      "year": 2015,
      "population": 28516545
    },
    {
      "year": 2010,
      "population": 24743946
    },
    {
      "year": 2000,
      "population": 18628700
    },
    {
      "year": 1990,
      "population": 13375121
    },
    {
      "year": 1980,
      "population": 9204938
    },
    {
      "year": 1970,
      "population": 6843607
    }
  ],
  "area_km2": 527968,
  "population_density": 63.8232,
  "population_growth_rate": 1.0217,
  "percentage_world_population": 0.42
}
{
  "country": "Zambia",
  "rank": 63,
  "cca3": "ZMB",
  "capital": "Lusaka",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 20017675
    },
    {
      "year": 2020,
      "population": 18927715
    },
    {
      "year": 2015,
      "population": 16248230
    },
    {
      "year": 2010,
      "population": 13792086
    },
    {
      "year": 2000,
      "population": 9891136
    },
    {
      "year": 1990,
      "population": 7686401
    },
    {
      "year": 1980,
      "population": 5720438
    },
    {
      "year": 1970,
      "population": 4281671
    }
  ],
  "area_km2": 752612,
  "population_density": 26.5976,
  "population_growth_rate": 1.028,
  "percentage_world_population": 0.25
}
{
  "country": "Zimbabwe",
  "rank": 74,
  "cca3": "ZWE",
  "capital": "Harare",
  "continent": "Africa",
  "population": [
    {
      "year": 2022,
      "population": 16320537
    },
    {
      "year": 2020,
      "population": 15669666
    },
    {
      "year": 2015,
      "population": 14154937
    },
    {
      "year": 2010,
      "population": 12839771
    },
    {
      "year": 2000,
      "population": 11834676
    },
    {
      "year": 1990,
      "population": 10113893
    },
    {
      "year": 1980,
      "population": 7049926
    },
    {
      "year": 1970,
      "population": 5202918
    }
  ],
  "area_km2": 390757,
  "population_density": 41.7665,
  "population_growth_rate": 1.0204,
  "percentage_world_population": 0.2
}
```
