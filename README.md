## 🏠 House Price Prediction Project

## An LGBMt and SHAP Analysis

---

### 📘 **Project Overview**

This project demonstrates a complete machine learning workflow for predicting house prices. It uses a Kaggle dataset and involves data loading, extensive pre-processing, outlier removal, and feature engineering. An LightGBM Regressor model is trained, and its predictions are interpreted using SHAP (SHapley Additive exPlanations) to understand feature importance.

---

### 🎯 **Objectives**

* Understand and pre-process real-world housing data.
* Implement feature engineering to create new, impactful variables.
* Train an `LightGBMRegressor` model for price prediction.
* Evaluate model performance using R².
* Interpret the model's predictions using SHAP values to explain feature contributions.

---

### 📖 **Contents Overview**

| Section | Description |
| --- | --- |
| **Library Imports** | Loads all necessary libraries like pandas, xgboost, and shap. |
| **Data Loading** | Reads the housing data from a CSV file. |
| **Pre-processing** | Checks for null values, duplicates, and removes outliers using Z-scores. |
| **Feature Engineering**| Creates new features such as `age_when_sold`, `yr_since_renovated`, and `bath_bed_ratio`. |
| **Encoding & Scaling** | Applies Dummy Encoding to categorical feature ( `city`) and RobustScaler to numerical features. |
| **Model Training** | Splits the data and trains an LightGBM Regressor model. |
| **Model Interpretation**| Uses SHAP to visualize global and local feature importance. |

---

### ⚙️ **Dependencies**

Make sure you have the following libraries installed:

* `pandas`
* `numpy`
* `seaborn`
* `matplotlib`
* `scikit-learn`
* `xgboost`
* `shap`
* `scipy`

---

### 🚀 **How to Run**

1.  Clone or download the repository.
2.  Install the required libraries (e.g., `pip install -r requirements.txt`).
3.  Download the dataset from Kaggle: [https://www.kaggle.com/datasets/shree1992/housedata](https://www.kaggle.com/datasets/shree1992/housedata).
4.  Update the `file_path` variable in the notebook to point to your `data.csv` location.
5.  Open and run the Jupyter Notebook: `house_price_prediction.ipynb`.
