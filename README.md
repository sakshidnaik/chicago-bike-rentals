# Chicago Bike Rental Demand Prediction Project

## Overview
This project aims to improve Chicago's bike-sharing program's efficiency and user satisfaction by predicting bike rental demand. By analyzing historical data, including weather, time of day, and system status, we use machine learning to forecast future rental needs accurately.

## Problem Statement
The Cook County Planning and Development Department wants to optimize the city's bike-sharing system by ensuring that bikes are available when and where they are needed. This project helps meet Chicago’s goals for sustainable transportation by reducing bike shortages and wait times, making the system more efficient for users.

## Data and Methodology
### Data Used:
We analyzed bike rental data along with variables like:
- **Weather**: Temperature, humidity, wind speed, and solar radiation.
- **Time**: Hour of the day, day of the week.
- **Operational Status**: Whether it’s a holiday or the system is functional.

### Key Steps:
1. **Missing Data Handling**: To handle missing data, we used techniques like the Magnus formula for dew point and median imputation for solar radiation and visibility.
2. **Feature Engineering**: We created new features, like peak and non-peak hours, and added indicators for operational status and precipitation.
3. **Exploratory Data Analysis (EDA)**: We analyzed how bike rentals change during the day and under different weather conditions.
4. **Predictive Modeling**: Regression models were used to predict bike rentals, focusing on the most important variables, such as weather and peak times.

## Key Insights and Recommendations
### Key Insights:
- **Peak Times**: The highest bike demand is from 7 AM to 9 PM.
- **Weather Effects**: Bad weather leads to fewer rentals, while good weather increases demand.
- **Operational Impact**: Whether the system is running (non-holiday, functioning day) is vital in rental volume.

### Recommendations:
1. **Dynamic Bike Distribution**: Make sure more bikes are available during peak hours and adjust supply based on weather forecasts.
2. **Marketing**: To balance demand, encourage bike use during good weather and non-peak times.
3. **Real-Time Data Use**: Incorporate real-time data to update predictions and improve bike distribution quickly.

## Conclusion
This project helps Chicago improve its bike-sharing system by predicting rental demand and making recommendations for bike distribution and marketing strategies. Other cities can use this model to optimize their bike-sharing systems, promoting sustainable urban transportation.

