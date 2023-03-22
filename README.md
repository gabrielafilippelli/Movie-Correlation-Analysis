<h1 align="center">Movie Correlation Data Analysis Project </h1>

## Overview
With a dataset containing 6820 movies (220 movies per year, 1986-2016). I looked at which variables effect the gross revenue from movies. I used Python Notebook to clean and visualize the data, and correlate the various attributes in films across multiple genres.

## Code Used:
Python Version: 3.8

Packages: Numpy, Pandas, Seaborn, Matplotlib

## Data Gathering
I downloaded a dataset from Kaggle which was scraped from IMDb:
- **[Movie Industry Dataset](https://www.kaggle.com/datasets/danielgrijalvas/movies)** (Source: Kaggle)

## Data Cleaning + Data Manipulation
After loading the dataset into Jupyter Notebooks, the first order of business is to clean the data by dropping any columns that will not be necessary for this analysis, as well as “Numerizing” categorical data such as Company name and Country to allow correlation analysis.

## Key Findings
High correlation between a film's budget and its gross earnings, created a positive linear graph from the correlation.

Results of correlation analysis was visualized in the form of a heatmap.
