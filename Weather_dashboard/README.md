# 🌦️ Weather & Air Quality Dashboard (Power BI)

## 📌 Overview

This project is an interactive **Weather and Air Quality Dashboard** built using Power BI and Weather API data. It provides real-time insights into temperature, air pollution levels, and weather forecasts in a visually intuitive format.

---

## 🎯 Objectives

* Analyze real-time weather data
* Monitor Air Quality Index (AQI) metrics
* Build an interactive and user-friendly dashboard
* Apply data modeling and DAX concepts

---

## 📊 Dashboard Features

### 🌡️ Weather Insights

* Current temperature and condition
* 7-day temperature forecast (line chart)
* Sunrise & sunset timings

### 🌧️ Environmental Metrics

* Rain probability analysis
* Wind speed, humidity, pressure, UV index

### 🌫️ Air Quality Analysis

* PM10, PM2.5, NO2, SO2, CO, O3 levels
* Color-coded indicators for pollution severity

---

## 🛠️ Tools & Technologies

* **Power BI**
* **DAX (Data Analysis Expressions)**
* **Weather API**
* **Data Modeling (Star Schema)**

---

## 🧠 Data Model

* Fact Tables:

  * Forecast_day
  * Forecast_hour
  * Current
* Dimension Table:

  * Location

Relationships are built using location and date keys to ensure proper filtering and analysis.

---

## 📈 Key Insights

* AQI levels can be tracked dynamically using DAX measures
* Forecast trends help in identifying temperature patterns
* Pollution indicators highlight environmental risks visually

---

## 📸 Dashboard Preview

(Add your dashboard screenshot here)

---

## 📂 Project Structure

```bash
powerbi-weather-dashboard/
│── Weather_Dashboard.pbix
│── README.md
│── screenshots/
│     ├── dashboard.png
│     ├── data_model.png
│     ├── measures.png
```

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open it in **Power BI Desktop**
3. Refresh data (if API connection is active)

---

## 💡 Future Improvements

* Add real-time API refresh using Power BI Service
* Implement alert system for high AQI levels
* Enhance drill-through and tooltip interactions

---

## 👤 Author

**Shahalam Rayeen**
Aspiring Data Analyst | Power BI Enthusiast

📌 LinkedIn:www.linkedin.com/in/shahalam-rayeen-104435319
📌 GitHub: https://github.com/ShahAlam0306

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share your feedback!
