# Weather Forecast App

A weather forecast application that displays real-time weather information based on the city entered by the user. The app dynamically adjusts the background and applies weather-related animations to enhance the user experience.

## Features
- **Search for any city**: Enter a city name and see the current weather.
- **Weather Info**: Displays temperature, humidity, wind speed, and weather conditions.
- **Dynamic Background**: Changes background image according to the weather condition (e.g., sunny, rainy, snowy).
- **Weather Animations**: Includes weather-specific animations like snowflakes, rain, and clouds to visually reflect the current weather condition.

## Technologies Used
- **HTML**: For the basic structure of the web page.
- **CSS**: For styling, including weather-related animations and background changes.
- **JavaScript**: For fetching weather data and updating the UI dynamically.
- **OpenWeather API**: For real-time weather data.

## Animations & Backgrounds
- **Background Image**: The app dynamically changes the background image to reflect the weather condition. 
    - Sunny days will show a clear sky background.
    - Rainy or snowy weather will display related backgrounds.
- **Weather Animations**: The app displays animations based on the weather condition:
    - **Snow Animation**: Snowflakes falling when it’s snowing.
    - **Rain Animation**: Raindrops falling when it’s raining.
    - **Cloud Animation**: Moving clouds when the sky is cloudy.
    - **Clear Sky Animation**: A calm, sunny weather animation.

## File Structure
weather-app/
│
├── images/                # Folder containing the weather icons and background images
│   ├── sunny.png          # Sunny weather icon
│   ├── clouds-icon.png    # Cloudy weather icon
│   ├── rainy-icon.png     # Rainy weather icon
│   ├── drizzle-icon.png   # Drizzle weather icon
│   ├── mist-icon.png      # Mist weather icon
│   ├── image.jpg     # Background image for the app
│
│
├── index.html             # Main HTML file for the app
├── app.js                 # JavaScript file for fetching weather data and animations
└── styles.css             # CSS file for styling and animations
