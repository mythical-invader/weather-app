# Weather App 🌤️

A clean, responsive web application that provides real-time weather updates for any city using the OpenWeatherMap API. 

## 🚀 Features
* **Real-Time Data:** Fetches current weather conditions, temperatures, and updates based on user search.
* **City Search:** Allows users to input any global city name to instantly retrieve its weather data.
* **Visual Elements:** Uses dynamic weather icons and images to visually represent current conditions.

## 🛠️ Tech Stack
* **HTML:** Structure of the web page.
* **CSS:** Styling and responsive layout.
* **Vanilla JavaScript:** Application logic, event handling, and asynchronous API fetching.

## 📁 File Structure
* `assets/` — Directory containing all the images and weather icons used in the application.
* `index.html` — The main layout and structure of the app.
* `style.css` — Contains all the styling for the user interface.
* `script.js` — Handles the main application logic, including the asynchronous `checkWeather` function.

## 💻 How to Run Locally

1. Clone this repository to your local machine:

```
   git clone https://github.com/mythical-invader/weather-app.git
```
2. Navigate to the project folder.

      * Open script.js and locate the api_key variable.
      * Replace the placeholder string with your own free API key from OpenWeatherMap:

        ` JavaScript: const api_key = "YOUR_API_KEY_HERE"; `

3. Double-click the index.html file to open it in your default web browser.

## 🔌 API Reference
This project relies on the OpenWeatherMap API to fetch live weather data via their data/2.5/weather endpoint.
