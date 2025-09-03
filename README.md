**Road Accident Dashboard**
 *Project Overview*

This project presents an interactive Road Accident Dashboard built using an existing accident dataset. The dashboard provides insights into road accident casualties, categorized by severity, vehicle type, road type, area, road conditions, and light conditions. It helps stakeholders analyze accident patterns, monitor trends, and make data-driven decisions for road safety improvements.

*Data Cleaning & Preparation*

The raw dataset contained missing values, inconsistencies, and redundant columns. The following steps were taken to clean and prepare the data for analysis:

 1.Removed duplicate records.

 2.Handled missing values in road type, light condition, and weather condition fields.

 3.Standardized categorical values (e.g., "Wet/Dry" conditions, "Daylight/Dark" conditions).

 4.Converted accident date into year and month format for trend analysis.

 5.Filtered irrelevant columns that were not required for KPI and dashboard visualization.

 6.Ensured proper data types for numerical and categorical variables.


*Key Performance Indicators (KPIs)*

The following KPIs were calculated to highlight accident insights:

Total Casualties → 134,613

Represents all recorded casualties in the dataset.

Fatal Casualties → 1,513 (1.12%)

Percentage of casualties that were fatal.

Serious Casualties → 16,230 (12.06%)

Percentage of casualties categorized as serious injuries.

Slight Casualties → 116,870 (86.82%)

Majority of accidents resulted in slight injuries.

Casualties by Cars → 107,637 (80%)

Most casualties involved cars compared to other vehicle types.

*Dashboard Insights*

The dashboard provides multiple perspectives on accident data:

Casualties by Vehicle Type → Breakdown by cars, bikes, buses, vans, and other vehicles.

Trend Analysis → Monthly comparison of current year (CY) vs previous year (PY) casualties.

Road Type Analysis → Casualties by single carriageway, dual carriageway, roundabout, etc.

Road Condition Analysis → Casualties under wet, dry, and snow conditions.

Area-Based Analysis → Comparison of urban vs rural casualties.

Light Condition Analysis → Daylight vs dark accidents.

*Usage*

Filters Available:

Accident year filter (2021, 2022, 2023).

Urban/Rural filter.

Users can interactively explore accident data and identify patterns.

*File Structure*

KPI Sheet → Contains calculated KPIs.

Dashboard Sheet → Main interactive dashboard.

Data Analysis Sheet → Cleaned dataset used for visualization.

Other Sheets → Breakdown by monthly rate, road type, road condition, and area.
