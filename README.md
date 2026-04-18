# Breast-Cancer-Prediction-ML
"A machine learning project to classify tumors using SVM, KNN, and Random Forest."
# Breast Cancer Prediction using Machine Learning

## 1. Project Overview
This project aims to classify breast cancer tumors as **Malignant** or **Benign** based on medical image features. Early detection is critical in healthcare, and this project demonstrates how Machine Learning can assist doctors in making accurate diagnoses.

## 2. The Dataset
The dataset includes 569 samples with features such as:
* **Radius, Texture, Perimeter, and Area**
* **Smoothness and Compactness**
* **Concavity and Symmetry**

## 3. Data Cleaning & Preprocessing (Key Steps)
To make this project more accurate, I followed these distinct cleaning steps:
* **Feature Removal:** Dropped the `id` column as it has no predictive value.
* **Redundancy Check:** Analyzed feature correlation and removed highly redundant features to prevent model confusion.
* **Encoding:** Converted categorical labels (M/B) into numerical values (1/0).
* **Scaling:** Applied `StandardScaler` to ensure all medical measurements were on the same scale for algorithms like SVM and KNN.

## 4. Models & Performance
I implemented and compared three different classification models:

| Model | Accuracy |
| :--- | :--- |
| **Random Forest** | **96.5%** |
| **Support Vector Machine (SVM)** | **95.6%** |
| **K-Nearest Neighbors (KNN)** | **94.7%** |

**Conclusion:** The Random Forest model provided the most reliable predictions for this dataset.

## 5. How to Run
1. Clone this repository.
2. Ensure you have `pandas`, `seaborn`, and `sklearn` installed.
3. Open `Breast_Cancer_Prediction.ipynb` in Jupyter Notebook or Google Colab.
4. Run all cells to see the results and visualizations.
