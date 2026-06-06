# 🏠 Real Estate House Price Prediction Using Supervised Learning

## 📌 Project Overview

This project focuses on predicting house prices using different Supervised Learning Regression techniques. The dataset was preprocessed, analyzed, and used to build multiple regression models. The performance of each model was evaluated and compared using various evaluation metrics and visualizations.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model building, model evaluation, polynomial regression, gradient descent optimization, and bias-variance analysis.

---

## 🎯 Objectives

* Understand the fundamentals of Supervised Learning.
* Perform data preprocessing and exploratory data analysis.
* Implement Simple Linear Regression.
* Implement Multiple Linear Regression.
* Implement Polynomial Regression.
* Evaluate model performance using regression metrics.
* Understand Gradient Descent Optimization techniques.
* Analyze Bias-Variance Trade-Off.
* Compare different regression models and identify the best-performing model.

---

## 📂 Dataset Information

**Dataset Name:** RealEstate_HousePrice_Dataset_4200.csv

The dataset contains various features related to residential properties and a target variable representing house prices.

---

# 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

# 📚 Libraries Used

```python
import pandas as pd
import numpy as np

import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.model_selection import train_test_split

from sklearn.linear_model import LinearRegression

from sklearn.preprocessing import PolynomialFeatures
from sklearn.preprocessing import StandardScaler

from sklearn.metrics import mean_squared_error
from sklearn.metrics import mean_absolute_error
from sklearn.metrics import r2_score
```

---

# 🔍 Project Workflow

## 1. Data Loading

* Imported dataset using Pandas.
* Displayed dataset structure and basic information.

## 2. Data Understanding

* Dataset Information
* Statistical Summary
* Data Types Analysis

## 3. Data Cleaning

* Missing Value Check
* Duplicate Value Check
* Duplicate Removal

## 4. Exploratory Data Analysis (EDA)

### Visualizations Performed

* Histogram Plot
* Correlation Heatmap
* Boxplot Analysis

### EDA Objectives

* Understand feature distributions.
* Identify relationships among variables.
* Detect potential outliers.

---

## 5. Outlier Treatment

Outliers were identified and treated using the IQR (Interquartile Range) method to improve model performance and stability.

---

## 6. Feature Scaling

StandardScaler was applied to normalize feature values and bring them to a similar scale.

---

# 🤖 Machine Learning Models Implemented

## Simple Linear Regression

* Implemented using a single independent variable.
* Visualized regression line.
* Interpreted slope and intercept.
* Validated regression assumptions.

### Evaluation Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score
* Adjusted R² Score

---

## Multiple Linear Regression

* Implemented using multiple features.
* Compared performance with Simple Linear Regression.
* Analyzed performance improvement.

---

## Polynomial Regression

* Implemented Polynomial Regression (Degree 2).
* Compared with Linear Regression.
* Performed visual and numerical comparisons.
* Analyzed overfitting and underfitting behavior.

---

# ⚙️ Gradient Descent Optimization

The following optimization techniques were studied and implemented:

## Batch Gradient Descent

* Uses the entire dataset for parameter updates.
* Stable convergence.
* Slower training process.

## Stochastic Gradient Descent (SGD)

* Uses one data point at a time.
* Faster updates.
* More fluctuations during convergence.

## Mini-Batch Gradient Descent

* Uses small batches of data.
* Balances speed and stability.
* Commonly used in practical machine learning applications.

---

# 📈 Model Evaluation Metrics

The models were evaluated using:

| Metric            | Purpose                                           |
| ----------------- | ------------------------------------------------- |
| MAE               | Average prediction error                          |
| MSE               | Squared prediction error                          |
| RMSE              | Error in original units                           |
| R² Score          | Measures goodness of fit                          |
| Adjusted R² Score | Adjusted performance measure considering features |

---

# 🧠 Concepts Covered

This project helped in understanding:

* Supervised Learning
* Regression Algorithms
* Simple Linear Regression
* Multiple Linear Regression
* Polynomial Regression
* Feature Scaling
* Outlier Treatment
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Gradient Descent Optimization
* Model Evaluation
* Bias-Variance Trade-Off
* Overfitting
* Underfitting

---

# 📊 Results

* Successfully trained and evaluated multiple regression models.
* Compared model performance using metrics and visualizations.
* Studied the impact of model complexity on prediction accuracy.
* Analyzed optimization techniques and convergence behavior.
* Identified the most suitable regression model based on performance.

---

# 🎓 Learning Outcomes

Through this project, the following skills were developed:

* Data preprocessing and cleaning
* Data visualization
* Regression modeling
* Performance evaluation
* Optimization techniques
* Model comparison and diagnostics
* Machine learning workflow implementation

---

# ✅ Conclusion

This project demonstrates the complete implementation of supervised learning techniques for house price prediction. Different regression models were developed, evaluated, and compared to understand their strengths and limitations. The project highlights the importance of data preprocessing, model evaluation, and optimization in building effective machine learning solutions.

---

## 👨‍💻 Author

**Student Name:** Gopi Gadara

**Course:** Supervised Learning Module

**Project:** Real Estate House Price Prediction Using Supervised Learning
