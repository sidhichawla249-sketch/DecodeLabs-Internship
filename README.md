# DecodeLabs Data Science & Analytics Internship

This repository contains the projects completed during the DecodeLabs Internship program. It showcases end-to-end data pipelines, advanced exploratory data analysis, feature engineering, and predictive modeling.

---

## 📁 Repository Structure

*   **`Internship 1/`** : Advanced EDA & Feature Engineering (Folder).
    *   `online_store_analysis.ipynb` (Main Jupyter Notebook)
    *   `Online-Store-Orders.xlsx` (Dataset)
*   **`Project 2.ipynb`** : Supervised Learning - Fraud Detection System (File).

---

## 📊 Project 1: Advanced EDA & Feature Engineering

### 🔹 Project Overview
The primary goal of this project is to transform raw, chaotic retail/store data into a mathematically clean dataset ready for downstream machine learning algorithms. It covers complete statistical cleaning and algorithmic preprocessing pipelines.

### 🔹 Key Features & Workflow
*   **Statistical Missing Data Imputation:** Wrote optimized Python scripts to handle missing values programmatically using Mean, Median, or KNN imputation strategies.
*   **Outlier Detection & Neutralization:** Identified and treated data anomalies/outliers using rigorous statistical metrics, including **Z-Scores** and the **Interquartile Range (IQR)** method.
*   **Feature Engineering:** Extracted and engineered at least 3 new predictive features from existing data columns to boost potential model performance.
*   **Key Skills Demonstrated:** Data Cleaning, Feature Extraction, Statistical Analysis, and Exploratory Data Analysis (EDA).

### 🔹 Tech Stack
*   **Language:** Python
*   **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
*   **Data Format:** Microsoft Excel (`.xlsx`)

---

## 🔒 Project 2: Supervised Learning (Fraud Detection Pipeline)

### 🔹 Project Overview
An end-to-end, leak-free machine learning pipeline designed to detect fraudulent financial transactions with high precision and robust validation rules.

### 🔹 Key Features & Workflow
*   **The Leak-Free Pipeline:** Formulated rigid preprocessing boundaries ensuring data transformation (scaling, encoding) happens strictly within cross-validation folds to completely eliminate data leakage.
*   **Handling Highly Imbalanced Data:** Implemented **SMOTE (Synthetic Minority Over-sampling Technique)** inside cross-validation splits to handle skewed class distributions responsibly.
*   **Machine Learning Classifiers:** Evaluated multiple supervised models including **Logistic Regression, Decision Trees, and XGBoost**.
*   **Hyperparameter Tuning:** Conducted fine-tuning on decision boundaries and hyperparameter combinations to minimize false negatives.
*   **Rigorous Model Evaluation:** Tracked performance across multiple metrics specifically checking for **Precision, Recall, ROC-AUC, and F1-Score**.

### 🔹 Tech Stack & Tools
*   **Language:** Python
*   **Libraries:** Scikit-learn, Imbalanced-learn (imblearn), XGBoost, Pandas, NumPy, Matplotlib, Seaborn

### 🔹 Dataset Information
*   **Source:** https://www.kaggle.com/code/janiobachmann/credit-fraud-dealing-with-imbalanced-datasets?select=creditcard.csv
*   *Note: Due to the large volumetric size of this fraud transaction dataset, it has been hosted and referenced directly from its source link on Kaggle instead of committing raw data directly into the web interface.*

---

## 🛠️ Setup & Execution Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com
   ```
2. **Install Dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn openpyxl xgboost imbalanced-learn
   ```
3. **Run the Notebooks:**
   Launch Jupyter Notebook to execute `Internship 1/online_store_analysis.ipynb` and `Project 2.ipynb`.
