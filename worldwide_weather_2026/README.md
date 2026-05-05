# Worldwide Weather 2026: Daily City Weather Data

## Overview

This dataset contains daily weather data for 42 major cities worldwide for the year 2026, from January 1 up to the most recent available date. It is designed for time series analysis, machine learning, and climate-related research.

The data is collected using the Open-Meteo Historical Weather API and enhanced with temporal and engineered features to support predictive modeling tasks.

---

## Coverage

* 42 cities across multiple regions
* Global coverage including North America, South America, Europe, Africa, Asia, and Oceania
* Time period: 2026-01-01 to latest available date

---

## Features

### Raw Weather Variables

* temperature_2m_max: Daily maximum temperature (°C)
* temperature_2m_min: Daily minimum temperature (°C)
* temperature_2m_mean: Daily mean temperature (°C)
* apparent_temperature_max: Maximum perceived temperature
* apparent_temperature_min: Minimum perceived temperature
* precipitation_sum: Total precipitation (mm)
* rain_sum: Rainfall (mm)
* snowfall_sum: Snowfall (cm)
* windspeed_10m_max: Maximum wind speed (km/h)
* windgusts_10m_max: Maximum wind gusts (km/h)
* cloudcover_mean: Average cloud cover (%)
* weathercode: Weather condition code

---

### Temporal Features

* date
* month
* day_of_week
* day_of_year
* week_of_year
* is_weekend
* season

---

### Engineered Features

* temp_range: Difference between maximum and minimum temperature
* heavy_rain_flag: 1 if precipitation exceeds 20 mm
* heatwave_flag: 1 if maximum temperature is greater than or equal to 35°C
* high_wind_flag: 1 if wind speed exceeds 40 km/h

---

### Time Series Features

* temp_lag_1: Temperature from the previous day
* temp_lag_7: Temperature from 7 days prior
* temp_7d_avg: Rolling 7-day average temperature
* precip_7d_sum: Rolling 7-day precipitation sum

---

### Location Metadata

* city
* country
* continent
* latitude
* longitude
* coastal_city: Binary indicator (1 = coastal, 0 = inland)

---

## Use Cases

* Time series forecasting
* Weather prediction models
* Extreme weather classification
* Climate comparison across cities
* Feature engineering practice for machine learning

---

## Notes

* The dataset includes data only up to the current available date (no future values)
* Rows with missing values due to lag features have been removed
* Weather codes follow Open-Meteo standards
* Coastal classification is manually defined

---

## File Format

CSV file containing all features described above.

Filename:
worldwide_weather_2026_to_2026-05-05.csv

---

## Data Source

Open-Meteo Historical Weather API
[https://open-meteo.com/](https://open-meteo.com/)

---

## Author

Moustafa Mohamed

Linkedin: [*Moustafa Mohamed*](https://www.linkedin.com/in/moustafamohamed01/)

GitHub: [*MoustafaMohamed01*](https://github.com/MoustafaMohamed01)

Kaggle: [*moustafamohamed01*](https://www.kaggle.com/moustafamohamed01)

