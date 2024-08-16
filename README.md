# Regression-and-Out-of-Distribution-Prediction-on-Wine-Quality-Data

## Overview

This repository contains the code and documentation for an assignment focused on regression and out-of-distribution prediction using the Wine Quality dataset. The project involves exploring and preprocessing the dataset, training and validating multiple models, evaluating feature importance, and testing model applicability across different types of wine.

## Dataset

The Wine Quality dataset can be downloaded from [UCI Machine Learning Repository - Wine Quality](https://archive.ics.uci.edu/ml/datasets/Wine+Quality).

### Dataset Details

- *Red Wine Dataset*: Contains attributes and quality ratings for red wines.
- *White Wine Dataset*: Contains attributes and quality ratings for white wines.

## Tasks Completed

### 1. Data Exploration, Visualization, and Preprocessing

- *Exploration*: Analyzed the structure and summary statistics of the datasets.
- *Visualization*: Created plots to understand the distributions and relationships between features.
- *Preprocessing*: Handled missing values, normalized data, and performed feature scaling as needed.

### 2. Model Training and Validation

- *Models Implemented*:
  - *Random Forest*: Trained a random forest regressor and tuned hyperparameters.
  - *Support Vector Regression (SVR)*: Trained an SVR with RBF kernel and optimized hyperparameters.
  - *Neural Network*: Developed a neural network with a single hidden layer and linear activation in the output layer.

- *Hyperparameter Tuning*: Explored and validated different hyperparameters for each model to optimize performance.

### 3. Feature Importance

- *Feature Importance Determination*: Evaluated the importance of each feature in the final models. Comments on the consistency of important features across different models are provided.

### 4. Out-of-Distribution Testing

- *Cross-Type Testing*:
  - Tested models trained on red wine data using white wine data and vice versa.
  - Analyzed the applicability of models across different types of wine and provided commentary on the results.
 
    
## Note: You will find wine_quality_pridiction.ipynb file in this repository which has more than the necessary information. The first part of the question contains the solution described above.


## Results

- *Model Performance*: Detailed performance metrics for each model, including metrics like RMSE, MAE, or R^2 score.
- *Feature Importance*: Summary of important features identified by each model and comparison across models.
- *Out-of-Distribution Testing*: Insights into how well models trained on one type of wine generalize to the other type.
