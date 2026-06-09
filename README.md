# Deloitte-data-analytics-job-simulation
Data Analytics project completed as part of the Deloitte Data Analytics Job Simulation on Forage. Includes workforce compensation analysis, equality score classification, downtime trend analysis, interactive Tableau dashboards, and business insights generated using Excel and Tableau.

## Description
📊 Daikibo Telemetry Data Analysis Dashboard
Project Overview

This project focuses on analyzing industrial machine telemetry data provided by Daikibo using Tableau. The objective was to identify operational downtime across factories and machine types by transforming raw JSON telemetry data into meaningful business insights through interactive visualizations.

The dashboard helps stakeholders monitor equipment health, identify downtime patterns, and pinpoint factories and device types contributing most to operational inefficiencies.

🎯 Business Problem

Manufacturing organizations rely on machine telemetry data to monitor equipment performance and minimize production downtime.

The challenge was to:

Analyze machine health status data
Calculate potential downtime caused by unhealthy machines
Identify factories with the highest downtime
Determine which device types contribute most to downtime
Create an interactive dashboard for operational decision-making
📂 Dataset

Source: Daikibo Telemetry Data

Format: JSON

Key Fields
Device ID
Device Type
Timestamp
Factory Location
Factory Section
Machine Status (Healthy / Unhealthy)
Temperature
🛠 Tools & Technologies Used
Tableau Desktop
JSON Data Processing
Calculated Fields
Interactive Dashboards
Data Visualization
Business Analytics
📈 Data Preparation
Calculated Field Created

Unhealthy

IF [Status] = "unhealthy" THEN 10
ELSE 0
END

Each unhealthy status represents 10 minutes of potential downtime, allowing downtime analysis across factories and machine categories.

📊 Dashboard Components
1. Down Time per Factory

A bar chart showing total downtime across all factories.

Purpose:

Identify the factory experiencing the highest operational downtime.
Compare performance across manufacturing locations.
2. Down Time per Device Type

A bar chart displaying downtime by machine category.

Purpose:

Determine which equipment types contribute most to downtime.
Support maintenance prioritization.
3. Interactive Filtering

The dashboard includes cross-filtering functionality:

Selecting a factory automatically filters device-level downtime data.
Enables detailed root-cause analysis.
Improves operational decision-making.
🔍 Key Insights
Identified the factory with the highest cumulative downtime.
Determined the device types responsible for the majority of downtime events.
Demonstrated how telemetry data can be transformed into actionable operational intelligence.
🚀 Skills Demonstrated
Data Analytics
Data Cleaning
Data Transformation
Exploratory Data Analysis (EDA)
Business Intelligence
Tableau
JSON Data Integration
Calculated Fields
Dashboard Design
Interactive Filters
KPI Analysis
Data Visualization
Business Skills
Operational Analytics
Downtime Analysis
Root Cause Investigation
Data-Driven Decision Making
📸 Dashboard Preview

(Insert Dashboard Screenshot Here)

📚 Learning Outcomes

Through this project, I gained hands-on experience in:

Working with real-world telemetry datasets
Building interactive Tableau dashboards
Converting raw machine data into business insights
Analyzing operational performance metrics
Creating stakeholder-focused visualizations
Author

Shreya Bandhe
MBA (Business Analytics & Operations) | Aspiring Business Analyst
Skills: Tableau • Power BI • Excel • SQL • Python • Data Analytics
