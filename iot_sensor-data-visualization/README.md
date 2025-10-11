

## 📸 Dashboard Preview

Below are sample screenshots from the Power BI dashboard, showcasing different views of the sensor data analysis:

### 1️⃣ Overview Page
<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/93b6d3c9-9988-41f8-bebc-1c89c37e8839" />



### 2️⃣ CO & Smoke Analysis
<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/493b30ff-fbce-439f-9b07-6afb93e98569" />


### 3️⃣ Alert Timing Insights
<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/5dcc024e-9a53-422b-b374-303deb556941" />


### 4️⃣ LPG & Smoke Analysis 
<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/036a914b-a282-46a4-8ccb-88d280f141b2" />

### 5️⃣ Motion & Environment Analysis
<img width="1302" height="732" alt="image" src="https://github.com/user-attachments/assets/0f098076-42e5-464c-9bde-ff429336e5a3" />


# 📊 Sensor Data Analysis Dashboard – Power BI

This Power BI project presents an in-depth analysis of **sensor data** collected from various environmental and motion detectors. It includes measurements such as **CO**, **humidity**, **LPG**, **motion**, **smoke**, and **temperature**.

The dashboard follows a **storytelling approach** to uncover patterns and correlations that can inform safety, automation, and monitoring decisions — applicable in real-world contexts like **smart homes**, **industrial safety**, and **environmental control systems**.

---
## 🧾 Dataset Overview

This project uses **real-time sensor data** collected from a smart device identified by its MAC address. The dataset includes time-series readings from multiple environmental and motion sensors:

### 📌 Key Columns in the Dataset:
- **ts**: Timestamp of the reading (date and time)
- **device**: Device identifier (MAC address)
- **co**: Carbon monoxide levels
- **humidity**: Relative humidity (%)
- **light**: Light intensity (value varies by sensor)
- **lpg**: LPG (liquefied petroleum gas) concentration
- **motion**: Motion detected (binary: 0 = no motion, 1 = motion)
- **smoke**: Smoke level detected
- **temp**: Temperature in Celsius
- **Alert**: Indicates whether an alert was triggered (0 = normal, 1 = alert)
- **CO_Smoke_Spike**: Custom tag indicating unusual spikes in CO or smoke levels

### 🧠 Time Intelligence Columns:
- **Date, Time, Hour, Day, Month**: Extracted using Power Query and used for time-series analysis

This rich dataset enables detailed **environmental monitoring**, anomaly detection, and pattern recognition based on both **sensor inputs** and **human activity indicators** (e.g., motion detection).

---

## 🌍 Environmental Monitoring and Sensor Data Analysis Using Power BI

This Power BI dashboard provides a comprehensive analysis of **multi-sensor IoT data**, offering meaningful insights into:

- 🏠 **Indoor air quality** (CO, smoke, LPG)
- 🔥 **Fire risk indicators** through CO–smoke correlation
- 🚶 **Motion-triggered alerts** linked to human activity
- 🕒 **Time-based trends** in temperature and environmental behavior

The dashboard is designed with **storytelling visuals** to support real-time monitoring and decision-making in domains such as **smart homes**, **industrial safety**, and **environmental automation**.

---

## 🔧 Tools & Technologies

- **Power BI** – Data visualization and reporting
- **Power Query** – ETL processes for sensor data
- **DAX** – KPI calculations and time intelligence
- **Power BI Dataflows** – Reusable transformation pipelines
- **Azure Data Factory** – Ingesting and orchestrating data pipelines
- **Azure Data Lake** – Scalable data storage and access

---

## 📌 Project Overview

| Attribute        | Details                                                                 |
|------------------|--------------------------------------------------------------------------|
| 🛠️ **Built With** | Power BI Desktop                                                        |
| 📁 **Data Source**| IoT sensor readings (CO, humidity, LPG, motion, smoke, temperature)     |
| 🎯 **Goal**       | Discover relationships between environmental conditions and human activity |
| 💡 **Use Cases**  | Smart homes, fire detection, gas leak alerts, safety automation         |

