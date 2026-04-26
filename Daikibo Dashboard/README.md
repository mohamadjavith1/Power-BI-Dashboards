Factory Telemetry Analysis – Finding Machine Breakdowns with Power BI

Project Overview

I recently completed a data analysis project focused on manufacturing efficiency for Daikibo, a global client with four major production hubs (Tokyo, Osaka, Berlin, and Shenzhen). The goal was to transform a month’s worth of raw telemetry data (May 2021) into a clear, actionable dashboard that identifies where and why production is being interrupted.



The Problem Statement

The client needed to answer two critical operational questions:



Location Analysis: In which factory location did machines break down the most?



Root Cause: Which specific machine types were responsible for the highest frequency of failures in that high-risk location?



Technical Approach

Data Source: Processed a single JSON file containing telemetry messages sent every 10 minutes across 9 machine types.



Data Transformation: Used Power Query to flatten the JSON structure and ensure data types were optimized for analysis.



Data Modeling: Focused on a minimalist star schema to keep the dashboard responsive and user-friendly.



Visualization: Designed a high-impact, single-page dashboard. I prioritized scannability over complexity to ensure the "worst-performing" factory and machine types were immediately visible via sorted bar charts and KPI cards.



Key Insights

By filtering the telemetry for specific "breakdown" indicators, the dashboard clearly identifies the bottleneck factory and the specific machine models that require maintenance or replacement to minimize future downtime.

