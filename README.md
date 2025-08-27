# 🌦️ Weather Report Dashboard (Power BI)

## 📌 Project Overview

This project presents a **Weather Report Dashboard** built in **Power BI**, leveraging real-time and historical weather data from [WeatherAPI.com](https://www.weatherapi.com/). The dashboard provides interactive insights into temperature trends, humidity, wind speed, and overall weather conditions across different cities and time ranges.

The goal is to visualize weather data in a user-friendly way that helps track daily, weekly, and monthly patterns — useful for travelers, researchers, and businesses impacted by weather conditions.

---

## 📂 Data Source

* **API Provider:** [WeatherAPI.com](https://www.weatherapi.com/)
* **Type:** REST API (JSON format)
* **Data Collected:**

  * `location` → City, Region, Country, Latitude/Longitude
  * `current` → Temperature, Humidity, Wind Speed, UV Index, Cloud Cover
  * `forecast` → Daily Forecasts (Temperature highs/lows, Rainfall, Condition text/icon)
  * `historical` → Past weather data (if enabled)

Data was fetched using **API calls** and integrated into Power BI through:

* **Power Query (Web connector)** for live API calls
* **JSON parsing** to transform and load data into structured tables

---

## 🛠️ Tools & Technologies

* **Power BI Desktop** (for dashboard design)
* **WeatherAPI.com** (data source)
* **Power Query** (ETL – Extract, Transform, Load)
* **DAX (Data Analysis Expressions)** for calculations

---

## 🔍 Key Features of Dashboard

1. **📊 Current Weather Overview**

   * Real-time conditions for selected cities
   * Temperature, Humidity, Wind Speed, UV Index

2. **📈 Trends & Forecast Analysis**

   * Daily & Weekly temperature variations
   * Rainfall probability and seasonal changes
   * Forecast visualization with line/area charts

3. **🗺️ Geo-Visualization**

   * Interactive map showing weather across cities/countries
   * Color-coded temperature and humidity indicators

4. **📅 Historical Analysis**

   * Compare weather across multiple time periods
   * Detect anomalies & extreme conditions

5. **⏳ Filters & Slicers**

   * City/Region selection
   * Time range (Daily, Weekly, Monthly)
   * Weather condition filters (Sunny, Rainy, Cloudy, etc.)

---

## 📊 Example Insights

* Identify **hottest and coldest cities** in real time.
* Analyze **rainfall patterns** across different months.
* Compare **day vs. night temperatures**.
* Monitor **wind speed trends** for weather-sensitive industries.

---

## 🚀 Project Outcomes

* An **interactive Power BI dashboard** powered by live API data.
* Ability to **monitor real-time weather updates** across locations.
* Historical and forecast views for **trend detection & decision making**.

---


## 📌 Future Enhancements

* Integrate **alerts/notifications** for extreme weather events.
* Add **custom Power BI visuals** for advanced forecasting.
* Extend dashboard with **climate comparison across years**.

---

## 🙌 Acknowledgments

* **[WeatherAPI.com](https://www.weatherapi.com/)** for providing the free weather data API.
* **Microsoft Power BI Community** for DAX & visualization resources.

---

