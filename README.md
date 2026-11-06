# 🌦️ Weather Application Using Python

A desktop-based Weather Application developed using Python and PyQt5 that fetches real-time weather information using the OpenWeatherMap API. Users can enter a city name to retrieve current temperature, weather conditions, and corresponding weather emojis through a simple graphical user interface.

## 📌 Project Overview

This project demonstrates the integration of Python GUI development with external REST APIs. It allows users to check current weather conditions for different cities and displays the results in an interactive desktop application.

The application also incorporates exception handling to manage API errors, invalid city names, and network connectivity issues.

## ✨ Features

- **City-Based Weather Search:** Search for weather information by entering a city name.
- **Real-Time Weather Data:** Fetch current weather information using the OpenWeatherMap API.
- **Temperature Conversion:** Display temperature in Celsius.
- **Weather Descriptions:** Display weather conditions such as clear sky, rain, clouds, and snow.
- **Dynamic Weather Emojis:** Show corresponding emojis based on weather conditions.
- **Error Handling:** Handle invalid city names, authentication errors, server errors, and network connectivity issues.
- **Graphical User Interface:** Simple and interactive desktop interface built with PyQt5.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| PyQt5 | Graphical User Interface (GUI) |
| Requests | Sending HTTP requests to the API |
| OpenWeatherMap API | Fetching real-time weather data |
| JSON | Processing API responses |

## 📂 Project Structure

```text
Weather-Application/
│
├── Weatherapp.py       # Main application source code
├── requirements.txt    # Project dependencies
└── README.md           # Project documentation
```

## ⚙️ Installation & Setup

**1. Clone the repository**

```bash
git clone https://github.com/your-username/Weather-Application.git
```

**2. Navigate to the project directory**

```bash
cd Weather-Application
```

**3. Install the required dependencies**

```bash
pip install -r requirements.txt
```

Alternatively:

```bash
pip install PyQt5 requests
```

**4. Configure the API key**

- Visit [OpenWeatherMap](https://openweathermap.org/api).
- Create an account and generate an API key.
- Configure your API key in the application before running it.

**Security note:** The current source code uses a hardcoded API key. Replace the exposed key with a newly generated key and preferably use an environment variable to avoid committing credentials to GitHub.

**5. Run the application**

```bash
python Weatherapp.py
```

## 🌐 API Integration

This project uses the OpenWeatherMap Current Weather Data API to retrieve weather information.

**API Endpoint:**

```text
https://api.openweathermap.org/data/2.5/weather
```

The application retrieves the following information:

- City weather details
- Temperature
- Weather condition ID
- Weather description

The API response is processed using Python's JSON handling capabilities, and the relevant information is displayed through the PyQt5 interface.

## 🧠 Concepts Practiced

- Python Object-Oriented Programming (OOP)
- Classes and Objects
- Functions and Static Methods
- Exception Handling
- API Integration
- HTTP Requests and JSON Processing
- GUI Development using PyQt5
- Conditional Statements
- Data Extraction and Processing

## 🚀 Future Improvements

- Add humidity and wind speed information.
- Display a five-day weather forecast.
- Improve the graphical interface with modern styling.
- Add automatic location detection.
- Include sunrise and sunset information.
- Add weather history and city search suggestions.

## 👨‍💻 Author

**Varun Pant**

Aspiring Machine Learning Engineer | Python Developer | Data Analyst

GitHub: https://github.com/varunpant18

---

⭐ If you find this project useful, consider giving the repository a star!
