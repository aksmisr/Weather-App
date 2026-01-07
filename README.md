# 🌤️ Weather App (PyQt5)

A simple desktop Weather Application built using Python and PyQt5 that fetches real-time weather data from the OpenWeatherMap API.

The app allows users to enter a city name and displays:
- Temperature in Celsius
- Weather description
- Weather emoji based on conditions

---

## 🚀 Features

- Clean and responsive PyQt5 GUI
- Real-time weather data
- Emoji-based weather visualization
- Proper error handling (invalid city, network issues, API errors)
- Secure API key handling using environment variables

---

## 🛠️ Tech Stack

- Python 3
- PyQt5
- Requests
- OpenWeatherMap API

---

## 📦 Installation & Setup

1. Clone the repository

    git clone https://github.com/aksmisr/Weather-App.git  
    cd Weather-App

2. Create and activate virtual environment

   Windows (PowerShell):

    python -m venv .venv  
    .\.venv\Scripts\activate

   Linux / macOS:

    python -m venv .venv  
    source .venv/bin/activate

3. Install dependencies

    pip install -r requirements.txt

---

## 🔑 API Key Setup (IMPORTANT)

Create a free API key from:  
https://openweathermap.org/api

Windows (PowerShell):

    setx OPENWEATHER_API_KEY "your_api_key_here"

Linux / macOS:

    export OPENWEATHER_API_KEY="your_api_key_here"

Restart VS Code or terminal after setting the API key.

---

## ▶️ Run the Application

    python main.py

---

## 📁 Project Structure

Weather-App/
│
├── main.py
├── requirements.txt
├── .gitignore
└── README.md

---

## 🔐 Security Notes

- API key is NOT hardcoded in the source code
- Environment variables are used for safety
- Do NOT push .env or secret files to GitHub
- Delete leaked API keys immediately if exposed

---

## 🧪 Common Errors & Fixes

401 Unauthorized:
- OPENWEATHER_API_KEY not set correctly
- Restart terminal or VS Code

City Not Found:
- Check spelling of the city name

---

## 📄 License

This project is created for learning and personal use.

---

## 🙌 Acknowledgements

- OpenWeatherMap API
- PyQt5 Documentation

⭐ If you like this project, don’t forget to star the repository!
