# House Price Prediction Using Linear Regression

## 📌 Project Overview

This project is part of the **Codveda Machine Learning Internship – Level 1, Task 2**.

The objective of this task is to build a simple **Linear Regression model** to predict a continuous variable. In this project, the model predicts **median house values (MEDV)** using the **average number of rooms (RM)** as the input feature.

The project demonstrates the complete basic machine learning workflow, including data preprocessing, exploratory analysis, model training, prediction, evaluation, and visualization.

---

## 🎯 Objectives

- Load and inspect the house price dataset.
- Check and preprocess the data.
- Analyze the relationship between features and house prices.
- Build a Linear Regression model using scikit-learn.
- Interpret the model coefficient.
- Make predictions on unseen test data.
- Evaluate the model using **Mean Squared Error (MSE)** and **R-squared (R²)**.
- Visualize actual and predicted house values.

---

## 📂 Dataset

The dataset contains information about housing characteristics and median house values.

### Dataset Details

- **Number of observations:** 506
- **Number of variables:** 14
- **Missing values:** 0
- **Duplicate rows:** 0
- **Target variable:** `MEDV`
- **Predictor variable:** `RM`

### Important Variables

| Variable | Description |
|---|---|
| `RM` | Average number of rooms per dwelling |
| `MEDV` | Median value of owner-occupied homes |

Other variables in the dataset include crime rate, residential land proportion, industrial area proportion, accessibility, property tax rate, pupil-teacher ratio, and lower-status population percentage.

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

### 1. Data Loading

The dataset was loaded into a Pandas DataFrame and the structure of the data was inspected.

### 2. Data Preprocessing

The dataset was checked for:

- Missing values
- Duplicate rows
- Data types
- Statistical characteristics

No missing values or duplicate rows were found.

### 3. Exploratory Data Analysis

Correlation analysis was performed to understand the relationship between the input features and the target variable.

The `RM` feature showed a positive correlation with `MEDV`:

**Correlation between RM and MEDV: 0.6954**

This indicates that houses with a higher average number of rooms tend to have higher median values.

### 4. Feature and Target Selection

For simple linear regression:

- **Feature:** `RM`
- **Target:** `MEDV`

### 5. Train-Test Split

The dataset was divided into:

- **Training samples:** 404
- **Testing samples:** 102

The test size was set to 20%.

### 6. Model Training

A Linear Regression model from Scikit-learn was trained using the training data.

The resulting regression equation is:

**MEDV = -36.2463 + 9.3483 × RM**

### 7. Coefficient Interpretation

The coefficient of `RM` is **9.3483**.

This means that for every one-unit increase in the average number of rooms, the model predicts an increase of approximately **9.35 units** in median house value, on average.

The positive coefficient indicates a positive relationship between the number of rooms and house value.

---

## 📊 Model Evaluation

The model was evaluated using Mean Squared Error and R-squared.

| Metric | Result |
|---|---:|
| Mean Squared Error (MSE) | **46.1448** |
| R-squared (R²) | **0.3708** |

### Interpretation

The R² score of **0.3708** indicates that approximately **37.1% of the variation in median house values** is explained by the average number of rooms alone.

The moderate R² score is expected because house prices are influenced by several factors, while this project uses only one predictor variable.

---

## 📈 Visualizations

The project includes the following visualizations:

### RM vs MEDV

A scatter plot showing the relationship between the average number of rooms and median house value.

### Actual vs Predicted House Values

This visualization compares the actual house values with the values predicted by the regression model.

### Linear Regression Line

The regression line illustrates the positive relationship learned by the model between `RM` and `MEDV`.

---

## 🔍 Key Observations

- The dataset contains **506 observations and 14 variables**.
- No missing values or duplicate rows were found.
- `RM` has a strong positive correlation with `MEDV` (**0.6954**).
- The regression coefficient for `RM` is positive.
- House values generally increase as the average number of rooms increases.
- The model achieved an **R² score of 0.3708**.
- Using only one feature limits the model's ability to accurately predict house values.

---

## ✅ Conclusion

A simple Linear Regression model was successfully developed to predict median house values using the average number of rooms as the predictor.

The model identified a positive relationship between the number of rooms and house value. However, the R² score of **0.3708** shows that the number of rooms alone cannot fully explain house-price variation.

A future improvement would be to use **multiple linear regression with additional housing features**, which could potentially improve the prediction performance.

---

## 📁 Project Files

```text
Task-2-Linear-Regression/
│
├── Linear_Regression.ipynb
├── house_prediction.csv
└── README.md
