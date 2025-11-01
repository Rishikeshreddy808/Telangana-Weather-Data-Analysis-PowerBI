🌦️ Telangana Weather Data Analysis — Power BI Project
📘 Overview

This project focuses on analyzing Telangana’s weather data (2021–2024) using Power BI to uncover insights into rainfall, temperature, humidity, and wind speed patterns across 33 districts.

The aim is to track climate trends, identify anomalies, and support data-driven environmental planning and agricultural decision-making through interactive dashboards and visual storytelling.

🎯 Objectives

Analyze multi-year weather data across Telangana districts.

Identify rainfall anomalies, temperature variations, and humidity fluctuations.

Enable comparative analysis between years, districts, and seasons.

Demonstrate the power of Power BI for data visualization and trend interpretation.

🧩 Dataset Information

Source: Telangana Meteorological Records / Open Weather Data

Key Columns:

District, Mandal, Year, Month, Quarter

Rainfall (mm)

Max_Temperature (°C), Min_Temperature (°C)

Max_Humidity (%), Min_Humidity (%)

Max_WindSpeed (Kmph), Min_WindSpeed (Kmph)

Data Cleaning Steps:

Removed missing/null values

Standardized date/time formats

Ensured unit consistency

Derived average and range metrics for each weather factor

⚙️ Data Preparation

Data modeling and transformation were performed using Power Query and DAX in Power BI.

Key Steps:

Created calculated columns for:

Average Rainfall

Temperature Range

Humidity Range

Wind Speed Range

Established relationships between District, Year, and Weather Metrics tables.

Built DAX measures for Trend Analysis, Sum of Metrics, and Averages.

Added slicers, drill-through, and interactive filters for deeper analysis.

📊 Dashboard Visualizations

The project includes 7 interactive dashboards in Power BI:

1️⃣ Average of Rain Dashboard — Annual rainfall trends and district comparisons.
2️⃣ Comprehensive Insights Dashboard — Unified view of rainfall, temperature, humidity, and wind speed.
3️⃣ Humidity Insights Dashboards (1 & 2) — Quarterly humidity trends and district-level variations.
4️⃣ Rainfall Analysis Dashboard — Yearly rainfall by district and mandal contribution.
5️⃣ Rainfall Values Dashboard — Geographic rainfall mapping and time-series patterns.
6️⃣ Temperature Insights Dashboard — District-wise and monthly temperature analysis.
7️⃣ Wind Speed Insights Dashboard — Wind speed ranges and temporal trends.

💡 Applications & Recommendations

Applications:

Support agricultural planning and water resource management.

Identify climate change indicators and extreme weather anomalies.

Provide data-driven insights for regional policy-making.

Track humidity and wind patterns for forecasting monsoon behavior.

Recommendations:

Integrate real-time meteorological APIs for live updates.

Extend project with AI/ML-based predictive weather modeling.

Add automated alerts for extreme weather conditions.

Use visual insights for seasonal planning and climate awareness.

🛠️ Tools & Technologies

Power BI – Data visualization and modeling

Power Query – Data transformation

DAX – Measures and calculations

Excel / CSV – Dataset source and preprocessing
