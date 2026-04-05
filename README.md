

# Credit Risk Modelling with Explainable AI (SHAP)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Explainable AI](https://img.shields.io/badge/Explainability-SHAP-critical)
![Framework](https://img.shields.io/badge/Framework-Streamlit-red)
![License](https://img.shields.io/badge/License-MIT-green)

---

## Overview

A production-oriented machine learning system for predicting credit risk using financial and behavioral data. The project integrates Explainable AI techniques to ensure transparency and interpretability of model predictions, making it suitable for real-world financial applications.

---

## Key Highlights

* End-to-end machine learning pipeline from data processing to deployment
* Real-time credit risk prediction through an interactive interface
* Integration of SHAP (SHapley Additive exPlanations) for model interpretability
* Modular and scalable architecture aligned with industry practices
* Designed for fintech, banking, and risk analytics use cases

---

## Explainability

The project incorporates SHAP (SHapley Additive exPlanations) to provide both global and local interpretability.

* Global feature importance across the dataset
* Local explanations for individual predictions
* Transparent decision-making aligned with financial regulations

---

## Architecture

```
Raw Data → Preprocessing → Feature Engineering → Model Training → SHAP Explainability → Deployment (Streamlit)
```

---

## Project Structure

```
Credit_Risk_Modelling/
│
├── app/
│   ├── main.py
│   ├── prediction_helper.py
│   └── artifacts/
│       └── model_data.joblib
│
├── dataset/
├── artifacts/
├── credit_risk_model.ipynb
├── requirements.txt
└── README.md
```

---

## Tech Stack

| Category         | Tools         |
| ---------------- | ------------- |
| Language         | Python        |
| Machine Learning | scikit-learn  |
| Data Processing  | pandas, numpy |
| Explainability   | SHAP          |
| Deployment       | Streamlit     |
| Serialization    | joblib        |

---

## Model Features

* Age
* Income
* Loan Amount
* Loan Tenure
* Loan-to-Income Ratio
* Credit Utilization
* Delinquency Metrics
* Number of Accounts
* Loan Type and Purpose
* Residence Type

---

## Installation

```bash
git clone https://github.com/your-username/credit-risk-modelling.git
cd credit-risk-modelling
pip install -r requirements.txt
```

---

## Usage

```bash
streamlit run app/main.py
```

Access the application at:

```
http://localhost:8501
```

---

## Business Applications

* Credit risk assessment for banks and NBFCs
* Automated loan approval support systems
* Risk analytics for fintech platforms

---

## Future Improvements

* Integration of SHAP visualizations within the UI
* Deployment on cloud infrastructure
* REST API integration for scalability
* Model enhancement using ensemble techniques

---

## Contributing

Contributions are welcome through pull requests. Please ensure code quality and proper documentation.

---

## Author

Aman N Shah
Data Science and Machine Learning Enthusiast

---

## License

This project is licensed under the MIT License.


