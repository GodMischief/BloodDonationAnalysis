# Blood Donation Prediction

This repository contains a machine learning project aimed at predicting whether a person will donate blood in a specific month based on previous donation patterns. The project leverages several classification algorithms to determine the best performing model.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Data](#data)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction

Blood donation is a vital process that helps save countless lives. However, predicting whether a person will donate blood can be challenging. This project explores various machine learning models to predict blood donation behavior based on past data. The models used include Logistic Regression, Support Vector Machine (SVM), Random Forest, Decision Tree, and Multi-Layer Perceptron (MLP).

## Installation

To get started with this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/your-username/blood-donation-prediction.git
cd blood-donation-prediction
pip install -r requirements.txt
```

## Data

The dataset used in this project includes information about previous blood donations. The data is split into training and testing sets.
- Training Data: Contains features like the number of months since the last donation, total volume donated, and more.
- Testing Data: Used to evaluate the performance of the models.

The data files are named as:
- blood-train.csv
- blood-test.csv

# Feature Engineering

Feature engineering plays a crucial role in enhancing the model's performance. In this project, several features were engineered, including:
-Donating for: Calculated as the difference between "Months since First Donation" and "Months since Last Donation."

Features with high correlations were dropped to avoid multicollinearity. For example, the Total Volume Donated (c.c.) feature was removed due to its high correlation with other features.

# Modeling

Multiple classification models were applied to the dataset:
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier
- Decision Tree Classifier
- Multi-Layer Perceptron (MLP)
  
Each model was evaluated based on the following metrics:
- Accuracy Score
- ROC AUC Score
- Confusion Matrix

# Results
  
The performance of each model was evaluated, and the results are as follows:

- Logistic Regression:
-- Accuracy Score: XX.XX
-- ROC AUC Score: XX.XX

- Support Vector Machine:
-- Accuracy Score: XX.XX
-- ROC AUC Score: XX.XX

- Random Forest:
-- Accuracy Score: XX.XX
-- ROC AUC Score: XX.XX

- Decision Tree:
-- Accuracy Score: XX.XX
-- ROC AUC Score: XX.XX
  
- MLP Classifier:
-- Accuracy Score: XX.XX
-- ROC AUC Score: XX.XX

# Conclusion

This project demonstrates the effectiveness of various machine learning models in predicting blood donation behavior. The results indicate that [insert the best performing model] performed the best, making it a strong candidate for real-world implementation in blood donation prediction systems.
