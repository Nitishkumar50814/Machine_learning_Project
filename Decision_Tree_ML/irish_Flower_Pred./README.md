# Decision-Tree-On-irish_data
Machine learning model using Decision Tree on the Iris dataset

# Iris Flower Classification using Decision Tree
### Machine Learning • Classification • Scikit-Learn

This project uses a **Decision Tree Classifier** to classify Iris flowers into three species:
- Setosa  
- Versicolor  
- Virginica  

The Iris dataset is a classic dataset used in machine learning to understand classification algorithms.

---

##  1. Project Objective
To train a Decision Tree model on the **Iris dataset** and accurately predict the species of a flower based on its features.

---

##  2. Dataset Features
The Iris dataset contains the following features:

- **Sepal Length**
- **Sepal Width**
- **Petal Length**
- **Petal Width**
- **Species** (target)

There are **150 samples** and **3 classes**.

---
# 3. Technologies Used
- **Python**
- **Pandas**
- **Scikit-Learn**
- **Jupyter Notebook**

##  4. Machine Learning Workflow

### ✔️ Import Libraries
```python
import pandas as pd
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeClassifier
from sklearn.metrics import accuracy_score
