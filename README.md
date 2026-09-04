# Telecommunications Customer Churn & Behavioral Analysis
**Codveda Data Science Internship Project**

## Project Overview
This repository contains an end-to-end data analytics and predictive modeling project on customer churn within the telecommunications industry. Using a real-world customer dataset (`churn-bigml-80.csv`), the project follows a structured workflow across three levels: data cleaning and exploratory analysis, regression and unsupervised clustering, and predictive machine learning.

---

## Project Structure & Progression

### Level 1: Data Cleaning & Exploratory Data Analysis (EDA)
* **File:** `Level_1_Tasks.ipynb`
* **Tasks Completed:**
  * Cleaned missing values, verified feature data types, and binary-encoded key demographic/plan attributes.
  * Computed descriptive statistics for operational calling metrics and customer account history.
  * Visualized churn distributions, bivariate boxplots, numerical correlation heatmaps, and charge-versus-usage scatter plots.

---

### Level 2: Intermediate Analysis & Modeling
* **File:** `Level_2_Tasks.ipynb`
* **Tasks Completed:**
  * **Task 1 (Linear Regression):** Trained an 80/20 train-test split regression model using `scikit-learn` to predict total daily call charges from total day minutes, evaluating model fit with $R^2$ and Mean Squared Error (MSE).
  * **Task 3 (K-Means Clustering):** Applied `StandardScaler` to customer usage metrics, determined optimal cluster count via the Elbow Method, and segmented users into distinct behavioral usage personas.

---

### Level 3: Advanced Predictive Modeling
* **File:** `Level_3_Tasks.ipynb`
* **Tasks Completed:**
  * **Task 1 (Churn Prediction):** Built a balanced `RandomForestClassifier` to identify customers at high risk of churning.
  * **Task 2 (Evaluation & Feature Importance):** Assessed model performance using a Confusion Matrix, Precision, Recall, and ROC-AUC score, identifying the top operational drivers behind customer attrition (e.g., customer service interactions and daytime usage costs).

---

## Tech Stack & Libraries
* **Language:** Python 
* **Development Environment:** Visual Studio Code / Jupyter Notebooks
* **Data Processing & Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (`LinearRegression`, `KMeans`, `RandomForestClassifier`, `StandardScaler`, metrics evaluation)
