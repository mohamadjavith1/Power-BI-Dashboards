# 🌦 Live IoT Weather Dashboard – Real-Time Analytics System

**Access Live Dashboard here:** https://tinyurl.com/3je5c5jw

## 📊 Project Overview
This project is a real-time weather analytics dashboard powered by a custom-built IoT weather station. Unlike traditional dashboards that rely on static or historical datasets, this solution captures live environmental data and transforms it into actionable insights through Power BI.

The project demonstrates an end-to-end data pipeline, integrating IoT hardware, cloud storage, data transformation, and interactive visualization.

---

## ⚙️ Technical Overview

### 📡 Data Collection
Built using an ESP8266 microcontroller with DHT11 and BMP280 sensors to capture real-time:
* Temperature
* Humidity
* Atmospheric Pressure

### ☁️ Cloud Integration
Sensor data is continuously transmitted to Google Sheets, providing a lightweight cloud-based storage solution and enabling near real-time dashboard updates.

### 🌍 Region-Specific Calibration
The system is calibrated for the tropical climate conditions of Trichy, Tamil Nadu, improving measurement accuracy and relevance compared to generic weather APIs.

### 🧮 Advanced Analytics
Custom DAX measures were developed to calculate:
* Heat Index ("Feels Like" Temperature)
* Dew Point
* Temperature Variation
* Weather Trend Patterns

### 📊 Interactive Dashboard
The dashboard includes:
* Real-time KPI cards
* Historical trend analysis
* Dynamic weather condition indicators
* Automated data refresh
* Interactive filtering and exploration

---

## 🚀 Key Features
* Real-time IoT data pipeline
* Live weather monitoring and reporting
* Custom weather analytics using DAX
* Integration of hardware, cloud services, and business intelligence
* End-to-end system design and implementation

### Data Pipeline
`Sensor` ➔ `ESP8266` ➔ `Google Sheets` ➔ `Power BI` ➔ `Interactive Dashboard`

---

## 🛠 Tools & Technologies
* **BI & Analytics:** Power BI, DAX, Power Query
* **Hardware & IoT:** ESP8266, DHT11 Sensor, BMP280 Sensor
* **Cloud Storage:** Google Sheets

---

## 📈 Skills Demonstrated
* Data Analysis and Visualization
* Business Intelligence Reporting
* DAX Measure Development
* Data Transformation with Power Query
* IoT System Integration
* Real-Time Data Processing
* Dashboard Design and Development

---

## 🎯 Project Objective
To design and implement a real-time weather analytics solution that demonstrates the integration of IoT devices with modern business intelligence tools, enabling data-driven insights from live environmental data.
