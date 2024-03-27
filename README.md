## Multi-Class Prediction of Obesity Risk - Readme

This repository contains my code for the Kaggle competition, [Multi-Class Prediction of Obesity Risk](https://www.kaggle.com/competitions/playground-series-s4e2).

### Competition Description

This is a machine learning competition hosted on Kaggle. The goal is to predict obesity risk in individuals using a synthetic dataset. The competition aims to improve cardiovascular disease prediction.

### Solution Overview

This repository contains code using various machine learning models to predict obesity risk. Here's a breakdown of the models used:

* Logistic Regression
* XGBoost
* LightGBM
* Stacked Ensemble
* Voting Classifier

### Getting Started

To run the code in this repository, you'll need the following:

* Python 3.6 or later
* Necessary libraries:
  * scikit-learn
  * xgboost
  * lightgbm

Once you have these installed, you can clone this repository and run the scripts.

### Usage

The scripts in this repository can be run independently. Each script trains a specific model and makes predictions on the test set.

### Results

The results of each model are summarized in the table below. You can then compare the performance of each model and submit the best performing model's predictions to Kaggle.

| Model             | Score                    |
| ----------------- | ------------------------ |
| XGBoost           | 0.90245                  |
| Voting Classifier | 0.90272 (**Best**) |
| Stacked Ensemble  | 0.90254                  |

### Credits

The notebook is based on [another submission](https://www.kaggle.com/code/kumudithasilva/multi-class-obesity-risk/notebook) by [KUMUDITHASILVA](https://www.kaggle.com/kumudithasilva). 

### Conclusion

This repository provides a starting point for exploring machine learning approaches to predict obesity risk. Feel free to experiment with different models and hyperparameters to improve the results.
