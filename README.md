## Project Overview

This project started life as something else.

The original idea was to investigate whether housing instability could be linked to the higher rates of criminal convictions seen amongst care-experienced adults. Unfortunately, the data had other ideas.

Whilst research exists, the datasets needed to reproduce or test those findings aren't publicly available. After spending far too long trying to find a way around that problem, I accepted defeat and changed direction.

Rather than forcing a conclusion from incomplete evidence (the hypothesis that I knew was true and I realised I was to prove within the confines of the brief), I focused on a question that could actually be answered with the data available. 

Using publicly available government statistics, this project looks at trends in homelessness and unsuitable accommodation amongst care leavers and compares Manchester against the national picture.

In the end, the project became as much about understanding the limitations of public data as it did about understanding housing outcomes.

This topic connects directly to my professional experience as a Magistrate, where I regularly see how housing instability and difficult early life experiences shape outcomes for the people who appear before the court. In the end, the project became as much about understanding the limitations of public data as it did about understanding housing outcomes

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
