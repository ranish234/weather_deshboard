# 🌦 Weather Dashboard

A Python project for visualizing hourly weather trends using a dataset (CSV) or live weather data from the OpenWeather API. It highlights how temperature, apparent temperature, humidity, and wind speed change over time.

---

## 📊 Features

- 📅 **Date Parsing**: Converts and parses the `Formatted Date` column to datetime objects.
- 🌡 **Temperature Trends**: Visualizes Actual vs Apparent Temperature over time.
- 💧 **Extendable Metrics**: Easily extend to plot Humidity, Wind Speed, Pressure, etc.
- 🎨 **Beautiful Visuals**: Uses Matplotlib and Seaborn for clear and customizable plots.
- 📂 **File-Based Input**: Reads from a properly formatted CSV (`weather_data.csv`).

---

## 📁 Dataset Columns

The dataset should include the following columns:

- `Formatted Date`
- `Summary`
- `Precip Type`
- `Temperature (C)`
- `Apparent Temperature (C)`
- `Humidity`
- `Wind Speed (km/h)`
- `Wind Bearing (degrees)`
- `Visibility (km)`
- `Loud Cover`
- `Pressure (millibars)`
- `Daily Summary`

> ✅ Ensure the CSV file is named `weather_data.csv` or change the filename in the code.

---

## 🔧 Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/weather_dashboard.git
cd weather_dashboard
