PowerCo Churn Prediction Project
This repository contains the code and analysis for the PowerCo Churn Prediction project, where we predict customer churn using machine learning techniques. The Random Forest Classifier achieved an impressive 85% accuracy, demonstrating its effectiveness in handling this classification problem.

Table of Contents
Project Overview
Dataset
Methodology
Results
Technologies Used
How to Use
Future Work
Acknowledgments
Project Overview
Customer churn is a significant challenge in the energy sector, including for companies like PowerCo. Retaining customers is more cost-effective than acquiring new ones. This project aims to predict whether a customer will churn based on their historical behavior and demographic attributes.

Dataset
The dataset contains anonymized customer information, including:

Demographics (e.g., age, income)
Energy consumption patterns
Contract and subscription details
Customer service interactions
Target Variable:

Churn: A binary variable indicating whether a customer has churned (1) or not (0).
Methodology
Data Preprocessing:

Handled missing values.
Encoded categorical variables using techniques like One-Hot Encoding and Label Encoding.
Scaled numerical features for better model performance.
Exploratory Data Analysis (EDA):

Identified trends, patterns, and correlations in the dataset.
Visualized churn distribution and feature importance.
Modeling:

Built several machine learning models (Logistic Regression, Decision Tree, SVM, etc.).
Fine-tuned the Random Forest Classifier, which performed the best with an accuracy of 85%.
Evaluation:

Used metrics such as accuracy, precision, recall, F1-score, and the confusion matrix to assess performance.
Results
The Random Forest Classifier was the most effective model, achieving:

Accuracy: 85%
Precision: High precision in identifying churners.
Recall: Balanced recall for both churners and non-churners.
Feature Importance: Key features influencing churn included contract type, customer service calls, and energy usage patterns.
Technologies Used
Python: Programming language for data analysis and modeling.
Libraries:
pandas, numpy for data manipulation
matplotlib, seaborn for visualization
scikit-learn for machine learning models
imbalanced-learn for handling class imbalance
