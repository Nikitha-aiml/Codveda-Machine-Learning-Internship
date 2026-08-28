# Support Vector Machine (SVM) – Codveda Machine Learning Internship

## 📌 Project Overview

This project is part of the **Codveda Machine Learning Internship – Level 1**. The objective of this task is to implement **Support Vector Machine (SVM)** models for a supervised classification problem.

Support Vector Machine is a powerful supervised learning algorithm that finds an optimal decision boundary to separate different classes. In this project, both **Linear SVM** and **RBF (Radial Basis Function) SVM** models are implemented and evaluated.

---

## 🎯 Objectives

The main objectives of this task are:

* Load and explore the dataset
* Perform necessary data preprocessing
* Select features and target variable
* Split the dataset into training and testing sets
* Train a Linear SVM classifier
* Train an RBF SVM classifier
* Evaluate both models using classification metrics
* Compare the performance of the two SVM approaches

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

The dataset was loaded using Pandas and inspected to understand its structure, features, data types, and target variable.

### 2. Data Exploration

Exploratory analysis was performed to examine:

* Dataset dimensions
* Data types
* Missing values
* Class distribution
* Feature characteristics

### 3. Data Preprocessing

The required preprocessing steps were performed to prepare the dataset for SVM classification.

Feature scaling was applied because SVM models are sensitive to the scale of input features.

### 4. Feature and Target Selection

The independent variables were selected as input features (`X`), while the categorical variable to be predicted was selected as the target (`y`).

### 5. Train-Test Split

The dataset was divided into training and testing sets. The training data was used to train the models, while the testing data was used to evaluate their performance on unseen data.

### 6. Linear SVM

A **Linear Support Vector Machine** classifier was trained to find a linear decision boundary between the classes.

### 7. RBF SVM

An **RBF Kernel SVM** classifier was trained to capture nonlinear relationships between the features and target classes.

### 8. Model Evaluation

Both SVM models were evaluated using:

* **Accuracy**
* **Precision**
* **Recall**
* **F1 Score**
* **AUC (Area Under the ROC Curve)**

### 9. Model Comparison

The performance of the **Linear SVM** and **RBF SVM** models was compared using the evaluation metrics to determine their effectiveness for the classification task.

---

## 📊 Model Evaluation

### Accuracy

Measures the proportion of correctly classified observations out of all observations.

### Precision

Measures the proportion of positive predictions that are actually positive.

### Recall

Measures the proportion of actual positive observations correctly identified by the model.

### F1 Score

The harmonic mean of precision and recall, providing a balanced measure of classification performance.

### AUC

The Area Under the ROC Curve measures the model's ability to distinguish between different classes. A higher AUC generally indicates better class discrimination.

---

## 📈 Results

Both **Linear SVM** and **RBF SVM** classifiers were successfully trained and evaluated.

The models achieved strong classification performance on the test dataset, demonstrating their ability to distinguish between the target classes.

The evaluation metrics obtained from the notebook were used to compare the performance of the two SVM approaches.

---

## 📚 Internship Details

**Program:** Codveda Machine Learning Internship
**Level:** Level 3
**Task:** Support Vector Machine (SVM)

---

## 👩‍💻 Author

**Nikitha.S**

GitHub: **Nikitha-aiml**
