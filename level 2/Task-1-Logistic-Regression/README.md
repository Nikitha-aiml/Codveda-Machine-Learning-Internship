# Logistic Regression – Codveda Machine Learning Internship

## 📌 Project Overview

This project is part of the **Codveda Machine Learning Internship – Level 1**. The objective of this task is to implement **Logistic Regression** for a supervised classification problem.

Logistic Regression is a classification algorithm that estimates the probability of an observation belonging to a particular class. It is commonly used for binary classification problems.

---

## 🎯 Objectives

The main objectives of this task are:

* Load and explore the dataset
* Perform necessary data preprocessing
* Select the features and target variable
* Split the dataset into training and testing sets
* Scale numerical features where required
* Train a Logistic Regression model
* Make predictions on unseen data
* Evaluate the model using classification metrics
* Analyze the model's performance

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Scikit-learn** – Machine learning and model evaluation
* **Jupyter Notebook** – Development environment

---

## 🔄 Workflow

### 1. Data Loading

The dataset was loaded using Pandas and examined to understand its structure, features, data types, and target variable.

### 2. Data Exploration

Exploratory data analysis was performed to examine:

* Dataset dimensions
* Data types
* Missing values
* Duplicate records
* Class distribution
* Feature characteristics

### 3. Data Preprocessing

The required preprocessing steps were performed to prepare the dataset for Logistic Regression.

Numerical features were scaled where necessary to ensure that features with different ranges did not disproportionately influence the model.

### 4. Feature and Target Selection

The independent variables were selected as input features (`X`), while the categorical variable to be predicted was selected as the target (`y`).

### 5. Train-Test Split

The dataset was divided into training and testing sets. The training data was used to build the model, while the test data was used to evaluate its performance on unseen observations.

### 6. Model Training

A **Logistic Regression** classifier from Scikit-learn was trained using the training dataset.

### 7. Prediction

The trained model was used to predict the class labels and probabilities for the test dataset.

### 8. Model Evaluation

The model was evaluated using classification metrics such as:

* **Accuracy**
* **Precision**
* **Recall**
* **F1 Score**
* **ROC-AUC**

### 9. Visualization

Appropriate visualizations were used to understand the model's classification performance and the relationship between predicted and actual classes.

---

## 📊 Model Evaluation

### Accuracy

Measures the proportion of correctly classified observations out of the total number of observations.

### Precision

Measures how many of the observations predicted as positive are actually positive.

### Recall

Measures how many of the actual positive observations were correctly identified by the model.

### F1 Score

The harmonic mean of precision and recall, providing a balanced measure of classification performance.

### ROC-AUC

The Area Under the Receiver Operating Characteristic Curve measures the model's ability to distinguish between the classes. A higher AUC generally indicates better classification performance.

---

## 📈 Key Outcome

A **Logistic Regression** classification model was successfully implemented and evaluated on the dataset.

The model was trained using the prepared features and tested on unseen data. Multiple classification metrics were used to assess its predictive performance.

---


## 📚 Internship Details

**Program:** Codveda Machine Learning Internship
**Level:** Level 2
**Task:** Logistic Regression

---

## 👩‍💻 Author

**Nikitha.S**

GitHub: **Nikitha-aiml**

