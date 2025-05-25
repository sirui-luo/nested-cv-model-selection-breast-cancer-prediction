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

---------------------------------------------------------
**Nested Cross-validation Framework**:  
<img width="1022" alt="image" src="https://github.com/user-attachments/assets/dc57e757-c051-47e3-ae43-927e70781739" />

**Model Evaluation (SVM)**:  
#### Confusion matrix
<img width="506" alt="image" src="https://github.com/user-attachments/assets/b1405db6-66f7-46dc-86c1-9e399f7cafb5" />

#### ROC
<img width="709" alt="image" src="https://github.com/user-attachments/assets/658818dc-d321-4f61-a170-d0affe6e677f" />
