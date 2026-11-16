# CO2 Emissions Analysis: Nepal

**Student:** [Your Name]  
**Country / ISO-3:** Nepal / NPL  
**Study Period:** 1990–2024  
**Data Source:** Our World in Data (OWID)

## Research Question

How have annual CO2 emissions and CO2 emissions per capita changed in Nepal from 1990 to 2024?

## Data Source and Methods

This study uses the Our World in Data (OWID) CO2 and Greenhouse Gas Emissions dataset. The data were downloaded and analyzed using RStudio.

The analysis focuses on:
- Annual CO2 emissions (million tonnes).
- CO2 emissions per capita (tonnes per person).
- Year-to-year percentage changes.

## How to Reproduce the Analysis

1. Install R, RStudio, and Git.
2. Open this project in RStudio.
3. Make sure you have an internet connection.
4. Run this command in the RStudio Console:

```r
source("scripts/analyze_co2.R")
```

## Results

The analysis generated the following files:

- `data/NPL_co2.csv`
- `figures/NPL_annual_co2.png`
- `figures/NPL_per_capita.png`
- `figures/NPL_annual_change.png`
- `results/NPL_summary.csv`
- `results/NPL_yearly_changes.csv`
- `results/session_info.txt`

## Figures

### Annual CO2 Emissions

![Annual CO2 Emissions](figures/NPL_annual_co2.png)

### CO2 Emissions Per Capita

![CO2 Per Capita](figures/NPL_per_capita.png)

### Annual Percentage Change

![Annual Change](figures/NPL_annual_change.png)

## Interpretation

[Write your 200–300-word interpretation here using the actual values from NPL_summary.csv and your graphs.]

## Limitations

The dataset focuses on CO2 emissions from fossil fuels and industrial processes. It excludes land-use change. Missing data may also affect the results. The analysis shows changes in emissions but does not prove the causes of those changes.

## References

Our World in Data. CO2 and Greenhouse Gas Emissions Dataset.  
https://github.com/owid/co2-data