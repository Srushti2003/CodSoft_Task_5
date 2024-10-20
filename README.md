# Credit Card Fraud Detection Project

## Overview
This project implements a machine learning model to detect fraudulent transactions in credit card data. Using Python and various libraries, we preprocess the data, address class imbalance, train a classification model, and evaluate its performance. This project serves as a practical application of data science techniques and machine learning algorithms for fraud detection.

## Dataset
The dataset used for this project is the Credit Card Fraud Detection dataset from Kaggle, which contains transactions made by credit cards in September 2013 by European cardholders. It includes a mix of legitimate and fraudulent transactions.

## Key Steps
  Data Loading and Exploration:
    Loaded the dataset using pandas.
    Explored the data to understand its structure and check for missing values.
  Data Visualization:
    Visualized class distribution using a count plot to identify the imbalance between legitimate and fraudulent transactions.
  Data Preprocessing:
    Separated features and the target variable ('Class').
    Standardized the feature set using StandardScaler to improve model performance.
    Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset by generating synthetic samples of the minority class.
  Model Training:
    Trained a Random Forest Classifier on the resampled training data.
    Evaluated the model using metrics such as accuracy, confusion matrix, and classification report.
  Results Visualization:
    Visualized the confusion matrix to assess model performance.
    Displayed feature importance to understand which features contribute most to the model’s predictions.

Technologies Used
  Python
  Pandas
  NumPy
  Scikit-learn
  Seaborn
  Matplotlib
  imbalanced-learn (for SMOTE)

Key Learnings
  Gained hands-on experience in handling imbalanced datasets and utilizing techniques like SMOTE.
  Enhanced understanding of the Random Forest algorithm and its application in classification tasks.
  Developed skills in data preprocessing, visualization, and model evaluation.
