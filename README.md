# Module 5 Week 4 Day 1 Homework - React Weather App

**Course:** WEB 403 / WEB 603 - Full Stack Web Development  
**Student:** Migo Sea  
**Assignment:** React Weather App with OpenWeatherMap API & FontAwesome  

---

## Project Overview

This project is a React Weather Application built using React Hooks (`useState`, `useEffect`), OpenWeatherMap Current Weather Data API, Bootstrap 4 for styling, FontAwesome icons, and the `i18n-iso-countries` package for converting country codes to full official country names.

Users can enter any city/location in the search bar to fetch and view:
- Current weather status icon
- Current temperature in Fahrenheit
- Location / City name with map marker icon
- Daily Low temperature (in °F) with temperature-low icon
- Daily High temperature (in °F) with temperature-high icon
- Weather conditions (e.g., Clouds, Clear, Rain)
- Full official country name (e.g., United States of America)

---

## Technologies Used

- **React.js** (Functional Components, `useState`, `useEffect`)
- **Bootstrap 4** (`bootstrap/dist/css/bootstrap.min.css`)
- **FontAwesome Icons** (`@fortawesome/react-fontawesome`, `@fortawesome/free-solid-svg-icons`)
- **OpenWeatherMap API** (`https://api.openweathermap.org/data/2.5/weather`)
- **i18n-iso-countries** (ISO 3166-1 country code lookup)
- **CSS3** (Custom responsive card & footer styling)

---

## Setup & Running Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MigoSea/m5-w4-d1-homework.git
   cd m5-w4-d1-homework/react-weather-app
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure API Key:**
   Ensure `.env` exists in the `react-weather-app` root directory:
   ```env
   REACT_APP_API_KEY=c47c20ba679b36d0130ce1fe73ee627d
   ```

4. **Start Development Server:**
   ```bash
   npm start
   ```
   Open `http://localhost:3000` in your web browser.

---

## Project Structure

```
m5-w4-d1-homework/
├── README.md
├── .gitignore
└── react-weather-app/
    ├── .env
    ├── .gitignore
    ├── package.json
    ├── public/
    │   └── index.html
    └── src/
        ├── App.css
        ├── App.js
        ├── index.css
        └── index.js
```
