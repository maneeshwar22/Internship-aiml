Machine Learning Projects

This repository contains several introductory machine learning projects implemented in Python using libraries like scikit-learn, pandas, matplotlib, and seaborn.

 Contents:-

Titanic Survival Prediction – Logistic Regression on Titanic dataset
House Price Prediction – Linear Regression with synthetic data
Diabetes Prediction – Logistic Regression on Pima Indians dataset
Handwritten Digit Recognition – Support Vector Machine (SVM) on Digits dataset
1. Titanic Survival Prediction

Dataset: Built-in from Seaborn (sns.load_dataset('titanic'))
Model: Logistic Regression
Features: pclass, sex, age, fare
Target: survived

Evaluation:

Accuracy: ~75%
Classification Report: Balanced performance between precision and recall
Visualization: Confusion Matrix using seaborn heatmap

2.  House Price Prediction

Dataset: Manually created dataset (area vs. price)
Model: Linear Regression
Feature: Area (sq. ft)
Target: Price

Evaluation:

Mean Squared Error: ~18,297,301
R² Score: 0.999 – Very high accuracy due to simple, linear data
Prediction Example:

Area: 1700 sq. ft → Predicted Price: ₹336,126
Visualization: Scatter plot with regression line

3. Diabetes Prediction

Dataset: Pima Indians Diabetes Dataset
Source: UCI ML Repository
Model: Logistic Regression
Features: Clinical and biological parameters (e.g., glucose, insulin, age)
Target: Outcome (0 = No diabetes, 1 = Diabetes)

Evaluation:

Accuracy: ~74.6%
Confusion Matrix: 78 true negatives, 37 true positives
Classification Report: Balanced performance with slight drop in recall for positives


4. 🔢Handwritten Digit Recognition

Dataset: Digits dataset from sklearn.datasets
Model: Support Vector Classifier (SVC) with RBF kernel
Features: 64 pixel values (8x8 image)
Target: Digits 0–9

Evaluation:

Accuracy: ~99%
Excellent precision and recall for all digits
Visualization: Prediction of 10 digits with actual grayscale image display

