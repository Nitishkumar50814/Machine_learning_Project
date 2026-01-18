# LDA-Feature-reduction-project
Supervised feature reduction using LDA with visualization and model training.


# Linear Discriminant Analysis (LDA) – Classification Project
A machine learning project demonstrating **Linear Discriminant Analysis (LDA)** for dimensionality reduction and classification.  
LDA is a supervised algorithm used to maximize class separation and reduce the feature space while maintaining class information.

---

##  Project Objective
The goal of this project is to:

- Apply **LDA for dimensionality reduction**
- Improve class separability
- Build a classification model using transformed features
- Evaluate model performance
- Visualize LDA components

---

##  Dataset Information
This project uses a labeled dataset for classification.  
Each sample contains:
- Multiple input features  
- Target class labels  
- LDA reduces features → builds a classifier → measures accuracy  

*(Replace this section with your actual dataset name if needed)*

---

##  What is LDA?
**Linear Discriminant Analysis (LDA)** is used for:
- Supervised dimensionality reduction  
- Maximizing separation between multiple classes  
- Improving performance of ML models when many features exist  

LDA finds the best axes that clearly separate classes.

---
# Model Performance

Accuracy : 95%

# Technologies Used

Python

Pandas

NumPy

Scikit-Learn

Matplotlib / Seaborn

##  Machine Learning Workflow

###  Import Libraries
```python
import numpy as np
import pandas as pd
from sklearn.discriminant_analysis import LinearDiscriminantAnalysis
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import accuracy_score, classification_report, confusion_matrix
