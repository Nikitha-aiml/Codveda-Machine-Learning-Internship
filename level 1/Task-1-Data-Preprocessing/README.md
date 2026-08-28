# Data Preprocessing – Codveda Machine Learning Internship

## 📌 Project Overview

This project is part of the **Codveda Machine Learning Internship**.

The objective of this task is to preprocess a customer churn dataset and prepare it for machine learning by applying essential data preprocessing techniques such as:

- Dataset exploration
- Missing value checking
- Feature and target separation
- Categorical variable encoding
- Numerical feature standardization
- Train-test splitting
- Data leakage prevention

---

## 📊 Dataset

The project uses the **Customer Churn dataset** (`churn-bigml-80.csv`).

The dataset contains information about telecommunications customers and whether they have churned.

### Dataset Details

- **Rows:** 2,666
- **Columns:** 20
- **Input Features:** 19
- **Target Variable:** `Churn`

### Feature Types

**Categorical Features:**
- `State`
- `Area code`
- `International plan`
- `Voice mail plan`

**Numerical Features:**
- `Account length`
- `Number vmail messages`
- `Total day minutes`
- `Total day calls`
- `Total day charge`
- `Total eve minutes`
- `Total eve calls`
- `Total eve charge`
- `Total night minutes`
- `Total night calls`
- `Total night charge`
- `Total intl minutes`
- `Total intl calls`
- `Total intl charge`
- `Customer service calls`

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Data Preprocessing Steps

### 1. Dataset Exploration

The dataset was loaded and examined using:

- `head()`
- `shape`
- `info()`
- `describe()`

This helped understand the dataset structure, feature types, and statistical properties.

### 2. Missing Value Check

Missing values were checked across all columns.

**Result:**

```text
Total missing values: 0
