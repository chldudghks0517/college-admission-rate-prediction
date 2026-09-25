# college-admission-rate-prediction
CM3070: Final Project: Predicting US Institutional Admission Rates Using Machine Learning and College Scorecard Data  

# Predicting US Institutional Admission Rates Using Machine Learning

This repository contains the source code for my CM3070 Final Project.

## Project Overview

This project uses publicly available College Scorecard institutional data to predict
US institutional admission rates.

The modelling configurations include:

- Baseline Linear Regression
- Linear Regression with manually engineered features
- Polynomial Regression
- Random Forest Regressor
- Support Vector Regression

## Main Notebook

The complete implementation is contained in:

`admission_rate_prediction.ipynb`

The notebook includes:

- data loading and filtering
- exploratory data analysis
- preprocessing
- feature engineering
- model training
- five-fold cross-validation of the baseline model
- model comparison
- prediction diagnostics and visualisation

## Dataset

The project uses the US Department of Education College Scorecard
Most Recent Institution-Level Data.

The notebook expects the following CSV file to be stored in the same directory:

`Most-Recent-Cohorts-Institution.csv`

## Python Libraries

The main libraries used are:

- NumPy
- pandas
- Matplotlib
- scikit-learn

## Reproducibility

The final implementation uses an 80:20 train-test split with:

`random_state = 42`

After filtering, the modelling dataset contains 1,725 institutions.

## Author

CM3070 Final Project
