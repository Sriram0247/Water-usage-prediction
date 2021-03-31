## Objective
The purpose of this project is to apply machine learning techniques to forecast water consumption in Baltimore. 

### Methods used
* Inferential statistics
* Machine Learning
* Data Visualization

### Technologies
* Python, Jupyter

## Project Description
* The dataset used for this project is the Baltimore Water Usage Dataset from 1885 to 1963. The values are in units of litres per capita per day.
* This project demonstrates the use of ARIMA models, with a walk-forward validation strategy to forecast water usage per capita per day.
* Data visualization techniques used in this project include lineplots, histograms, kernel density plots, ACF and PACF plots.
* A grid-search of ARIMA hyperparameters gives the ARIMA(2,1,0) model with least RMSE.
* Bias-correction is performed before final forecasts are made.
