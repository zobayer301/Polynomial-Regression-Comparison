# Polynomial Regression Comparison

A Python implementation and comparison of **Simple Linear Regression** and **Polynomial Regression** using Scikit-Learn. This project demonstrates how polynomial feature transformation enables linear models to capture non-linear relationships more effectively.

---

## Overview

Linear Regression performs well when the relationship between variables is approximately linear. However, many real-world datasets exhibit non-linear patterns.

This project generates a synthetic quadratic dataset and compares:

* Simple Linear Regression
* Polynomial Regression (Degree 2)
* Polynomial Regression (Degree 3)
* Pipeline Concepts

The models are evaluated using the **R² score**, and the fitted curves are visualized to illustrate the improvement achieved by polynomial features.

---

## Features

* Synthetic quadratic dataset generation
* Train-test split
* Simple Linear Regression model
* Polynomial Regression with multiple degrees
* Model performance evaluation
* Data visualization
* Comparison of regression curves

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---



## Workflow

1. Generate a quadratic dataset.
2. Split the dataset into training and testing sets.
3. Train a Simple Linear Regression model.
4. Apply polynomial feature transformation.
5. Train Polynomial Regression models.
6. Evaluate model performance using R² score.
7. Visualize the fitted curves.
8. Pipeline Concepts

---


## Libraries

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.preprocessing import PolynomialFeatures
from sklearn.metrics import r2_score
```

---

## Model Evaluation

Performance is measured using the coefficient of determination (**R² Score**).

* Simple Linear Regression
* Polynomial Regression (Degree 2)
* Polynomial Regression (Degree 3)

Polynomial Regression generally provides a better fit for non-linear data and achieves higher R² scores.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/zobayer301/Polynomial-Regression-Comparison.git
```

Move into the project directory:

```bash
cd Polynomial-Regression-Comparison
```

Install the required packages:

```bash
pip install numpy pandas matplotlib scikit-learn
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
PolynomialLinearRegression.ipynb
```

---

## Key Concepts Covered

* Linear Regression
* Polynomial Regression
* Feature Engineering
* Train-Test Split
* Model Evaluation
* R² Score
* Data Visualization

---



## Author
**Md. Zobayer Chowdhury**
- Computer Science and Engineering
- Interested in Data Science, Machine Learning, and Artificial Intelligence

## ⭐ If you found this project useful, consider giving it a star!
