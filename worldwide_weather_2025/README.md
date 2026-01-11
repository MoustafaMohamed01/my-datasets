# Worldwide Weather 2025

## Overview
This dataset contains **daily historical weather data for major cities worldwide in 2025**.  
It is designed to be **machine-learning ready**, supporting tasks such as exploratory data analysis (EDA), time-series forecasting, climate pattern analysis, and feature engineering experiments.

The dataset combines **raw meteorological variables**, **geographic metadata**, and **engineered temporal features**, making it suitable for both beginners and advanced practitioners.

**Kaggle:** (https://www.kaggle.com/datasets/moustafamohamed01/worldwide-weather-2025](https://www.kaggle.com/datasets/moustafamohamed01/worldwide-weather-2025)

---

## Dataset Contents

### Core Weather Features
| Column | Description |
|------|-------------|
| `date` | Date of observation (YYYY-MM-DD) |
| `temperature_2m_max` | Maximum daily temperature at 2m height (°C) |
| `temperature_2m_min` | Minimum daily temperature at 2m height (°C) |
| `temperature_2m_mean` | Mean daily temperature (°C) |
| `apparent_temperature_max` | Maximum perceived temperature (°C) |
| `apparent_temperature_min` | Minimum perceived temperature (°C) |
| `precipitation_sum` | Total daily precipitation (mm) |
| `rain_sum` | Total daily rainfall (mm) |
| `snowfall_sum` | Total daily snowfall (mm) |
| `windspeed_10m_max` | Maximum wind speed at 10m height (km/h) |
| `windgusts_10m_max` | Maximum wind gust speed (km/h) |
| `cloudcover_mean` | Mean daily cloud cover (%) |
| `weathercode` | Numeric weather condition code |

---

### Geographic Metadata
| Column | Description |
|------|-------------|
| `city` | City name |
| `country` | Country name |
| `continent` | Continent |
| `latitude` | City latitude |
| `longitude` | City longitude |
| `coastal_city` | Binary flag indicating coastal cities |

---

### Temporal & Engineered Features
| Column | Description |
|------|-------------|
| `month` | Month number |
| `day_of_week` | Day of the week (0 = Monday) |
| `day_of_year` | Day of the year |
| `week_of_year` | ISO week number |
| `is_weekend` | Weekend indicator |
| `season` | Meteorological season |
| `temp_range` | Daily temperature range |
| `heavy_rain_flag` | Heavy precipitation indicator |
| `heatwave_flag` | Extreme heat indicator |
| `high_wind_flag` | High wind indicator |
| `temp_lag_1` | Temperature lag (1 day) |
| `temp_lag_7` | Temperature lag (7 days) |
| `temp_7d_avg` | 7-day rolling temperature average |
| `precip_7d_sum` | 7-day rolling precipitation sum |

---

## Key Statistics
- **Entries:** ~9,500 daily records  
- **Cities Covered:** Major cities across all continents  
- **Time Range:** January 1, 2025 – December 31, 2025  
- **Format:** CSV  
- **Missing Values:** Minimal (only due to lag/rolling features)

---

## Sample Data
```text
date        temperature_2m_max  temperature_2m_min  precipitation_sum  city        country
2025-01-01  10.8                3.8                 4.5                New_York    United States
2025-01-02  5.3                 0.2                 0.0                New_York    United States
2025-01-03  3.1                 -2.0                0.0                New_York    United States
````

---

## Data Collection & Processing

* Data sourced from the **Open-Meteo Historical Weather API**
* Collected programmatically using **Python**
* Cleaned, merged, and feature-engineered using **Pandas**
* Designed to be directly usable for **ML pipelines and forecasting models**

---

## Use Cases

* Climate trend analysis
* Time-series forecasting (ARIMA, LSTM, Prophet, etc.)
* Weather-based risk modeling
* Feature engineering practice
* Data visualization and geospatial analysis
* Machine learning & AI experiments

---

## License

This dataset is released under the **CC0 1.0 Universal (Public Domain)** license.
You are free to use, modify, and distribute it for any purpose without attribution.

---

## Author & Contact

**Moustafa Mohamed**

* LinkedIn: [https://www.linkedin.com/in/moustafamohamed01/](https://www.linkedin.com/in/moustafamohamed01/)
* Kaggle: [https://www.kaggle.com/moustafamohamed01](https://www.kaggle.com/moustafamohamed01)
* GitHub: [https://github.com/MoustafaMohamed01](https://github.com/MoustafaMohamed01)
