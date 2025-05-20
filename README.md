# Nested Cross-Validation for Breast Cancer Diagnosis

This project applies **nested cross-validation** to identify the best-performing classification model and its optimal hyperparameters for predicting breast cancer malignancy using the Wisconsin Diagnostic Breast Cancer dataset.

**Key Highlights**:
- Compared SVM, KNN, Decision Tree, and Logistic Regression using recall as the primary metric
- Performed nested cross-validation to prevent overfitting during hyperparameter tuning
- Selected the best model and fine-tuned it using GridSearchCV
- Evaluated final model performance on a held-out test set

**Dataset**:  
[UCI Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))

**Goal**:  
Maximize recall to better capture high-risk (malignant) cases and minimize false negatives.

**Tools**:  
Python, scikit-learn, pandas, numpy, matplotlib

**Nested Cross-validation Framework**:  
<img width="675" alt="image" src="https://github.com/user-attachments/assets/fc1861fd-a720-40d3-a4cc-0e5cbb7b217a" />
