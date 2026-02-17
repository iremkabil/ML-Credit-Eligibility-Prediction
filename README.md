# Credit Eligibility Prediction Project

This project focuses on predicting the eligibility of loan applications using machine learning techniques. The workflow includes data analysis, preprocessing, modeling, hyperparameter optimization, and model explainability.

---

## Project Objective

Various machine learning algorithms are used to predict whether a loan application will be approved. The goal is to help banks and financial institutions evaluate applications faster and more accurately.

---

## Dataset Description

- **Raw Data:** Contains demographic information, income, credit history, and employment status of applicants.
- **Processed Data:** Missing values are handled, categorical variables are encoded, and class imbalance is addressed using SMOTE.
- **Feature List:** The most important features used in the final model are stored in `final_feature_list.json`.

---

## Project Structure

Credit_Eligibility_Prediction/
├── dataset_description.md
├── data/
│ ├── processed/
│ └── raw/
├── notebooks/
│ ├── 01_eda.ipynb
│ ├── 02_preprocessing_and_feature_engineering.ipynb
│ └── 03_modeling.ipynb

- **data/raw/**: Raw dataset files  
- **data/processed/**: Preprocessed data with feature engineering applied  
- **notebooks/**: Jupyter notebooks for analysis, preprocessing, and modeling  
- **dataset_description.md**: Dataset and feature explanations  

---

## Workflow

1. **Exploratory Data Analysis (EDA):** Initial data exploration and visualization (`01_eda.ipynb`)
2. **Preprocessing & Feature Engineering:** Handling missing values, encoding categorical variables, and solving class imbalance using SMOTE (`02_preprocessing_and_feature_engineering.ipynb`)
3. **Modeling & Evaluation:** Training multiple machine learning models, comparison, and hyperparameter optimization (`03_modeling.ipynb`)
4. **Model Explainability:** Interpreting model predictions using SHAP (`03_modeling.ipynb`)

---

## Libraries Used

- pandas, numpy – Data processing and analysis  
- scikit-learn – Machine learning algorithms and evaluation metrics  
- matplotlib, seaborn – Visualization  
- shap – Model explainability  

---

## How to Run

1. Install required Python libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn shap

⚠️ This project is for educational and portfolio purposes.
