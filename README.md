# Multiple Linear Regression - Ensemble Modeling
**Course:** _DA5030 - Introduction to Machine Learning & Data Mining_

## Overview
This project applies multiple linear regression to predict a target variable from synthetic data. Three regression models are trained on random subsets of the data, and their results are combined into an ensemble model to improve prediction accuracy.

## Data
The following data was provided and was loaded using their URLs:
* **Training Data:** [synth-data.csv](https://s3.us-east-2.amazonaws.com/artificium.us/datasets/synth-data.csv)
* **Testing Data:** _not provided_
* **Validation Data:** [synth-data-validation-500.csv](https://s3.us-east-2.amazonaws.com/artificium.us/datasets/synth-data-validation-500.csv)

## Deliverables
* `multiple_linear_regression.Rmd` - R Notebook
* `multiple_linear_regression.html` - knitted HTML report

## Dependencies
This project uses the following packages:
* dplyr
* kableExtra
* knitr
* psych
* caret

## Methodology
1. Load Data
2. Data Preparation
   * Explore Data
   * Handle Outliers
   * Data Distribution and Correlation
   * Encode Categorical Data
   * Split Data into training and testing sets
3. Train Multiple Linear Regression Models using Stepwise Backwards Elimination
4. Build Ensemble Model
5. Evaluate Model
6. Model Validation
   * Preprocess validation dataset
   * Make predictions
   * Evaluate using RMSE
  
## Results
The [final report](https://zoechow24.github.io/multiple-regression-ensemble/multiple_linear_regression.html) gives a step-by-step breakdown and explanation of the steps I took to build the ensemble model. 
