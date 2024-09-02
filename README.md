# Richter_Prediction
## application used:
- jupyter notebook
- postgresql
- sklearn Random Forest
- Catboost
- Optuna 
- mlflow

## overview:
In this work I have used different classification models to predict a multi-class classification where we predict the destruction grade that an earthquake will have on a bulding based on the features given.

## Exploratory Data Analysis:
To understand the data I have used postgresql to analyze different features and feature correlation in jupyter and opandas data frames ([Notebook File](Richter_prediction_EDA.ipynb)).

## Training and optimizing:
I have used optuna for optimizng my models and used mlflow to register the results of my test for different models([Notebook File](Richter_prediction_ML.ipynb)).

## Serving:
After training and optimizing my models I ahve used mlflow as backend server where we put the best model in production([Notebook File](Richter_prediction_ML.ipynb)).