# CO2-emissions-analysis
This project analyzes global CO₂ emissions per capita using a dataset of fossil fuel-based emissions from various countries. It includes data cleaning, exploratory data analysis (EDA), and visualizations using Python libraries such as Pandas, Matplotlib, Seaborn, and Plotly. Key insights include trends over time, country-wise comparisons, and emissions patterns from 2000 to 2022.

## Overview

This project analyzes fossil CO₂ emissions per capita across different countries and over time. The dataset includes emissions from coal, oil, gas, flaring, cement, steel, and other industrial processes but does not account for land use change, deforestation, soils, or vegetation.

## Dataset

The [dataset](https://www.kaggle.com/datasets/willianoliveiragibin/greenhouse-gas-emissions) used in this analysis is co-emissions-per-capita new.csv, which contains the following key columns:

- Entity: Country or region name

- Year: Year of the recorded emission data

- Annual CO₂ emissions (per capita): CO₂ emissions per capita for the given entity and year

## Libraries Used

The following Python libraries were used for data analysis and visualization:

- numpy
- pandas
- matplotlib.pyplot
- seaborn
- plotly.express

## Data Preprocessing

1. Loaded the dataset and inspected its structure.
2. Checked for missing values and dataset shape.
3. Cleaned the Annual CO₂ emissions (per capita) column by removing unwanted characters and converting the datatype to integer.
4. Explored unique values in the Entity column.


## Exploratory Data Analysis (EDA)

- Identified the top 10 countries with the highest and lowest CO₂ emissions per capita.
- Created bar plots to visualize these emissions.
- Analyzed total CO₂ emissions per capita over time using a line plot.
- Filtered data for the years 2000-2022.
- Selected specific countries (China, India, Germany, Afghanistan, Africa) for focused analysis.
- Used seaborn FacetGrid to plot CO₂ emissions trends for these selected countries.



## Visualizations

- Bar Charts: Top 10 countries with highest and lowest CO₂ emissions per capita.

- Line Plot: CO₂ emissions per capita over time.

- FacetGrid Line Charts: CO₂ emissions trends from 2000-2022 for selected countries.

