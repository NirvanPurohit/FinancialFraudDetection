
# Loan Default Prediction - Mini Project

This project is a machine learning mini project focused on predicting **loan default risk** based on borrower and loan information. It involves a complete data pipeline from preprocessing and feature engineering to model building and evaluation.

## 📂 Project Structure

- Data cleaning and preprocessing
- Outlier detection and removal
- Missing value imputation
- Feature encoding
- Model building using various classifiers
- Model evaluation and comparison

## 📊 Dataset

The dataset used is named `Loan_Default.csv`, which contains both categorical and numerical features related to borrower demographics, loan details, and risk indicators.

Key columns include:
- `loan_amount`, `rate_of_interest`, `Credit_Score`, `income`, etc.
- `loan_type`, `Gender`, `Credit_Worthiness`, etc.

## 🧹 Data Preprocessing

- **Outlier Removal**: Using IQR method for numerical features.
- **Missing Value Imputation**: Median for numerical, most frequent for categorical.
- **Encoding**: One-hot encoding for categorical variables.
- **Custom Mapping**: Age groups mapped to ordinal values.

## ⚙️ Models Used

- **Logistic Regression**
- **Random Forest**
- **Gradient Boosting**
-**KNN**
-**SVM**

Model selection and tuning were done using:
- `train_test_split`
- `StandardScaler` for normalization
- `GridSearchCV` for hyperparameter tuning (in some cases)

## ✅ Evaluation

Models were evaluated using accuracy and other metrics (details likely found in the latter part of the notebook). Feature importance or confusion matrices may be included as well.

## 🧰 Libraries Used

- `pandas`, `numpy`
- `sklearn` (imputation, encoding, model building, scaling, evaluation)
- `matplotlib`, `seaborn`, `missingno` (for EDA and visualization)
-`shap`
## SHAP analysis 
To interpret the model's predictions and understand feature importance, we applied SHAP (SHapley Additive exPlanations), a game theory-based approach to explain individual predictions.
## 📌 How to Run

1. Upload the `Loan_Default.csv` dataset to your environment (e.g., Google Colab).
2. Open and run each cell in the notebook `FinancialFraudDetection.ipynb`.
3. Follow the outputs and charts to explore the model training and evaluation.


