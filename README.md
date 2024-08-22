# Customer Churn Prediction

## Overview

This project focuses on predicting customer churn for a telecom company using machine learning techniques. Customer churn refers to the loss of customers, which can result from various factors such as dissatisfaction with services, pricing issues, or network quality. By predicting churn, the company can implement strategies to retain customers and reduce turnover.

## Key Features

- **Data Analysis and Preprocessing**: Initial data exploration revealed that the dataset is imbalanced, with more customers not churning than churning. The dataset was preprocessed by removing redundant features, encoding categorical variables, and scaling numerical features.
- **Model Training**: Multiple machine learning models were trained to predict churn, including Logistic Regression, Decision Tree, Random Forest, Support Vector Machines (SVM), and Gradient Boosting. 
- **Model Evaluation**: The models were evaluated using metrics such as accuracy, precision, recall, F1 score, and area under the ROC curve (AUC).
- **Best Performing Model**: The Gradient Boosting Classifier emerged as the best model, offering the highest performance in terms of accuracy and recall, particularly for identifying customers likely to churn.

## Methodology

1. **Data Exploration**: The dataset, sourced from Kaggle, was examined to understand the distribution of features and their correlation. Imbalanced classes were identified, leading to considerations for resampling.
2. **Data Preprocessing**: The data was cleaned by removing unnecessary features, encoding categorical variables, and scaling numerical data. Principal Component Analysis (PCA) was applied to explore the variance and structure of the dataset.
3. **Modeling**: Various classification models were trained and tested, including:
   - Logistic Regression (baseline)
   - Decision Tree
   - Random Forest
   - SVM with linear and RBF kernels
   - Gradient Boosting
4. **Model Evaluation**: The models were evaluated on their ability to accurately predict churn. The Gradient Boosting model showed the best performance, particularly in handling the imbalanced nature of the dataset.

## Findings and Insights

- **Model Performance**: Gradient Boosting outperformed other models with the highest accuracy, precision, and recall, making it the recommended model for predicting customer churn.
- **Challenges**: The imbalanced nature of the dataset posed challenges, particularly for the recall of the minority class (churn). Techniques like resampling (ADASYN) were explored but did not significantly improve performance.
- **Future Work**: Further improvements could include experimenting with additional resampling techniques, feature engineering, and trying other machine learning models such as ensemble methods or deep learning.

## Installation

1. **Clone the repository**: 
   ```bash
   git clone https://github.com/anzanthapa/2021_ChurnPrediction.git
