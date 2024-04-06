# Bicycle Rental Prediction

This repository contains code and data for a data science project focused on predicting the number of bicycle rentals based on seasonality and weather conditions using regression techniques. The project is based on a real study utilizing data from a bicycle sharing scheme, with a simplified version of the dataset being used here.

## Overview

In this notebook, we explore various regression algorithms to predict bicycle rentals. We start by loading the dataset, examining its structure, and preprocessing it as necessary. Then, we train regression models using different algorithms, including linear, tree-based, and ensemble methods. The goal is to improve the predictive performance of the models compared to previous iterations.

## Dataset

The dataset consists of the following columns:

- `instant`: A unique row identifier
- `dteday`: The date of observation
- `season`: Numerically encoded value for season (1:winter, 2:spring, 3:summer, 4:fall)
- `yr`: Year of observation (0: 2011, 1: 2012)
- `mnth`: Calendar month of observation (1:January ... 12:December)
- `holiday`: Binary value indicating whether it's a public holiday
- `weekday`: Day of the week (0:Sunday ... 6:Saturday)
- `workingday`: Binary value indicating whether it's a working day
- `weathersit`: Categorical value indicating weather situation (1:clear, 2:mist/cloud, 3:light rain/snow, 4:heavy rain/hail/snow/fog)
- `temp`: Normalized temperature in celsius
- `atemp`: Normalized apparent ("feels-like") temperature in celsius
- `hum`: Normalized humidity level
- `windspeed`: Normalized windspeed
- `rentals`: Number of bicycle rentals (target variable)

## Algorithms Explored

We explore the following regression algorithms:

- **Linear algorithms:** Variants such as Linear Regression, Lasso.
- **Tree-based algorithms:** Decision Tree Regression.
- **Ensemble algorithms:** Random Forest Regression.

## Citation

The dataset used in this exercise is derived from Capital Bikeshare and is utilized in accordance with the published license agreement.

Feel free to explore the code and experiment with different regression algorithms for predicting bicycle rentals based on seasonality and weather conditions.

