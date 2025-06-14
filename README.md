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
<img width="1026" alt="image" src="https://github.com/user-attachments/assets/8a559461-a379-4cb6-a4db-b358e560f1e9" />

**Model Evaluation (SVM)**:  
#### Confusion matrix
<img width="506" alt="image" src="https://github.com/user-attachments/assets/b1405db6-66f7-46dc-86c1-9e399f7cafb5" />

#### ROC
The ROC curve for the SVM model closely hugs the top-left corner, indicating excellent performance and strong capability to distinguish between the classes.

<img width="709" alt="image" src="https://github.com/user-attachments/assets/658818dc-d321-4f61-a170-d0affe6e677f" />

#### Lift Ratio Curve
In the top 50% of the ranked data, the model achieves a lift ratio greater than 2, meaning it captures at least twice the number of positive cases that a random selection would in the same proportion of the population.

<img width="695" alt="image" src="https://github.com/user-attachments/assets/72e355dd-f304-401c-aa4d-9b2a5813c271" />
