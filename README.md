## Project Overview

This repository contains the files and outputs for a data science project.
The original project was attempting to reconcile the rate of Adult Court Criminal Convictions however the data for analysis was unavalable so it was amended to investigating housing outcomes for care leavers in England, with a comparison to Manchester.
The project explores whether trends in unsuitable accommodation and homelessness follow similar patterns over time using publicly available government datasets. D

---

## Repository Structure

```text
Data Science - project 1/
│
├── Data/
│   ├── Care leaver accommodation dataset
│   ├── Homelessness datasets
│   └── master_joined_table.csv
│
├── Figures/
│   ├── Source data evidence screenshots
│   ├── ETL evidence
│   ├── Joined table evidence
│   └── Analysis visualisations
│
├── Report/
│   └── Data Science Project.pdf
│
└── Scripts/
    └── Analysis.py
```

---

## Data Sources

The project uses publicly available data published under the Open Government Licence:

- Department for Education (DfE) Care Leaver Accommodation Statistics
- Ministry of Housing, Communities and Local Government (MHCLG) Statutory Homelessness Statistics
- Office for National Statistics (ONS) background research

### Source Links

- https://explore-education-statistics.service.gov.uk
- https://www.gov.uk/government/statistical-data-sets/live-tables-on-homelessness
- https://www.ons.gov.uk

---

## Tools and Technologies

- Python
- Pandas
- Microsoft Excel

These tools were used for data extraction, transformation, validation, analysis and visualisation.

---

## Key Outputs

The repository includes:

- Original source datasets
- Python ETL and analysis script
- Joined analytical dataset
- Visualisations used within the report
- Final project report

---

## Key Finding

The analysis found that homelessness among care leavers increased substantially faster than unsuitable accommodation rates. Whilst both datasets indicate housing instability remains an important issue, the available public data does not allow direct testing of any relationship between housing outcomes and criminal convictions.
