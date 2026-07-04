# Deloitte Australia Data Analytics Job Simulation

This repository contains my submission for the **Deloitte Australia Data Analytics** virtual job simulation on [Forage](https://www.theforage.com/).

## Task Overview
Daikibo, a global company with 4 factories (Tokyo, Osaka, Berlin, and Shenzhen), collected one month of telemetry data from 9 types of machines at each location. The goal was to analyze this data to answer two business questions:

1. **Which factory location had the most machine breakdowns?**
2. **Which type of machine broke down most often at that location?**

## Tools Used
- **Tableau Desktop** — for data visualization and dashboard building
- JSON telemetry dataset (provided by Deloitte via Forage)

## Approach
1. Imported and cleaned the raw JSON telemetry data in Tableau.
2. Built a bar chart showing the count of "unhealthy" (broken) machine status readings, grouped by factory.
3. Identified **Daikibo Factory Seiko (Osaka)** as the location with the most breakdowns.
4. Built a second chart filtering specifically for Factory Seiko, broken down by device/machine type.
5. Found that the **LaserWelder** machine accounted for all 48 breakdown events at that factory.
6. Combined both visuals into a single interactive dashboard.

## Key Findings
- **Factory with most breakdowns:** Daikibo Factory Seiko (Osaka, Japan)
- **Machine responsible:** LaserWelder

## Dashboard Screenshot


![Daikibo Dashboard](Daikibo-Dashboard-Submission.png)



## Skills Demonstrated
- Data cleaning and transformation
- Data visualization with Tableau
- Business insight generation from raw telementry data 
- Data cleaning and transformation
- Data visualization with Tableau
- Business insight generation from raw telemetry data
