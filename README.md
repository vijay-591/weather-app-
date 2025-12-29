# 🌦️ Weather Forecasting Web Application

This is a **Weather Forecasting Web Application** built using **Python and Flask**.  
It fetches real-time weather data using a weather API and displays it through a simple, user-friendly web interface.

---

## ✨ Features

- 🌍 Search weather by city name
- 🌡️ Displays temperature, humidity, wind speed, and weather condition
- ⚡ Real-time weather data using API
- 🌐 Web interface using HTML, CSS, and JavaScript
- 🧠 Simple Flask backend
- 🖥 Runs locally on your system

---

## 🛠 Technologies Used

- **Python 3**
- **Flask**
- **HTML**
- **CSS**
- **JavaScript**
- **Weather API (OpenWeatherMap)**
- **VS Code**
- **Git & GitHub**

---

## 📁 Project Structure

weather-app/
│
├── app.py
├── README.md
├── requirements.txt
│
├── templates/
│   └── index.html
│
├── static/
│   ├── style.css
│   └── script.js
│
└── venv/

> ⚠️ Do not push `venv/` to GitHub.

---

##  API Key Setup

1. Create an account at **OpenWeatherMap**
2. Generate your API key
3. In `app.py`, add your API key:

```python
API_KEY = "YOUR_API_KEY_HERE"


## For security, avoid pushing API keys to GitHub.
Use environment variables for production.


## Install Dependencies
pip install flask requests

## Run the Application
python app.py

## Example Output

City: Hyderabad
Temperature: 30°C
Weather: Clear Sky
Humidity: 55%
Wind Speed: 3.2 m/s

## Limitations

Requires internet connection
Free API has request limits
Accuracy depends on weather API

## Future Enhancements

Dark / Light mode
  Auto location detection
  7-day weather forecast
  Graphs and charts
  Deploy on cloud (Render / Railway)

## Author

Vijay Kumar,
AI / ML & Python Developer,
Built as a learning and portfolio project
