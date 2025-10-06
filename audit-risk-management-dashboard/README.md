
# 🛡️ Audit, Risk & Compliance Dashboard 
<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/348e2d9f-bd8f-41de-875f-64fec165d7fe" />

This project presents an interactive **Audit, Risk, and Compliance Dashboard** developed using **Power BI**. It allows users to explore audit status, risk ratings, responsible departments, geographic locations, and financial exposure in a dynamic and visual manner.

The dashboard is designed to assist:
- **Audit and Risk Managers**
- **Compliance Officers**
- **Executives**
- **Business Analysts**
in identifying high-risk areas, tracking audit progress, and allocating audit responsibilities efficiently.

---

## 📁 Dataset Overview

The dataset includes audit entries spanning multiple years and cities, covering various departments and risk types. The key fields are:

| Column                    | Description |
|---------------------------|-------------|
| `Audit Status`           | Current stage of the audit (e.g., Pending, Fieldwork) |
| `Assigned Audit Manager` | Person responsible for the audit |
| `Cities`, `Latitude`, `Longitude` | Geographic information for mapping |
| `Risk Identified`        | Description of the identified risk |
| `Risk Type`              | Category of risk (e.g., IT, Finance, HR) |
| `Risk Rating`            | Numeric score denoting severity: **Low (30)**, **Medium (50)**, **High (70)** |
| `Department`             | Department responsible for managing the risk |
| `Total Amount`           | Financial amount associated with the risk |
| `Audit Outcome`          | Status of the audit (e.g., Work in progress) |
| `Beg Audit Date`, `End Audit Date` | Timeline of the audit |
| `Entity`, `Office Name`, `Year` | Organizational metadata |

> 📌 **Filters (Slicers) in the dashboard**:  
> Year ▪ Quarter ▪ City ▪ Department ▪ Risk Type

---

## 📊 Key Visuals and Insights

### 1. **Managerial Risk Allocation**
- **Chart**: Pie/Bar showing % of total risks managed per Audit Manager.
- **Insight**:  
  > **Mark Tucker** manages approximately **60%** of all recorded audit risks, which may indicate either an expertise concentration or resource allocation imbalance.

---

### 2. **Risk Rating by Audit Outcome**
- **Chart**: Stacked bar showing distribution of risk levels across audit outcomes.
- **Insight**:  
  > About **66% of high-risk items** are still in a "Work in progress" state, highlighting areas of concern in audit resolution timelines.

---

### 3. **Risk Mapping by Location and Department**
- **Chart**: Azure Map plotting audits by latitude and longitude, colored by department and sized by risk rating.
- **Insight**:  
  > Cities like **Bedford, Green Bay, and Springfield** show concentrations of **high-risk audits**—especially in **IT and Finance-related departments**.

---

### 4. **Risk Breakdown by Department**
- **Chart**: Grouped bar showing Low, Medium, High risks by Department.
- **Insight**:
  - **Strategic Planning** carries the **highest risk rating** overall.
  - **HR Department** isn't highest in rating, but has the **highest associated financial exposure**, indicating hidden vulnerability.

---

## 🎯 Key Takeaways

- 🔴 **High-Risk Backlog**: Most high-rated risks remain unresolved (Work in progress).
- ⚖️ **Uneven Managerial Load**: Risk distribution across managers is unbalanced.
- 🗺️ **Geographic Clusters**: Certain cities consistently show higher risks.
- 🏢 **Departmental Red Flags**: Strategic Planning and HR departments require immediate attention based on rating and financial exposure.

---
### 📂 Included File

**`Audit_Risk_Dashboard.pbix`**  
This is the main Power BI report file containing the interactive **Audit, Risk & Compliance Dashboard**. It includes all visuals, filters, and the data model used to analyze audit statuses, risk levels, departmental exposure, and geographic distribution of risks.

> 🧩 Open this file in **Power BI Desktop** to explore or customize the dashboard.
---
## 🚀 How to Use This Dashboard

1. **Download** the `.pbix` file from this repository.
2. **Open** it using **Power BI Desktop**.
3. Use the **slicers** to explore:
   - Specific **Years**
   - **Quarters**
   - **Cities**
   - **Departments**
   - **Risk Types**
4. **Interact** with the visuals to view distribution, manager workload, audit outcomes, and risk mapping.

---

## 🛠️ Technologies Used

- **Microsoft Power BI Desktop**
- **Azure Maps** (for location visualization)
- **Data Model with DAX Calculations**
- Slicers and visual interactions for dynamic filtering

---

### 🏷️ Tags

`#PowerBI` `#AuditDashboard` `#RiskManagement` `#Compliance` `#DataVisualization`  
`#BusinessIntelligence` `#AzureMaps` `#RiskAnalytics` `#PowerBIDashboard` `#InternalAudit`  
`#Governance` `#DataAnalysis` `#FinancialRisk` `#RiskAssessment` `#DepartmentalRisk`
