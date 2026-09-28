# Personal Dashboard

A lightweight, browser-based personal dashboard that provides a quick overview of useful daily information. This project features real-time cryptocurrency tracking, local weather updates, a live clock, and a dynamic background image.

## Features

*   **Real-Time Clock:** Displays the current local time, updated every second.
*   **Cryptocurrency Tracker:** Fetches live data from the CoinGecko API to display the current price, 24-hour high, and 24-hour low for Dogecoin.
*   **Local Weather:** Integrates with the OpenWeatherMap API to display the current temperature, city name, and weather condition icon based on the user's location.
*   **Dynamic Background:** Displays a beautiful, randomized background image with author attribution.
*   **Robust Error Handling:** Utilizes modern asynchronous JavaScript (`async/await`) wrapped in `try...catch` blocks to gracefully handle potential API failures or network issues.

## Technologies Used

*   **HTML5**
*   **CSS3**
*   **Vanilla JavaScript (ES6+)**
*   **[CoinGecko API](https://www.coingecko.com/en/api)** (for cryptocurrency data)
*   **[OpenWeatherMap API](https://openweathermap.org/api)** (for weather data)

## Project Structure

*   `index.html`: Contains the core structure and layout of the dashboard.
*   `index.css`: Handles the styling, layout positioning, and visual aesthetics.
*   `index.js`: Manages the application logic, asynchronous API calls, error handling, and DOM updates.
*   `manifest.json`: Configuration file for potential use as a browser extension.

## Setup and Installation

1.  Clone or download the repository to your local machine.
2.  Ensure all files (`index.html`, `index.css`, `index.js`, etc.) are in the same directory.
3.  Open `index.html` in any modern web browser. 
    *   *Note: To ensure location-based features (like weather) work correctly, you may need to run the project through a local development server (like VS Code's Live Server) and grant the browser location permissions.*
