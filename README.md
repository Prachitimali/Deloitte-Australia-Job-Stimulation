# 🏭 Deloitte Australia job Stimulation via Forage

## 📌 Project Overview
This project focuses on analyzing two major datasets provided by Daikibo Industrials:
1. **Telemetry data** from machines across four international factories (May 2021).
2. **Employee compensation data** to assess gender pay equality across job roles and locations.

## ❓ Questions to Be Answered
**Task 1 – Telemetry Analysis**
- Which Daikibo factory experienced the most machine downtime?
- Which machine types were responsible for the most downtime in that factory?

**Task 2 – Pay Equality Analysis**
- Which job roles and locations demonstrate fair, unfair, or highly discriminatory pay practices based on gender?

## 🧪 Analysis Method
**Telemetry Data:**
- Imported `.json` data into Tableau.
- Created a calculated field called **"Unhealthy"** assigning 10 minutes per unhealthy machine report.
- Built bar charts:
  - *Down Time per Factory*
  - *Down Time per Device Type*
- Created an interactive dashboard using factory-wise filters.

**Equality Data:**
- Used Excel to classify the **Equality Score** into:
  - *Fair* (±10)
  - *Unfair* (< -10 or > 10)
  - *Highly Discriminative* (< -20 or > 20)
- Added a new column `Equality class` using logical formulas.

## 📊 Insights After Analysis
- The factory with the highest downtime was **[Factory Name]**, and the top failing machine types were **[Machine Types]** (from Tableau analysis).
- Several roles across regions showed signs of **high pay inequality**, notably in **[highlighted roles or factories]**.

## 🛠️ Tools Used
- Tableau (Data Visualization & Dashboarding)
- Microsoft Excel (Data Transformation & Classification)
- JSON Data Parsing

## ✅ Conclusion
The analysis helped Daikibo identify critical operational inefficiencies and pay disparities. The insights will guide both maintenance strategies and HR policy improvements.
