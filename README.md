Breast Cancer
Problem Statement
Breast cancer is one of the most common and life-threatening diseases. Early and accurate detection is crucial for effective treatment. The goal of this project is to develop a machine learning model that can accurately classify tumors as benign or malignant based on various cell nucleus features extracted from medical images. This classification problem is a supervised binary classification task, where the model learns patterns from labeled data to make predictions on unseen data.

Objectives
To build a machine learning model to classify tumors as benign or malignant
To compare the performance of Random Forest and XGBoost algorithms
To evaluate models using holdout validation and k-fold cross-validation
To analyze feature importance and identify key predictors
To understand the impact of feature relationships and correlations on model performance
Dataset Description
The dataset contains features computed from digitized images of breast mass cell nuclei Each sample represents measurements of a tumor Target variable:

0 → Benign
1 → Malignant
The dataset consists of three types of features:

Mean Features
radius_mean
texture_mean
perimeter_mean
area_mean
smoothness_mean
compactness_mean
concavity_mean
concave points_mean
symmetry_mean
fractal_dimension_mean
Standard Error Features (_se)
radius_se
texture_se
perimeter_se
area_se
smoothness_se
compactness_se
concavity_se
concave points_se
symmetry_se
fractal_dimension_se
Worst Features (_worst)
radius_worst
texture_worst
perimeter_worst
area_worst
smoothness_worst
compactness_worst
concavity_worst
concave points_worst
symmetry_worst
fractal_dimension_worst
Target Variable
diagnosis
0 → Benign
1 → Malignant
