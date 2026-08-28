# Random Forest Classifier – Codveda Machine Learning Internship

## 📌 Project Overview

This project is part of the **Codveda Machine Learning Internship – Level 3**. The objective of this task is to implement a **Random Forest Classifier** for solving a supervised classification problem.

Random Forest is an ensemble machine learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## 🎯 Objectives

The main objectives of this task are:

* Load and explore the dataset
* Perform data preprocessing
* Select features and the target variable
* Split the dataset into training and testing sets
* Train a Random Forest Classification model
* Evaluate the model using classification metrics
* Perform cross-validation
* Analyze the model's performance

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Scikit-learn** – Machine learning and evaluation
* **Jupyter Notebook** – Development environment

---

## 🔄 Workflow

### 1. Data Loading

The dataset was loaded using Pandas and inspected to understand its structure, features, data types, and target variable.

### 2. Data Exploration

Exploratory analysis was performed to examine:

* Dataset dimensions
* Data types
* Missing values
* Class distribution
* Feature characteristics

### 3. Data Preprocessing

The necessary preprocessing steps were performed to prepare the dataset for machine learning.

### 4. Feature and Target Selection

The independent variables were selected as the input features (`X`), while the categorical variable to be predicted was selected as the target (`y`).

### 5. Train-Test Split

The dataset was divided into training and testing sets. The training data was used to train the model, while the testing data was used to evaluate its performance on unseen data.

### 6. Random Forest Model

A **Random Forest Classifier** was trained using multiple decision trees. The ensemble approach helps improve generalization and provides more robust predictions than a single decision tree.

### 7. Model Evaluation

The trained model was evaluated using:

* **Accuracy**
* **Precision**
* **Recall**
* **F1 Score**
* **Confusion Matrix**

### 8. Cross-Validation

Cross-validation was performed to assess the model's performance across multiple subsets of the dataset and obtain a more reliable estimate of its generalization performance.

---

## 📊 Model Evaluation

The Random Forest model was evaluated using standard classification metrics.

### Accuracy

Measures the proportion of correctly classified observations out of all observations.

### Precision

Measures how many of the observations predicted as positive actually belong to the positive class.

### Recall

Measures how many of the actual positive observations were correctly identified by the model.

### F1 Score

The F1 score is the harmonic mean of precision and recall and provides a balanced measure when both metrics are important.

### Confusion Matrix

The confusion matrix provides a detailed view of correct and incorrect predictions for each class.

---

## 🔁 Cross-Validation

K-Fold Cross-Validation was used to evaluate the consistency of the Random Forest model.

The dataset was divided into multiple folds, with the model trained and evaluated multiple times using different training and validation subsets.

The **mean cross-validation F1 score** was used as an additional measure of model performance.

---


## 📈 Key Outcome

A **Random Forest Classifier** was successfully implemented for the classification task. The model was trained and evaluated using multiple performance metrics, followed by cross-validation to assess its reliability and generalization ability.

---

## 📚 Internship Details

**Program:** Codveda Machine Learning Internship
**Level:** Level 3
**Task:** Random Forest Classification

---

## 👩‍💻 Author

**Nikitha.S**

GitHub: **Nikitha-aiml**
