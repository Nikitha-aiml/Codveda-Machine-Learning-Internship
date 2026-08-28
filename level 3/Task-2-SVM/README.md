# Support Vector Machine (SVM) for Binary Classification

## Codveda Machine Learning Internship – Level 3, Task 2

This project implements a Support Vector Machine (SVM) for binary classification using the Iris dataset.

The objective is to train SVM models using different kernels, compare their performance, visualize their decision boundaries, and evaluate them using multiple classification metrics.

---

## 📌 Project Overview

The original Iris dataset contains three species:

- Setosa
- Versicolor
- Virginica

For this project, the dataset was converted into a **binary classification problem** by selecting:

- Setosa → 0
- Versicolor → 1

The `Virginica` class was excluded.

Two features were selected for classification:

- Petal Length
- Petal Width

These features were chosen because they provide good separation between Setosa and Versicolor and allow the SVM decision boundaries to be visualized in two dimensions.

---

## 🎯 Objectives

The main objectives of this task are:

- Train an SVM model on a labeled dataset.
- Implement Linear and RBF kernels.
- Compare the performance of different SVM kernels.
- Visualize the SVM decision boundaries.
- Evaluate the models using:
  - Accuracy
  - Precision
  - Recall
  - AUC
- Visualize and compare ROC curves.
- Identify the most suitable kernel for the dataset.

---

## 📂 Dataset

**Dataset:** Iris Dataset

**File:** `iris.csv`

### Dataset Features

| Feature | Description |
|---|---|
| `sepal_length` | Length of the sepal |
| `sepal_width` | Width of the sepal |
| `petal_length` | Length of the petal |
| `petal_width` | Width of the petal |
| `species` | Iris species |

The original dataset contains **150 observations** with 50 observations for each species.

For binary classification, only Setosa and Versicolor were selected, resulting in **100 observations**.

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

The Iris dataset was loaded using Pandas.

### 2. Data Exploration

The dataset was examined for:

- Shape
- Data types
- Missing values
- Class distribution
- Descriptive statistics

No missing values were found.

### 3. Binary Classification

The original three-class dataset was converted into a binary classification problem:

```text
Setosa      → 0
Versicolor  → 1
