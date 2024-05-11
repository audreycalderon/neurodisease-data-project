# Neurodisease Data Cleansing and Visualization

[![Excel](https://img.shields.io/badge/Excel-Used-green.svg)](https://products.office.com/en/excel)
[![Power Query](https://img.shields.io/badge/Power_Query-Implemented-blue.svg)](https://docs.microsoft.com/en-us/power-query/)

## Overview

Utilization of Statistics Canada’s _Deaths, by cause, Chapter VI: Diseases of the nervous system (G00 to G99)_  to transform nervous system disease health data from 2018 - 2022 into a compilation of datasets and visuals, providing valuable insights/ analyses into Canadian neurological health trends.

## Tabular Data

Compiled/ restructured three sets of raw data into Excel tables.

- Tables are grouped by year and gender
- Each table includes disease classification, ICD-10 disease code, total deaths and deaths by age range

## Visualizations

Leveraged Power Query to clean and load data into pivot charts. Sample visualizations include:

- **Segregated Bar Graph**: displays total deaths of each disease classification for each year (2018 - 2022) in Canada
- **Pie Charts**: displays total deaths from inflammatory CNS diseases from 2020 - 2022 in Canada, categorized by male vs. female

## Limitations

- Report does not account for geographical population (provinces, cities, etc. are unspecified)

## Next Steps

- **Age-Specific Analysis**: incorporate the utilization of **Python** data libraries (**NumPy**, **Pandas**, **Matplotlib**) to extract, manipulate, and plot large-scale data within specific age ranges, such as 0-19 years, segmented by gender. Results will identify previously unnoticed patterns in nervous system disease death prevalence over time and enable proactive intervention strategies.
- **Cost-Benefit Financial Analysis**: conduct and include a comprehensive financial analysis from external sources to assess the cost-effectiveness of preventative measures/ treatments in each given disease category against the deaths over time. Results will identify potential budgeting strategies in Canadian healthcare expenses over time.

## References

Statistics Canada. Table 13-10-0145-01  Deaths, by cause, Chapter VI: Diseases of the nervous system (G00 to G99). https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1310014501

Frequency: Annual

Table: 13-10-0145-01 (formerly CANSIM 102-0526)

Release date: 2023-11-27

Geography: Canada

International Statistical Classification of Diseases and Related Health Problems 10th Revision (ICD-10)-WHO Version for ;2019-covid-expanded. https://icd.who.int/browse10/2019/en#/VI
