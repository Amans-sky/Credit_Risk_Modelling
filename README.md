
# Credit Risk Modeling

## Overview

This project aims to build a **Credit Risk Prediction Model** that helps financial institutions assess the risk of loan applicants defaulting on their payments. It integrates **customer demographics, loan details, and credit bureau data** to predict loan repayment likelihood.

## Problem Statement

Banks and lending institutions face significant financial losses due to loan defaults. This project focuses on predicting **creditworthiness of customers** using machine learning models to enable better risk management and minimize non-performing assets (NPAs).

## Key Features

* **Data Integration:** Combined customer, loan, and bureau datasets (50,000+ records).
* **Exploratory Data Analysis (EDA):** Identified trends in age, income, loan purpose, and repayment behavior.
* **Feature Engineering:** Created features such as debt-to-income ratio, active loans count, and credit utilization.
* **Modeling:** Built machine learning models (e.g., Logistic Regression, Random Forest, XGBoost).
* **Evaluation Metrics:** ROC-AUC, Precision-Recall, F1-score.
* **Visualization:** Used Matplotlib and Seaborn to visualize distributions and risk patterns.

## Tech Stack

* **Languages:** Python
* **Libraries:** pandas, NumPy, matplotlib, seaborn, scikit-learn
* **Tools:** Jupyter Notebook

## Dataset

The dataset includes three CSV files:

* `customers.csv` – Demographics & financial details of customers
* `loans.csv` – Loan information including amount, purpose, tenure
* `bureau_data.csv` – External credit bureau data

## Workflow

1. Data loading & cleaning
2. Exploratory Data Analysis (EDA)
3. Feature selection & engineering
4. Train-test split
5. Model training (Logistic Regression, Random Forest, etc.)
6. Model evaluation
7. Insights & business recommendations

## Results

* Achieved **ROC-AUC: \~0.87** on test set
* Identified high-risk segments based on income, loan type, and employment status
* Recommended risk-based interest rate adjustments

## Future Scope

* Deploy the model as a **REST API for real-time loan applications**
* Integrate with **credit scoring systems**
* Experiment with **deep learning models** for non-linear patterns

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/<your-username>/credit-risk-model.git
   cd credit-risk-model
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook credit_risk_model.ipynb
   ```

## Author

Aman N Shah
Aspiring Data Scientist | Financial Analytics Enthusiast



