# Basic-Projects
# 🌤️ WeatherNow - Live Weather Dashboard

A modern, responsive weather application featuring a **Glassmorphism UI** and real-time data integration. This project fetches live weather conditions and a 5-day forecast for any city globally using the OpenWeatherMap API.

![Project Banner](placeholder_for_your_screenshot.png) 
*(Tip: Take a screenshot of your beautiful "Blue Sky" app and replace this line with the image)*


## ✨ Key Features
* **Real-Time Data:** Fetches current temperature, humidity, wind speed, and atmospheric pressure.
* **5-Day Forecast:** Implements a custom filtering algorithm to extract and display daily forecasts from raw 3-hour interval data.
* **Dynamic Visuals:** Weather icons change dynamically based on the specific condition (Clear, Rain, Clouds, etc.).
* **Glassmorphism UI:** A modern, semi-transparent user interface built with pure CSS (backdrop-filter).
* **Error Handling:** gracefully handles invalid city names (404 errors) and API connection issues.
* **Smart Date Handling:** Automatically calculates correct weekdays for the forecast, handling weekend rollovers (Saturday -> Sunday).

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3 (Flexbox, CSS Variables), JavaScript (ES6+).
* **API:** OpenWeatherMap (Current Weather & 5-Day Forecast endpoints).
* **Architecture:** Asynchronous Fetch API with `async/await`.

## 🧠 What I Learned
Building this project helped me master several core web concepts:
* **API Integration:** How to fetch data, handle JSON responses, and parse nested objects.
* **Data Manipulation:** How to filter large datasets (arrays) to extract specific time-slots for the 5-day forecast.
* **DOM Manipulation:** Updating HTML elements dynamically without reloading the page.
