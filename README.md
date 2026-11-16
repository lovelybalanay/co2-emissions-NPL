CO2 Emissions Analysis: Nepal (NPL)

Student Name: Lovely G. Balanay
Country: Nepal
ISO-3 Code: NPL
Period Covered: 1990–2024
Data Source: Our World in Data (OWID)

Research Question

How have Nepal's annual CO₂ emissions and CO₂ emissions per capita changed from 1990 to 2024?

Data Source and Method

This analysis uses the Our World in Data CO₂ dataset. The data were filtered to include Nepal (NPL) from 1990 to 2024. The analysis examined annual CO₂ emissions, CO₂ emissions per capita, and yearly changes in emissions. Missing values were not treated as zero.

Interpretation

Nepal’s CO₂ emissions increased greatly from 1990 to 2024. In 1990, the country emitted about 0.73 million tonnes of CO₂, while in 2024, emissions reached 15.80 million tonnes. This represents an increase of approximately 2,062.23%. The highest recorded emissions occurred in 2021, reaching 16.15 million tonnes. However, emissions slightly decreased by 2024. Nepal’s CO₂ emissions per capita in 2024 were about 0.53 tonnes per person. Total emissions show the country's overall contribution, while per-capita emissions show the average emissions for each person.

One possible reason for the increasing emissions is the country's dependence on fossil fuels for transportation, industries, and other activities. The World Bank reported that Nepal relies on imported petroleum products, coal, and liquefied petroleum gas to meet many of its energy needs (World Bank, 2024). These activities can contribute to CO₂ emissions. Increasing emissions are important because carbon dioxide contributes to global warming and climate change, which can affect ecosystems, biodiversity, water resources, and wildlife habitats. Monitoring national emissions can help countries understand their environmental impact and plan ways to reduce emissions. However, this analysis only covers fossil-fuel and industrial CO₂ emissions and does not represent all greenhouse gases or emissions from land-use change. The results show trends but cannot identify the exact causes of each annual change.

Figures

Annual CO₂ emissions: figures/NPL_annual_co2.png

CO₂ emissions per capita: figures/NPL_per_capita.png

Annual change in CO₂ emissions: figures/NPL_annual_change.png

Files

scripts/analyze_co2.R – R script used for the analysis.

data/NPL_co2.csv – Filtered Nepal dataset.

results/NPL_summary.csv – Summary of the analysis.

results/NPL_yearly_changes.csv – Yearly changes in emissions.

results/session_info.txt – R session information.

How to Reproduce

Run the following command in RStudio:

source("scripts/analyze_co2.R")

Limitations

The analysis covers fossil-fuel and industrial CO₂ emissions only. It does not include all greenhouse gases or emissions from land-use change. The results describe trends and do not prove the causes of changes.

References

Our World in Data. (n.d.). CO₂ emissions. https://ourworldindata.org/co2-emissions

World Bank. (2024). Nepal development update. https://documents1.worldbank.org/curated/en/099102424114517592/pdf/P50198516a3027051bea61a20af76517ef.pdf