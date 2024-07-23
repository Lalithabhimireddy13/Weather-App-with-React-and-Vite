# Weather App with React and Vite
Description
This project is a weather application built using React and Vite. It allows users to search for the current weather conditions in any city using the OpenWeatherMap API. The application displays temperature, humidity, wind speed, and weather icons based on the current weather conditions.

# Features
City Search: Enter the name of any city to get the current weather information.
Current Weather: Displays temperature, humidity, and wind speed.
Weather Icons: Shows icons representing the current weather conditions.
Responsive Design: Optimized for various screen sizes.
# Technologies Used
React: JavaScript library for building user interfaces.
Vite: Build tool providing a fast and lean development experience.
OpenWeatherMap API: Service for fetching weather data.
CSS: Styling the application.
# Getting Started
Prerequisites
Node.js and npm installed on your machine.
An API key from OpenWeatherMap.
# Installation
Clone the repository:

sh
Copy code
git clone https://github.com/Lalithabhimireddy13/my-react-weather-app.git
cd my-react-weather-app
Install dependencies:

sh
Copy code
npm install
Create a .env file in the root of the project and add your OpenWeatherMap API key:

plaintext
Copy code
VITE_APP_ID=your_openweathermap_api_key
Start the development server:

sh
Copy code
npm run dev
Open your browser and go to http://localhost:3000 to view the application.

# Project Structure
bash
Copy code
/public
  index.html
/src
  /assets
    search.png
    clear.png
    cloud.png
    drizzle.png
    humidity.png
    rain.png
    snow.png
    wind.png
  /components
    Weather.jsx
  App.jsx
  main.jsx
  index.css
.env
package.json
vite.config.js
# How to Run the Project
1. Clone the repository:

sh
Copy code
git clone https://github.com/your-username/my-react-weather-app.git
cd my-react-weather-app
2. Install dependencies:

sh
Copy code
npm install
3. Create a .env file:

plaintext
Copy code
VITE_APP_ID=your_openweathermap_api_key
4.Start the development server:

sh
Copy code
npm run dev
