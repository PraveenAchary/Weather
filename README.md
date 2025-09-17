# 🌤 Weather App

A simple **Weather Application** built using **HTML, JavaScript, and Bootstrap** that fetches real-time weather data from the **OpenWeather API**.

---

## 🔹 Features
- Enter any **city name** to get live weather information.
- Displays:
  - 🌍 City Name  
  - 🌡 Temperature (°C)  
  - 🤔 Feels Like Temperature (°C)  
  - 💧 Humidity (%)  
  - 🌀 Wind Speed (m/s)  
  - 🌬 Pressure (hPa)  
  - 🌥 Weather Description  
- Error Handling:
  - Shows **❌ Invalid City** message in red if the input is incorrect.

---

## 🔹 Tech Stack
- **Frontend**: HTML5, JavaScript (Vanilla JS), Bootstrap 5  
- **API**: [OpenWeather API](https://openweathermap.org/api)  
- **Styling**: Bootstrap classes for responsive design  

---

## 🔹 How It Works
1. User enters a city name in the input box.  
2. On clicking **CHECK**, a request is made to OpenWeather API.  
3. The app fetches JSON data and displays weather details inside a styled Bootstrap card.  
4. If the city is invalid, an error message appears.  

---

## 🔹 Setup & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/PraveenAchary/Weather.git
