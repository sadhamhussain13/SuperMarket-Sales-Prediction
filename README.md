# Supermarket Sales Prediction Project

## Overview:
This project aims to predict supermarket sales based on various features. The prediction is crucial for supermarkets to manage inventory, plan promotions, and optimize operations. The dataset used for this project contains historical sales data along with other relevant features.

## Exploratory Data Analysis (EDA):
- Analyzed the dataset to understand the distribution of features and their relationship with the target variable (sales).
- Visualized key statistics and distributions using plots and charts.
- Handled missing values and outliers appropriately.

## Data Preprocessing:
- Performed data cleaning to handle missing values, outliers, and inconsistencies.
- Converted categorical variables into numerical representations using encoding techniques like one-hot encoding or label encoding.
- Split the dataset into training and testing sets for model training and evaluation.

## Model Training:
- Utilized various machine learning algorithms including:
  - KNeighbors Classifier
  - Support Vector Classifier (SVC)
  - Random Forest Classifier
  - Gradient Boosting Classifier
  - Extra Trees Classifier
- Trained each model using the training data.
- Fine-tuned hyperparameters to optimize model performance.

## Model Evaluation:
- Evaluated the trained models using appropriate evaluation metrics such as accuracy.
- Determined the performance of each model on the test dataset.
- Achieved the following accuracies on the test dataset:
  - KNeighbors Classifier: 64.75%
  - SVC: 55.50%
  - Random Forest Classifier: 100%
  - Gradient Boosting Classifier: 89%
  - Extra Trees Classifier: 100%
- Identified Random Forest Classifier and Extra Trees Classifier as the best-performing models with 100% accuracy.

## Conclusion:
- The Random Forest Classifier and Extra Trees Classifier models demonstrated superior performance in predicting supermarket sales.
- The project provides valuable insights into the sales patterns of the supermarket, which can aid in decision-making and strategic planning.
- Further enhancements could involve feature engineering, exploring more advanced algorithms, and incorporating additional datasets for improved predictions.
