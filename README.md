# Real_Estate_Price_Prediction

## Overview
This project predicts property prices based on various features such as location, total square feet area, and BHK (bedroom) count. The dataset is cleaned, preprocessed, and analyzed before applying multiple machine learning models to identify the best-performing model.

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
