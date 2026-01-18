# Logistic-Regression-On-Heart-Disease-Prediction.
A simple ML project to predict heart disease using Logistic Regression.
<!-- Title: largest font -->
# ❤️ Heart Disease Prediction using Logistic Regression

<!-- Slightly smaller subtitle -->
## A simple, beginner-friendly ML project to predict heart disease

---

<!-- Large section header -->
###  Project Summary
This project builds a **Logistic Regression** model to predict whether a person has heart disease using medical features.  
It includes data cleaning, feature selection, model training, and basic evaluation.

---

<!-- Bigger subheading feel -->
####  Key Features
- Clean, beginner-friendly code (Jupyter Notebook)  
- Data preprocessing and categorical encoding  
- Train/Test split and model evaluation  
- Clear results and suggestions for improvements

---

<!-- Medium heading -->
###  Dataset Features (used in model)
- **age** — Age of the person  
- **ldl** — LDL cholesterol  
- **tobacco** — Tobacco use  
- **adiposity** — Body fat measure  
- **famhist** — Family history (Present / Absent)  
- **typea** — Type-A behavior  
- **obesity** — Obesity index  
- **alcohol** — Alcohol consumption  
- **chd** — Target: 1 = Heart Disease, 0 = No




##  Model Used
### Logistic Regression
Why this model?
Easy to understand
Works well for binary classification
Fast and efficient
Perfect for beginners

##  Model Results

Training Accuracy: 73.0%
Testing Accuracy: 73.0%
(Replace with your actual output).

##  Technologies Used
Python,
Pandas,
NumPy,
Matplotlib,
Scikit-Learn.

###  Model
**Logistic Regression** — chosen for its simplicity and interpretability.

**Model Code (important part)**:
```python
from sklearn.linear_model import LogisticRegression
model = LogisticRegression(C=100, penalty='l1', solver='liblinear')
model.fit(X_train, y_train)
print("Train Acc:", model.score(X_train, y_train))
print("Test Acc:", model.score(X_test, y_test))


