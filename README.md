# Tree Population and Climate Analysis

## Overview
This project analyzes Torrey Pine tree population survey data from the years 2006 and 2018 to investigate changes in tree population over time. Additionally, it examines climate data to determine if there is a correlation between tree population changes and climate variables such as precipitation and temperature.

## Data Sources
1. **Tree Population Survey Data:**
   - Years: 2006 and 2018
   - Source: CA State Parks
2. **Climate Data:**
   - Variables: Minimum Daily Temperature and Precipitation
   - Timeframe: Daily data for the months of December, January, and February for the three years prior to each survey date (i.e., 2003-2006 and 2015-2018)
   - Source: PRISM Climate Group

## Methodology
1. **Tree Population Analysis:**
   - Used Python in Google Colab to analyze the survey data.
   - Found that the tree population decreased between 2006 and 2018.
2. **Climate Data Analysis:**
   - Investigated whether changes in tree population correlated with climate data.
   - Focused on minimum temperatures and precipitation for the winter months (December, January, February) for the three years prior to each survey date.
   - Analyzed daily data rather than monthly averages to capture more detailed trends.
3. **Trend Analysis:**
   - Performed trend analysis using linear regression to identify trends in minimum winter temperatures and precipitation.
   - Found that minimum winter temperatures are rising over the analyzed period.
   - Found no significant change in precipitation trends over the same period.

## Results
- **Tree Population:** Decreased between 2006 and 2018.
- **Minimum Winter Temperature:** Rising trend observed.
- **Precipitation:** No significant trend observed.

## Conclusion
Based on the statistical analysis, the findings indicate that temperature differences between the years 2003-2006 and 2015-2018 were statistically significant, while precipitation differences were not. This suggests that temperature changes could have contributed to the observed Torrey pine deaths, but further research is needed to fully understand the impact and other potential factors involved.

## Tools and Libraries
- Python
- Google Colab
- Pandas
- Matplotlib
- Scikit-learn

## How to Use
1. Clone the repository.
2. Ensure you have the necessary data files in the correct format.
3. Run the provided notebooks in Google Colab or your local environment to reproduce the analysis.
