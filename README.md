# DataAnalytics
Data Analytics project developed as part of the Deloitte Data Analytics Certification Program, analyzing industrial telemetry data using Tableau to identify factory downtime patterns and device-level failures.
# Daikibo Telemetry Data Analytics Dashboard

This project was developed as part of the **Deloitte Data Analytics Certification Program**.  
It focuses on analyzing industrial telemetry data from Daikibo factories to identify downtime patterns and device performance issues using **Tableau**.

---

## 📌 Project Objective
- Analyze telemetry data collected from multiple factories
- Identify factories with maximum downtime
- Drill down into device-level downtime causes
- Create an interactive Tableau dashboard for decision-making

---

## 🛠 Tools & Technologies
- Tableau (Calculated Fields, Filters, Dashboards)
- JSON Data
- Data Visualization
- Exploratory Data Analysis

---

## 📊 Dashboard Insights
### 1. Down Time per Factory
- Factory B identified as having the **highest downtime**
- Visual comparison across Factory A, B, and C

### 2. Down Time per Device Type (Filtered)
- Robot Arm contributes the highest downtime
- Followed by Conveyor and Sensor devices

---

## 🧮 Calculated Field Used
```text
Field Name: Unhealthy
Logic: IF [Status] = "Unhealthy" THEN 10 ELSE 0 END
