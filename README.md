# 🌤️ Weather App

This is a responsive, interactive weather application that displays current weather data for any city using the WeatherAPI. It shows temperature, condition, humidity, cloudiness, and wind speed, along with dynamic background visuals that reflect the current weather.

## 🚀 Features

- Search for weather in any city
- Predefined city quick-select options
- Displays:
  - Current temperature
  - Weather condition and icon
  - Time and date
  - Humidity, cloud cover, and wind speed
- Dynamically updates background images based on:
  - Time of day (day/night)
  - Weather condition (clear, cloudy, rainy, snowy)
- Responsive design for mobile and desktop

## 🛠️ Technologies Used

- **HTML5** – Structure and markup
- **CSS3** – Styling with responsiveness and dynamic background overlays
- **JavaScript (Vanilla)** – Fetching and rendering live weather data
- **WeatherAPI** – External API for weather data
- **Font Awesome** – Icons for UI elements

## 📂 File Structure

- `index.html` – Main HTML layout of the weather app
- `style.css` – Styling including weather-based backgrounds and responsive design
- `main.js` – JavaScript logic for fetching and displaying weather data
- `weather/64x64/` – (Assumed) folder for condition-based background and icon images

## 📦 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   ```

2. **Open `index.html` in your browser**
   ```bash
   open index.html
   ```

3. **Search for any city or click on a listed one to see its current weather.**

> ⚠️ Replace the `key` in the API URL inside `main.js` with your own WeatherAPI key:
```javascript
https://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=${cityInput}
```

## 📸 Screenshots

> *(Add screenshots here for visual context)*

## 🧩 Future Improvements

- Add forecast (hourly/daily)
- Show more weather metrics (e.g., UV index, pressure)
- Improve error handling and input validation
- Add localization/multiple languages

## 📄 License

This project is licensed under the MIT License.

---

*Built with vanilla JavaScript and ❤️ for weather enthusiasts.*
