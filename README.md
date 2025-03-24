# Impact of COVID-19 on Energy Consumption in Seattle

This project analyzes how the COVID-19 pandemic influenced electricity usage in Seattle by comparing pre-pandemic forecasts with actual consumption during COVID-19.

## Goals

- Analyze trends in energy usage before and during the pandemic.
- Forecast expected usage using time series models.
- Compare predicted vs. actual consumption.

## Tools Used

- Python, Pandas, Matplotlib, Seaborn  
- Scikit-learn, Statsmodels  

## Key Steps

1. Data cleaning & resampling to monthly usage.
2. Time series decomposition & forecasting.
3. Visual comparison of predicted vs. actual usage.

## Key Findings

![res_2021](https://github.com/user-attachments/assets/89367371-a46d-4d83-8e29-4e83f4556c7f)

- Significant drop in energy usage during initial lockdown months.
- Pre-pandemic models overestimated usage during early COVID-19.
- Gradual recovery in usage observed by late 2020.
- Seasonal patterns were disrupted but began to normalize post-2021.

## Run the Notebook

```bash
pip install pandas matplotlib seaborn scikit-learn statsmodels
jupyter notebook "Impact_of_COVID_19_on_Energy_Consumption_in_Seattle.ipynb"
