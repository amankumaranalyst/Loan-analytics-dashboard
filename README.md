# Bank Loan Analytics Dashboard

Interactive **Power BI** dashboard tracking loan portfolio performance and customer lending behavior.

---

## 📌 Overview

This project analyzes bank loan application data to monitor overall loan book health — tracking funded amounts, repayments, interest rates, and risk indicators to understand customer behavior and loan performance.

---

## 🗂️ Dataset

Loan-level dataset with the following fields:

`ISSUE_DATE` · `ID` · `PURPOSE` · `VERIFICATION_STATUS` · `GRADE` · `HOME_OWNERSHIP` · `ADDRESS_STATE` · `LOAN_STATUS` · `EMP_LENGTH` · `EMP_TITLE` · `LAST_CREDIT_PULL_DATE` · `LAST_PAYMENT_DATE` · `NEXT_PAYMENT_DATE` · `MEMBER_ID` · `SUB_GRADE` · `TERM` · `ANNUAL_INCOME` · `DTI` · `INSTALLMENT` · `INT_RATE` · `LOAN_AMOUNT` · `TOTAL_ACC` · `TOTAL_PAYMENT`

---

## 🛠️ Approach / Solution

- Modeled and transformed the loan dataset in Power BI (Power Query + DAX)
- Built category-wise filters (loan purpose: Car, Credit Card, Debt Consolidation, Educational, Home Improvement, House, Medical, Small Business, Vacation, Wedding, etc.)
- Designed a two-page dashboard — **Summary** and **Overview** — to track loan portfolio performance and customer behavior

---

## 📊 Dashboard Features

### Summary Page
- **KPI Cards:** Total Loan Applications (39K), Total Funded Amount (436M), Total Amount Received (473M), Average Interest Rate (12.05%), Average DTI Ratio (13.33%)
- **Good vs. Bad Loan Application** — donut charts (86.18% Good vs. 13.82% Bad)
- **Loan Status Breakdown** (Fully Paid / Charged Off / Current) across:
  - Funded Amount vs. Amount Received
  - Loan Application Count
  - Average Interest Rate
  - Average DTI Ratio

### Overview Page
- **Monthly Loan Application Trend** — line chart (Jan–Dec)
- **Loan Application by State** — interactive map
- **Loan Application by Term** — donut chart (36 vs. 60 months)
- **Loan Application by Home Ownership** — bar chart (Rent, Mortgage, Own, Other, None)
- **Loan Application by Purpose** — treemap (Debt Consolidation, Credit Card, Home Improvement, etc.)

---

## 🧰 Tech Stack / Key Skills

`Power BI` · `DAX` · `Power Query` · `Data Modeling` · `KPI Reporting` · `Loan Portfolio Analysis`

---

## 📈 Outcome

Delivered a dynamic, filter-driven dashboard that enables quick monitoring of loan portfolio health, repayment performance, and risk indicators (interest rate, DTI) — helping track customer lending behavior at a glance.

---

## 👤 Author

**Aman Kumar**
[GitHub](https://github.com/amansingh134) · [LinkedIn](https://linkedin.com/in/aman-kumar27)
