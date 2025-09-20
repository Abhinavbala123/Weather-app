# Weather App – Real-Time Local Weather Dashboard

A **modern weather web app** that displays real-time weather information including temperature, humidity, wind speed, sunrise, and sunset times for any location, using **OpenWeatherMap** and **TimeZoneDB APIs**.  

---

## Table of Contents

- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [How It Works](#how-it-works)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)  



---

## Features
- Search for any city to get real-time weather data.  
- Displays temperature, humidity, wind speed, and weather description.  
- Accurate **local date and time** using **IANA time zones**.  
- Sunrise and sunset times displayed correctly for each location.  
- Clean and responsive design using HTML, CSS, and JavaScript.  
- Handles invalid inputs with user-friendly error messages.  

---

## Tech Stack
- **Frontend:** HTML5, CSS3, JavaScript  
- **APIs:** OpenWeatherMap API, TimeZoneDB API  
- **Version Control:** Git & GitHub  

---

## How It Works
1. **User Input**  
   - User enters a city name in the search bar.  

2. **API Requests**  
   - Frontend sends a request to **OpenWeatherMap API** for weather data.  
   - Retrieves **latitude and longitude** from the response.  
   - Sends a request to **TimeZoneDB API** to get the **local time** using IANA time zones.  

3. **Display**  
   - JavaScript updates the UI with real-time weather info, date, and time.  
   - Sunrise and sunset times are converted to the local timezone.  

---

## Installation

**Clone the repository:**
```bash
git clone https://github.com/yourusername/weather-app.git
cd weather-app

const WEATHER_API_KEY = 'your_openweathermap_api_key';
const TIMEZONE_API_KEY = 'your_timezone_db_api_key';

