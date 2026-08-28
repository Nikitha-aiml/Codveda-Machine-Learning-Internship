# Linear Regression – Codveda Machine Learning Internship

## 📌 Project Overview

This project is part of the **Codveda Machine Learning Internship**.

The objective of this task is to build a **Simple Linear Regression model** using the Boston Housing dataset to predict the median value of owner-occupied homes based on the average number of rooms per dwelling.

The project covers:

- Loading and exploring the dataset
- Selecting the feature and target variable
- Splitting the dataset into training and testing sets
- Building a Linear Regression model
- Interpreting model coefficients
- Evaluating model performance
- Visualizing actual and predicted values
- Visualizing the regression line

---

## 📊 Dataset

The project uses the **Boston Housing dataset**.

The dataset contains information about housing characteristics and their relationship with median house values.

For this project, **RM (average number of rooms per dwelling)** is used as the independent variable, while **MEDV (median value of owner-occupied homes)** is used as the target variable.

### Features Used

- **RM** – Average number of rooms per dwelling
- **MEDV** – Median value of owner-occupied homes

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Dataset Loading and Exploration

The dataset was loaded and examined using:

- `head()`
- `shape`
- `info()`
- `describe()`

These steps were used to understand the structure and statistical characteristics of the dataset.

### 2. Data Analysis

The relationship between the number of rooms (`RM`) and median house value (`MEDV`) was explored using correlation analysis and visualization.

A scatter plot was created to observe the relationship between the two variables.

### 3. Feature and Target Selection

For this simple linear regression model:

```python
X = df[["RM"]]
y = df["MEDV"]
