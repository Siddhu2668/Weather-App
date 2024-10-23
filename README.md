# Weather App


## Overview

This Weather App retrieves and displays weather data from the OpenWeatherMap API, offering real-time updates with user-configurable temperature units (Celsius, Fahrenheit, Kelvin). The app provides a 5-day weather forecast, including humidity, wind speed, and daily summaries for minimum, maximum, and average temperatures.

## Features
- **Weather Data Retrieval**: Fetches weather information using OpenWeatherMap API.
- **Temperature Unit Conversion**: Allows users to switch between Celsius, Fahrenheit, and Kelvin.
- **Real-Time Weather Display**: Displays current temperature, "feels like" temperature, and other essential data like wind speed and humidity.
- **5-Day Forecast**: Provides a visual breakdown of upcoming weather over the next 5 days.
- **User Input**: Search functionality for any city in the world.
- **Responsive Design**: Optimized for different screen sizes.

## Design Choices
- **Background Video**: A fullscreen background video is used to create an immersive experience.
- **Modular Design**: Cleanly separated the logic for fetching, displaying, and converting weather data.
- **User-friendly**: The app features a simple interface with intuitive controls for searching cities and changing temperature units.

## Requirements
- Screen resolution of at least 1070x680.
- Optional: Node.js for hosting on a live server, if live-server utility isn't available.

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, etc.).
- **Node.js** (for optional local development).

### Installation
1. **Clone the Repository**
   ```bash
   git clone https://github.com/Siddhu2668/Weather-App.git
   cd Weather-app-main
   ```
2. **Optional: Install Dependencies for Backend (if live server is required)**
   ```bash
   npm install
   ```
3. **Run the App Locally**
   If you don't have a live server utility, install and run `http-server` to view the app:
   ```bash
   npm install http-server -g
   http-server -p 8080
   ```
4. **Open in Browser**
   Open your browser and navigate to:
   ```
   http://localhost:8080
   ```

## Usage
- **Search for a City**: Type in the name of the city and press "Enter" or click the search button to fetch the weather data.
- **Change Temperature Units**: Use the dropdown in the top left to switch between Celsius, Fahrenheit, and Kelvin.
- **View 5-Day Forecast**: Scroll down to see the detailed weather forecast for the next 5 days.

## Code Breakdown
- **HTML/CSS**: The structure and styling of the web page, including the background video and layout of weather data.
- **JavaScript**: Handles fetching weather data, converting temperature units, and dynamically updating the UI.
- **API Integration**: Uses OpenWeatherMap API to get real-time weather data.

## API Integration
To fetch the weather data, the app uses OpenWeatherMap's API:

```bash
https://api.openweathermap.org/data/2.5/forecast?q={city}&units=metric&appid={API_KEY}
```
- Replace {city} with the user-input city and {API_KEY} with your API key.

## Future Enhancements
- Add more detailed weather metrics like UV index, pressure, and visibility.
- Implement geolocation to detect the user's location and show the weather automatically.
- Add hourly forecasts for better short-term predictions.


## Contact
Feel free to reach out for any queries: siddharthasiddhu036@gmail.com

---

Enjoy exploring the weather anywhere in the world! 🌍🌦️
```

You can now update your `README.md` file with this content.
