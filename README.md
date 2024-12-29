# WeatherApp

WeatherApp is a Flutter application that provides real-time weather information based on the user's current location. This app uses OpenWeather API to fetch weather data and integrates various Flutter packages to enhance functionality.

## Features
- Get current weather information.
- Automatically fetches weather data based on the user's location.
- Supports internationalization with the `intl` package.
- State management using `flutter_bloc`.

## Requirements
- Flutter SDK
- OpenWeather API Key

## Installation

1. Clone this repository:
   ```bash
   https://github.com/mhdthariq/WeatherAppFlutter.git weatherapp
   cd weatherapp
   ```

2. Install dependencies:
   ```bash
   flutter pub get
   ```

3. Add your OpenWeather API key in a `data/my_data.dart` file or directly in the code (You can create it in `lib` folder):
   ```dart
   const String apiKey = 'YOUR_OPENWEATHER_API_KEY';
   ```

4. Run the app:
   ```bash
   flutter run
   ```

## Dependencies

This project uses the following dependencies:

```yaml
geolocator: ^13.0.2
weather: ^3.1.1
intl: ^0.20.1
flutter_bloc: ^8.1.6
equitable: ^2.0.7
```

- **geolocator**: For obtaining the device's location.
- **weather**: To fetch weather data from OpenWeather API.
- **intl**: For internationalization and date formatting.
- **flutter_bloc**: To manage application state.
- **equitable**: For value equality in Dart objects.

## Usage

1. When the app is launched, it will request location permission.
2. Once permission is granted, the app fetches weather data for the current location.
3. The weather data is displayed with temperature, conditions, and other relevant details.

## Screenshots

![Screenshot 1](screenshots/screen1.png)
![Screenshot 2](screenshots/screen2.png)
