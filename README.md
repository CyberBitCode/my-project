# 🏥 Breast Cancer Classification

## Problem Statement
Breast cancer is one of the most common and life-threatening diseases. Early and accurate detection is crucial for effective treatment.
The goal of this project is to develop a machine learning model that can accurately classify tumors as benign or malignant based on various cell nucleus features extracted from medical images.
This classification problem is a supervised binary classification task, where the model learns patterns from labeled data to make predictions on unseen data.

## Models Used
- ✅ Random Forest — **96.49% accuracy**
- ✅ XGBoost

## Dataset
Wisconsin Breast Cancer Dataset — 569 samples, 30 features

## Key Results
| Model | Accuracy | Precision (Malignant) | Recall (Malignant) |
|---|---|---|---|
| Random Forest | 96.49% | 98% | 93% |

## Top Predictive Features
- area_worst
- concave points
- radius & perimeter

## Libraries Used
`pandas` `numpy` `scikit-learn` `matplotlib` `seaborn` `xgboost`

## Open in Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR-USERNAME/breast-cancer-detection/blob/main/breast_cancer_classification.ipynb)
