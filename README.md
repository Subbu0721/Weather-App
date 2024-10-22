## Overview
The Weather App is a simple web application that allows users to search for weather information by city. It displays the current weather, including temperature, humidity, wind speed, and an appropriate weather icon. Additionally, the app shows the local time of the searched city based on its timezone.

## Features
Search for the current weather by city name.
Display the current temperature, humidity, and wind speed.
Show appropriate weather icons based on weather conditions (Clear, Clouds, Rain, etc.).
Display the local time of the city based on its timezone.
Responsive design to work across different screen sizes.

## Technologies
HTML5: Structure and content of the app.
CSS3: Styling and layout (including responsiveness).
JavaScript (ES6): Logic for interacting with the weather API and updating the UI.
OpenWeatherMap API: Provides weather data.

## Installation
Clone the repository to your local machine.
git clone https://github.com/your-username/weather-app.git
Navigate into the project directory.
cd weather-app

Create an images folder in the root directory and add the necessary weather icons:
search.png
clear.png
clouds.png
rain.png
drizzle.png
mist.png
humidity.png
wind.png

Open the project in your favorite code editor or simply open index.html in your browser.

## Usage
Open the Weather App in your browser.

Enter the name of a city in the search bar.

Click the search button (magnifying glass icon).

The app will fetch and display the current weather information and local time of the city.

If an invalid city name is entered, an error message will appear.

# Example:
Searching for "Texas" will display the temperature, weather conditions, humidity, wind speed, and the local time in Texas.

# API Reference
This project uses the OpenWeatherMap API to fetch weather data.

# API Endpoint:
https://api.openweathermap.org/data/2.5/weather?units=metric&q={city}&appid={API_KEY}
city: The name of the city to get weather information for.
API_KEY: Your personal API key from OpenWeatherMap. You can get one by signing up here.

# Important:
Replace the apiKey variable in the JavaScript file (script.js) with your own API key.

const apiKey = "your-api-key"; // Replace with your OpenWeatherMap API key

# Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page to submit any suggestions or bugs.
