# Codebook for County Health Rankings Data for 432 Labs

Codebook for the `chr_2024` and `chr_2015` data

Variable | NHANES | Summary | Definition | CHR 2024 describes | CHR 2015 describes
:--------- | :--------: | :-------------------------: | :------------------------------------------------------------------------- | :----------: | :----------:
`FIPS_code` | -- | five-digit FIPS code | five-digit FIPS code preceded by `C-`	
`state` | state | [USPS state abbreviation](https://en.wikipedia.org/wiki/List_of_U.S._state_and_territory_abbreviations#Postal_codes) | includes all 50 states, plus DC for District of Columbia (DC)
`county` | county | county name	| CHR 2024 and CHR 2015 contain the same 3054 counties
`year` | year	| Release Year | Date for CHR Data Release | released 2024 | released 2015
`prem_death` | v001_rawvalue | Premature death	| [Years of potential life lost before age 75 per 100,000 population (age-adjusted)](https://www.countyhealthrankings.org/health-data/health-outcomes/length-of-life/premature-death?year=2024) | 2019-2021 | 2010-2012
`pf_health`	| v002_rawvalue	| Poor or fair health	| [Proportion of adults reporting fair or poor health (age-adjusted)](https://www.countyhealthrankings.org/health-data/health-outcomes/quality-of-life/poor-or-fair-health?year=2024) | 2021 | 2006-2012
`poor_phys`	| v036_rawvalue	| Poor physical health days	| [Average number of physically unhealthy days reported in past 30 days (age-adjusted).](https://www.countyhealthrankings.org/health-data/health-outcomes/quality-of-life/poor-physical-health-days?year=2024) | 2021 | 2006-2012
`poor_ment` | v042_rawvalue | Poor mental health days | [Average number of mentally unhealthy days reported in past 30 days (age-adjusted).](https://www.countyhealthrankings.org/health-data/health-outcomes/quality-of-life/poor-mental-health-days?year=2024) | 2021 | 2006-2012
`low_bwt` | v037_rawvalue | Low birthweight | [Proportion of live births with low birthweight (< 2,500 grams)](https://www.countyhealthrankings.org/health-data/health-outcomes/quality-of-life/low-birthweight?year=2024) | 2016-2022 | 2006-2012
`smoking` | v009_rawvalue | Adult smoking | [Proportion of adults who are current smokers (age-adjusted)](https://www.countyhealthrankings.org/health-data/health-factors/health-behaviors/tobacco-use/adult-smoking?year=2024) | 2021 | 2006-2012
`obesity` | v011_rawvalue | Adult obesity | [Proportion of the adult population (age 18 and older) that reports a body mass index (BMI) greater than or equal to 30 kg/m^2 (age-adjusted)](https://www.countyhealthrankings.org/health-data/health-factors/health-behaviors/diet-and-exercise/adult-obesity?year=2024) | 2021 | 2011
`food_env` | v133_rawvalue | Food environment index | 
`drinking` | v049_rawvalue | Excessive drinking |
`sti` | v045_rawvalue | Sexually transmitted infections |
`uninsured` | v085_rawvalue | Uninsured |
`pcps` | v004_rawvalue | Primary care physicians |
`prev_hosp` | v005_rawvalue | Preventable hospital stays |
`mammog` | v050_rawvalue | Mammography screening |
`hsgrad` | v021_rawvalue | High school graduation |
`unemp` | v023_rawvalue | Unemployment
`inc_ineq` | v044_rawvalue | Income inequality
`social` | v140_rawvalue | Social associations | 
`med_inc` | v063_rawvalue | Median household income |
`sev_hous` | v136_rawvalue | Severe housing problems |
`alone` | v137_rawvalue | Long commute - driving alone |
`popn` | v051_rawvalue | Population |
`age65` | v053_rawvalue | age 65 and older |
`nh_white` | v126_rawvalue | Non-Hispanic white |
`non_eng` | v059_rawvalue | Not proficient in English |
`female` | v057_rawvalue | Female
`rural` | v058_rawvalue | Rural
