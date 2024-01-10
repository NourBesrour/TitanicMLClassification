# Titanic Survival Prediction

This Python script predicts passenger survival on the Titanic using machine learning models. The script achieves an F1 score of 0.74 on the Kaggle dataset.

## Features:

# Data preprocessing: 
Handles missing values, extracts titles, and creates new features.
# Encoding: 
Utilizes label encoding for categorical variables.
# Model Training: 
Implements Gradient Boosting, LGBM, XGBoost, SGD, and Logistic Regression.
# Evaluation: 
Calculates accuracy, precision, recall, and F1 score.
# Prediction: 
Applies the trained model to the test set and saves results.

## Usage:

Ensure Python and required libraries (pandas, numpy, sklearn, lightgbm, xgboost, seaborn) are installed.
Download the Kaggle Titanic dataset (train.csv, test.csv, gender_submission.csv).
Run the script (python titanic_prediction.py).
Check the generated predictions_result.csv for the model predictions.

## Results:

# F1 Score: 
0.74
# Kaggle Public Score:
0.67464

## File Descriptions:
# main1.py: 
The main Python script.
# train.csv, test.csv, gender_submission.csv: 
Kaggle Titanic dataset files.

## Note:
The script preprocesses data, trains models, and predicts survival on the test set.
Achieved F1 score indicates good model performance.
Results are saved in a CSV file for Kaggle submission.
Feel free to explore and modify the script for further improvements!






