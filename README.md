# Weatherapp
# WeatherApp - Django Weather Forecast Application

## Introduction

Welcome to the WeatherApp! This is a Django-based web application that allows users to search for the current weather conditions of any city in the world. With WeatherApp, users can quickly access up-to-date weather information for their desired location.

This README will provide you with detailed information on setting up and using the WeatherApp.

## Features

- **Current Weather Data**: Users can enter the name of a city, and the app will display the current weather situation, including temperature, humidity, wind speed, and more.

- **Real-Time Data**: WeatherApp fetches real-time weather data from a weather API to ensure accurate and up-to-date information.

- **User-Friendly Interface**: The application provides an intuitive and user-friendly interface for a seamless weather search experience.

## Prerequisites

Before getting started, ensure you have the following prerequisites installed:

- Python (3.6 or higher)
- Django (3.0 or higher)
- An internet connection (for fetching weather data)

## Installation

Follow these steps to set up the WeatherApp on your local machine:

1. Clone the repository (or download and extract the ZIP file):

   ```bash
   git clone https://github.com/yourusername/weatherapp-django.git
   cd weatherapp-django
   ```

2. Create a virtual environment (recommended):

   ```bash
   python -m venv venv
   ```
   --OR
   virtualenv env
  
4. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

5. Install the project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Configure the WeatherApp settings:

   - Create a `.env` file in the project root directory and add your API key for weather data. You can get an API key from a weather data provider like OpenWeatherMap or WeatherAPI.

     ```
     WEATHER_API_KEY=your_api_key_here
     ```

7. Apply the database migrations:

   ```bash
   python manage.py migrate
   ```

8. Start the development server:

   ```bash
   python manage.py runserver
   ```

9. Open a web browser and navigate to `http://localhost:8000` to access WeatherApp.

## Usage

1. Open WeatherApp in your web browser.

2. On the homepage, you'll find a search box where you can enter the name of a city.

3. After entering the city name, click the "Search" button.

4. WeatherApp will retrieve and display the current weather conditions for the specified city.

5. You can enter additional cities to check their weather as well.

## External APIs

WeatherApp uses an external weather API to fetch weather data. Ensure you have a valid API key and add it to the `.env` file as mentioned in the installation steps.

## Customization

You can customize the WeatherApp further by modifying the Django templates, styles, or adding additional features to enhance the user experience.

## Contributing

If you would like to contribute to this project, please follow the [contributing guidelines](CONTRIBUTING.md).

## Acknowledgments

- Thanks to the Django community for creating an excellent web framework.

## Contact

If you have any questions or need assistance, reach out

Stay informed about the weather with WeatherApp! 🌦️🌍
