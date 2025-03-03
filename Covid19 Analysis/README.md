## Dataset Details
In this project I've worked with 3 datasets related to COVID19. 
+ [Confirmed Cases](https://github.com/Debraj-Bora/Python-Portfolio/blob/main/Covid19%20Analysis/covid19_Confirmed_dataset.csv): This dataset contains information about the confirmed cases in various countries.
+ [Confirmed Deaths](https://github.com/Debraj-Bora/Python-Portfolio/blob/main/Covid19%20Analysis/covid19_deaths_dataset.csv): This dataset contains information about the confirmed deaths due to the pandemic.
+ [Worldwise Happiness Index](https://github.com/Debraj-Bora/Python-Portfolio/blob/main/Covid19%20Analysis/worldwide_happiness_report.csv): This dataset contains information related to happiness score and factors to determine the same like GDP, Social Support
, Healthy Life Expectancy, and Freedom to make life choices.

## Project Overview
The main objective of this project was to find a good measure represented by a number that describes the spread and death rate of Covid-19 across different countries. This
was done by computing the maximum infection rate and maximum death rate for each country.
+ Methodology
  - The dataset contains daily cumulative confirmed cases and deaths for various countries.
  - To calculate the maximum infection rate, the first derivative(daily increase) of confirmed cases was taken using the **diff()** function. The highest daily increase
for each country was then identified.
  - The maximum death rate was similarly calculated by taking the first derivative of the death count and finding the highest daily increase.

Additionally, the project aimed to explore correlations between Covid-19 metrics and factors from the World Happiness Report to determine whether economic or social well-being played a role in pandemic
impact. For this correlation matrix and heatmaps were utilised.
## Comaprison Report : Correlation Heatmaps

| Variable | Correlation with GDP per capita | Correlation with Social Support | Correlation with Healthy Life Expectancy | Correlation with Freedom to Make Life Choices |
| ---- | --- | --- | --- | --- |         
| Max Infection Rate | 0.25 | 0.19 | 0.29 | 0.078 |
| Max Death Rate | 0.26 | 0.20 | 0.31 | 0.08 |

+ Max Death Rate has a slightly stronger correlation with Healthy Life Expectancy (0.31) compared to Max Infection Rate (0.29).
  - This suggests that lower healthy life expectancy is more strongly associated with higher death rates than with infection rates.
+ Max Death Rate & GDP per Capita (0.26) vs. Max Infection Rate & GDP per Capita (0.25):
  - Very minimal change, indicating that economic strength does not significantly affect either infection or death rates.
+ Max Death Rate & Social Support (0.20) vs. Max Infection Rate & Social Support (0.19):
  - A negligible increase, meaning that social support has little impact on either infection rates or death rates.
+ Max Death Rate & Freedom to Make Life Choices (0.08) vs. Max Infection Rate & Freedom to Make Life Choices (0.078):
  - No significant change, indicating that personal freedoms do not strongly influence infection or death rates.
## Insights and Interpretation
- Economic factors (GDP per capita) play a crucial role in social and health-related well-being, but they do not significantly affect infection or death rates.
- Stronger social support is linked with better health outcomes, as seen in its correlation with Healthy Life Expectancy (0.77).
- Max Infection Rate and Max Death Rate have weak correlations with economic and social factors, suggesting that external factors (such as healthcare infrastructure, government policies, and disease control measures) play a larger role.

View the python notebook [here](https://github.com/Debraj-Bora/Python-Portfolio/blob/main/Covid19%20Analysis/covid19%20data%20analysis%20notebook.ipynb).
