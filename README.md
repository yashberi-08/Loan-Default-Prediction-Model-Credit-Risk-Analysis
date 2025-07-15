# Loan-Default-Prediction-Model-Credit-Risk-Analysis

This project was completed as part of the JPMorgan Chase & Co. "Powering Financial Decisions" Virtual Experience on Forage.

## 📌 Objective
Build a logistic regression model to predict loan default based on key financial indicators, simulating how banks assess credit risk.

## 💡 Key Features
- Engineered features: 
  - Debt-to-Income Ratio (DTI)
  - Payment-to-Income Ratio (PTI)
- Trained a logistic regression model using:
  - `credit_lines_outstanding`
  - `debt_to_income`
  - `payment_to_income`
  - `years_employed`
  - `fico_score`
- Evaluated model with:
  - ROC Curve and AUC score
  - Classification error rate

## 📈 Results
- Achieved ~85% ROC-AUC
- Reduced classification error by 15%
- Scored over 1,000+ profiles for default probability

## 🔧 Tools & Libraries
- Python, Pandas, NumPy, scikit-learn, matplotlib

## 📂 Files
- `loan_default_prediction.ipynb`: Main model training & evaluation code
- `loan_data_created.csv`: Input data (simulated)
- `requirements.txt`: Python package requirements

