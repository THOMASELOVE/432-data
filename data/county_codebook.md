# Codebook for 432 `chr_2024` data

Variable | NHANES | Summary | Definition | Years
:--------- | :--------: | :-------------------------: | :------------------------------------------------------------------------- | :----------:
`FIPS_code` | -- | five-digit FIPS code | five-digit FIPS code preceded by `C-`	
`state` | state | [USPS state abbreviation](https://en.wikipedia.org/wiki/List_of_U.S._state_and_territory_abbreviations#Postal_codes) | includes all 50 states, plus DC for District of Columbia (DC)
`county` | county | county name	| --
`year` | year	| Release Year | 2024 for the `chr_2024` data
`prem_death` | v001_rawvalue | Premature death raw value	| [Years of potential life lost before age 75 per 100,000 population (age-adjusted)](https://www.countyhealthrankings.org/health-data/health-outcomes/length-of-life/premature-death?year=2024) | 2019-2021
`pf_health`	| v002_rawvalue	| Poor or fair health raw value	| [Proportion of adults reporting fair or poor health (age-adjusted)](https://www.countyhealthrankings.org/health-data/health-outcomes/quality-of-life/poor-or-fair-health?year=2024) | 2021
`poor_phys`	| v036_rawvalue	| Poor physical health days raw value	| 
