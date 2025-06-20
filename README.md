# 🩺 Patient Readmission & Care Analytics Dashboard

An advanced healthcare analytics project focused on identifying the cost, clinical, and operational factors contributing to patient readmissions using a synthetic dataset. The dashboard uncovers patterns in demographics, risk, provider behavior, and financial outcomes.

---

## 📊 Project Overview

This 4-page dashboard was built using **18 structured synthetic healthcare datasets** from Synthea, discovered through a real-world **healthcare business case study**. It models over:

- **250K+ encounters**
- **100K+ claims**
- **5K+ providers**
- **13K+ medical supplies**

---

## 📁 Dashboard Pages

| Page | Title | Description |
|------|-------|-------------|
| **1️⃣** | **Patient Overview & Segmentation** | Gender, age, and chronicity-based segmentation with COVID impact, observation patterns, and encounter distribution. |
| **2️⃣** | **Readmission Analysis** | Trends and drivers of readmission rates by condition type, age group, and time. Risk segmentation included. |
| **3️⃣** | **Claim & Cost Analytics** | Complexity of claims, payment timelines, cost concentration, claim types, and collection rates. |
| **4️⃣** | **Provider & Supply Insights** | Performance metrics by provider specialty and location. Costliest procedures, most used supplies, and prescribing patterns. |

> 📷 Screenshots of all four pages (unfiltered) are provided in the `/Dashboard Preview` folder.

---

## 🛠️ Tech Stack

| Step | Tools Used |
|------|------------|
| **Data Source** | Synthea (18 synthetic healthcare CSVs) |
| **Initial Cleaning** | Excel |
| **Storage & Queries** | MySQL |
| **ETL & Prep** | Power Query Editor |
| **Visualization** | Power BI (main), Tableau (for planned comparative analysis) |
| **Analytics** | DAX measures & calculated columns (LOS, Readmission Rate, Claim Collection Rate,  Risk Segments, Claim Duration Buckets, etc.) |

---

## 📌 Key Insights (Across All Pages)

| Insight | Finding |
|--------|---------|
| 🔁 **Readmission Rate** | Avg. **37.6%**, with **lowest in age 36–50 (28.74%)** |
| ⚕️ **Cause of Readmissions** | **63%** driven by **chronic conditions** |
| 🧒 **COVID Burden** | Highest in age group **0–18 (40%)** |
| 🍺 **Top Frequent Condition** | **Unhealthy alcohol use** |
| 💉 **Most Expensive Procedure** | **Medication reconciliation** (\$2.5K avg.) |
| 🧪 **Top Supply by Volume** | **Nitrile examination gloves** |
| 💳 **Best Claim Recovery** | **1–3 months** window with **79% collection rate** |
| 🩺 **Top Diagnosis Reason** | **Diabetes**, across medications and outcomes |

---

## 🎯 Key Takeaways

- **Clinically actionable**: Identifying chronic disease as the top readmit factor helps optimize discharge and post-care planning.
- **Operational impact**: Readmission trends by age group can inform **bed forecasting** and **staff allocation**.
- **Financial optimization**: Claims processed within 1–3 months recover faster — supports **process improvement initiatives**.
- **Inventory planning**: High-demand supplies like nitrile gloves and high-cost procedures highlight **procurement and billing priorities**.
- **Targeted prevention**: Conditions like diabetes and alcohol misuse can be flagged for **preventive care intervention strategies**.
- **Pandemic preparedness**: COVID-19 age analysis showed **children (0–18)** as the most affected age group (40%) — supports **targeted vaccination and school policy planning**.
- **Tool diversification**: Tableau is planned for **comparative analysis** of regional trends and dashboard adaptability across platforms.

---

## 🏥 Real-World Applications

- **Hospitals & Clinics**: For discharge planning, readmission risk scoring, and COVID response strategies.
- **Healthcare BI Teams**: Replicable framework for EHR analytics and executive dashboards.
- **Consulting Firms**: Can adapt to pharmaceutical segmentation, IC design, or payer analytics cases.

---

## 📬 Contact

Chaitanya Moudgil 
Email: chaitanya.moudgil5112@gmail.com 
LinkedIn: www.linkedin.com/in/chaitanya-moudgil-da  
