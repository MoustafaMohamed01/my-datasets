# Worldwide Weather 2025

## Overview
This dataset contains **daily weather observations for major cities worldwide in 2025**. It is designed for data analysis, visualization, and machine learning applications such as climate studies, time series forecasting, and geospatial analysis.

---

## Dataset Contents
| Column | Description |
|--------|-------------|
| `time` | Date of the observation (YYYY-MM-DD). |
| `temperature_2m_max` | Maximum air temperature at 2 meters above ground level (°C). |
| `temperature_2m_min` | Minimum air temperature at 2 meters above ground level (°C). |
| `precipitation_sum` | Total daily precipitation (mm). |
| `weathercode` | Numeric code representing weather conditions. |
| `city` | Name of the city where the observation was recorded. Includes major global cities such as New York, London, Tokyo, Cairo, Sydney, Moscow, and more. |

---

## Key Statistics
- **Entries:** 6,318  
- **Cities Covered:** Worldwide major cities  
- **Time Range:** January 1, 2025 – August 31, 2025  

**Sample Data:**
```text
time        temperature_2m_max  temperature_2m_min  precipitation_sum  weathercode  city
2025-01-01  10.8                3.8                 4.5                63.0         New_York
2025-01-02  5.3                 0.2                 0.0                3.0          New_York
2025-01-03  3.1                 -2.0                0.0                3.0          New_York
````

---

## Methodology

* Data was collected programmatically from the **[Open-Meteo API](https://open-meteo.com/)**.
* Processed and structured using **Python and Pandas**.
* The dataset is ready for exploratory data analysis, visualization, and machine learning experiments.

---

## Use Cases

* Climate and weather pattern analysis
* Time series forecasting of temperature and precipitation
* Data visualization and geospatial mapping
* Machine learning and AI experiments

---

## Visualization Example

A sample visualization could show the **average temperature per city** or a **world map with city-specific weather trends**. (See the `plots` folder if included.)

---

## License

This dataset is licensed under **[CC0 1.0 Universal (Public Domain)](https://creativecommons.org/publicdomain/zero/1.0/)**.
You are free to use, modify, and distribute the dataset for any purpose, without attribution.

---

## Contact

For questions, suggestions, or collaborations, feel free to reach out to **Moustafa Mohamed**
 * [LinkedIn](https://www.linkedin.com/in/moustafamohamed01/)
 * [Kaggle](https://www.kaggle.com/moustafamohamed01)
