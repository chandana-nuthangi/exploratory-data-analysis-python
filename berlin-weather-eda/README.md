# Berlin Weather EDA using DWD API Data

This project is an exploratory data analysis of Berlin weather observations using the Bright Sky API, which provides access to Deutscher Wetterdienst (DWD) weather data.

The goal of this project is to demonstrate a complete entry-level data analytics workflow: API data extraction, data cleaning, missing-value handling, feature engineering, trend analysis, seasonality analysis, visualization, and analytical reporting.

## Project Objective

The main objective is to understand Berlin's weather patterns from 2020 to 2025 and communicate the results in a clear, business-friendly format.

This project answers the following questions:

- Which weather variables have missing data?
- How does Berlin's average temperature change over time?
- What monthly and seasonal temperature patterns are visible?
- Which months show higher precipitation?
- How do extreme weather days vary by year?
- Which weather variables are most strongly related?

## Data Source

Data was collected from the Bright Sky API.

- API: https://api.brightsky.dev/weather
- Data provider: Deutscher Wetterdienst (DWD)
- Location: Berlin, Germany
- Latitude: `52.52`
- Longitude: `13.405`
- Period analyzed: `2020-01-01` to `2025-12-31`

## Tools Used

- Python
- Pandas
- Requests
- Matplotlib
- Seaborn
- Google Colab
- PowerPoint for final reporting

## Project Structure

```text
berlin-weather-eda/
├── notebooks/
│   └── berlin_weather_eda.ipynb
├── reports/
│   └── berlin-weather-eda-report.pptx
├── visuals/
│   ├── missing_values_by_variable.png
│   ├── daily_average_temperature_trend_berlin.png
│   ├── monthly_temperature_seasonality_berlin.png
│   ├── temperature_distribution_by_season_berlin.png
│   ├── average_monthly_precipitation_berlin.png
│   ├── extreme_weather_days_by_year_berlin.png
│   └── weather_variable_correlation_berlin.png
├── requirements.txt
└── README.md
