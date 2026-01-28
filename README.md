# AURA_Energy_consumption

Project Overview:

This project analyzes the historical evolution of the electricity production mix in the Auvergne-Rhône-Alpes (AURA) region, France. Using high-resolution data from RTE France (éco2mix), the study covers over a decade of energy data to identify shifts in generation sources, seasonal trends, and the regional reliance on specific energy types.

Objectives
Quantify Production Shares: Calculate the monthly percentage of Nuclear, Thermal, and Hydraulic power within the total regional output.

Temporal Evolution: Observe the stability and changes in the energy mix from January 2013 to December 2024.

Data Reliability: Clean and process raw CSV exports from RTE into a structured SQLite database for efficient querying.

Data Source
Provider: RTE France - éco2mix

Scope: Regional (AURA)

Period: 2013 – 2024

Format: CSV processed via SQLite, data vizualisation in Power BI

Technical Implementation
The core analysis is performed via SQL, calculating monthly aggregates and calculating the relative share of each energy source while handling potential null values to ensure statistical accuracy.

Key Metrics Tracked:

Vol_Total_Prod: Aggregate of all generation sources (Nuclear, Thermal, Hydro, Wind, Solar, Bioenergy).

Part_Nucleaire_Pct: Relative share of nuclear energy (the backbone of the AURA grid).

Part_Hydraulique_Pct: Tracking the impact of regional geography on the energy mix.
