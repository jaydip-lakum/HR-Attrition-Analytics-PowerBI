# HR Attrition & Workforce Analytics Dashboard 📊

**Live Dashboard / Snapshot:** 
![Dashboard Preview](https://github.com/jaydip-lakum/HR-Attrition-Analytics-PowerBI/blob/main/HR_Employee_Attrition_Dashboard.jpg)

## 📌 Quick Overview
A highly interactive Power BI dashboard analyzing employee attrition and retention trends for a dataset of **400 employees**. Built with a focus on premium corporate UI/UX to help HR teams make data-driven retention strategies.

## 🛠️ Tech Stack
**Power BI | DAX | Power Query | Data Visualization | UI/UX Design**

## 💡 Key Business Insights
- **Overall Attrition:** The company faces an attrition rate of **24.25%** (97 out of 400 employees left).
- **High-Risk Areas:** **IT (23)** and **Sales (21)** departments have the highest turnover rates.
- **Overtime Factor:** Strong visual correlation found between overtime work and employee exits.
- **Tenure vs. Income:** Scatter plot analysis reveals specific clusters of employees leaving based on their salary progression and years at the company.

## ⚙️ Key DAX Measures
- `Total Employees` = COUNTROWS('Table')
- `Attrited Employees` = CALCULATE(COUNTROWS('Table'), Attrition = "Yes")
- `Attrition Rate %` = [Attrited Employees] / [Total Employees]

## 🚀 Features
- **Clean Corporate UI/UX:** Built using modern design principles (soft shadows, light theme, whitespace).
- **Dynamic Cross-Filtering:** Clickable KPIs and charts for instant department and gender-wise drill-downs.