---




---

## 📦 Example Data Snapshot

| ts                   | device              | co         | humidity | light | lpg        | motion | smoke     | temp | Alert | CO_Smoke_Spike |
|----------------------|---------------------|------------|----------|-------|------------|--------|-----------|------|--------|----------------|
| 17/07/2020 11:01:15  | b8:27:eb:bf:9d:51   | 0.0059     | 53.3     | 0     | 0.0086     | 0      | 0.0233    | 22.2 | 0      | Normal         |
| 17/07/2020 11:01:18  | b8:27:eb:bf:9d:51   | 0.0059     | 53.3     | 0     | 0.0087     | 0      | 0.0233    | 22.2 | 0      | Normal         |
| ...                  | ...                 | ...        | ...      | ...   | ...        | ...    | ...       | ...  | ...    | ...            |

---

## 🔍 Key Insights & Storytelling Findings

This dashboard delivers actionable insights by combining environmental sensor data with motion patterns over time. The goal is to understand how different environmental variables relate to each other — and to human activity — to improve safety and monitoring outcomes.

---

### 💨🔥 CO and Smoke Levels Move Together

There is a **clear, consistent correlation** between **carbon monoxide (CO)** and **smoke levels** across the dataset. These two variables rise and fall together, which suggests they often originate from the **same source** — such as **cooking**, **burning**, or other combustion-based activities.

> ✅ **Impact:** Monitoring these two indicators together enhances **early detection** of potentially hazardous situations like fires or indoor pollution events.

---

### 🚨🕙 Alerts Are Triggered by Human Activity

Alert data reveals that hazards are **only triggered when motion is detected**, meaning they are **closely tied to human presence or behavior**.

- **No alerts are recorded during inactive periods**, particularly early mornings (4:00 AM – 10:00 AM).
- **Most alerts occur between 7:00 PM and 10:00 PM**, aligning with evening activity and peaks in CO and smoke.

> ✅ **Impact:** The environment is generally **safe when unoccupied**, and **alert logic is effectively linked to human-triggered events**.

---

### 🛢️❌ No Link Between LPG and Smoke Levels

Analysis shows **no observable correlation** between **LPG** and **smoke levels**. Throughout the monitoring period:

- All **LPG readings remained low**, showing **no spikes** or abnormal behavior.
- No events suggested potential gas leaks or LPG-related safety concerns.

> ✅ **Impact:** Indicates **no gas leaks** occurred during data collection, and confirms the reliability of the environment with respect to LPG safety.

---

### 😴🔍 Motion Patterns Do Not Influence Environmental Variables

Motion was largely **absent between 4:00 AM and 10:00 AM**, and overall patterns of activity appeared **sporadic** throughout the day.

- There is **no meaningful correlation** between motion events and changes in **CO, smoke, or LPG** levels.
- Even when motion is detected, **gas and smoke readings remain stable**.

> ✅ **Impact:** Confirms that **human activity has minimal environmental impact** under normal conditions, and that the system can distinguish between passive and risk-related activity.

---

---

## 📁 Files Included

- `IoT Insights Dashbord.pbix` – Power BI dashboard file
- `README.md` – This documentation

---



## 📈 Potential Applications

- 🏠 Smart Home Monitoring
- 🏭 Industrial Safety Dashboards
- 🌍 Environmental Condition Tracking
- 🔥 Fire and Gas Leak Risk Detection


---
## Let's Connect
[![github](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ahammedjaleel)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahammed-jaleel-33772b5b/)
---
## 🔖 Tags

`Power BI` • `IoT Data` • `Sensor Analysis` • `Environmental Monitoring` • `Smart Home` • `Data Visualization` • `Power Query` • `DAX` • `Azure Data Factory` • `Azure Data Lake` •  `Motion Detection` • `Gas Leak` • `Time Series` • `Air Quality` • `Storytelling` • `Dashboard`



