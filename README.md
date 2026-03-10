# Online vs In-Store Shopping Behavior Classification

## Project Overview

The rapid growth of e-commerce has significantly changed how consumers shop. While many customers prefer online platforms, others still favor physical retail stores, and a growing number adopt a hybrid approach.

This project analyzes consumer shopping behavior and builds machine learning models to **predict a customer’s preferred shopping channel** based on demographic, behavioral, and psychological features.

The workflow includes **data exploration, preprocessing, feature engineering, model training, and evaluation** using multiple machine learning algorithms.

---

## Dataset Description

This dataset simulates real-world consumer behavior by combining multiple factors that influence shopping decisions.

**Dataset Size**

* **11,789 records**
* **26 features**

**Feature Categories**

* **Demographic information**

  * Age
  * Gender
  * City tier
* **Digital behavior**

  * Online activity level
  * Website engagement
  * Digital familiarity
* **Shopping patterns**

  * Purchase frequency
  * Average spending
  * Preferred shopping time
* **Logistics preferences**

  * Delivery speed preference
  * Distance to store
  * Shipping sensitivity
* **Psychological factors**

  * Convenience preference
  * Brand loyalty
  * Price sensitivity

**Target Variable**

* `shopping_preference`

  * Online
  * In-store
  * Hybrid

---

## Project Objectives

The goal of this project is to:

* Perform **Exploratory Data Analysis (EDA)** to understand shopping trends
* Apply **feature engineering and preprocessing**
* Train multiple **machine learning classification models**
* Compare model performance
* Identify the **most influential features affecting shopping preference**

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Project Workflow

### 1. Data Exploration

Initial exploration includes:

* Dataset inspection
* Data type checking
* Summary statistics
* Missing value detection

### 2. Data Cleaning

* Removed duplicate records
* Handled outliers using the **IQR method with value capping**
* Verified numeric and categorical data types

### 3. Exploratory Data Analysis

EDA visualizations include:

* Distribution of shopping preferences
* Feature distributions
* Correlation heatmap
* Feature relationships with the target variable

### 4. Feature Engineering

* Separation of numeric and categorical variables
* **One-hot encoding** for categorical features
* **Power transformation** for skewed numeric features
* **Feature scaling** using StandardScaler
* **Principal Component Analysis (PCA)** for dimensionality reduction

### 5. Model Training

The following machine learning models were trained:

1. Logistic Regression
2. Random Forest
3. Gradient Boosting

All models were trained using **Scikit-learn pipelines** to ensure consistent preprocessing.

### 6. Model Evaluation

Models were evaluated using:

* Accuracy
* Weighted F1 Score
* Classification report
* Confusion matrix visualization

### 7. Feature Importance

Feature importance analysis was performed using the **Random Forest model** to identify the most influential predictors of shopping behavior.

---

## Model Comparison

| Model               | Accuracy | F1 Score |
| ------------------- | -------- | -------- |
| Logistic Regression | 0.98     | 0.98     |
| Random Forest       | 0.91     | 0.86     |
| Gradient Boosting   | 0.89     | 0.85     |

---

## Example Visualization

The project includes visualizations such as:

* Correlation heatmaps
* Confusion matrices
* Feature importance charts

These help interpret how different variables influence consumer shopping choices.

---
## Author

Bill Gao
