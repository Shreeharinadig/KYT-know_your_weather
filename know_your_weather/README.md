# KYT - Know Your Weather

## Introduction

Welcome to KYT - Know Your Weather, a Flutter app designed to provide real-time weather information for any city in the world. KYT makes API calls to fetch accurate and up-to-date weather data, offering users a convenient way to stay informed about the current weather conditions.

## Features

- **Weather Information:** Get detailed weather data for any city globally.
- **User-Friendly Interface:** A simple and intuitive user interface for easy navigation.
- **Flutter Framework:** Developed with Flutter, offering a seamless cross-platform experience for both Android and iOS users.
- **API Integration:** Utilizes API calls to fetch real-time weather data from reliable sources.

## Getting Started

### Prerequisites

- Ensure you have Flutter installed. If not, follow the [Flutter installation guide](https://flutter.dev/docs/get-started/install).
- Obtain an API key from a weather data provider (e.g., OpenWeatherMap, WeatherAPI) and configure it in the app.

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/kyt-know_your_weather.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd know_your_weather
    ```

  

3. **Install dependencies:**

    ```bash
    flutter pub get
    ```

4. **Run the app:**

    ```bash
    flutter run
    ```

## Configuration

### API Key Setup

1. Obtain an API key from a weather data provider (e.g., [OpenWeatherMap](https://openweathermap.org/), [WeatherAPI](https://www.weatherapi.com/)).
2. Add the API key to the `secrets.dart` file in the `lib/` directory.

## App Structure

- `lib/` contains the Flutter source code.
  - `main.dart` is the entry point of the application.
  - `screens/` includes various screens for displaying weather information.
  - `services/` contains the code for making API calls and handling data.
  - `widgets/` includes reusable UI components.

## Dependencies

- `flutter_bloc`: State management for Flutter applications.
- `http`: HTTP client for making API calls.
- `intl`: Internationalization and localization support.
- `provider`: Dependency injection for state management.



---

Stay informed about the weather with KYT - Know Your Weather! If you have any questions or suggestions, feel free to reach out.
