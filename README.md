# Weather Data Analysis

## Overview
This project analyzes a real-world weather dataset to explore patterns in temperature, humidity, precipitation, and visibility.  
The goal is to identify seasonal trends and understand general weather conditions.

## Dataset
- Source: [CUNY LaGuardia Data Analytics Weather CSV](https://raw.githubusercontent.com/CunyLaguardiaDataAnalytics/datasets/refs/heads/master/weather.csv)
- Columns include:
  - `year`, `month`, `day`, `hour` — date and time of the reading
  - `origin` — weather station code
  - `temp` — temperature (°F)
  - `dewp` — dew point (°F)
  - `humid` — humidity (%)
  - `wind_speed` and `wind_gust` — wind conditions (mph)
  - `precip` — precipitation (inches)
  - `pressure` — atmospheric pressure (mb)
  - `visib` — visibility (miles)

## Tools Used
- Python
- Pandas
- Matplotlib

## Analysis & Charts
The analysis includes:
1. Average Temperature by Month  
2. Temperature vs Dew Point  
3. Humidity Distribution  
4. Days with vs without Rain  
5. Precipitation Distribution / Total Monthly Precipitation  
6. Visibility Distribution  

## Key Insights
- **Temperature Trends:** Average temperatures vary by month, showing seasonal patterns. Dew point correlates with temperature, indicating humidity trends.  
- **Humidity:** Most readings fall in a moderate range, with occasional extremes.  
- **Precipitation:** Only a portion of days have measurable rain. Monthly totals show wetter months.  
- **Visibility:** Generally high, with occasional low-visibility days due to weather events.  

**Overall:**  
This project demonstrates data cleaning, aggregation, visualization, and interpretation of multiple weather metrics from real-world data.

## Files
- `weather-data-analysis.ipynb` — Notebook containing code, charts, and analysis.
