# 📊 Inventory Analysis Dashboard – Power BI
## 🧾 Project Description
This Power BI dashboard provides a comprehensive analysis of inventory and warehouse performance using ABC/XYZ inventory classification, KPI cards, vendor ranking, and reorder tracking. It's designed for warehouse managers, inventory analysts, and supply chain teams to optimize stock, reduce holding costs, and improve inventory efficiency.
## Screenshots
<img width="866" height="492" alt="image" src="https://github.com/user-attachments/assets/5b1c606c-17ad-4380-b3be-f657644d16b1" />



## 📁 Dashboard Features & Visuals
🔹 1. Card Visuals (KPIs)

| Card Metric              | Description                                                                  |
| ------------------------ | ---------------------------------------------------------------------------- |
| **Total Number of SKUs** | Displays the total number of unique inventory items (Stock Keeping Units).   |
| **Inventory Value**      | Shows the total monetary value of all items in stock.                        |
| **Inventory Turnover**   | Indicates how efficiently inventory is being sold and replenished over time. |

## 🔄 Inventory Turnover – Explained

Inventory Turnover is a measure of how often inventory is sold and replaced in a period.
## 📌 Formula:

`Inventory Turnover = Revenue / Inventory Value
`

## 📈 Interpretation:
| Turnover Rate | What it Means                                             |
| ------------- | --------------------------------------------------------- |
| **High**      | Fast-moving inventory – good efficiency.                  |
| **Low**       | Slow-moving inventory – potential overstock or low sales. |


## ✅ Business Use:
Detect slow vs fast-moving stock

Optimize inventory holding cost

Guide purchasing and replenishment decisions

## 🔹 2. Donut Charts
| Visual                              | Description                                                 |
| ----------------------------------- | ----------------------------------------------------------- |
| **Inventory Value by Warehouse**    | Compares the total stock value across different warehouses. |
| **Inventory Quantity by Warehouse** | Displays unit counts of inventory items by warehouse.       |

## 🔹 3. Bar Charts
| Visual                                  | Description                                                      |
| --------------------------------------- | ---------------------------------------------------------------- |
| **Top 5 Vendors by Inventory Value**    | Identifies which vendors contribute the most by inventory value. |
| **Top 5 Vendors by Inventory Quantity** | Highlights vendors supplying the most units.                     |

## 🔹 4. Gauge Chart
| Visual                  | Description                                                                                                |
| ----------------------- | ---------------------------------------------------------------------------------------------------------- |
| **Stock Reorder Level** | Shows current inventory level against a defined reorder threshold. Alerts when stock nears minimum levels. |

## 🔹 5. ABC & XYZ Inventory Analysis
🅰️ ABC Analysis (Based on Inventory Value Contribution)

ABC analysis categorizes inventory based on its financial impact:

| Category | Meaning            | Contribution               |
| -------- | ------------------ | -------------------------- |
| **A**    | High-value items   | ~70-80% of inventory value |
| **B**    | Medium-value items | ~15-25% of value           |
| **C**    | Low-value items    | ~5-10% of value            |


Purpose: Focus control on high-value items for cost optimization.

❌ XYZ Analysis (Based on Demand Variability)


XYZ analysis classifies items by demand stability:
| Category | Meaning              | Description                          |
| -------- | -------------------- | ------------------------------------ |
| **X**    | Stable               | Predictable usage, consistent demand |
| **Y**    | Moderate variability | Seasonal or moderate fluctuations    |
| **Z**    | Unstable             | Irregular, unpredictable usage       |

Purpose: Helps with forecasting and supply planning.


🧠 ABC/XYZ Matrix
Combining both analyses gives a 9-segment matrix for better stock control.
| ABC/X | X  | Y  | Z  |
| ----- | -- | -- | -- |
| **A** | AX | AY | AZ |
| **B** | BX | BY | BZ |
| **C** | CX | CY | CZ |

Example Interpretations:


AX → High value + stable demand → High priority, tight control

CZ → Low value + unstable → Low priority, minimal stock

## ⚙️ Tools & Technologies Used

Power BI Desktop

Power Query

DAX (Data Analysis Expressions)

Relational Data Modeling

Custom Measures for ABC/XYZ
