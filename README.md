# Credit Score Classification

## Overview
This project uses machine learning to classify individuals into credit score categories. The goal is to help financial institutions assess creditworthiness effectively.

It is focused on classifying credit scores into three categories: **Good**, **Standard**, and **Bad**. The classification models used in this project include Logistic Regression, Random Forest, and Decision Tree. Data cleaning, scaling, and encoding were performed to prepare the dataset for model training and evaluation.

## Dataset

- **Train Data**: `train.csv` – The training dataset containing features and target labels for training the models.
- **Test Data**: `test.csv` – The test dataset used to evaluate the performance of the trained models.

## Data Preprocessing

- **Data Cleaning**: Missing values were handled and irrelevant or duplicate data were removed.
- **Feature Scaling**: Numerical features were scaled to ensure consistency for model training.
- **Encoding**: Categorical variables were encoded using appropriate methods for machine learning models.

## Models Used

1. **Logistic Regression**: A basic linear model for binary classification, used here to predict the credit score class.
2. **Random Forest**: An ensemble learning method that constructs multiple decision trees and merges them to obtain a more accurate and stable prediction.
3. **Decision Tree**: A tree-based model that splits data based on the feature values to predict the target.

## Model Performance

- **Random Forest**: Achieved an accuracy of **80%** on the test dataset.
- **Decision Tree**: Achieved an accuracy of **75%** on the test dataset.
- **Logistic Regression**: Achieved an accuracy of **63%** on the test dataset.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

