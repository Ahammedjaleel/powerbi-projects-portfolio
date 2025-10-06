# 📊 Department Spend Overview - Power BI Report
<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/ffa1cb50-5c66-4ed1-baf7-fae29094aec0" />


This Power BI report provides a comprehensive analysis of departmental spending across various expense types, employees, and regions. It is designed to help stakeholders understand where the organization is incurring costs, who is spending the most, and on what categories — enabling data-driven budgeting and cost optimization decisions.

---

## 🗂️ Report Overview

The **Department Spend Overview** report focuses on analyzing spending data across the following key dimensions:

- **Department**
- **Employee Name**
- **Employee Country**
- **Spend Category**
- **Expense Type**
- **Payment Type**
- **Transaction Date**

### 🎯 Key Features

- Dynamic **filters/slicers** for:
  - Department
  - Employee Name
  - Employee Country
  - Spend Category

- Interactive visuals including:
  - Cost distribution by Expense Type
  - Department-wise Spending Summary
  - Decomposition Tree for drilling into Actual Spending

---

## 📅 Dataset Description

The dataset includes detailed expense records with the following fields:

| Column Name               | Description |
|---------------------------|-------------|
| Year of Transaction Date  | Year of the transaction (e.g., 2017) |
| Quarter of Transaction Date | Fiscal quarter (e.g., Q3) |
| Month of Transaction Date | Month name (e.g., July) |
| Spend Category            | Broad category like "Meal" |
| Department                | Department name (e.g., Sales, TechOps) |
| Employee Name             | Name of employee incurring the expense |
| Expense Type              | Type of expense (e.g., Lunch, Hotel) |
| Payment Type              | Mode of payment (e.g., Cash/Out of Pocket) |
| Transaction Date          | Full transaction date |
| Approval Status           | Approval workflow status (e.g., Approved) |
| City/Location             | Transaction location (e.g., Seattle) |
| Employee Country          | Country where the employee is based |
| Actual Spending           | Actual amount spent in dollars |

Sample entries include lunch expenses incurred by employees in the Sales department during Q3 2017 in Seattle, United States.

---

## 📈 Key Visuals & Insights

### 1. 💸 **Cost Distribution by Expense Type**

- **Insight:** Hotels represent the highest spending category compared to other expense types such as meals or transportation.
- **Use Case:** Identifies where the bulk of the organization’s expenses are going, useful for negotiating better hotel rates or introducing policies to limit non-essential stays.

---

### 2. 🏢 **Spending by Department**

- **Insight:** The **TechOps** department stands out as having the highest overall spending.
- **Use Case:** This prompts a deeper dive into TechOps’ budget allocations and spending justifications, which could lead to strategic cost reviews.

---

### 3. 🌲 **Decomposition Tree (Actual Spending)**

- **Breakdown Path:**
  - **Department:** TechOps  
  - → **Employee Name:** Alice Cooper  
  - → **Expense Type:** Hotel

- **Insight:** Alice Cooper from TechOps has the highest actual spending, primarily on hotel expenses.
- **Use Case:** This allows leadership to explore individual-level spending and investigate whether travel policies and guidelines are being followed.

---

## 🧭 Key Takeaways

- **High hotel expenses** across departments may indicate potential for cost-saving through bulk booking deals or travel policy reviews.
- **TechOps is a cost-intensive department**, necessitating further review of operational spend.
- **Individual employee spend (e.g., Alice Cooper)** reveals opportunities for personalized budget control and policy enforcement.

---

## 📂 How to Use This Report

1. Open the Power BI report file (.pbix) in Power BI Desktop or Power BI Service.
2. Use the slicers to filter data by Department, Employee Name, Employee Country, or Spend Category.
3. Hover over visuals for tooltips and additional context.
4. Use the decomposition tree to explore spend patterns down to employee and expense-type levels.

---

## ✅ Business Value

By using this report, finance and operations teams can:

- Detect high-spending departments or individuals
- Analyze expense trends by category and time
- Make informed decisions to control and reduce operational costs

---

## 📌 Future Enhancements

- Add time series analysis for spend trends across years/quarters
- Integrate budget vs. actual comparison
- Include KPI cards for alerts on overspending

---


## 📁 Repository Contents

DepartmentSpendOverview.pbix     
---
## Let's Connect
[![github](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ahammedjaleel)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahammed-jaleel-33772b5b/)
---
## 🏷️ Tags

`Power BI` `Data Analysis` `Dashboard` `Business Intelligence` `Expense Tracking`  
`Financial Analysis` `Data Visualization` `Department Spending` `DAX` `Budgeting`


