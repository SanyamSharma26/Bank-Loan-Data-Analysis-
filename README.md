# Bank Loan Data Analysis

An end-to-end data analytics project built in Python to explore and visualize a bank’s loan portfolio.  
It helps track **loan performance, repayments, risk levels, and borrower demographics** using KPIs and dashboards.

## 🚀 Features
- **Key Metrics & KPIs**
  - Total & Month-to-Date (MTD) Loan Applications
  - Total & MTD Funded Amount and Amount Received
  - Average Interest Rate & Debt-to-Income (DTI)
  - Good vs Bad Loan Segmentation (Default Risk)

- **Interactive & Static Visualizations**
  - Monthly Trends: Funded Amount, Amount Received & Loan Applications
  - Regional Analysis by State
  - Loan Term Distribution (Donut chart)
  - Employment Length vs Funded Amount
  - Loan Purpose Analysis
  - Home Ownership Treemap (Plotly)

## 🛠️ Tech Stack
- Python • Pandas • NumPy • Matplotlib • Seaborn • Plotly Express
- Jupyter Notebook / Google Colab

## 📊 Insights
- Monitor loan growth and repayments month over month.
- Understand borrower risk with DTI & interest metrics.
- Segment customers by state, employment, home ownership, and loan purpose.
- Visualize good vs bad loan performance for better credit risk management.

## 📂 Dataset
The project uses a bank loan dataset (`financial_loan.xlsx`) containing:
- Loan details — `id`, `issue_date`, `loan_amount`, `total_payment`, `int_rate`, `dti`
- Customer info — `emp_length`, `address_state`, `home_ownership`, `purpose`
- Loan status — `Fully Paid`, `Current`, `Charged Off`

*(Replace with your dataset link if public)*

## 🚀 Getting Started
1. Clone this repo:
```bash
git clone https://github.com/SanyamSharma26/Bank-Loan-Data-Analysis.git
