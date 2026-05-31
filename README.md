
#  Introduction to Machine Learning (IML) Lab

Welcome to my Introduction to Machine Learning (IML) lab repository! This repository contains Python implementations for a series of assignments covering fundamental machine learning concepts, from basic data manipulation to advanced classification and clustering algorithms.

##  Overview

The goal of this repository is to demonstrate the practical application of machine learning algorithms using standard Python libraries. The assignments progress from basic NumPy and Pandas operations to evaluating supervised and unsupervised learning models on standard datasets.

##  Lab Assignments

Here is a breakdown of the assignments and experiments included in this repository:

| Assignment | Topic | Description |
| :---: | :--- | :--- |
| **1** | **Data Basics & Error Calculation** | • Initializing 1D and 2D arrays and converting them using **NumPy** and **Pandas**.<br>• Calculating the error of a line equation using 5 different coordinates. |
| **2** | **Evaluation Metrics** | • Calculating TP, TN, FP, FN, Precision, Recall, Accuracy, and F1 Score.<br>• Plotting the Confusion Matrix. |
| **3** | **Regression Models** | • Implementing **Linear Regression** and **Polynomial Regression**.<br>• Comparing model performance using the $R^2$ Score. |
| **4** | **Logistic Regression** | • Implementing Logistic Regression for classification.<br>• Generating evaluation metrics, Confusion Matrix, and ROC Curve. |
| **5** | **K-Nearest Neighbour (KNN)** | • Applying the KNN algorithm to the `Titanic.csv`, `Diabetes.csv`, and `Social_Network.csv` datasets. |
| **6** | **Support Vector Machine (SVM)**| • Applying the SVM algorithm to the `Titanic.csv`, `Diabetes.csv`, and `Social_Network.csv` datasets. |
| **7** | **K-Means Clustering** | • Applying Unsupervised Learning (K-Means) to the `Titanic.csv`, `Diabetes.csv`, and `Social_Network.csv` datasets. |

##  Datasets Used

Assignments 5, 6, and 7 make use of the following standard datasets (located in the `/datasets` folder):
* `Titanic.csv`: Survival prediction based on passenger data.
* `Diabetes.csv`: Predicting the onset of diabetes based on diagnostic measures.
* `Social_Network.csv`: Predicting whether a user purchased a product based on age and estimated salary.

##  Technologies & Libraries

To run the programs in these assignments, the following Python libraries are required:

* **Language:** Python 3.x
* **Data Manipulation:** `numpy`, `pandas`
* **Machine Learning:** `scikit-learn`
* **Data Visualization:** `matplotlib`, `seaborn` (for Confusion Matrices and ROC Curves)
