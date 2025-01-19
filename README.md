# Sampling_assignment
README for Credit Card Fraud Detection Using Sampling Techniques

Overview

This project aims to detect credit card fraud using machine learning models applied to a dataset with imbalanced class distribution. To address the imbalance, Synthetic Minority Oversampling Technique (SMOTE) was used to balance the dataset, followed by the application of five sampling techniques. These techniques were evaluated across five machine learning models to determine the best combination for achieving the highest accuracy.

Dataset

The dataset used for this project is publicly available at:
Creditcard_data.csv

Dataset Details

Features: Time, V1 through V28, Amount

Target Variable: Class (0 = Non-fraudulent, 1 = Fraudulent)

Imbalance: The dataset is highly imbalanced with only a small percentage of fraudulent transactions.

Methodology

1. Data Balancing

Technique Used: SMOTE

SMOTE was applied to generate synthetic samples for the minority class, creating a balanced dataset.

2. Sampling Techniques

Five sampling techniques were implemented to create subsets of the data:

Random Sampling: Randomly selects samples from the dataset.

Stratified Sampling: Ensures proportional representation of each class.

Systematic Sampling: Selects samples at regular intervals from the dataset.

Cluster Sampling: Divides the dataset into clusters based on the Time feature and samples clusters randomly.

Bootstrap Sampling: Samples with replacement to create multiple subsets.

3. Machine Learning Models

Five machine learning models were trained and evaluated:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

Gradient Boosting Classifier

4. Evaluation Metrics

The primary metric used to evaluate model performance was accuracy.

Results

Each sampling technique was evaluated with each machine learning model. The results were analyzed to determine the highest accuracy achieved by the sampling technique and model combination.

Findings

The combination of [sampling technique] and [model] produced the highest accuracy of [value]. Refer to the discussion file for detailed analysis.
