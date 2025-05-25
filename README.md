
# UK Traffic and Accident Analysis


# Project Background and Overview
This repository presents a comprehensive data analysis of UK road traffic and accident trends, as visualized in the interactive dashboard:
**[UK Traffic and Accident Analysis Dashboard](https://mukeshtheanalyst.github.io/UK_traffic_and_accident/UK_traffic_and_accident_2025_05_20_v01.html)**

The project leverages recent UK road accident data to uncover actionable insights into accident frequency, severity, and contributing factors. The analysis is aimed at supporting stakeholders—such as policymakers, road safety authorities, and the public—in understanding key patterns and developing targeted interventions to improve road safety.



# Data Structure Overview

## Data Source

* UK Department for Transport open datasets (latest available, up to 2024)

* Data covers accident records with attributes including date, time, location, severity, weather, road surface, and vehicle type.
  
  
**Files Used:**

* Accident_Information.csv file – accident_index, road_class, road_number, date, time, junction_detail, light_detail, road_surface_conditions, weather_conditions



**Data Preparation**

* Removed duplicates and handled missing values

* Standardized column names, date/time formats, and categorical variables

* Merged datasets for multi-year, multi-factor analysis


**Data Limitations**

* Underreporting of minor accidents possible

* Some environmental factors (e.g., lighting, signage) may be inconsistently recorded

* No direct behavioral data (e.g., driver distraction, intoxication)


# Analysis Summary
This analysis highlights critical trends and risk factors in UK road accidents. While the total number of accidents has shown a gradual decline, the proportion of serious and fatal incidents remains a concern. Key findings reveal strong links between accident severity and factors such as weather, road surface, and time of day. The dashboard enables users to filter and explore data by year, region, severity, and contributing factors.

## Snapshot of Findings:

* Declining trend in total accidents, but serious/fatal cases remain steady

* Wet or icy road surfaces and poor weather conditions significantly increase accident severity

* Peak accident times align with rush hours and poor visibility periods

* Motorcycles and young drivers are overrepresented in severe accidents


# Insights Deep Dive

**1. Accident Severity by Weather and Road Surface**
Wet/icy surfaces and adverse weather conditions see a 40% higher rate of serious/fatal accidents compared to dry/clear conditions

Business Metric: Accident severity index

Story: Targeted road maintenance and weather-responsive alerts can mitigate risk

**2. Temporal Patterns**
Accidents peak during weekday rush hours (8–10 AM, 4–7 PM)

Nighttime accidents, though less frequent, are more likely to be severe

Business Metric: Accidents per hour, severity by time of day

Story: Enhanced enforcement and public awareness during high-risk periods

**3. Vehicle and Demographic Analysis**
Motorcycles and young male drivers have higher involvement in severe accidents

Business Metric: Severity rate by vehicle type and driver age

Story: Focused education and enforcement for high-risk groups

**4. Regional Hotspots**
Urban centers report more accidents, but rural roads have higher fatality rates

Business Metric: Accidents and fatalities per 100,000 population by region

Story: Infrastructure improvements and tailored interventions needed in rural areas


# Recommendations
* **Dynamic Road Safety Campaigns**: Launch targeted awareness and enforcement during high-risk times and adverse weather conditions.

* **Infrastructure Upgrades**: Prioritize improvements on rural and high-severity corridors (e.g., better lighting, signage, surface treatments).

* **Data-Driven Policy**: Use dashboard insights to inform local and national road safety strategies.

* **Further Data Collection**: Integrate behavioral and vehicle telematics data for deeper analysis.


# How to Use
**1. Explore the Dashboard:**

* Filter by year, severity, region, weather, and road type

* Visualize trends, hotspots, and key risk factors

**2. Reproduce the Analysis:**

* Download the data and code from this repository

* Follow the documented RMarkdown/HTML workflow for data cleaning, analysis, and visualization


# License
This project is licensed under the MIT License.


# Author
Mukesh Shirke

**Explore the RMarkdown file for detailed code, data cleaning steps, visualizations, and the full analysis process. This project demonstrates my expertise in data analysis, R programming, and the application of data-driven insights to real-world challenges in urban analytics.**
