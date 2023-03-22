## Overview
With a dataset containing 45,000 movies and 26 million ratings from over 270,000 users I looked at what variables effect the gross revenue from movies. I used Python Notebook to clean and visualize the data, and identified key drivers of movie budgets and gross revenue fluctuations in various films across multiple genres.

## Code Used:
Python Version: 3.8

Packages: Numpy, Pandas, Seaborn, Matplotlib

## Data Gathering
With these questions I had, I downloaded a dataset from Kaggle to help me answer these questions:
- **[New York City AirBnB Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)** (Source: Kaggle)

## Data Cleaning + Data Manipulation
After loading the dataset into Jupyter Notebooks, the first order of business is to clean the data by dropping any columns that will not be necessary for this analysis, as well as “Numerizing” categorical data such as Company name and Country to allow correlation analysis.

## Key Findings
High correlation between a film's budget and its gross earnings and grew exponentially

Results of correlation analysis was visualized in the form of a heatmap
