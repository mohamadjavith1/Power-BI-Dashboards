# 🏭 Factory Telemetry Analysis – Finding Machine Breakdowns with Power BI

**Access Live Dashboard here:** https://tinyurl.com/mr9k3xt

## 📊 Project Overview
This data analysis project focuses on manufacturing efficiency for **Daikibo**, a global manufacturer with four major production hubs: Tokyo, Osaka, Berlin, and Shenzhen. The objective was to transform a month’s worth of raw telemetry data (May 2021) into a high-impact, actionable dashboard that pinpoints exactly where and why production lines are stalling.

---

## 🎯 The Problem Statement
The client needed to answer two critical operational questions to minimize costly manufacturing downtime:
1. **Location Analysis:** In which factory location do machines break down the most?
2. **Root Cause Analysis:** Which specific machine types are responsible for the highest frequency of failures in that high-risk location?

---

## ⚙️ Technical Approach

* **Data Source:** Processed a single, high-frequency JSON file containing telemetry messages transmitted every 10 minutes across 9 distinct machine types.
* **Data Transformation (ETL):** Utilized **Power Query** to flatten the nested JSON structure, clean timestamps, and optimize data types for high-performance querying.
* **Data Modeling:** Built a minimalist **Star Schema** to maintain a lightweight file size and ensure rapid, responsive cross-filtering.
* **Visualization & UI Design:** Designed a focused, single-page dashboard. Prioritized high scannability over visual clutter, using sorted bar charts and dynamic KPI cards to make the worst-performing factories and machines instantly recognizable.

---

## 🚀 Key Insights & Impact
* **Downtime Bottlenecks:** By filtering the telemetry data specifically for "breakdown" status indicators, the dashboard immediately isolates the bottleneck factory.
* **Targeted Maintenance:** Pinpoints the exact machine models driving the failures in the at-risk facility, moving the client from reactive troubleshooting to targeted preventative maintenance.