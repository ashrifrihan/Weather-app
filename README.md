# 🌤️ Weather App

A simple and responsive weather forecast app built using **React (Vite)** and **manual CSS**, powered by a free **Weather API**. Users can search for any city and get real-time weather information including temperature, weather conditions, and more.

---

## 🚀 Tech Stack

- ⚛️ React (Vite)
- 🎨 Manual CSS (No framework like Tailwind or Bootstrap)
- 🌐 Weather API (e.g., OpenWeatherMap)

---

## 📸 Features

- 🔍 Search weather by city name
- 📡 Real-time weather data
- 🌦️ Shows temperature, humidity, wind, weather condition icon
- 🧑‍🎨 Clean UI with pure CSS
- 🌙 Light/Dark theme friendly (optional enhancement)

---

## 🛠️ Setup & Installation

### Prerequisites:
- Node.js >= 14+
- Weather API key (get it from [OpenWeatherMap](https://openweathermap.org/api))

### 1. Clone the repo

```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app
```

### 2. Install dependencies

```bash
npm install
```

### 3. Add your API Key

Create a `.env` file in the root folder:

```env
VITE_WEATHER_API_KEY=your_api_key_here
```

### 4. Run the app

```bash
npm run dev
```

Open your browser and go to [http://localhost:5173](http://localhost:5173)

---

## 🧾 File Structure

```
📁 src
 ┣ 📄 App.jsx
 ┣ 📄 main.jsx
 ┣ 📁 components
 ┃ ┗ 📄 WeatherCard.jsx
 ┣ 📁 styles
 ┃ ┗ 📄 style.css
 ┗ 📄 index.css
```

---

## 📡 API Example (OpenWeatherMap)

**Endpoint:**
```
https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY&units=metric
```

---

## 🧠 Learnings

- How to use Vite with React for faster development
- How to consume REST APIs using `fetch`
- Managing state in functional components
- Writing custom CSS without a framework

---

## 🎯 Future Improvements

- Add 5-day forecast feature
- Improve accessibility and responsiveness
- Add local storage for last searched cities
- Add geolocation weather fetching

---

## 🙌 Acknowledgements

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [OpenWeatherMap API](https://openweathermap.org/api)

---

## 📄 License

MIT License © 2025 [Ashrif](https://github.com/your-username)
