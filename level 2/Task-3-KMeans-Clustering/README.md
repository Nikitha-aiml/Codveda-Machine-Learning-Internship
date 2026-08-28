# K-Means Clustering – Codveda Machine Learning Internship

## 📌 Project Overview

This project is part of the **Codveda Machine Learning Internship – Level 1**. The objective of this task is to implement **K-Means Clustering**, an unsupervised machine learning algorithm used to group similar data points into clusters.

The project explores different values of **K** and uses the **Silhouette Score** to evaluate the quality of the resulting clusters and determine a suitable number of clusters.

---

## 🎯 Objectives

The main objectives of this task are:

* Load and explore the dataset
* Perform necessary data preprocessing
* Select relevant features for clustering
* Scale the features
* Apply K-Means clustering
* Test different values of K
* Evaluate clustering using the Silhouette Score
* Select an appropriate number of clusters
* Visualize the resulting clusters

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Scikit-learn** – Machine learning and clustering
* **Jupyter Notebook** – Development environment

---

## 🔄 Workflow

### 1. Data Loading

The dataset was loaded using Pandas and examined to understand its structure, features, data types, and overall characteristics.

### 2. Data Exploration

Exploratory data analysis was performed to identify:

* Dataset dimensions
* Data types
* Missing values
* Duplicate records
* Feature distributions
* Relationships between numerical features

### 3. Data Preprocessing

The required preprocessing steps were performed to prepare the dataset for clustering.

Numerical features were scaled so that features with larger numerical ranges would not disproportionately influence the clustering algorithm.

### 4. Feature Selection

Relevant numerical features were selected as inputs for the clustering model.

Since K-Means is an unsupervised learning algorithm, there is no target variable used during clustering.

### 5. Testing Different Values of K

K-Means clustering was performed using different numbers of clusters.

The clustering results were evaluated for different values of **K** to identify an appropriate cluster configuration.

### 6. Silhouette Score

The **Silhouette Score** was used to evaluate the quality of the clusters.

A higher Silhouette Score indicates that the data points are generally well matched to their own clusters and well separated from other clusters.

### 7. Final K-Means Model

Based on the Silhouette Score and clustering analysis, a suitable value of **K** was selected and the final K-Means model was trained.

### 8. Cluster Visualization

The resulting clusters were visualized to better understand the grouping of observations and the separation between clusters.

---

## 📊 Evaluation Metric

### Silhouette Score

The Silhouette Score measures how similar each data point is to its own cluster compared with other clusters.

The score ranges from **-1 to 1**:

* **Closer to 1** → Well-separated and compact clusters
* **Around 0** → Overlapping clusters
* **Below 0** → Data points may have been assigned to the wrong clusters

The Silhouette Score was calculated for multiple values of K to help select a suitable number of clusters.

---

## 📈 Key Outcome

K-Means clustering was successfully implemented to group similar observations into clusters.

Different values of **K** were evaluated using the Silhouette Score, and the clustering results were visualized to understand the structure of the dataset.

---


## 📚 Internship Details

**Program:** Codveda Machine Learning Internship
**Level:** Level 2
**Task:** K-Means Clustering

---

## 👩‍💻 Author

**Nikitha.S**

GitHub: **Nikitha-aiml**

