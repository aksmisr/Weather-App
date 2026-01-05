# 🌤️ Weather App (PyQt5)

A simple desktop Weather Application built using Python and PyQt5 that fetches real-time weather data from the OpenWeatherMap API.

The app allows users to enter a city name and displays:
- Temperature in Celsius
- Weather description
- Weather emoji based on conditions

--------------------------------------------------

🚀 FEATURES

- Clean PyQt5 GUI
- Real-time weather data
- Emoji-based weather visualization
- Proper error handling (invalid city, network issues, API errors)
- Secure API key handling using environment variables

--------------------------------------------------

🛠️ TECH STACK

- Python 3
- PyQt5
- Requests
- OpenWeatherMap API

--------------------------------------------------

📦 INSTALLATION & SETUP

1) Clone the repository

git clone https://github.com/aksmisr/Weather-App.git
cd Weather-App

2) Create and activate virtual environment

Windows:
python -m venv .venv
.\.venv\Scripts\activate

Linux / macOS:
python -m venv .venv
source .venv/bin/activate

3) Install dependencies

pip install -r requirements.txt

--------------------------------------------------

🔑 API KEY SETUP (IMPORTANT)

Create a free API key from:
https://openweathermap.org/api

Windows (PowerShell):
setx OPENWEATHER_API_KEY "your_api_key_here"

Linux / macOS:
export OPENWEATHER_API_KEY="your_api_key_here"

Restart VS Code or terminal after setting the API key.

--------------------------------------------------

▶️ RUN THE APPLICATION

python main.py

--------------------------------------------------

📁 PROJECT STRUCTURE

Weather-App/
│
├── main.py
├── requirements.txt
├── README.md
└── .gitignore

--------------------------------------------------

🔐 SECURITY NOTES

- API key is NOT hardcoded in the source code
- Environment variables are used for safety
- Do NOT push .env files to GitHub
- Old leaked API keys should be deleted immediately

--------------------------------------------------

🧪 COMMON ERRORS & FIXES

401 Unauthorized:
- OPENWEATHER_API_KEY not set correctly
- Restart terminal / VS Code

City Not Found:
- Check spelling of the city name

--------------------------------------------------

📄 LICENSE

This project is created for learning and personal use.

--------------------------------------------------

🙌 ACKNOWLEDGEMENTS

- OpenWeatherMap API
- PyQt5 Documentation
