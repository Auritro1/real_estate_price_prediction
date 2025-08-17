# Real Estate Price Analysis using Machine Learning

## Overview
This project focuses on predicting property prices in Bengaluru using real-world data from the `Bengaluru House Prices` dataset. The goal was to apply data cleaning, feature engineering, and machine learning techniques to build an accurate price prediction model. Throughout the project, I explored the dataset, handled missing values and outliers, and experimented with multiple regression models to identify the one that best captures the patterns in Bengaluru’s real estate market.

---

## Features & Preprocessing
- Extracted **BHK** from the `size` column.
- Calculated **price per square foot** (`price_per_sqft`).
- Handled missing and inconsistent values.
- Grouped rare locations into `other`.
- Removed outliers based on **price per sqft** and BHK comparisons.
- One-hot encoded categorical variables (`location`).

---

## Models Implemented
- **Linear Regression**
- **Lasso Regression**
- **Decision Tree Regressor**

- Hyperparameter tuning is done using **GridSearchCV** with cross-validation.
- Visualizations are included to detect anomalies and analyze trends.

---

## Tools & Technologies
- Python 3.12
- Pandas, NumPy
- Scikit-learn
- Matplotlib

---

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/yourusername/real_estate_model.git
