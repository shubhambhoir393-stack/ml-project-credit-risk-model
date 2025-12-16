# Lauki Finance – Credit Risk Modelling (Streamlit App)

## Project Overview

This project is an **end-to-end Credit Risk Modelling application** built using **Python, Machine Learning, and Streamlit**.
It predicts the **probability of loan default**, generates a **credit score**, and assigns a **risk rating** based on customer financial and credit behavior.

The solution mirrors a **real-world BFSI lending use case** and is fully **deployment-ready**.
---

## Live Demo

🚀 **Streamlit Application**
https://ml-project-credit-risk-model-haeccujymit33uapbvqcjb.streamlit.app/
---

## Application Preview
<img width="1175" height="713" alt="image" src="https://github.com/user-attachments/assets/5c0ed5b2-194e-4f04-8ea8-700105ca5814" />

```
---

## Business Problem
Lending institutions must assess creditworthiness quickly and accurately to:

* Reduce default risk
* Improve portfolio quality
* Enable data-driven loan decisions

This application helps by converting customer attributes into:
* Default probability
* Credit score
* Risk category
---

## Key Features
* Interactive Streamlit UI
* Real-time credit risk prediction
* Probability of Default (PD) output
* Credit score generation (300–900 scale)
* Risk rating classification (Good / Average / Poor)
* Pre-trained ML model loaded using `joblib`
* Clean, production-ready project structure
---

## Input Features
The model evaluates the following inputs:
* Age
* Annual Income
* Loan Amount
* Loan-to-Income Ratio
* Loan Tenure (months)
* Average Days Past Due (DPD)
* Delinquency Ratio
* Credit Utilization Ratio
* Number of Open Loan Accounts
* Residence Type (Owned / Rented)
* Loan Purpose (e.g., Education)
* Loan Type (Secured / Unsecured)
---

## Output
The application returns:
* **Default Probability (%)**
* **Credit Score**
* **Risk Rating**

Example:
* Default Probability: `59.43%`
* Credit Score: `543`
* Rating: `Average`
---

## Tech Stack
* Python
* Pandas, NumPy
* Scikit-learn
* Joblib
* Streamlit
* Git & GitHub
---

## Project Structure

ml-project-credit-risk-model/
│
├── artifacts/
│   └── model_data.joblib
│
├── main.py
├── prediction_helper.py
├── requirements.txt
├── README.md
└── .gitignore


## How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/ml-project-credit-risk-model.git
cd ml-project-credit-risk-model
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the application
```bash
streamlit run main.py
```

## Model Notes
* The model is **pre-trained** and serialized using `joblib`
* Focus is on **practical deployment and interpretability**
* Feature design is inspired by **real BFSI credit risk parameters**
---

## Key Learnings
* End-to-end ML project lifecycle
* Feature engineering for credit risk
* Model serialization and loading
* Streamlit deployment on cloud
* Git best practices for ML projects
---

## Future Enhancements
* Model retraining pipeline
* SHAP-based explainability
* Performance metrics dashboard
* Database integration
* Authentication & access control
---

## Disclaimer
⚠️ This project is for **educational and demonstration purposes only** and should not be used for real-world lending decisions.
---

## Author
**Shubham Bhoir**
