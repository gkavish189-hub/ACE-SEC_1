# 🌤️ GlassWeather Pro — Google-Inspired Weather Dashboard

A modern, responsive, and feature-rich Weather Application built with **Python (Flask)** and **JavaScript**. Inspired by Google's clean weather card design, this application fetches real-time weather metrics, multi-day forecasts, and hourly timelines using the free **Open-Meteo API**.

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-2.0+-000000?style=for-the-badge&logo=flask&logoColor=white)
![Iconify](https://img.shields.io/badge/Icons-Iconify--Meteocons-1769aa?style=for-the-badge)

---

## ✨ Features

- **Real-Time Data**: Instant updates for temperature, "feels like" status, humidity, wind speed, atmospheric pressure, and visibility.
- **3D Animated SVGs**: Interactive and smooth animated weather icons provided by Meteocons via Iconify.
- **6-Day Forecast**: Multi-day weather preview cards with daily high/low temperatures.
- **Hourly Weather Timeline**: Interactive horizontal scroll displaying hourly temperature fluctuations.
- **Dynamic Embedded Map**: Real-time location visualizer centered on the searched city.
- **No API Keys Required**: Uses open-access geocoding and forecasting endpoints.

---

## 🌐 Weather Data Provider

All meteorological data and geocoding services used in this application are provided by:

* **Open-Meteo**: [https://open-meteo.com](https://open-meteo.com)

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask, Requests
- **Frontend**: HTML5, CSS3 (Flexbox/Grid), JavaScript
- **Icons**: [Iconify (Meteocons)](https://iconify.design/), [Lucide Icons](https://lucide.dev/)
- **API**: [Open-Meteo API](https://open-meteo.com/)

---

## 📁 Project Structure

```text
weather-app/
│
├── app.py                # Flask application & API handling
├── templates/
│   └── index.html        # Main dashboard UI template
├── README.md             # Repository documentation
└── requirements.txt      # Project dependencies