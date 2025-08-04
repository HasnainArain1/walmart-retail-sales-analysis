#Walmart Retail Sales Time Series Analysis

This project analyzes the Walmart sales dataset from Kaggle using time series techniques to uncover trends, seasonality, and forecast future sales.

#Objective
To perform a time series breakdown of Walmart's retail sales at both the national and regional level by:
- Aggregating weekly data into monthly trends
- Applying moving averages
- Analyzing seasonal behavior across store types and departments
- Performing simple forecasting using exponential smoothing

#Dataset Source

Walmart Recruiting: Store Sales Forecasting  
https://www.kaggle.com/competitions/walmart-recruiting-store-sales-forecasting

Used files:
`train.csv` – Weekly sales data per store and department
`stores.csv` – Store metadata (type and size)
`features.csv` – Additional context (holidays, temperature, etc.)

#Tools & Libraries

- Python 3.x
- Pandas
- Matplotlib & Seaborn
- Statsmodels (for exponential smoothing)

#Key Analysis & Visualizations

Monthly sales trend (national)
3-month moving average
Sales breakdown by department
Regional trend by store type (A, B, C)
Exponential Smoothing forecast
