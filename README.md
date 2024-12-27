Breast Cancer Classification using Random Forest

Overview
This project aims to classify breast cancer tumors as malignant or benign using the Breast Cancer Wisconsin (Diagnostic) Dataset. A Random Forest Classifier is used to build a robust and interpretable model for prediction. The dataset contains features extracted from digitized images of breast masses, making it suitable for machine learning tasks.

Features of the Dataset
The dataset includes the following:

Target Variable:
diagnosis: Malignant (M) or Benign (B).
Key Features:
radius_mean, texture_mean, perimeter_mean, area_mean, smoothness_mean, compactness_mean, concavity_mean, and concave points_mean.
Project Workflow
The project follows a structured workflow:

Data Import and Library Setup:
Import necessary Python libraries.
Load the dataset and preview its structure.
Data Cleaning:
Remove irrelevant columns (e.g., Unique ID).
Encode the target variable (diagnosis).
Handle missing values and ensure all features are numeric.
Data Preview:
Summarize the dataset and visualize key statistics.
Model Training and Testing:
Split the data into training and testing sets.
Train a Random Forest Classifier on the training data.
Evaluate model performance using metrics like accuracy, precision, recall, F1-score, and confusion matrix.
Feature Importance:
Visualize feature importance to identify key predictive features.
Setup Instructions
Prerequisites
Python 3.8 or higher
Required Python libraries:
pandas
numpy
seaborn
matplotlib
scikit-learn
