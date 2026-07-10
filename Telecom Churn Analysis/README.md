# 📡 Telecom Customer Churn Analysis Dashboard

**Access Live Dashboard Here:** https://tinyurl.com/mpr52bvd

## 📊 Project Overview
This Power BI dashboard provides an in-depth, end-to-end analysis of customer churn for a telecommunications business. It is strategically engineered to identify distinct churn patterns, decode customer behavior, and uncover risk indicators to support data-driven customer retention strategies. 

The report is structured across multiple analytical views, allowing stakeholders to seamlessly explore churn dynamics from the perspective of customer profiles, service subscriptions, and billing configurations.

---

## 📌 Dashboard Structure

### 🧭 1. Executive Summary (Overview)
Provides a high-level baseline of the global customer dataset:
* **Total Customers:** 7,043
* **Customers Churned:** 2,000
* **Average Monthly Charges:** $64.76
* **Average Tenure:** 32.37 Months

**Key Insights:**
* The majority of the subscriber base utilizes high-speed **Fiber Optic** services.
* **Month-to-Month contracts** dominate the current customer contract mix.
* **Electronic Check** is identified as the most widely preferred payment method.
* Customer gender distribution across the entire dataset is almost perfectly equal.

### 📉 2. Churn Analysis Page
Focuses heavily on isolating where churn risk is concentrated across key account attributes:
* **Churn by Contract Type:** A significantly higher churn rate is observed in **Month-to-Month contracts** compared to long-term agreements.
* **Churn by Internet Service:** Fiber Optic users exhibit a higher churn propensity compared to traditional DSL subscribers.
* **Churn by Payment Method:** Customers utilizing **Electronic Checks** show a noticeably higher tendency to churn.
* **Churn by Gender:** Attrition distribution remains virtually identical across both male and female customer segments.

### 🔧 3. Churn by Services Page
Analyzes how the adoption of core and add-on services impacts customer stickiness:
* **Services Tracked:** Phone Service, Online Security, Tech Support, Streaming TV, Movie Streaming, and Device Protection.
* **Key Insights:**
  * Customers who *do not* subscribe to **Online Security** and **Tech Support** exhibit drastically higher churn rates.
  * The absence of value-added utility services strongly correlates with an increased churn risk profile.
  * Strategic onboarding of auxiliary services acts as a proven driver for improving long-term customer retention.

### 📊 4. Granular Usage Analysis
A detailed customer-level repository designed for deep-dive exploratory data analysis (EDA):
* **Granular Attributes:** Customer ID, Gender, Internet Service type, Payment Method, Monthly Charges, Tenure, and Total Cumulative Charges.
* **Interactive Slicers:** Dynamic filtering by *Partner status*, *Internet Service type*, and *Payment Method*.
* **Business Purpose:** Empowers retention teams to easily perform granular risk screening and proactively identify specific high-risk customer accounts.

---

## ⚙️ Technical Highlights

### 🗂 Data Modeling
* Engineered an optimized, structured data schema to facilitate lightning-fast cross-filtering and responsive dashboard load performance.

### 🧮 DAX Measures
* Formulated robust DAX expressions to track baseline and advanced KPIs, including:
  * **Total Customers** (Distinct counts)
  * **Churn Count & Churn Rate %**
  * **Average Charges & Revenue Realization**
  * **Tenure Distribution Analysis**

### 🎛 UI/UX & Interactivity
* Implemented intuitive multi-page custom navigation panels.
* Enabled synchronized dynamic slicing across separate report pages.
* Integrated granular drill-down pathways on visual matrices for deep exploration.

---

## 🛠 Tools Used
* **Power BI Desktop** – Report Architecture & Dashboard Design
* **Power Query** – ETL, Missing-Value Handling, and Feature Formatting
* **DAX (Data Analysis Expressions)** – Advanced Business Intelligence Metrics