#  Loan Delinquency Analysis Dashboard – Power BI Project

This project is a data-driven analysis and interactive dashboard designed to explore borrower delinquency behavior, assess loan performance, and assist credit & collections teams in identifying and managing high-risk accounts.

---

##  Project Objective

To analyze loan repayment patterns using borrower and payment history data, with a focus on:
- Identifying high-risk and delinquent borrowers
- Understanding behavioral risk patterns (like late payments)
- Segmenting risk based on tenure, payment method, and DPD (Days Past Due)
- Enabling actionable insights for credit, risk, and recovery teams

---

##  Dataset Overview

The dataset includes anonymized borrower records with:
- `loan_tenure`, `disbursed_loan`, `emi_value`
- `present_outstanding`, `curr_dpd_numeric`, `overdue_amount`, `penalties`
- `last_payment_mode`, `late_payment_days`, and `average_late_payment`

---

##  Key Features & Metrics

- **DPD Risk Segmentation**: Categorizes accounts into Low, Medium, High, Very High, and Critical risk buckets based on Days Past Due.
- **Late Payment Behavior**: Labels borrowers as *Disciplined*, *Inconsistent*, or *Chronically Late*.
- **Top 5 Defaulters**: Highlights accounts with the highest overdue amount.
- **Tenure-Based Analysis**: Shows how risk and loan value vary with loan duration.
- **Dynamic Slicers**: Allow filtering by Payment Mode, Tenure Range, DPD Bucket, and Payment Behavior.

---

##  Tech Stack

- **Power BI** for visualization, modeling, and DAX
- **Power Query** for data preprocessing
- **Excel** as the source file (can scale to SQL or cloud DB)
- Supports integration with **Azure**, **SharePoint**, or **OneDrive** for scheduled refresh

---

##  Reporting Structure

- Power Query cleans and transforms raw data
- DAX measures calculate KPIs like:
  - % High-Risk Accounts
  - Overdue Ratio
  - Avg Late Payment
- Slicers provide real-time filtering
- Can be connected to SQL/cloud for large-scale deployment

---

## 📊 Screenshots
1. Portfolio Overview
<img width="1869" height="962" alt="Image" src="https://github.com/user-attachments/assets/b8bdb59f-150a-4738-a3f7-0e9b39fb0d85" />

2. Delinquency Deep Dive
<img width="1867" height="976" alt="Image" src="https://github.com/user-attachments/assets/94ccb373-4369-4e4b-af46-0db3922a23da" />



---

## ✅ Insights Summary

- Over **90% of accounts** fall in the *High Risk* category (DPD ≥ 181)
- Borrowers with **consistent late payments** are more likely to default long-term
- **Longer tenure loans** (24–36 months) carry higher disbursed amounts and higher delinquency risk
- Specific payment modes like Razorpay/Enach show a pattern among defaulters

---

## 📁 Files Included

- `Loan delinquency analysis.pdf`: Final dashboard export
- `Delinquency Cases cleaned .xlsx`: Cleaned dataset
- Power BI file (`.pbix`) – 
- Live Report :https://app.powerbi.com/view?r=eyJrIjoiZjhlMmIwMGUtMmU4Ny00ZmE4LTk0MmEtMWViNzc2N2ZhMWEyIiwidCI6IjM1ODI5MjgzLWNhMjctNGVjNi04ZDg1LWUyM2Y2ZmE5N2Y2MCJ9
---

## 🤝 Credits

This project was developed as part of an assignment from **Aequitas Debt Solutions Pvt Ltd**.

---

## 📬 Contact

For questions or collaboration, reach out via [LinkedIn](https://www.linkedin.com/in/riyaztheanalyst/) or email me at riyaztheanalyst@email.com.
