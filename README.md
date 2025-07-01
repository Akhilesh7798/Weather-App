# Weather App

A fully working weather application that shows the current weather for any city using the OpenWeatherMap API.

## How it works

1. The user enters a city name in the search box.
2. When the search button is clicked or Enter is pressed, the app requests weather data for that city from the OpenWeatherMap API.
3. The app displays the temperature, humidity, wind speed, and a weather icon appropriate for the current conditions.
4. If the city name is invalid, it shows an error message.

## Getting Started

1. Clone this repository  
   git clone https://github.com/Akhilesh7798/weather-app.git

2. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api).

3. Replace the API key  
   - Open script.js
   - Replace the value of apikey with your OpenWeatherMap API key:
          const apikey = "YOUR_API_KEY";
     

4. Run the App  
   Open index.html in your web browser.

## Features

- Search weather by city name
- Real-time temperature, humidity, and wind speed
- Weather icons for different conditions (clouds, clear, rain, drizzle, mist, snow)
- Responsive and modern design
- Error handling for invalid city names

## Project Structure

weather-app/
├── weather-app-img/
│   └── images/
│       ├── clouds.png
│       ├── clear.png
│       ├── rain.png
│       ├── drizzle.png
│       ├── mist.png
│       ├── snow.png
│       └── humidity.png
├── index.html
├── style.css
└── script.js

## License

This project is licensed under the MIT License.
