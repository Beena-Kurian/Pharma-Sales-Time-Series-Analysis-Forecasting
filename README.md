# Pharma Sales Time Series Analysis & Forecasting

This repository contains code for analyzing and forecasting pharmaceutical sales data using time series techniques. The code is structured as follows:

## Importing Libraries
Libraries such as pandas, matplotlib, seaborn, and statsmodels are imported for data manipulation, visualization, and time series analysis.

## Reading the Data
The dataset consists of monthly sales data for pharmaceutical products collected over six years from January 2014 to October 2019.

Selected group of drugs (57 drugs) is classified to 8 Anatomical Therapeutic Chemical (ATC) Classification System categories:

* M01AB - Anti-inflammatory and antirheumatic products, non-steroids, Acetic acid derivatives and related substances

* M01AE - Anti-inflammatory and antirheumatic products, non-steroids, Propionic acid derivatives

* N02BA - Other analgesics and antipyretics, Salicylic acid and derivatives

* N02BE - Other analgesics and antipyretics, Pyrazolones and Anilides

* N05B - Psycholeptics drugs, Anxiolytic drugs

* N05C - Psycholeptics drugs, Hypnotics and sedatives drugs

* R03 - Drugs for obstructive airway diseases

* R06 - Antihistamines for systemic use
## Data Exploration
Basic exploration of the dataset is performed using statistical summaries and visualization techniques to understand the underlying patterns and distributions.

## Data Preprocessing
The 'datum' column is converted to datetime format, and year and month are extracted as separate columns. Zero values in the dataset are replaced with mean values to ensure data integrity.

## Outlier Detection
Box plots are created to visualize the distribution of sales for each medicine, and zero values in the dataset are identified and handled appropriately.

## Time Series Analysis
The time series analysis includes decomposing the data into trend, seasonality, and residual components, as well as assessing stationarity using the Augmented Dickey-Fuller (ADF) test.

## Forecasting Future Sales
Two forecasting models, ARIMA and SARIMAX, are implemented to forecast future sales for each medicine category. The forecasted values are visualized to provide insights into future sales trends.

Feel free to explore the code files and Jupyter notebooks for detailed implementation and analysis steps.

