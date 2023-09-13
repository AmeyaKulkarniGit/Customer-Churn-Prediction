# Customer Churn Prediction using Machine Learning

## Table of Contents

- [Overview](#overview)
- [Project Goals](#project-goals)
- [Dataset](#dataset)
- [Models](#models)
- [Evaluation](#evaluation)

## Overview

Customer churn, the phenomenon where customers stop using a company's products or services, is a critical challenge for businesses across various industries. It not only impacts revenue but also raises questions about customer satisfaction and loyalty. In response to this challenge, I developed a machine learning-based customer churn prediction project to help businesses understand, anticipate, and reduce customer churn rates.

## Project Goals

The primary goals of this project are as follows:

1. **Churn Prediction**: Develop accurate machine learning models to predict customer churn based on historical data and customer interactions.

2. **Customer Insights**: Gain insights into the key factors that influence customer churn, enabling businesses to take proactive measures to retain valuable customers.

3. **Model Comparison**: Compare the performance of two different machine learning approaches: logistic regression and artificial neural networks (ANNs). Determine which model provides the best predictive power for this specific problem.

## Technologies and Libraries Used

- Python
- NumPy
- Scikit-learn
- TensorFlow (for ANNs)
- Pandas
- Matplotlib/Seaborn

## Dataset

I sourced our dataset from Kaggle, which includes a wide range of features related to customer behavior, interactions, and historical data. The dataset has undergone rigorous data cleaning and preprocessing to prepare it for model development. You can find the dataset [here](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)


## Models

My project employs two machine learning models for customer churn prediction:

1. **Logistic Regression**:
   - Logistic regression is a simple yet interpretable model that allows us to understand the significance of different features in predicting churn.

2. **Artificial Neural Network (ANN)**:
   - ANNs are used for capturing complex patterns and relationships in the data, potentially achieving higher predictive accuracy.

## Evaluation

For evaluating the predictions of the Machine Learning model / Artificial Neural Network, I carried out a creation of a Classification Report as well as a Confusion matrix was created to visulaise the results better.
