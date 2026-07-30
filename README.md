# Healthcare RCM & Denial Intelligence Dashboard 📊🏥

## 📌 Project Overview
This repository contains the architecture, data modeling, and DAX calculations for a comprehensive **Revenue Cycle Management (RCM) Intelligence Dashboard** built in **Microsoft Power BI**. 

The goal of this project is to analyze clinical billing data, identify key drivers of claim denials, and provide actionable insights to reduce revenue leakage in US Healthcare workflows.

> **Status:** 🚧 *Data transformation, ETL pipelines, and reporting metrics are currently being finalized and published.*

## 🛠️ Tech Stack & Methodologies
* **Business Intelligence:** Power BI (Desktop & Service)
* **Data Modeling:** Dimensional Data Modeling (Star Schema)
* **Calculations:** Advanced DAX (CALCULATE, FILTER, SUMX, Time Intelligence)
* **ETL & Automation:** Power Query (M-Query) for data cleaning and validation
* **Domain Focus:** Healthcare RCM, Medical Billing (ICD-10/CPT), Claim Denials, HIPAA Compliance awareness

## 📂 Project Architecture (In Progress)
### 1. Data Transformation (Power Query)
* Handling missing values and standardizing unstructured medical billing datasets.
* Normalizing payer data and clinical documentation records.

### 2. Data Modeling (Star Schema)
* **Fact Table:** `Fact_Claims` (Contains claim amounts, dates, and denial status)
* **Dimension Tables:** `Dim_Patients`, `Dim_Payers`, `Dim_Denial_Codes`, `Dim_Calendar`

### 3. Key Performance Indicators (DAX)
Core measures being implemented:
* Total Billed Revenue vs. Total Denied Revenue
* Claim Denial Rate (%)
* Average Claim Cycle Time (Days)
* Top Denial Reasons by Payer

## 💡 Business Impact
By transitioning raw operational claims data into interactive visual insights, this dashboard allows healthcare analysts to isolate systemic coding errors, track payer-specific denial trends, and optimize the overall revenue cycle.
