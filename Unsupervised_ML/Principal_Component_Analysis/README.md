# principal-component-analysis-ML-Model
PCA-based dimensionality reduction with variance analysis and component visualization.
# Principal Component Analysis (PCA) – Dimensionality Reduction Project
A machine learning project demonstrating **Principal Component Analysis (PCA)** for reducing high-dimensional data into fewer principal components while preserving maximum variance.

---

##  Project Objective
The goal of this project is to:

- Perform **dimensionality reduction** using PCA  
- Visualize the contribution of each principal component  
- Understand variance explained by components  
- Plot transformed data in reduced dimensions  
- Improve model performance by reducing noise  

---

##  What is PCA?
**PCA (Principal Component Analysis)** is an unsupervised method used to:

- Reduce the number of features  
- Remove multicollinearity  
- Keep only the most important variance from the data  
- Improve training speed and simplify datasets  

PCA finds new axes called **Principal Components**, ranked by how much variance they explain.


---

#  Technologies Used

Python

NumPy

Pandas

Scikit-Learn

Matplotlib

Seaborn

##  Machine Learning Workflow

###  Import Libraries
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.preprocessing import StandardScaler
from sklearn.decomposition import PCA
