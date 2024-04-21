# Analysis of Cab Services in NYC

## Overview
This project explores why New Yorkers often choose cabs over subways by analyzing comprehensive data from 2021 to 2023. This analysis includes customer behavior, operational effectiveness, and the influences of environmental factors such as weather and traffic on the preference for Yellow Cabs, Uber, Lyft, and other For-Hire Vehicles (FHV).

## Table of Contents
- [Objective](#objective)
- [Data Sources](#data-sources)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusions](#conclusions)
- [Team](#team)
- [References](#references)

## Objective
The objective of this study is to explore and understand why cabs are frequently preferred over subways by New Yorkers. This analysis focuses on evaluating various factors including convenience, cost, weather conditions, traffic, and overall transportation efficiency. By examining detailed data from Yellow Cabs, Uber, Lyft, and other For-Hire Vehicles (FHV) from 2021 to 2023, this study aims to provide actionable insights into urban mobility and guide improvements in city transportation planning.


## Data Sources
We utilized a variety of data sources to ensure a robust analysis:
- **NYC Open Data**: Provides a wealth of city-wide data including transportation metrics.
- **Kaggle**: Used for additional datasets related to transportation and urban mobility.
- **data.gov**: A source for governmental data with broader urban data.
- **TLC Trip Record Data** from NYC.gov: Specific to taxi and FHV trip records from 2021 to 2023.
- **Research papers and online resources**: For theoretical frameworks and previous research findings relevant to NYC transportation.

## Methodology
### Data Preparation
The data collection spanned multiple formats and sources. Key steps included:
- **Data Segmentation**: Organizing data monthly and converting from PARQUET to CSV to simplify processing.
- **Preprocessing**: Cleaning and structuring the data using Python libraries like Pandas and Geopandas for spatial analysis.

### Data Analysis
Focused analysis was conducted on:
- **Usage Patterns**: Detailed hourly and daily usage stats for Yellow Taxis and FHVs.
- **Comparative Study**: Operational comparisons between taxi services and subway usage.
- **Geospatial Analysis**: Mapping key locations based on taxi pickup and drop-off data.

### Feature Engineering
Enhancing the dataset with calculated features to better understand trends:
- **Peak Times**: Identifying high traffic times for service demand.
- **Location Hotspots**: Pinpointing frequent taxi activity areas.
- **Tipping Behavior**: Analyzing patterns in how and when riders tip service drivers.

## Results
This section highlights key insights derived from the data:
- **Service Demand**: Peak times and locations where taxi demand spikes.
- **Weather and Traffic Impact**: How external conditions affect taxi usage compared to subways.
- **Operational Efficiency**: Analysis of taxi and subway services under various urban conditions.

## Conclusions
The comprehensive analysis of cab and subway use in New York City highlights several critical insights:
- **Convenience and Accessibility**: Cabs and FHVs offer greater convenience and are often more accessible than subways, especially during adverse weather conditions or in areas with limited subway connectivity.
- **Impact of External Factors**: Traffic and weather conditions significantly influence the choice between cabs and subways, with cabs often being preferred during bad weather and high traffic periods.
- **Operational Efficiency**: Despite the higher cost, the demand for cabs remains strong due to their operational efficiency and the personal space they offer compared to subways.
- **Strategic Implications**: The findings suggest that enhancing the availability and efficiency of cabs, along with improving subway services, could address gaps in NYC’s transportation network.

## Team
- **Advisor**: Prof. Steven Skiena

## References
1. [NYC Taxi and Ride-hailing Data Analysis by Todd W. Schneider](https://toddwschneider.com/dashboards/nyctaxi-ridehailing-uber-lyft-data/)
2. [Research on Ride Sharing from ResearchGate](https://www.researchgate.net/publication/312575543_The_Rise_of_Ride_Sharing_in_Urban_Transport_Threat_or_Opportunity)
3. [Visualizing NYC's Subway Traffic with Leafmap](https://towardsdatascience.com/visualizing-nycs-subway-traffic-census-data-using-leafmap-29904b634046)
