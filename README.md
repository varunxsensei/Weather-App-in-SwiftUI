# 🌦️ Weather App (Swift & SwiftUI)

A simple weather app built using **SwiftUI** and **OpenWeather API**, which fetches real-time weather data based on the user's current location.

## 🚀 Features

- Fetches current location using `CoreLocation`
- Calls OpenWeatherMap API for weather data
- Displays:
  - Location name
  - Temperature in °C
  - Weather condition (e.g., Clear, Rainy)
- Clean SwiftUI interface with a glass-style card view

## 🧱 Tech Stack

- **SwiftUI** – UI building
- **CoreLocation** – Accessing user's GPS location
- **URLSession** – Networking for API requests
- **Codable** – Parsing JSON data

## 🔧 How It Works

1. The app requests the user's permission to access location.
2. Upon location fetch, it uses `latitude` and `longitude` to call OpenWeather API.
3. Parses the JSON response and displays weather data in a SwiftUI view.

## 📁 Project Structure

- `Weather_AppApp.swift`: Entry point of the app
- `ContentView.swift`: Main view with weather display logic
- `WeatherData.swift`: Models and `LocationManager` logic

## 🛠️ Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/varunxsensei/weather-app.git
