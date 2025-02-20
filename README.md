Weather App

A simple weather application that fetches real-time weather data using the OpenWeather API and displays temperature, humidity, and wind speed based on the user's city input.

Features

Search for weather by city name

Displays temperature, humidity, and wind speed

Weather icons change dynamically based on conditions

Error handling for invalid city names

Technologies Used

HTML

CSS

JavaScript

OpenWeather API

Setup Instructions

Clone the repository:

git clone https://github.com/your-username/weather-app.git

Navigate to the project folder:

cd weather-app

Open index.html in a web browser.

API Key Configuration

This project uses the OpenWeather API. Replace YOUR_API_KEY in script.js with your own API key:

const apiKey = "YOUR_API_KEY";
const apiUrl = "https://api.openweathermap.org/data/2.5/weather?units=metric&q=";

How to Use

Enter a city name in the search box.

Click the search button or press "Enter".

The weather details for the city will be displayed.
