# Weather App — WeatherAPI ☁️

A small web app that shows the current weather and a 5-day forecast for a searched city using the OpenWeather API. Built with plain HTML, CSS, and JavaScript.

---

## Features ✅

- Search weather by **city name**
- Current weather: **temperature**, **condition**, **humidity**, and **wind speed**
- 5-day forecast (snapshot at **12:00** each day)
- Responsive layout and weather icons

---

## How to use 🔍

1. Open `index.html` in your browser (recommended: run a local server for best compatibility).
2. Type a city name into the search box and press **Enter** or click the **Search** button.
3. The app shows the current weather and the 5-day forecast (if available).

Tip: If you see the **Not found** message, check the city name spelling or try a different city.

---

## Setup / Download 📥

To clone the repository:

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>/weatherAPI
```

Serve the files locally (recommended):

```bash
# using Python 3
python -m http.server 8000
# or using npm http-server
npx http-server -p 8000
```

Then open http://localhost:8000 in your browser and navigate to the `weatherAPI` folder (or open `index.html` directly).

---

## API Key 🔑

This project uses the OpenWeather API. The API key is stored in `script.js` as the `APIkey` constant. If you'd like to use your own key:

1. Sign up at https://openweathermap.org/api and get an API key.
2. Open `script.js` and replace the value of `APIkey`:

```js
const APIkey = '<YOUR_API_KEY>'
```

---

## Project files

- `index.html` — Main webpage / UI
- `style.css` — Styles
- `script.js` — Fetches weather data and updates the DOM
- `assets/` — Weather icons and images

---

Made as a simple solo project for learning and practice. Enjoy! ✨

