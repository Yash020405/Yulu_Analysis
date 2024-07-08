# Yulu Bike Rental Analysis

## Overview

This project analyzes data from Yulu, India's leading micro-mobility service provider, to understand factors affecting demand for their shared electric cycles. The analysis aims to help Yulu address recent revenue dips by identifying key drivers of bike rental demand in the Indian market.

## Dataset

The dataset contains hourly rental data spanning 2011-2012, including:

- Date and time
- Season 
- Holiday/Working day
- Weather conditions
- Temperature
- Humidity
- Wind speed
- Number of casual users, registered users, and total count

## Analysis Performed

1. Data cleaning and preprocessing
2. Exploratory data analysis 
3. Univariate and bivariate analysis
4. Correlation analysis
5. Hypothesis testing:
   - Effect of working days on rentals
   - Impact of seasons on rental numbers
   - Influence of weather conditions on rentals
   - Dependency between weather and seasons

## Key Findings

- Working days do not significantly affect rental numbers
- Seasons have a significant impact on bike rentals
- Weather conditions influence the number of rentals
- Weather is dependent on the season

## Recommendations

- Adjust fleet allocation based on demand trends
- Implement seasonal promotions 
- Provide weather-ready bikes
- Optimize maintenance schedules
- Prioritize rider safety

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels

## How to Run

1. Ensure you have Python and the required libraries installed
2. Download the Jupyter notebook file
3. Run the cells in order to reproduce the analysis

## Future Work

- Incorporate more recent data
- Analyze impact of pricing strategies
- Explore machine learning models for demand prediction
