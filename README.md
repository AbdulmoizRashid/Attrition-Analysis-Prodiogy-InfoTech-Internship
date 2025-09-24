# Employee Attrition Analysis – Internship Task 2 (Prodigy InfoTech)

## Executive Summary
This project analyzes employee attrition using **Python** and **Jupyter Notebook**.  
The objective was to identify the main drivers of employee turnover and provide actionable insights for HR teams to improve retention.  

The analysis revealed two critical factors:  
- **Early-Career Vulnerability**: younger employees in lower job levels with limited income and experience are more likely to leave.  
- **Manager Disconnect**: employees under newer managers with shorter relationship tenure show higher attrition.  

---

## Business Problem
Employee attrition is a costly challenge for organizations. High turnover leads to:  
- Increased recruitment and training expenses  
- Loss of skilled talent and institutional knowledge  
- Reduced morale and productivity  

**Key business question**:  
*"Which factors contribute most to attrition, and how can HR address them to retain talent?"*

---

## Methodology
1. **Data Preparation** – cleaned dataset, handled categorical variables, created derived features such as `AgeGroup` and `ManagerTenureGroup`.  
2. **Exploratory Data Analysis (EDA)** – performed univariate, bivariate, and multivariate analysis with visualizations.  
3. **Feature Engineering** – grouped variables into strategic combinations (Early-Career Vulnerability, Manager Disconnect).  
4. **Insight Extraction** – identified patterns linking attrition with demographics, compensation, and managerial relationships.  

---

## Skills and Tools Used
- **Python** (Pandas, NumPy, Seaborn, Matplotlib)  
- **Data Visualization** (scatter plots, bar charts, line graphs, heatmaps)  
- **Exploratory Data Analysis (EDA)**  
- **Feature Engineering and Risk Flagging**  
- **Business Storytelling** – translating data into actionable HR insights  

---

## Results
- **Early-Career Vulnerability**: Employees aged 18–35, in Job Levels 1–2, with low income and limited working years showed the highest attrition.  
- **Manager Disconnect**: Employees with managers of less than 2 years tenure or weak relationship satisfaction were more likely to leave.  
- **Compensation and Growth**: Lower monthly income and fewer promotions correlated with higher exits.  

 *Insert visuals here for clarity:*  
- Scatter plot: `TotalWorkingYears vs MonthlyIncome` (colored by Attrition)  
- Bar chart: `AgeGroup + JobLevel + Gender vs Attrition`  
- Line chart: `ManagerTenureGroup + RelationshipSatisfaction vs Attrition`  

---

## Recommendations
- **Mentorship and Career Development**: Support early-career employees with mentorship and growth opportunities.  
- **Manager Training**: Provide onboarding and coaching for new managers to strengthen employee relationships.  
- **Compensation Review**: Benchmark salaries and ensure fair progression for entry-level roles.  
- **Retention Dashboard**: Implement HR dashboards with risk flags for vulnerable employee groups.

This project was completed as part of my **Data Science Internship at Prodigy InfoTech**.  
It demonstrates my ability to combine **technical analysis** with **business impact storytelling**.
