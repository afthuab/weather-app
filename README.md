# Weather App

A simple and responsive web application that provides real-time weather data for any city. It displays the current weather conditions and a 5-day forecast.




---

## Live Demo

[**Click here to view the live application**](https://weather-app-flame-two.vercel.app/)





## Features

-   **Real-time Weather Data:** Get up-to-the-minute weather information.
-   **Current Conditions:** Displays temperature, humidity, and a weather description (e.g., "Cloudy," "Sunny").
-   **5-Day Forecast:** Shows the minimum and maximum temperature forecast for the next five days.
-   **Search Functionality:** Users can search for any city worldwide.
-   **Weather Icons:** Dynamically updates icons based on the weather conditions.
-   **Responsive Design:** The layout adapts seamlessly to desktop, tablet, and mobile devices.
-   **Error Handling:** Provides user-friendly messages for invalid city names or API errors.

## Technology Stack

-   **Frontend:** HTML, Tailwind CSS, JavaScript
-   **API:** [OpenWeatherMap API](https://openweathermap.org/api)
-   **API Calls:** Native Fetch API

## Setup and Usage

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/afthuab/weather-app.git
    cd weather-app
    ```

2.  **Get an API Key:**
    -   Go to [OpenWeatherMap](https://openweathermap.org/) and create a free account.
    -   Navigate to the "API keys" tab on your dashboard and copy your default API key.

3.  **Add the API Key to the project:**
    -   Open the `index.html` file.
    -   Find the following line in the `<script>` section:
        ```javascript
        const apiKey = 'YOUR_API_KEY';
        ```
    -   Replace `'YOUR_API_KEY'` with the actual API key you obtained from OpenWeatherMap.

4.  **Open the application:**
    -   Simply open the `index.html` file in your web browser.

That's it! You can now search for cities and view the weather.

## Deployment

This application is built with static files (HTML, CSS, JS) and can be easily deployed on various platforms:

-   **GitHub Pages:** Push the code to a GitHub repository and enable GitHub Pages in the repository settings.
-   **Netlify:** Drag and drop the project folder into the Netlify dashboard.
-   **Vercel:** Connect your Git repository and deploy with a few clicks.

## Environment Variables

For a more secure and standard setup in a larger project, you would use environment variables. Create a `.env` file in your project root and add your API key like this:

##
 Made with ❤️ by **afthuab**.

-   **GitHub:** [afthuab](https://github.com/afthuab)