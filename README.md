# Credit Card Fraud Detection using Machine Learning

## Objective

Develop a machine learning model to detect fraudulent credit card transactions using multiple classification algorithms and evaluate their performance on a highly imbalanced dataset.

---

## Dataset

The project uses the **Credit Card Fraud Detection** dataset available on Kaggle.

**Note:** The dataset is not included in this repository due to GitHub file size limitations. Please download it from the link below and place `creditcard.csv` in the project directory before running the notebook.

* **Source:** Kaggle Credit Card Fraud Detection Dataset
* **Download:** https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
* **Total Transactions:** 284,807
* **Fraudulent Transactions:** 492
* **Genuine Transactions:** 284,315

---

## Workflow

* Data Loading
* Exploratory Data Analysis (EDA)
* Missing Value Analysis
* Class Distribution Analysis
* Data Preprocessing
* Feature Scaling
* Train-Test Split
* Model Training
* Model Evaluation
* Feature Importance Analysis
* Feature Selection
* Model Retraining
* Performance Comparison

---

## Machine Learning Models

The following classification algorithms were implemented and compared:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)

---

## Best Performing Model

**Random Forest**

| Metric    |        Value |
| :-------- | -----------: |
| Accuracy  | **99.9614%** |
| Precision |   **94.19%** |
| Recall    |   **82.65%** |
| F1-Score  |   **88.04%** |

---

## Feature Selection

Feature importance analysis using the Random Forest model identified the **12 most significant features**.

All machine learning models were retrained using these selected features. Reducing the feature set from **30 to 12 features** slightly improved the performance of Random Forest, SVM, Decision Tree, and KNN while reducing the dimensionality of the dataset.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab
