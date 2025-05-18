# COVID-19 Analysis and Visualization

## Project Overview

This project analyzes and visualizes COVID-19 data to explore the spread, impact, and trends of the pandemic across different countries and regions. The analysis leverages datasets containing global COVID-19 case counts, deaths, recoveries, and testing data. The project uses Python with libraries such as Pandas, Matplotlib, and Plotly to process the data and create interactive visualizations.

## Objectives

- Perform exploratory data analysis (EDA) on COVID-19 datasets.  
- Visualize key metrics such as total cases, deaths, recoveries, and cases per million population.  
- Provide insights into the global and regional impact of the pandemic.

## Datasets

The project uses three CSV files:

1. **covid.csv (dataset1)**: Contains aggregated COVID-19 data by country, including:
   - Country/Region, Continent, Population  
   - Total Cases, New Cases, Total Deaths, New Deaths, Total Recovered, New Recovered, Active Cases  
   - Serious/Critical cases, Total Cases per 1M population, Deaths per 1M population  
   - Total Tests, Tests per 1M population, WHO Region, ISO Alpha-3 code

2. **covid_grouped.csv (dataset2)**: Time-series data with daily COVID-19 metrics by country, including:
   - Date, Country/Region, Confirmed Cases, Deaths, Recovered, Active Cases, New Cases, New Deaths, New Recovered

3. **coviddeath.csv (dataset3)**: Likely contains data related to COVID-19 deaths (not fully explored in the provided notebook snippet).

*Note: The datasets are assumed to be stored in the `/content/` directory in the original Colab environment.*

## Prerequisites

- Python 3.x  
- Jupyter Notebook or Google Colab  
- Required Python libraries:
  - pandas  
  - matplotlib  
  - plotly

