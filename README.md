# 🏦 Atliqo Bank Data Analysis

This repository contains data analysis and processing notebooks for **Atliqo Bank**, focusing on customer demographics, credit profiles, and transaction behaviors. The analysis is structured across two key phases:

- **Phase 1**: Data exploration, cleaning, and feature engineering  
- **Phase 2**: Experimental analysis and campaign impact evaluation

---

## 📁 Repository Structure

- `phase_1_atliqo_bank.ipynb`  
  Data cleaning, feature creation, and exploratory analysis on customer, credit, and transaction datasets.

- `phase_2_atliqo_bank.ipynb`  
  Experimental analysis, including A/B testing and marketing campaign impact assessment.

---

## 📊 Data Overview

The following datasets were analyzed in phase 1:

### 🧍 Customer Data
- **Fields**: `cust_id`, `name`, `gender`, `age`, `location`, `occupation`, `annual_income`, `marital_status`

### 💳 Credit Data
- **Fields**: `cust_id`, `credit_score`, `credit_utilisation`, `outstanding_debt`, `credit_inquiries_last_6_months`, `credit_limit`

### 💸 Transaction Data
- **Fields**: `tran_id`, `cust_id`, `tran_date`, `tran_amount`, `platform`, `product_category`, `payment_type`

---

## 🛠️ Key Features & Processing

### 🔧 Data Cleaning
- Handled missing values across all datasets
- Outlier detection and correction for `tran_amount` (e.g., replaced outliers with category means)

### 🧪 Feature Engineering
- Age group segmentation (e.g., 18–25, 26–48, 49–65)
- Credit score range categorization (e.g., 300–449, 700–749)
- Aggregated customer metrics for profiling

### 📈 Statistical Analysis
- Correlation analysis between:
  - Credit score
  - Credit utilization
  - Outstanding debt
  - Annual income
- Transaction behavior breakdown by:
  - Platform
  - Product category
  - Payment type

---

## 📈 Example Analyses

### 🎯 Customer Segmentation
Analyze spending and credit patterns by age group and occupation.

### 💰 Credit Limit Assignment
Assign credit limits based on credit score ranges and validate with summary statistics.

### 📊 Campaign Impact
Compare average transaction values between control and test groups across campaign dates to measure uplift.

---

## 📝 Notes

- The notebooks are designed for step-by-step execution and are heavily commented for educational and reproducibility purposes.
- Data samples shown in the notebooks are anonymized and/or synthetic.

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or new analyses.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 📬 Contact

For questions or collaborations, please contact dutta280302@gmail.com.

---

> **Disclaimer:**  
> This repository is for educational and analytical purposes only. No real customer data is exposed.
