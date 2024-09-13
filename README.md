# Weather App

## Overview
![image](https://github.com/user-attachments/assets/084f6592-2e53-44f7-ac87-03b694293ac1)

This Weather App provides current weather information, a forecast for the day, air conditions, and a 7-day weather forecast. The app fetches data from the [FreeWeather API](https://www.weatherapi.com/) and displays it in a user-friendly format.

**View project here**: https://pilord1.github.io/Weather-App

## Features

- **Current Weather**: Displays the current temperature, city name, and chance of rain.
- **Today's Forecast**: Shows the weather forecast every 4 hours of the current day.
- **Air Conditions**: Provides information about real feel temperature, wind speed, chance of rain, and UV index.
- **7-Day Forecast**: Displays the weather forecast for the next 7 days including temperature highs and lows.

## Files

- `index.html`: Contains the structure and layout of the weather app.
- `style.css`: Provides the styling for the app, including layout and design.
- `index.js`: Handles the JavaScript logic for fetching and displaying weather data.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Weather-App.git
2. **Navigate to the project directory:**
   ```
   cd Weather-App
   ```
3. **Open** `index.html` in your browser to view the application.

## Usage

1. **Open the app in your browser**: Double-click `index.html` or open it from your browser’s file menu.
2. **Enter a city name** in the search box and press Enter.
3. **View the results**: The app will display current weather, today’s forecast, air conditions, and a 7-day forecast for the specified city.

## API

The app uses the [FreeWeather API](https://www.weatherapi.com/) to fetch weather data. You need an API key to access the data. Replace `YOUR_API_KEY` in `index.js` with your actual API key.

```
const API_KEY = 'YOUR_API_KEY';
```

## Challenges and Solutions
### 1. Studying the API Documentation
**Challenge**: Understanding how to properly use the FreeWeather API documentation to fetch the required data for the app. The documentation was extensive, which made it challenging to pinpoint the exact endpoints and parameters needed.

**Solution**: To overcome this, I used the search function in the browser to look up keywords related to the data I needed. This approach helped me quickly locate relevant sections of the documentation. By focusing on specific keywords, I was able to identify the correct API endpoints and parameters to use.

### 2. Fetching Data from the API
**Challenge**: Writing the code to fetch data from the API and handle the JSON response correctly. This involved making asynchronous requests and handling various data formats.

**Solution**: I used async/await in JavaScript to simplify asynchronous operations and ensure the data was fetched and processed sequentially. By breaking down the data into manageable pieces and using console.log for debugging, I was able to track the data flow and identify any issues.

### 3. DOM Manipulation
**Challenge**: Dynamically updating the DOM with the fetched data. This included creating and appending elements based on the API response.

**Solution**: I used JavaScript to create and manipulate DOM elements efficiently. I employed `createElement` and `append` methods to dynamically build the weather information sections. By testing the app's functionality incrementally, I ensured that each part of the DOM was updated correctly based on the weather data.
