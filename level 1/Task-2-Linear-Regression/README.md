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

For this Simple Linear Regression model:

```python
X = df[["RM"]]
y = df["MEDV"]
RM is the independent variable.
MEDV is the dependent/target variable.

4. Train-Test Split

The dataset was divided into training and testing sets using an 80:20 ratio.
Training data: 80%
Testing data: 20%
A fixed random_state was used to make the results reproducible.

5. Model Building

A Linear Regression model from Scikit-learn was trained using the training data.
The fitted model produced the following regression equation:
MEDV = -36.2463 + 9.3483 × RM
The positive coefficient indicates that an increase in the average number of rooms is associated with an increase in the predicted median house value.

6. Model Prediction

The trained model was used to predict house values for the test dataset.

7. Model Evaluation

The model was evaluated using:
Mean Squared Error (MSE)
R-squared (R²)
Results
Mean Squared Error (MSE): 46.1448
R-squared (R²): 0.3708
Interpretation
The R² score of approximately 0.3708 indicates that the average number of rooms (RM) alone explains about 37.1% of the variation in median house values.
This also indicates that other housing and socioeconomic factors influence house prices and are not captured by this simple one-feature model.

📈 Visualizations

The project includes the following visualizations:
1. RM vs MEDV Scatter Plot
Shows the relationship between the average number of rooms and median house value.
2. Actual vs Predicted Values
Compares the actual house values with the values predicted by the Linear Regression model.
3. Regression Line
Shows the fitted linear regression line between RM and MEDV.

🔍 Key Observations
There is a positive relationship between the average number of rooms and median house value.
The regression coefficient for RM is positive.
An increase in the average number of rooms is associated with an increase in predicted house value.
The R² score of 0.3708 shows that RM alone does not fully explain house-price variation.
Other factors are likely required to build a more accurate house-price prediction model.

📁 Project Structure
Task-2-Linear-Regression/
│
├── Linear_Regression.ipynb
├── housing.csv
└── README.md

Conclusion

A Simple Linear Regression model was successfully developed to predict median house values using the average number of rooms per dwelling.
The model achieved an MSE of 46.1448 and an R² score of 0.3708.
While RM has a positive relationship with house prices, using a single feature limits the predictive capability of the model. Additional housing and socioeconomic features could be incorporated in future models to improve prediction performance.

👩‍💻 Internship

Codveda Technologies – Machine Learning Internship

Task: Linear Regression

Level: Level 1
