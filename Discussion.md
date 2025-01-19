Introduction
This study focuses on the application of various sampling techniques to an imbalanced dataset (Credit Card Fraud Detection) and evaluates their performance on different machine learning models. 
The goal is to determine which sampling technique yields the highest accuracy for each model.

Dataset Overview

Source: Creditcard_data.csv

Imbalance: The dataset contains two classes:

Class 0: Non-fraudulent transactions (majority class)

Class 1: Fraudulent transactions (minority class)

Steps Performed

Data Preprocessing:

The dataset was loaded, and features (X) were separated from the target variable (y).

The Synthetic Minority Oversampling Technique (SMOTE) was applied to balance the dataset.

Sample Size Calculation:

Using statistical formulas for margin of error, confidence level (95%), and population proportions, sample sizes were calculated for:

Random Sampling

Stratified Sampling

Cluster Sampling

Sampling Techniques Implemented:

Random Sampling: Data was sampled uniformly without considering class labels.

Stratified Sampling: Data was sampled proportionally within each class to preserve the class distribution.

Systematic Sampling: Every k-th record was selected, ensuring class balance.

Cluster Sampling: Data was divided into clusters based on the Time feature, and random clusters were selected.

Bootstrap Sampling: Sampling with replacement was applied to create multiple datasets.

Machine Learning Models Evaluated:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

Gradient Boosting Classifier

Model Training and Evaluation:

Each sampling technique was applied to train the models, and their accuracy was evaluated on a test set.

Accuracy was compared across all sampling techniques for each model.
