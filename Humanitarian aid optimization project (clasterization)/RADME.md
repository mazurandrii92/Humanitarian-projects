# Humanitarian Aid Optimization: Identifying High-Need Regions Through Data Analysis

## Project Overview
This project analyzes socio-economic data to optimize the allocation of humanitarian aid by identifying countries in greatest need. By using statistical techniques and machine learning, the analysis helps prioritize resources for maximum impact.

## Dataset Features
The dataset contains socio-economic indicators for 167 countries, including:
- `country`: Name of the country.
- `child_mort`: Under-five child mortality rate.
- `exports`: Export per capita.
- `health`: Health expenditure per capita.
- `imports`: Import per capita.
- `income`: Average income per capita.
- `inflation`: Annual inflation rate.
- `life_expec`: Average life expectancy.
- `total_fer`: Total fertility rate.
- `gdpp`: GDP per capita.


## Methodology
1. **Data Preprocessing**: Cleaned and normalized the dataset for consistency.
2. **Exploratory Data Analysis (EDA)**: Analyzed trends in child mortality, GDP, and fertility rates.
3. **Dimensionality Reduction**: Applied Principal Component Analysis (PCA) to identify critical factors.
4. **Clustering**: Used K-means clustering to group countries by socio-economic similarity.
5. **Insights Generation**: Highlighted key clusters and identified countries requiring urgent intervention.

## Final Conclusion
From the analysis, it is evident that countries like Haiti, Lesotho, and the Central African Republic face severe socio-economic challenges. These countries exhibit a combination of high child mortality, low GDP per capita, and other critical indicators. By prioritizing these regions, humanitarian organizations can maximize the impact of their resources and address urgent needs effectively.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib