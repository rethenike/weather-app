# Weather App 🌤️

A simple and elegant weather application that provides current weather conditions and hourly forecasts for any city worldwide.

## Features

- 🌍 Search weather for any city
- 🌡️ Current temperature display
- 📊 Hourly weather forecast
- 🌤️ Weather condition icons
- 📱 Responsive design

## Setup

1. Clone the repository:
```bash
git clone [your-repository-url]
cd WeatherApp
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your OpenWeather API key:
```bash
OPENWEATHER_API_KEY=your_api_key_here
```

4. Start the application:
```bash
npm start
```

## Environment Variables

The application requires the following environment variable:
- `OPENWEATHER_API_KEY`: Your OpenWeather API key (get one at [OpenWeather](https://openweathermap.org/api))

## Usage

1. Enter a city name in the search box
2. Press Enter or click the search button
3. View current weather conditions and hourly forecast

## Live Demo
https://rethenike.github.io/weather-app/

## Technologies Used

- HTML5
- CSS3
- JavaScript
- OpenWeather API
- dotenv (for environment variable management)

## Security

- API keys are stored securely in environment variables
- `.env` file is gitignored to prevent accidental exposure of sensitive information

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
