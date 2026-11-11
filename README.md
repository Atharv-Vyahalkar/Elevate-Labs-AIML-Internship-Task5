# Task 5: Decision Trees and Random Forests

## Overview
This project implements tree-based machine learning classification algorithms using Python and Scikit-learn. It focuses on understanding Decision Trees and Random Forests, analyzing overfitting, comparing model performance, and identifying important features using the Heart Disease dataset.

## Objective
- Understand Decision Tree classification.
- Visualize the structure of a Decision Tree.
- Analyze and control overfitting using tree depth.
- Implement a Random Forest classifier.
- Compare the performance of both models.
- Interpret feature importance.
- Evaluate models using cross-validation.

## Dataset
**Heart Disease Dataset**

The dataset contains medical attributes used to predict the presence of heart disease.

- **Target Variable:** `target`
- `0` – No Heart Disease
- `1` – Heart Disease

The dataset includes features such as:
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Maximum Heart Rate
- Exercise-Induced Angina
- ST Depression
- Other clinical attributes

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Models

### 1. Decision Tree Classifier
A Decision Tree classifier was trained using the Gini impurity criterion. Its structure was visualized to understand feature-based splitting and classification decisions.

### 2. Overfitting Analysis
Different maximum tree depths were tested to analyze the relationship between model complexity, training accuracy, and testing accuracy.

### 3. Random Forest Classifier
A Random Forest model with 100 decision trees was implemented. It combines predictions from multiple trees using majority voting.

## Model Evaluation
Both models were evaluated using:
- Training Accuracy
- Testing Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- 5-Fold Cross-Validation

## Feature Importance
Random Forest feature importance scores were calculated and visualized to identify which input features contributed most to the model's predictions.

## Results and Comparison
The Decision Tree and Random Forest models were compared based on their training accuracy, testing accuracy, and mean cross-validation accuracy.

The comparison helps evaluate the generalization performance of both algorithms and understand the advantages of ensemble learning.

## Project Outputs
- Decision Tree Visualization
- Decision Tree Confusion Matrix
- Overfitting Analysis Graph
- Random Forest Confusion Matrix
- Model Accuracy Comparison Graph
- Feature Importance Visualization
- Model Comparison Results CSV
- Feature Importance CSV

## Learning Outcomes
- Understanding tree-based classification algorithms.
- Learning how Decision Trees make predictions.
- Understanding Gini impurity and tree splitting.
- Identifying and controlling overfitting.
- Understanding ensemble learning and bagging.
- Comparing individual trees with Random Forests.
- Interpreting feature importance.
- Applying cross-validation for model evaluation.

## Conclusion
This task provided practical experience with Decision Tree and Random Forest classification algorithms. It demonstrated how controlling tree depth can help manage overfitting and how ensemble learning combines multiple decision trees to improve predictive performance. Feature importance and cross-validation provided additional insights into model behavior and reliability.