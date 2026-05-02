# 🌦️ Weather App

A simple weather application built with **React + Vite**.  
Users can search for a city and see the current temperature, weather conditions, and a dynamic background that changes based on the weather.

---

## 📦 Installation

Before running the project, install all dependencies with:

```bash
npm install
```

You don’t need the `node_modules` folder in the repository — it gets recreated automatically when someone runs the command above.

---

## 🚀 Running the Project

Start the development server with:

```bash
npm run dev
```

Vite will start a local server and show a link like:

```
http://localhost:/
```

Open it in your browser to view the app.

---

## 🗂️ Project Structure

```
weather-app/
│── public/
│   └── sounds/        # sound effects (rain, wind, thunder)
│
│── src/
│   ├── components/
│   │   ├── SearchBar.jsx
│   │   ├── WeatherCard.jsx
│   │   └── WeatherBackground.jsx
│   │
│   ├── hooks/
│   │   └── useWeather.js
│   │
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
│
│── .gitignore
│── index.html
│── package.json
│── package-lock.json
│── vite.config.js
│── eslint.config.js
│── README.md
```

---

## 🔑 Environment Variables

Create a `.env` file in the root of the project:

```
VITE_API_KEY=YOUR_API_KEY_HERE
```

This file is **ignored by GitHub** (thanks to `.gitignore`).

---

## 🎵 About the Sounds

The sound files are stored in:

```
public/sounds/
```

If the audio files are too large, you can convert them to `.mp3` or `.ogg` to make the project lighter.

---

## 📝 Important Note (the text you asked for)

> **Never upload the `node_modules` folder to GitHub.**  
> It is extremely large and should not be part of the repository.  
> GitHub only needs `package.json` and `package-lock.json`.  
> Anyone who downloads the project can simply run `npm install` to restore everything.

---

## 📚 Technologies Used

- React  
- Vite  
- JavaScript  
- Weather API (OpenWeather or similar)  
- CSS  

---

## 💡 Future Improvements

- 7‑day forecast  
- Light/Dark mode  
- More detailed animations  
- Optional sound toggle  
