# Binary Prediction with Rainfall Dataset

This folder contains my work for the [Playground Series - Season 5, Episode 3](https://www.kaggle.com/competitions/playground-series-s5e3) Kaggle competition.

## Competition Overview
- **Type**: Binary Classification
- **Goal**: Predict rainfall occurrence (binary: rain or no rain) using weather data
- **Evaluation Metric**: AUC (Area Under the ROC Curve)
- **Data Source**: Based on Hong Kong Weather Observation data (2015-2016)

## Approach

### Current Approach
- Exploratory Data Analysis (EDA) to understand relationships between features
- Handling missing values (one missing value in 'winddirection' column)
- Feature correlation analysis to identify multicollinearity
- Baseline model using Logistic Regression

### Planned Improvements
- Feature engineering to extract more information from weather data
- Testing advanced models (Random Forest, XGBoost, Neural Networks)
- Hyperparameter optimization
- Cross-validation for more robust evaluation
- Ensemble methods to combine multiple models

## Results
- **Current AUC Score**: 0.8726
- **Model**: Logistic Regression with default parameters
- **Leaderboard Position**: 1321/2792

## Key Learnings
TBD

## Files
- `notebooks/`: Jupyter notebooks for exploration and modeling
  - `ps5e3-compare-basic-models-v1.ipynb`: Baseline model with detailed comments
- `submissions/`: Competition submission files
