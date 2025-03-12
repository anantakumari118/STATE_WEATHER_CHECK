# Weather App

## 📌 Overview
The **Weather App** is a simple GUI-based application built with **Tkinter** and **OpenWeather API** that allows users to check the weather details of different Indian states. The app provides information on **weather conditions, temperature, and pressure**.

## ✨ Features
- **User-Friendly Interface:** A well-structured and easy-to-use interface.
- **Dropdown Selection:** Users can select a state from a predefined list.
- **Real-Time Weather Data:** Fetches current weather details using the **OpenWeather API**.
- **Temperature Conversion:** Displays temperature in **Celsius**.
- **Custom Styling:** Uses **Tkinter widgets** for a visually appealing layout.

## 🛠️ Technologies Used
- **Python** for scripting.
- **Tkinter** for GUI development.
- **Requests** module to fetch API data.
- **OpenWeather API** for real-time weather information.

## 📜 How to Run
1. Clone this repository:
   ```sh
   git clone https://github.com/anantakumari118/weather-app.git
   ```
2. Install dependencies:
   ```sh
   pip install requests
   ```
3. Run the script:
   ```sh
   python weather_app.py
   ```
4. Select a state from the dropdown and click **Done** to fetch weather details.

## 🔑 API Key Configuration
This app uses the **OpenWeather API**. Replace the existing API key in the script with your own:
```python
api_key = "your_api_key_here"
data = requests.get("https://api.openweathermap.org/data/2.5/weather?q="+city+"&appid="+api_key).json()
```

## 🚀 Future Enhancements
- Add city-wise weather search.
- Improve UI design.
- Include additional weather parameters like **humidity and wind speed**.

## 📩 Contribution
Feel free to **fork this repository** and submit pull requests for improvements.


---
#### 👤 Author: **Ananta Kumari**

