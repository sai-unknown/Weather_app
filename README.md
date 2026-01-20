# Weather Web App

A simple and responsive weather web application that allows you to:

- View current weather and 5-day forecast for your location.
- Search for weather in different cities worldwide.
- Add multiple cities to your “World Weather” view.

This app uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch weather data.

---

## Features

1. **Current Location Weather**  
   Automatically detects your location and displays the current weather and forecast.

2. **City Search**  
   Search for any city worldwide and view its weather, including temperature, humidity, wind, sunrise, and sunset.

3. **World Weather**  
   Add multiple cities to your “World” page to see weather at a glance for all your favorite locations.

4. **Responsive Design**  
   Works on desktop and mobile screens.

---

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- [OpenWeatherMap API](https://openweathermap.org/api)
- [Font Awesome](https://fontawesome.com) for icons

---

## Getting Started

1. **Clone or download the repository.**

```bash
git clone 
```
Add your OpenWeatherMap API key.

Open the JS files main.js, search.js, and world.js, and replace "YOUR_API_KEY_HERE" with your actual API key:
```
let apiKey = "YOUR_API_KEY_HERE";
```

⚠️ Do not share your API key publicly.

Open the HTML files in your browser
You can double-click index.html, search.html, or world.html.

Then open http://localhost:8000
in your browser.

File Structure
```
project/
│
├─ index.html        # Main page
├─ search.html       # Search page
├─ world.html        # World weather page
│
├─ css/
│  ├─ style.css
│  ├─ search.css
│  └─ world.css
│
├─ js/
│  ├─ main.js
│  ├─ search.js
│  └─ world.js
│
└─ img/              # Weather icons
```
Notes

Ensure an active internet connection to fetch weather data from OpenWeatherMap.

License

This project is open-source and free to use for personal or educational purposes.
