# WeatherApp - Android ☀️

A simple Android weather app built using Kotlin. It shows the current weather based on your location or searched city using the OpenWeatherMap API.

## Features

- Get weather using current location
- Search weather by city name
- Shows temperature, humidity, wind speed, and description
- Uses OpenWeatherMap API
- Clean and simple UI

## Tech Stack

- Java
- Retrofit (for API calls)
- ViewModel & LiveData
- Glide (for weather icons)
- MVVM Architecture
- Coroutines

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/dev-aniketj/WeatherApp-Android.git
   ```

2. Open the project in Android Studio.

3. Get your API key from [OpenWeatherMap](https://openweathermap.org/api) and add it in `Constants.kt`:
   ```kotlin
   const val API_KEY = "YOUR_API_KEY"
   ```

4. Run the app on your emulator or physical device.

## License

This project is open source and available under the MIT License.
