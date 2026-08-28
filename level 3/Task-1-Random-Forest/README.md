# Level 3 - Task 1: Random Forest Classifier

## 📌 Project Overview

This project is part of my **Codveda Machine Learning Internship - Level 3 (Advanced)**.

The objective of this task is to build a **Random Forest Classifier** to predict customer churn using a customer churn dataset.

The project covers data preprocessing, model training, hyperparameter tuning, cross-validation, classification evaluation, and feature importance analysis.

---

## 🎯 Objectives

- Explore and understand the customer churn dataset.
- Preprocess numerical and categorical features.
- Build a Random Forest classification model.
- Evaluate the model using classification metrics.
- Perform cross-validation.
- Tune Random Forest hyperparameters using GridSearchCV.
- Compare the initial and tuned models.
- Analyze feature importance.
- Identify the factors that contribute most to customer churn.

---

## 📂 Dataset

**Dataset:** `churn-bigml-80.csv`

The dataset contains **2,666 customer records and 20 columns**.

### Target Variable

- `Churn` - Indicates whether a customer has churned (`True`) or not (`False`).

### Main Features

- State
- Account length
- Area code
- International plan
- Voice mail plan
- Number of voicemail messages
- Total day minutes
- Total day calls
- Total day charge
- Total evening minutes
- Total evening calls
- Total evening charge
- Total night minutes
- Total night calls
- Total night charge
- Total international minutes
- Total international calls
- Total international charge
- Customer service calls

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Loading

The customer churn dataset was loaded using Pandas and inspected to understand its structure, data types, and dimensions.

### 2. Data Exploration

The dataset was analyzed using:

- Dataset shape
- Column names
- Data types
- Statistical summary
- Missing-value analysis
- Churn distribution

### 3. Data Preprocessing

Categorical features were encoded using **One-Hot Encoding**.

The categorical features included:

- State
- Area code
- International plan
- Voice mail plan

The dataset was then divided into training and testing sets using an **80:20 stratified split**.

### 4. Random Forest Classification

A `RandomForestClassifier` was trained to predict customer churn.

### 5. Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Classification Report

### 6. Cross-Validation

Five-fold cross-validation was performed using the F1-score to evaluate the consistency of the model.

### 7. Hyperparameter Tuning

`GridSearchCV` was used to tune the Random Forest parameters.

The parameters considered included:

- `n_estimators`
- `max_depth`
- `min_samples_split`
- `min_samples_leaf`

### 8. Feature Importance

Feature importance was analyzed to identify the variables that had the greatest influence on the model's predictions.

---

## 📊 Model Performance

### Initial Random Forest

| Metric | Score |
|---|---:|
| Accuracy | 94.38% |
| Precision | 100.00% |
| Recall | 61.54% |
| F1-score | 76.19% |

### Cross-Validation

| Metric | Score |
|---|---:|
| Mean F1-score | 75.64% |
| Standard Deviation | 3.10% |

The five-fold cross-validation F1-scores were:

```text
0.8000
0.7097
0.7786
0.7520
0.7419
