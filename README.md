# Stolen Vehicles Analysis Dashboard (Power BI)
This project presents a comprehensive analysis of vehicle thefts using Power BI dashboards. The analysis leverages a dataset sourced from Maven Analytics and provides visual insights into trends, patterns, and regional specifics related to vehicle thefts over a six-month period (2021-22) in New Zealand.

## Dataset Overview
The project utilizes the following main tables:

- `stolen_vehicles`: Contains details of stolen vehicles such as vehicle type, model year, and date of theft.
- `locations`: Contains location-specific details like region, population, and density.
- `make_details`: Includes information about vehicle makes, such as make name and type.

## Objectives
- Create interactive dashboards for visual exploration of theft patterns.
- Highlight insights such as the most stolen vehicle types, regions with high theft rates, and time-based trends.
- Provide actionable recommendations based on data insights.

## Dashboard Overview

### 1. General Overview
**Key Metrics:**
- Total thefts: 4,553
- Most affected region: Auckland

**Charts:**
- Theft distribution by region, population, and density. Applied Conditional Formatting on all three columns to understand relaion between of No of thefts with Population and Density of a Region separately.
- Theft counts by vehicle type, make, and brand.
- Model-Year-wise trends highlighting which model years' vehicles were most stolen.

### 2. Time-Series Analysis
**Monthly Theft Trends:**
- Theft numbers rose from October 2021 to March 2022, with a significant 53.24% increase from Q4 2021 to Q1 2022.

**Weekly Theft Trends:**
- Mondays and Tuesdays reported the highest thefts, while Saturdays saw the least.

**Quarterly Trends:**
- Sharp rise in thefts during Q1 2022.

**Interactive Features:**
- Clicking on any month in the line chart enables a detailed breakdown of vehicle thefts for that specific month, including vehicle types, makes, and colors.
- Similarly, selecting a specific day of the week provides in-depth insights into theft trends for that day, allowing users to analyze theft counts by time, vehicle characteristics, and location.

### 3. Top 5 Region Analysis
Focuses on regions with the highest theft counts:
- **Top regions:** Auckland, Canterbury, Bay of Plenty, Wellington, and Waikato.
- **The Top 5 Regions contribute to almost 80% of the total Country's Thefts'**

**Interactive Features:**
- Click on any region to view its in-depth analysis, including theft details by vehicle name ,type, make, and year.
- Use slicers to filter the dashboard by any specific month or day of the week for more granular insights.


## Key Findings

### Yearly and Monthly Trends:
- A consistent rise in thefts in early 2022, peaking in March.

### Day of the Week:
- Mondays and Tuesdays are high-risk days.

### Vehicle-Specific Insights:
- Older model years (e.g., 2005-06) are more targeted.
- Commonly stolen colors: Silver and white.
- High-risk vehicle types: Station Wagon, Saloon, and Hatchback.

### Regional Insights:
- Regions with higher populations, like Auckland and Canterbury, report more thefts.
- Density does not appear to significantly influence theft counts.

## Recommendations for NZ Police
- **Focus on high-theft regions:** Prioritize surveillance in Auckland and Canterbury, as thefts correlate strongly with population size.
- **Target high-risk vehicle types:** Station Wagons, Saloons, and Hatchbacks need enhanced security measures.
- **Increase patrols:** Deploy more resources on Mondays and Tuesdays.
- **Public Awareness Campaigns:**
  - Educate vehicle owners on securing older models (2005-06).
  - Highlight theft-prone months (e.g., March).

## Technologies Used
- **Power BI:** Built interactive dashboards for data visualization. Employed slicers for flexible filtering by months, regions, and days. Enabled clickable interactions in time-series charts for deeper analysis of specific timeframes.
- **SQL:** Prepared data for analysis by cleaning, joining, and aggregating tables.

## Additional Resources
To explore the SQL analysis version of this project, including the data preparation and exploratory steps used for creating the dashboard, visit the GitHub repository here, https://github.com/Gautam0211/StolenVehiclesAnalysis
