# 🌤️ Weather App 🌦️

This is a simple weather application built using **HTML**, **CSS**, and **JavaScript** that allows users to check the current weather in any city. The app uses the [OpenWeatherMap API](https://openweathermap.org/) to fetch real-time weather data such as temperature, humidity, and wind speed. Users can search for a city by typing its name, and the app will display the weather information dynamically. 🌍🌡️

## Features ✨

- 🏙️ **Search** for a city by name.
- 🌡️ Displays **temperature**, **humidity**, and **wind speed**.
- 🌥️ Shows different **weather icons** based on the condition (e.g., clear, rain, snow, clouds).
- 🚫 Handles **invalid city names** and shows an error message.

## Technologies Used 🛠️

- **HTML**: For creating the structure of the app. 📝
- **CSS**: For styling the app and making it visually appealing. 🎨
- **JavaScript**: For fetching and displaying the weather data. 💻
- **OpenWeatherMap API**: For real-time weather data. 🌐

## How It Works ⚙️

1. 💬 **Enter a city name** into the search input and click the search button or press `Enter`.
2. 🌦️ The app sends a request to the OpenWeatherMap API to fetch weather data for the entered city.
3. ✅ If the city is found, it will display:
   - Temperature 🌡️
   - Humidity 💧
   - Wind Speed 🌬️
   - An appropriate weather icon 🌞🌧️❄️
4. 🚫 If the city is not found, an **error message** will appear informing the user that the city is invalid.

## Files Overview 📂

- `index.html`: The main HTML file containing the structure and layout of the weather app. 📄
- `style.css`: The CSS file for styling the app, making it visually appealing and responsive. 💅
- `images/`: A folder containing weather icons (rain, clouds, sun, snow, etc.) used to visually represent the weather condition. 🌈

## API Integration 🔑

This weather app uses the **OpenWeatherMap API** to get the current weather data. You can get your own API key by signing up on the [OpenWeatherMap](https://openweathermap.org/) website and using it in place of the provided API key in the script. 🔒

```javascript
const apiKey = "YOUR_API_KEY";  // Replace with your OpenWeatherMap API key
