# 📊 HR Employee Attrition Analysis Dashboard

> An interactive HR Analytics dashboard built with **Microsoft Power BI, Power Query, DAX and Excel** to analyze employee attrition, identify key influencing factors, and explore high-risk employee segments.

---

## 🖼️ Dashboard Preview

<img width="1736" height="791" alt="image" src="https://github.com/user-attachments/assets/07fa29da-0b4e-444e-933f-4a58676f8620" />
<img width="1580" height="797" alt="image" src="https://github.com/user-attachments/assets/383d39ab-9b4a-425d-9ab8-a2fb999e4906" />
<img width="1540" height="786" alt="image" src="https://github.com/user-attachments/assets/0c958d5f-27d2-4893-b663-6e70e7fd95bf" />
<img width="1482" height="782" alt="image" src="https://github.com/user-attachments/assets/2ca5640f-09c1-4555-a8f8-705034f83b05" />
<img width="1492" height="790" alt="image" src="https://github.com/user-attachments/assets/6fa9f2a1-4e6d-485a-bbe2-be44c24920d5" />






---

## 🎯 Project Overview

Employee attrition is a major challenge for organizations because high employee turnover can increase recruitment costs, reduce productivity, and affect overall business performance.

This project analyzes the **IBM HR Analytics Employee Attrition dataset** to understand employee demographics, job characteristics, compensation, overtime, work-life balance, and other factors associated with employee attrition.

The raw HR data is transformed into an interactive and user-friendly dashboard using **Microsoft Power BI, Power Query, and DAX**.

---

## 📌 Project Objectives

- Analyze overall employee attrition
- Calculate and monitor attrition rate
- Identify major factors influencing attrition
- Compare attrition across departments and job roles
- Analyze the impact of overtime
- Analyze work-life balance and business travel
- Explore employee-level information
- Identify high-risk employee segments
- Provide interactive HR insights for data-driven decisions

---

## 📊 Dataset Overview

| Attribute | Details |
|---|---|
| Dataset | IBM HR Analytics Employee Attrition |
| Total Employees | 1,470 |
| Attributes | 35 |
| Target Variable | Attrition |
| Data Type | HR Employee Data |

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI** — Dashboard & Data Visualization
- **Power Query** — Data Cleaning & Transformation
- **DAX** — Measures & Calculated Columns
- **Microsoft Excel** — Data Source
- **Data Analytics** — Exploratory Analysis
- **HR Analytics** — Employee Attrition Analysis

---

# 📑 Dashboard Pages

## 1️⃣ Home

A clean landing page that introduces the project and provides navigation to the dashboard sections.

### Highlights
- Project Introduction
- Dataset Overview
- Dashboard Navigation
- Project Information

---

## 2️⃣ Executive Overview

Provides a high-level summary of the organization's workforce.

### KPI Cards

- 👥 Total Employees
- 📉 Attrition Rate
- ⏳ Average Tenure
- 💰 Average Monthly Income

### Visualizations

- Attrition Rate by Department
- Headcount by Gender

---

## 3️⃣ Attrition Drivers

This page explores the major factors associated with employee attrition.

### Visualizations

- Attrition Rate by OverTime
- Attrition Rate by Job Role
- Attrition Rate by Marital Status
- Attrition Rate by Business Travel
- Attrition Rate by Job Level
- Attrition Rate by Work-Life Balance
- Monthly Income vs Age by Attrition

### Interactive Filters

- Department
- Job Level
- Gender
- Marital Status
- Business Travel
- OverTime

---

## 4️⃣ Employee Explorer

An interactive employee-level analysis page that allows users to explore individual employee records.

### Key Information

- Department
- Job Role
- Attrition
- Monthly Income
- Years at Company
- High Risk Flag

### Filters

- Department
- Job Role
- Gender
- Attrition
- High Risk Flag

---

## 5️⃣ AI Insights

An advanced analytics page using Power BI analytical features.

### 🔍 Key Influencers

Analyzes factors that influence employee attrition, including:

- OverTime
- Job Level
- Stock Option Level
- Job Role
- Work-Life Balance
- Business Travel
- Job Satisfaction

### 🌳 Decomposition Tree

Provides an interactive breakdown of:

**Attrition Count → Department → Job Role → OverTime**

This helps users drill down into specific employee segments and understand where attrition is concentrated.

---

# 📈 Key DAX Measures

## Total Employees

```DAX
Total Employees =
COUNTROWS(RawData)
