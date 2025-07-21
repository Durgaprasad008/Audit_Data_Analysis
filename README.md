# Audit_Data_Analysis
# 🧾 Audit Data Analysis – Big 4 Firms (PwC, Deloitte, EY, KPMG)

## 📌 Project Overview

This project leverages **Python** and **Statistical Techniques** to analyze auditing performance data of Big 4 accounting firms. The goal is to assess the impact of AI usage, employee workload, and industry factors on key auditing outcomes such as fraud detection, compliance violations, and client satisfaction.

---

## 🧠 Objectives

- Analyze audit data for 100 cases from major firms.
- Evaluate the **impact of AI on fraud detection**.
- Explore how **employee workload affects audit effectiveness**.
- Determine if **fraud cases vary significantly across industries**.
- Visualize trends and relationships using graphs and heatmaps.
- Draw actionable insights from statistical testing (t-tests and chi-square).

---

## 📂 Dataset

File: `big4_financial_risk_compliance.csv`  
Size: 100 rows × 12 columns

### Columns:
- `Year`, `Firm_Name`, `Total_Audit_Engagements`, `High_Risk_Cases`
- `Compliance_Violations`, `Fraud_Cases_Detected`, `Industry_Affected`
- `Total_Revenue_Impact`, `AI_Used_for_Auditing`, `Employee_Workload`
- `Audit_Effectiveness_Score`, `Client_Satisfaction_Score`

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **SciPy** (for statistical tests)

---

## 🔍 Key Analysis Steps

1. **Data Cleaning & Feature Engineering**
   - Converted categorical `AI_Used_for_Auditing` to binary.
   - Created:
     - `Fraud_Detection_Rate` = Fraud Cases / Total Engagements
     - `Revenue_Per_Engagement` = Revenue Impact / Total Engagements

2. **Statistical Testing**
   - **T-Test 1**: AI vs Fraud Detection Rate → ❌ No significant difference
   - **T-Test 2**: Workload vs Audit Effectiveness → ❌ No significant difference
   - **Chi-Square**: Industry vs Fraud Level → ❌ No significant relationship

3. **Visualizations**
   - Bar plots: Audit engagements, fraud rate, revenue impact
   - Line plots: Fraud cases over years by firm & industry
   - Box plots: AI impact on fraud & effectiveness
   - Scatter plots: Workload vs effectiveness, revenue vs satisfaction
   - Heatmaps: Correlation matrix (basic and enhanced)

---

## 📊 Sample Visuals

- **Fraud Detection Rate by Firm**  
- **AI Usage vs Fraud Detection Rate**  
- **Employee Workload vs Audit Effectiveness**  
- **Industry Trends in Fraud Cases Over Time**  
- **Correlation Heatmap for Key Metrics**

*(Visuals are saved in the `Images/` folder if exporting or integrating in dashboard/website)*

---

## 📈 Insights

- AI usage **does not significantly improve fraud detection rate** statistically.
- Employee workload shows **no strong impact on effectiveness**.
- Fraud levels are **not industry-specific** (as per chi-square test).
- Some industries and firms show **higher revenue impact**, but no direct causation.
