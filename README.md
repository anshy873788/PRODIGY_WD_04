# ☁️ PRODIGY_WD_04 - Weather Dashboard

This is my submission for **Task 04** of the Web Development Internship at **Prodigy Infotech**.

---

## 📌 Project Description

This project is a dynamic **Weather Dashboard** web application built using **HTML, CSS, and JavaScript**. It allows users to view real-time weather information by searching for a city or using their current location.

---

## 🌟 Features

- 🔍 Search weather by city name
- 📍 Get weather data based on user's current geolocation
- 🌤️ Displays temperature, humidity, wind speed, pressure, visibility, and UV Index
- 🎨 Modern responsive UI with gradients and smooth animations
- ⚡ Option to switch between demo mode (mock data) and live API mode
- 🖼️ Weather icons for better visualization
- 🔄 Loading spinner and user-friendly error messages

---

## 🚀 How to Use

### 1. Open the App

Just open the `task04.html` file in your browser.

### 2. Search by City

- Enter any supported city (e.g., `London`, `Tokyo`, `Kanpur`) and click **Search**.
- In demo mode, only a few cities have mock data.

### 3. Use My Location

Click **"Use My Location"** to get the weather of your current location (if location permissions are granted).

---

## 🔧 Configuration

If you want to use **real-time weather data** instead of demo mode:

1. Sign up at [OpenWeatherMap](https://openweathermap.org/api) and get your **API Key**.
2. Replace the line in the script:
   ```js
   const API_KEY = 'your_api_key_here';
