# Customer Churn Rate Prediction

## Overview
This Jupyter Notebook file contains code for predicting customer churn rates using machine learning algorithms. The dataset used in this project is `Churn_Modelling.csv`.

## Data Preprocessing
- Necessary libraries like NumPy, Matplotlib, Pandas, Seaborn, and scikit-learn are imported.
- The dataset is imported using Pandas' `read_csv` function.

## Data Exploration
- Basic exploration of the dataset including its shape, information, and statistical summary.
- Handling missing data and encoding categorical features.

## Data Visualization
- Count plot to visualize the distribution of customer churn.
- Correlation matrix and heatmap to explore relationships between variables.

## Model Building
Three models are built:
1. Logistic Regression
2. Random Forest Classifier
3. XGBoost

## Model Evaluation
- Each model is trained, evaluated, and cross-validated to assess its performance.
- The Random Forest Classifier is fine-tuned using Randomized Search Cross Validation to optimize hyperparameters.

## Prediction
- A function is defined to predict the churn status of a single observation.

