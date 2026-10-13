# Data sources

| File | Source | Link | Downloaded | Notes |
|---|---|---|---|---|
| data/raw/census2022_age_sex_nationality.csv | GASTAT Census 2022, via RCRC Open Data Portal | https://opendata.rcrc.gov.sa/explore/dataset/population-by-age-citizenship-gender-and-governorate-2022/ | 2026-10-13 | Full dataset exported as CSV, unedited |
| data/raw/un_wpp_saudi_2015_2030_age_sex.csv | UN World Population Prospects 2024, Data Portal (indicator 46) | https://population.un.org/dataportal/ | 2026-10-13 | Saudi Arabia, 2015–2030, male & female, 21 five-year age groups, medium variant |
| data/raw/un_wpp_saudi_lifetable_survivors_2017_2030.csv | UN World Population Prospects 2024, Data Portal (indicator 78) | https://population.un.org/dataportal/ | 2026-10-13 | Survivors l(x), complete life table, 2017–2030, male & female, ages 0–100+ |
| data/raw/hipfracture_saudi_2022_paper.pdf | Al-Saleh Y. et al. Incidence of hip fracture in Saudi Arabia and the development of a FRAX model. Arch Osteoporos 2022;17:56 (open access, CC BY 4.0) | https://doi.org/10.1007/s11657-022-01085-x | 2026-10-13 | Table 1 (rates), Table 2 (projections), fracture sites in Results |
| data/raw/glmm_saudi_pop_agegroup_2010_2022.pdf | GASTAT, Saudi population by age group 2010–2022 (adjusted by census 2022), via GLMM | https://gulfmigration.grc.net/saudi-arabia-saudi-population-by-age-group-2010-2022-data-adjusted-by-census-2022/ | 2026-10-13 | Original PDF; values extracted to manual_tables |
| data/raw/manual_tables/hipfracture_rates_table1.csv | Extracted from the paper, Table 1 | – | 2026-10-13 | Checked: counts add to printed totals (296, 388); rates recomputed from counts |
| data/raw/manual_tables/hipfracture_published_projections_table2.csv | Extracted from the paper, Table 2 | – | 2026-10-13 | Checked: men + women = total for every year |
| data/raw/manual_tables/hipfracture_sites.csv | Extracted from the paper, Results | – | 2026-10-13 | 43 / 47 / 10 % |
| data/raw/manual_tables/glmm_saudi_pop_agegroup_2010_2022.csv | Extracted from the GLMM PDF | – | 2026-10-13 | Checked: age groups add to the printed TOTAL row in all 13 years |
| Treatment pathways | NICE Clinical Guideline CG124, Hip fracture: management | https://www.nice.org.uk/guidance/cg124 | – | Used for which operation each fracture type usually receives |
