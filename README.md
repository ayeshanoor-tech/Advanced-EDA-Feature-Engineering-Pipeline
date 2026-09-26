# Advanced EDA & Feature Engineering Pipeline (DecodeLabs Project 1)

An industrial data science pipeline built in Python (Pandas, NumPy, Scikit-Learn) performing missing value imputation, IQR outlier treatment, feature standardization, and Linear Regression modeling.

## 🚀 Project Overview
This project implements a complete End-to-End Data Science and Machine Learning workflow:
1. **Data Cleaning & Imputation:** Detecting missing values percentage and filling missing data using Median imputation.
2. **Outlier Treatment:** Managing anomalies and outliers using the Interquartile Range (IQR) method (Winsorization).
3. **Feature Scaling:** Standardizing features using Scikit-Learn's `StandardScaler` ($\mu = 0, \sigma^2 = 1$).
4. **Model Training & Prediction:** Training a `LinearRegression` model on split training/testing sets.

## 🛠️ Tech Stack
* **Language:** Python 3.14
* **Libraries:** Pandas, NumPy, Scikit-Learn
* **Environment:** VS Code on Windows

## 📂 File Structure
* `main.py` - Main execution script containing the complete pipeline.
* `dataset.csv` - Initial processed dataset.
* `cleaned_dataset.csv` - Cleaned dataset after handling missing values and outliers.
* `scaled_dataset.csv` - Final standardized dataset ready for machine learning.
* `decodelabs p1.odt` - Comprehensive project report.

## 💻 How to Run
Run the python script directly in your terminal:
```bash
python main.py
