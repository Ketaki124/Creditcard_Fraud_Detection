# Creditcard_Fraud_Detection

# Project Overview
This project aims to build a machine learning model to detect fraudulent credit card transactions. Given an imbalanced dataset, we use techniques like data preprocessing, handling class imbalance, training classifiers, and evaluating performance with appropriate metrics such as precision, recall, and F1-score.

The project leverages classification algorithms like Random Forest and employs oversampling (SMOTE) to handle class imbalance in the dataset.

# Table of Contents
- Installation
- Dataset
- Approach
- Model Training
- Results
- Evaluation
- Visualizations

# Approach
Steps followed in the project:
- Data Preprocessing:

Dropped irrelevant columns like Time.
Checked and handled missing values.
Scaled features using StandardScaler for better model performance.
- Handling Class Imbalance:

The dataset is highly imbalanced, with very few fraudulent transactions.
Used SMOTE (Synthetic Minority Over-sampling Technique) to oversample the minority class (fraudulent transactions).
- Model Training:

Trained a Random Forest Classifier.
Used train-test split to separate training and testing data.
Applied predict_proba() to get the probabilities for fraudulent transactions.
- Evaluation Metrics:

Calculated Precision, Recall, F1-score, and Accuracy.
Plotted a Confusion Matrix to visualize classification results.
Generated Precision-Recall and ROC Curves to assess model performance.
