# Covid-Vaccination-Analysis-and-Visualization
# Covid Vaccination Analysis and Visualization

An exploratory data analysis and visualization project on global COVID-19 vaccination data. Built and run entirely in Google Colab for easy, dependency-free execution.

## About the Project
This project analyzes publicly available COVID-19 vaccination datasets to understand global and country-level vaccination trends. It covers rollout speed, vaccination coverage, vaccine types, and comparisons across regions.

The goal is to extract meaningful insights using Python data analysis libraries and present them through clear visualizations.

## Key Analyses
1. **Global Trends**: Total vaccinations, daily doses administered, fully vs partially vaccinated populations
2. **Country Comparison**: Top countries by vaccination rate, total doses, and percentage of population covered
3. **Rollout Speed**: Time taken to reach 10%, 50%, 70% vaccination milestones
4. **Vaccine Type Breakdown**: Distribution and usage of different vaccines like Pfizer, Moderna, AstraZeneca, etc.
5. **Correlation Analysis**: Relationship between GDP, population density, and vaccination rates

## Tech Stack
- **Platform**: Google Colab
- **Language**: Python 3.x
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Plotly
- **Data Source**: Our World in Data COVID-19 Dataset or WHO dataset

## How to Run in Google Colab

1. Open Google Colab: [colab.research.google.com](https://colab.research.google.com)
2. Create a new notebook and upload this file, or open it directly from GitHub using "Open in Colab"
3. Run the first cell to install dependencies and load the dataset:
   ```python
   !pip install pandas numpy matplotlib seaborn plotly
   import pandas as pd
   import matplotlib.pyplot as plt
   import seaborn as sns





Load the dataset directly from URL:python   url = "https://github.com/MDAnsaar25/Covid-Vaccination-Analysis-and-Visualization/blob/main/country_vaccinations.csv"
   df = pd.read_csv(url)Run the notebook cells sequentially to reproduce the analysis and visualizations.Dataset
The notebook uses the Our World in Data COVID-19 Vaccinations Dataset, which is updated daily.Dataset link: https://github.com/owid/covid-19-data/tree/master/public/data/vaccinationsNo local files are required. Everything is loaded directly in Colab.Sample Visualizations
Line chart of cumulative vaccinations over time for top 10 countriesBar chart comparing vaccination percentage by countryHeatmap of vaccination rates across regionsScatter plot of GDP per capita vs vaccination rateRequirements
All dependencies are listed at the top of the notebook. No requirements.txt needed since Colab handles installation.Future Improvements
Add interactive dashboards using PlotlyInclude booster dose analysisMap-based visualization with GeoPandas/Plotly ChoroplethPredict future vaccination coverage using simple forecasting modelsContributing
Feel free to fork this notebook and add your own analysis. Pull requests with new visualizations or insights are welcome.License
MIT LicenseBuilt in Google Colab for easy sharing and reproducibility 📊
