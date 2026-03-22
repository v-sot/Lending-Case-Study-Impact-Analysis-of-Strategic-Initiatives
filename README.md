# Lending Case Study – Impact Analysis of Strategic Initiatives

This project analyzes the impact of key business initiatives on a lending portfolio using historical loan data.

The focus is on evaluating how strategic decisions affected **loan volume, credit risk, and profitability**.

---

## 📖 Overview

A dataset of lending activity (2010–2015) was provided alongside a timeline of business initiatives.

This analysis focuses on two major initiatives introduced in **Q1 2015**:

- Launch of a second aggregator channel  
- Implementation of stricter credit policy (loan size caps for risky customers)  

---

## 🎯 Objective

To quantify how these initiatives impacted:

- Application volume  
- Customer mix (risk profile)  
- Loan size  
- Profitability  
- Credit losses  

---

## 📊 Key Findings

### 📈 Portfolio-Level Impact (2014 vs 2015)

- Applications increased by **+43%**  
- Total profit decreased by **−27%**  
- Average loan size decreased by **−39%**  
- Total losses decreased by **−24%**  
- Net revenue decreased by **−28%**  

These results indicate a major **structural shift in portfolio dynamics** following the 2015 initiatives.

---

## 📌 Initiative 1: Second Aggregator Launch

### Impact:

- Aggregator applications **doubled**  
- Channel share increased from **20% → 40%**  

### Risk & Profitability Effects:

- Increased share of **Sub-Prime and Near-Prime borrowers**  
- Lower average loan sizes  
- Higher credit risk  
- Reduced profitability per loan  

👉 Insight:  
The aggregator significantly boosted volume but introduced **lower-quality borrowers**, negatively impacting margins.

---

## 📌 Initiative 2: Credit Policy Tightening

### Impact:

- Loan size caps applied to:
  - Sub-Prime  
  - Near-Prime customers  

- Higher-quality borrowers largely unaffected  

### Risk & Profitability Effects:

- Reduced loss rates for risky segments  
- Stabilized profit per loan despite smaller loan sizes  

👉 Insight:  
Credit policy tightening **mitigated risk exposure** and partially offset the negative effects of the aggregator expansion.

---

## ⚖️ Overall Business Insight

The two initiatives had **opposing effects**:

- Aggregator launch → increased growth but reduced quality  
- Credit tightening → reduced risk but constrained loan size  

👉 Combined effect:
A shift toward a **higher-volume, lower-margin portfolio**, with improved risk control.

---

## 📂 Dataset Description

The dataset includes:

- Application data (date, completion time)  
- Customer attributes (employment type, credit band)  
- Loan characteristics (loan size, term, APR)  
- Outcomes:
  - Approval  
  - Take-up  
- Financial metrics:
  - CAC  
  - Cost of funds  
  - Interest repaid  
  - Operating costs  
- Customer satisfaction (Trustpilot rating)  

---

## ⚙️ Methodology

- Time-based comparison (pre vs post 2015 initiatives)  
- Channel segmentation (Direct vs Aggregator)  
- Credit band segmentation  
- KPI analysis:
  - Approval rate  
  - Loan volume  
  - Profitability  
  - Loss rates  

---

## 🛠️ Tools Used

- Python  
- Pandas, NumPy  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## 📁 Repository Structure

```
├── analysis_final.ipynb
├── lending_case_study_presentation.pdf
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository  
2. Open:
   ```
   analysis_final.ipynb
   ```
3. Ensure dataset path is correct  
4. Run all cells  

---

## 💡 Why This Project Matters

This project demonstrates the ability to:

- Analyze the impact of real business initiatives  
- Balance growth vs risk trade-offs  
- Translate data into strategic insights  
- Communicate findings clearly (see presentation)  

---

## 👤 Author

Vasileios Sotiriadis
