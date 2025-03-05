# Motor-Vehicle-Theft-Analysis-
Motor Vehicle Theft Analysis in New Zealand: Identifying Trends, Risk Factors, and Prevention Strategies

Abstract

This project analyzes motor vehicle theft trends in New Zealand using Excel-based data analysis and visualization techniques. The goal is to identify high-risk regions, targeted vehicle types, and temporal theft trends to support crime prevention and policy-making. Data cleaning, exploratory analysis, and key performance indicator (KPI) tracking using pivot tables and slicers were employed. The findings revealed Auckland as the highest-risk region, station wagons as the most stolen vehicle type, and a rising theft trend from 2021 to 2022, with March 2022 having the highest number of thefts. The insights will help law enforcement allocate resources efficiently and develop targeted prevention strategies.

Introduction

Background

Motor vehicle theft poses significant challenges to public safety and increases insurance costs. Understanding theft patterns is essential for stakeholders to implement effective prevention measures. This study focuses on analyzing theft trends in New Zealand to uncover high-risk regions, frequently stolen vehicle types, and seasonal variations in theft rates.

Problem Statement

This analysis addresses key challenges in motor vehicle theft, including:
	•	High-Risk Locations: Identifying regions with the highest theft occurrences.
	•	Targeted Vehicle Types: Determining which vehicle makes and models are most vulnerable.
	•	Seasonal & Time-Based Trends: Examining how theft patterns change over time.
	•	Predictive Insights: Providing recommendations for crime prevention and policy interventions.

Objectives
	•	Clean and preprocess theft data for accurate analysis.
	•	Analyze vehicle theft distribution across different regions.
	•	Identify the most stolen vehicle types and brands.
	•	Explore seasonal and time-based theft patterns.
	•	Provide actionable recommendations for law enforcement and vehicle owners.

Key Objectives: The Dashboard Answers These Critical Questions
	1.	What is the total number of vehicle thefts in New Zealand from 2021 to 2022?
	2.	Which regions are most affected by vehicle theft?
	3.	What types and brands of vehicles are most frequently stolen?
	4.	How have theft trends changed over time?
	5.	What months experience peak theft incidents?
	6.	What recommendations can be derived for law enforcement and vehicle owners?

Dashboard Images

(Insert screenshots of your Excel dashboard highlighting key KPIs, pivot tables, and slicers.)

Data Preparation

Data Sources

The dataset comprises motor vehicle theft records across New Zealand from 2021 to 2022, provided by the TDI team. It includes information on stolen vehicles, locations, and vehicle makes.

Data Collection
	•	Data was provided as a zip file containing multiple CSV files.
	•	Extracted and combined into a single Excel workbook using Power Query.
	•	Standardized using Excel tables for consistency.

Data Characteristics

Key columns include:
	•	Vehicle ID: Unique ID of a stolen vehicle.
	•	Vehicle Type: Type of vehicle stolen.
	•	Make Name: Brand of the vehicle.
	•	Model Year: Year of the vehicle model.
	•	Date Stolen: Date the theft occurred.
	•	Region: Location of the theft.
	•	Population: Population of the region.

Data Cleaning and Transformation

Step 1: Data Cleaning
	•	Handling Missing Values: Removed rows with missing critical data.
	•	Duplicate Removal: Ensured unique theft records using the Remove Duplicates function.
	•	Standardization: Converted date formats to MM-DD-YYYY for consistency.

Step 2: Calculated Columns
	•	Theft Frequency by Region: Used COUNTIF function to calculate thefts per region.
	•	Theft Frequency by Vehicle Type: Used COUNTIFS to count thefts per vehicle type.

Metrics and Visualizations

Key Metrics
	•	Total Thefts: 4,553
	•	Most Stolen Vehicle Type: Station Wagon (946 thefts)
	•	Most Targeted Brand: Toyota (716 thefts)
	•	High-Risk Region: Auckland (1,638 thefts)

Key Visualizations
	•	Pivot Tables: Displaying theft trends by region and time.
	•	Charts: Bar charts for most stolen vehicle types and line charts for monthly theft trends.
	•	Slicers: Added for interactivity by year, region, and vehicle type.
	•	Heat Maps: Highlighted high-risk regions using conditional formatting.

(Insert images of charts and pivot tables here.)

Analyzing the Outcomes

Key Findings
	•	Rising Theft Trend: 73% increase in thefts from 2021 (1,668 thefts) to 2022 (2,885 thefts).
	•	Seasonal Peaks: March 2022 recorded the highest theft count (1,053).
	•	High-Risk Regions: Auckland led with the most thefts due to urban density.
	•	Vulnerable Vehicles: Older models, particularly Toyota and station wagons, were frequently targeted.

Recommendations

For Law Enforcement
	•	Increase patrols and surveillance in high-theft areas, especially in Auckland.
	•	Install CCTV and automated license plate readers at key locations.
	•	Enhance public awareness campaigns on vehicle theft prevention.

For Vehicle Owners
	•	Install anti-theft devices such as GPS trackers and alarms.
	•	Upgrade security systems on older vehicle models.

For Policymakers
	•	Strengthen vehicle theft laws and penalties.
	•	Improve urban parking security, especially in high-risk areas.

Conclusion

This analysis reveals a significant rise in vehicle thefts in New Zealand, particularly in Auckland, with station wagons and older Toyota models being the most targeted. By leveraging Excel’s data analysis and visualization tools, we identified high-risk regions, vulnerable vehicle types, and seasonal patterns. Implementing targeted security measures, data-driven solutions, and community engagement initiatives can significantly reduce vehicle theft rates and enhance public safety in New Zealand.

