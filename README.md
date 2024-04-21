# Analysis of Cab Services in NYC

## Overview
This project investigates why New Yorkers prefer cabs over subways, focusing on data from 2021 to 2023. It analyzes customer behavior, operational effectiveness, and the impact of factors like traffic and weather on choosing between Yellow Cabs, Uber, Lyft, and other For-Hire Vehicles (FHV).

## Table of Contents
- [Objective](#objective)
- [Data Sources](#data-sources)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusions](#conclusions)
- [Team](#team)
- [References](#references)

## Objective
The goal is to determine why cabs are often favored over subways in NYC by analyzing various factors such as convenience, fare structures, and external influences like weather and traffic conditions.

## Data Sources
Data was collected from several public sources including:
- **NYC Open Data**
- **Kaggle**
- **data.gov**
- **TLC Trip Record Data** from NYC.gov
- Various research papers and online resources relevant to NYC transportation.

## Methodology
### Data Preparation
Preprocessing involved handling data from 2021–2023 using Python tools like Pandas and Geopandas for spatial analysis. Data was segmented by month and converted from PARQUET to CSV for accessibility.

### Data Analysis
- **Usage Patterns**: Examined the daily and hourly usage of Yellow Taxis and FHVs.
- **Comparative Study**: Compared operational data of taxis with subway usage data.
- **Geospatial Analysis**: Identified key locations using latitude and longitude data.

### Feature Engineering
Developed insights from data features such as peak usage times, popular locations, and tipping behavior.

## Results
Findings include:
- Identification of peak usage times and popular locations for taxi services.
- Analysis of the impact of weather and traffic on taxi and subway demand.
- Efficiency comparison of taxis and subways under various conditions.

## Conclusions
The study underscores the importance of cabs in NYC's transportation landscape, particularly during adverse weather or subway disruptions.

## Team
- **Project Lead**: Sai Chakkera
- **Data Analysts**: Peter Geiss, [Your Name]
- **Advisor**: Prof. Steven Skiena

## References
1. [NYC Taxi and Ride-hailing Data Analysis by Todd W. Schneider](https://toddwschneider.com/dashboards/nyctaxi-ridehailing-uber-lyft-data/)
2. [Research on Ride Sharing from ResearchGate](https://www.researchgate.net/publication/312575543_The_Rise_of_Ride_Sharing_in_Urban_Transport_Threat_or_Opportunity)
3. [Visualizing NYC's Subway Traffic with Leafmap](https://towardsdatascience.com/visualizing-nycs-subway-traffic-census-data-using-leafmap-29904b634046)
