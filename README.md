# COMP432_Project - Concordia University - Fall 2021

## Authors: Matheus Nogueira and Zijian Wang - G27

## Professor: Andrew Delong

### Title: Neural Networks for Time Seris Forecast

### Description:

The goal of this project is to provide Time Series Forecasting Methdods and compare it's results for *financial time series*, such as stock returns and currency. The list of series that were used in this project is:

 - American Airlines Adjusted Closed Sotck Return from 2010 to 2019 (Weekly)
 - American Dolar x Canadian Dolar (Weekly)
 - American Dolar x Brazilian Real (Weekly)

All of the series were obtained at __[YahhoFinance]{finance.yahoo.com/}__

In this project we have implemented different models for Time Series Forecast, such as **ARIMA/GARCH**, **Random Forest Regressor**, **Support Vector Machine Regressor**, **Multi Layer Perceptron Neural Networks**, **Recurrence Neural Networks** and **Prophet**.

### Repository Organization

This project is divided into differente directories:

 - code: directory with the jupyter notebooks created for the project
   - SeriesAnalysis.ipynb: jupyter notebook for time series analysis that are necessary for each model implemented in other notebooks. **This must be the first notebook to be looked at!**
   - ARIMA.ipynb: jupyter notebook that implements ARIMA model for time series predictions
   - GARCH.ipynb: jupyter notebook that implements ARIMA/GARCH model for time series predictions
   - RandomForest.ipynb: jupyter notebook that implements Random Forest Regressors with hyperparameter search for time series predictions
   - SVM.ipynb: jupyter notebook that implements Support Vector Machines Regressors with hyperparameter search for time series predictions
   - MLP.ipynb: jupyter notebook that implements Multi Layer Perceptron Neural Networks with hyperparameter search for time series predictions
   - Recurrence.ipynb: jupyter notebook that implements Recurence Neural Networks with hyperparameter search for time series predictions
   - Prophet.ipynb: jupyter notebook that implements the Facebook Prophet Model with hyperparameter search for time series predictions
 - ref: bibliography and references used for the project
 - img: images created during the project
 - data: datasets collected and used as input for all methods implemented

### Important Information:

The first notebook to be llok at is **SeriesAnalysis.ipynb**.

Although the order of the remaining notebooks is not crucial, we suggest the following: ARIMA, ARIMA/GARCH, RF, SVM, MLP, RNN, Prophet.

Be aware that training some of the models can take a lot of time:
 - MLP -> over 30 minutes for each training cell (there are 2)
 - RF and SVM -> over 15/20 minutes for each training cell (there are 2)
 - RNN -> over X minutes for each training cell
 - Prophet -> over 20 minutes for each training cell (there are 2)

GPU not required

The notebooks are all full of comments and markdowns in order to make each one *independent* from the others and fully understandable by itself. That means all of them follow almost exactly the same structure. We prioritized understanding creating some redundancy.

### Packages needed

 - __[pandas]{https://anaconda.org/anaconda/pandas}__
 - __[matplotlib]{https://anaconda.org/conda-forge/matplotlib}__
 - __[numpy]{https://anaconda.org/anaconda/numpy}__
 - __[statsmodels]{https://anaconda.org/anaconda/statsmodels}__
 - __[arch]{https://anaconda.org/bashtage/arch}__
 - __[sklearn]{https://anaconda.org/anaconda/scikit-learn}__
 - __[fbprophet]{https://anaconda.org/conda-forge/fbprophet}__


