## Overview

This project performs a comprehensive comparison of multiple Machine Learning classification algorithms on a structured dataset.

The objective is to identify the best-performing model using proper validation techniques including:
- Train-Test Split
- Cross Validation
- Confusion Matrix
- ROC Curve
- Accuracy Comparison
---

## Algorithms Implemented

The following models were trained and evaluated:

- Logistic Regression
- Ridge Classifier
- Decision Tree
- Random Forest
- Extra Trees
- Bagging Classifier
- AdaBoost
- Gradient Boosting
---

## Model Comparison Results

After training across all algorithms, the models were ranked based on accuracy.

**Best Performing Model:** Random Forest  
**Final Accuracy:** ~89.5%  

Ensemble methods (Random Forest, Bagging, Extra Trees) significantly outperformed linear models, indicating non-linear relationships in the dataset.
---

## Evaluation Metrics Used

- Accuracy Score
- Classification Report (Precision, Recall, F1-score)
- Confusion Matrix
- ROC Curve & AUC Score
- Cross-Validation
---

## Project Workflow
1. Data Loading
2. Data Preprocessing
   - Handling categorical variables
   - Feature scaling (where required)
3. Train-Test Split
4. Model Training
5. Model Comparison
6. Performance Visualization
7. Final Model Selection
---

## Visualizations Included
- Accuracy Comparison Table
- Confusion Matrix (Best Model)
- ROC Curve (Best Model)
- Feature Importance (Tree-Based Models)
---
