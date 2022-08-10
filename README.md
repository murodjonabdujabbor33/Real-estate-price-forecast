# Real-estate-price-forecast
# Welcome Real-estate-price-forecast
***

This repository is an assignment in the Data Science course on the QWASAR Silicon Valley educational platform.
In this project, I will build a model to predict the price base based on predefined criteria.

## Task
Housing prices are a hot topic today. In this project, we are asked to create a model to predict the price base based on predefined criteria.
We have a collection of housing prices in Boston.
This project is divided into 2 parts:
  1) Understanding the data.
  2) Create a linear regression prediction model.

## Description
I worked on this assignment in 5 steps:
1) First look. At this stage, I explored the data (with visualization, correlation, etc.). 
2) Cleaning and preprocessing (I worked with NaN values in the data).
3) Data analysis (I visualized the data).
4) Search for correlations (I studied the correlation coefficients in the data. I found out which of them affects the result we expect). 
5) Prediction (A model was created using the results of this step).

## Installation
To run the project, the %pip install and %pip install seaborn sklearn commands must be executed in the jupyter notebook.
The project requires the use of the sklearn, numpy, pandas, seaborn, and matplotlib libraries,
as well as the LinearRegression and train_test_split classes from sklearn.

## Usage
A Jupyter notebook is used to implement the project.
the required package libraries and packages are installed. Then the functions are launched.
Available funtions:
load_dataset(url)
clean_dataset(dataset)
print_histograms(dataset)
compute_correlations_matrix(dataset)
print_scatter_matrix(dataset)
boston_fit_model(dataset)
boston_predict(estimator, array_to_predict)
print_model_prediction_evaluator(base_test, prediction)
