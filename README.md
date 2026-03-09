# 🏥 Hospital Emergency Room Analytics Dashboard (Power BI)

## 📊 Project Overview

This project analyzes hospital Emergency Room (ER) operations using Power BI to uncover insights about patient flow, wait times, referrals, and demographics.

The goal is to transform raw operational data into actionable insights that can help hospitals optimize staffing, reduce patient wait times, and improve overall patient experience.

The dashboard provides an interactive view of Emergency Room performance from **April 2023 to October 2024**, covering **9,216 unique patient records**.

---

## 🎯 Project Objectives

- Analyze ER patient volumes and admission patterns
- Evaluate patient wait times and satisfaction levels
- Identify peak hours and busiest days in the ER
- Understand patient demographics and referral trends
- Provide insights to support better hospital resource planning

---

## 🛠 Tools & Technologies

- **Power BI**
- **Power Query (ETL)**
- **DAX**
- **Data Modeling (Star Schema concepts)**

---

## 🔧 Data Preparation

The dataset was prepared using Power Query and involved several transformation steps:

- Data cleaning and formatting
- Standardizing categorical columns (e.g., Gender values)
- Creating derived columns such as:
  - Month
  - Year
  - Hour
- Creating a **Date Dimension Table** for time-based analysis
- Establishing relationships between tables for analytical reporting

---

## 📊 Dashboard Pages

### 1️⃣ Consolidated View

![Consolidated View](dashboards/Consolidated%20View.PNG)

Provides an overview of ER performance including:
- Total number of patients
- Average wait time
- Patient satisfaction score
- Admission status
- Patient demographics
- Department referrals
- Peak visit times

### 2️⃣ Monthly View

![Monthly View](dashboards/Monthly%20View.PNG)

Allows detailed analysis for a selected month, including:
- Monthly patient volume
- Average wait time
- Monthly satisfaction score
- Demographic distribution
- Department referrals
- Hourly patient traffic

### 3️⃣ Patient Details

![Patient Details](dashboards/Patient%20Details.PNG)

A detailed table view containing patient-level information such as:
- Patient ID
- Age
- Gender
- Race
- Wait Time
- Admission Status
- Department Referral

---

## 📈 Key Insights

### Patient Volume
- **9,216 patients** visited the ER over **19 months**

### Wait Time & Satisfaction
- **Average wait time:** 35.3 minutes
- **Average satisfaction score:** 4.99 / 10

### Admission Patterns
- **Admitted:** 4,612 patients
- **Not admitted:** 4,604 patients  
This indicates an almost equal distribution between admitted and released patients.

### Department Referrals
- **No referral:** 5,400 patients
- **General Practice:** 1,840
- **Orthopedics:** 995
- **Physiotherapy:** 276
- **Cardiology:** 248

### Peak ER Activity
**Busiest Days**
- Saturday: 1,377 patients
- Thursday: 1,332 patients

**Peak Hours**
- 11 AM
- 1 PM
- 7 PM
- 11 PM

These periods may require increased staffing.

### Patient Demographics
**Largest Age Groups**
- 30–39 years: 1,200 patients
- 20–29 years: 1,188 patients

**Race Distribution**
- White: 2,571
- African American: 1,951
- Multi-racial: 1,557
- Asian: 1,060
- Declined to identify: 1,030

---

## 💡 Business Impact

The insights from this dashboard can help hospitals:

- Improve ER staffing during peak hours
- Reduce patient wait times
- Optimize department referrals
- Better understand patient demographics
- Improve overall patient satisfaction

---

## 📌 Skills Demonstrated

- Healthcare Data Analysis
- Data Cleaning & Transformation
- Data Modeling
- DAX Calculations
- Dashboard Design
- Insight Generation
## 👤 Author
---

**Jameel Hanouneh**

Biomedical Engineering Graduate  
Aspiring Healthcare Data Analyst

