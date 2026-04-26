Live IoT Weather Dashboard

This is a real-time weather dashboard powered by a custom-built DIY IoT weather station. While many weather dashboards available online use static datasets or merely change color schemes on the same template, this project is fundamentally different. It is a live system that bridges the gap between physical hardware and digital analytics.



&#x20;



Technical Overview

Data Collection: Unlike dashboards that rely on CSV uploads, this station utilizes an ESP8266 microcontroller paired with DHT11 and BMP280 sensors. Live readings for Temperature, Humidity, and Pressure are logged directly to Google Sheets in real-time.



Region-Specific Calibration: Specifically calibrated for the unique tropical climate of the Trichy, Tamil Nadu region, ensuring localized accuracy that global APIs often miss.



Advanced Analytics: Using only four raw data points (Timestamp, Temp, Humidity, and Pressure), I have developed a custom suite of DAX measures. These calculate complex weather trends, "feels like" temperatures (Heat Index), and atmospheric dew points.



Dynamic Visuals: The interface isn't just a static skin; it features weather-dependent iconography and a custom refresh schema that ensures the data you see is as fresh as the air outside.



Why this stands out

Most dashboards you see are "re-skins" of existing templates. This project demonstrates a full-stack data engineering pipeline: Sensor → Microcontroller → Cloud Storage → Power BI Logic → End-User Visualization.

