# Data Dictionary – Credit Risk Scorecard Project

This document describes the key variables used in the credit risk scorecard model.

---

## 🎯 Target Variable

| Variable Name | Description |
|--------------|------------|
| `default_flag` | Binary target variable (1 = Default, 0 = Non-default) |

---

## 👤 Demographic Variables

| Variable | Description |
|--------|------------|
| `Age` | Customer age in years |
| `Gender` | Customer gender |
| `Marital_Status` | Marital status of customer |
| `Employment_Years` | Years of employment |

---

## 💰 Financial Variables

| Variable | Description |
|--------|------------|
| `Income_INR` | Monthly income of customer |
| `Loan_Amount` | Loan amount sanctioned |
| `Loan_Tenure_Months` | Loan tenure in months |
| `Outstanding_Loans` | Total outstanding loan balance |

---

## 🏦 Credit Bureau Variables

| Variable | Description |
|--------|------------|
| `Credit_History_Length` | Length of credit history (months) |
| `No_of_Open_Accounts` | Number of currently open accounts |
| `No_of_Closed_Accounts` | Number of closed credit accounts |
| `Credit_Card_Utilization` | Credit card utilization ratio |
| `No_of_Inquiries_6M` | Credit inquiries in last 6 months |

---

## ⚠️ Delinquency Variables

| Variable | Description |
|--------|------------|
| `DPD_30` | Count of 30+ DPD instances |
| `DPD_60` | Count of 60+ DPD instances |
| `DPD_90` | Count of 90+ DPD instances |
| `Worst_Current_Status` | Worst delinquency status |

---

## 🧠 Behavioral Variables

| Variable | Description |
|--------|------------|
| `Behavior_Spending_Score` | Spending behavior score |
| `Behavior_Repayment_Score` | Repayment behavior score |

---
