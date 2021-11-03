# COMP432_Project - Concordia University - Fall 2021

## Authors: Matheus Nogueira and Zijian Wang

## Professor: Andrew Delong

### Title: Neural Networks for Time Seris Forecast

### Description:

The goal of this project is to provide Time Series Forecasting Methdods and compare it's results for *financial time series*, such as stock returns and currency. The list of series that were used in this project is:

 - American Airlines Adjusted Closed Sotck Return from 2010 to 2019 (Daily)
 - **CHOOSE OTHER STOCK SERIES**
 - American Dolar x Canadian Dolar
 - American Dolar x Brazilian Real

The base method for comparison will be the ARIMA Model (see *Tsay* **Analysis of Financial Time Series, chapters 1-3**).
The main method for time series forecast will be different **Neural Networks**.
Ohter methods that may be used are **GARCH** Models and **Prophet**.

### Repository Organization

This repository is divided into differente directories.

 - code: directory with the jupyter notebooks created for the project
  - SeriesAnalysis.ipynb: jupyter notebook for time series analysis that are necessary for each model implemented in other notebooks. **This must be the first notebook to be looked at!**
  - ARIMA.ipynb: jupyter notebook that implements ARIMA model for time series predictions
  - GARCH.ipynb: jupyter notebook that implements GARCH model for time series predictions
 - ref: bibliography and references used for the project
 - img: images created during the project
 - data: datasets collected and used as input for all methods implemented

### Packages needed

 - pandas
 - matplotlib
 - numpy
 - statsmodels (various packages)
 - arch
