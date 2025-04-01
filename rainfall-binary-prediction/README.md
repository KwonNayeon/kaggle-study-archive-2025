# Binary Prediction with Rainfall Dataset
This folder contains my work for the [Playground Series - Season 5, Episode 3](https://www.kaggle.com/competitions/playground-series-s5e3) Kaggle competition.

## Competition Overview
- **Type**: Binary Classification
- **Goal**: Predict rainfall occurrence (binary: rain or no rain) using weather data
- **Evaluation Metric**: AUC (Area Under the ROC Curve)
- **Data Source**: Based on Hong Kong Weather Observation data (2015-2016)

## Approach
My project workflow included:
- Data exploration and visualization
- Missing value handling
- Feature engineering and selection
- Baseline model development
- Advanced modeling techniques
- Hyperparameter optimization
- Ensemble method implementation

## Results
- **Public Score (AUC)**: 0.86511
- **Final Score (AUC)**: 0.89712
- **Best Model**: `ps5e3-models-with-feature-engineering-v1.ipynb`
- **Leaderboard Position**: 700/4382

## Key Learnings
This was my first Kaggle competition, a significant milestone in my data science journey. Although my ranking wasn't particularly high, I discovered the potential for improvement with continued effort and practice. Some key takeaways include:

1. Gained hands-on experience with the entire machine learning pipeline
2. Refreshed my understanding of the model-building process
3. Learned practical techniques for feature engineering with weather data
4. Experienced the competitive aspect of applying machine learning in a time-bound environment
5. I identified areas where I can improve in future competitions

The most valuable outcome was seeing the potential for growth in my skills and the clear path forward for improving my performance in future competitions.

## Files
- `notebooks/`: Jupyter notebooks for exploration and modeling
  - `ps5e3-compare-basic-models-v1.ipynb`: Baseline models ![Kaggle Score](https://img.shields.io/badge/Kaggle%20Public%20Score-0.85679-blue)
  - `ps5e3-models-with-feature-engineering-v1.ipynb`: Models with feature engineering ![Kaggle Public Score](https://img.shields.io/badge/Kaggle%20Public%20Score-0.86511-blue) ![Kaggle Final Score](https://img.shields.io/badge/Kaggle%20Final%20Score-0.89712-green)
  - `ps5e3-enhanced-models-with-feature-selection.ipynb`: Enhanced models with additional feature engineering ![Kaggle Score](https://img.shields.io/badge/Kaggle%20Public%20Score-0.86618-blue)
  - `ps5e3-ensemble-models.ipynb`: Combining top three models for improved performance ![Kaggle Score](https://img.shields.io/badge/Kaggle%20Public%20Score-0.84419-blue)
