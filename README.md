🌍 Global Energy Production and Climate Change Analysis

This project analyzes global energy consumption patterns, renewable energy adoption, and their relationship with greenhouse gas emissions to identify opportunities for sustainable energy transitions. Using structured datasets and interactive visualizations, the project highlights long-term trends, correlations, and regional differences in energy usage and environmental impact.

📌 Project Objective

Primary Question:
How do global energy consumption trends, renewable adoption, and fossil fuel reliance impact climate change, and what insights can support sustainable energy transitions?

Key Goals:

Analyze dominant global energy sources and how they change over time.

Compare renewable energy adoption across countries and regions.

Study the relationship between energy consumption, CO₂ emissions, and carbon intensity.

Identify countries leading the transition to clean energy.

📊 Dataset Overview

Source: Kaggle (open-source energy datasets)

Type: Structured tabular data

Records: ~10,000 rows

Granularity: Country–year level

Key Attributes

country, year

primary_energy_consumption

renewables_consumption

fossil_fuel_consumption

solar_consumption, wind_consumption, hydro_consumption

greenhouse_gas_emissions

carbon_intensity_elec

🧹 Data Preprocessing

Removed missing and invalid values.

Filtered relevant countries and years.

Interpolated missing year-wise data.

Excluded countries with insufficient data coverage.

Identified and treated outliers using boxplots and log transformations.

Created calculated fields such as Renewable Energy Share.

🔍 Analysis & Methods

Exploratory Data Analysis (EDA) to understand trends and distributions.

Trend analysis using line charts for energy production and renewable growth.

Correlation analysis between energy consumption and CO₂ emissions.

Comparative analysis across countries and regions.

Geographical analysis using heatmaps for carbon intensity.

📈 Key Visualizations & Insights

Energy Production Trends: Global energy production has steadily increased, with renewables growing rapidly since the early 2000s.

Renewable Adoption by Country: European countries lead renewable adoption, while many developing nations lag.

CO₂ Emissions vs Energy Use: Strong positive correlation between energy consumption and emissions.

Carbon Intensity: Developing nations show higher carbon intensity due to fossil fuel reliance.

Renewable vs Fossil Share: Gradual decline in fossil fuel share and steady increase in renewables since ~2015.

🛠️ Tools & Technologies

Tableau (data cleaning, analysis, dashboards)

CSV datasets (Kaggle)

Calculated fields and interactive filters

📊 Deliverables

Interactive Tableau dashboards.

Visual analysis of global energy and emissions trends.

Report with insights and sustainability-focused recommendations.

All preprocessing and transformations were performed directly in Tableau.

