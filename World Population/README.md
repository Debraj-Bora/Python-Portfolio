## Dataset Details  
This [dataset](https://github.com/Debraj-Bora/Python-Portfolio/blob/main/World%20Population/world_population.csv) contains global population data for 234 countries, covering population figures from 1970 to 2022, along with geographical attributes like continent, area, and population density.  

## Project Overview  
The dataset was cleaned and analyzed to identify global population trends, growth patterns, and country-wise distributions. Key insights include growth rates, population density variations, and continent-wise trends.  

### **Key Analysis Performed:**  
#### **1. Data Cleaning:** Handled missing values, converted data types, and standardized formats.  
#### **2. Exploratory Data Analysis (EDA)**  
#### **Population Growth Trends**
- The world's population has stedily increased from 1970 - 2022, with a **higher growth rate in developing countries.**
- China and India remain the most populous countries, with India projected to overtake China.
#### **Density and Area Comparisons**
- The most densely populated country is Monaco, with over 23,000 people per km².
- The largest country by land area is Russia, while the smallest is Vatican City.
#### **Continent-wise Population Distribution**
- Asia has the highest population share, followed by Africa.
- Oceania remains the least populated continent.
#### **Growth Rate Insights**
- The highest population growth rates are seen in African nations
- Countries with negative or slow growth include Japan and some European nations due to aging populations.
#### **Correlation Heatmap Insights**
![plot](https://github.com/Debraj-Bora/Python-Portfolio/blob/main/World%20Population/heatmap.png)
- Population and Area showed moderate correlation (~0.45), meaning larger countries tend to have higher populations, but this is not always the case.
- Density and Growth Rate had a weak negative correlation (~-0.07), implying that denser countries may not necessarily have high growth rates.
- Rank and Population showed an inverse correlation (~-0.35), meaning countries with higher ranks had lower populations.
### **Libraries Used:** Pandas, Matplotlib, Seaborn.
### **[View my analysis here](https://github.com/Debraj-Bora/Python-Portfolio/blob/main/World%20Population/world_population_EDA.ipynb)**
