# Parkinson-s-Disease-Detection
Overview

This project applies Support Vector Machine (SVM) to classify whether a patient has Parkinson's disease based on medical voice measurements.

Technologies Used

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

Machine Learning Model: Support Vector Machine (SVM)

Data Processing: Min-Max Scaling, Standard Scaling

Dataset Details

Dataset Name: Parkinson's Disease Detection Dataset

Features: Acoustic voice measurements

Target Variable: status (1 = Parkinson’s, 0 = Healthy)

Objective: Predict Parkinson’s disease based on voice features.

Steps to Implement

1. Dataset Exploration

Load dataset using pandas

Display first few rows using .head()

Check for missing values and data types using .info() and .describe()

Perform Exploratory Data Analysis (EDA):

Use histograms and box plots to analyze numerical feature distributions

Use correlation heatmap to examine variable relationships

2. Data Preprocessing

Handle missing values (if any)

Standardize numerical features using Min-Max Scaling or Standard Scaling

Split dataset into 80% training and 20% testing sets

3. Implementing Support Vector Machine (SVM)

Train SVM model using Scikit-learn's SVC

Use acoustic features as independent variables

Experiment with different kernel functions:

Linear

Radial Basis Function (RBF)

Polynomial

Sigmoid

Tune hyperparameters C (regularization parameter) and gamma for better performance

4. Model Evaluation

Predict whether a person has Parkinson’s disease or not

Evaluate model performance using:

Accuracy Score

Confusion Matrix

Precision, Recall, and F1 Score

ROC Curve and AUC Score

Visualize Confusion Matrix and ROC Curve
