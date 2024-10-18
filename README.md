# Weather Dashboard

## Overview

Weather Dashboard is a responsive web application that provides real-time weather information and forecasts. It features a clean, modern interface with interactive charts, a data table, and a chatbot for weather-related queries.

## Features

- Current weather display
- 5-day weather forecast
- Interactive weather charts
- Searchable locations
- Unit toggle between Celsius and Fahrenheit
- Data table with sorting and filtering options
- AI-powered chatbot for weather-related questions

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Chart.js for data visualization
- OpenWeatherMap API for weather data
- Gemini AI API for the chatbot functionality

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have a modern web browser installed (Chrome, Firefox, Safari, or Edge)
- You have obtained API keys for OpenWeatherMap and Gemini AI

## Installation and Running the Project Locally

### Prerequisites

1. **Web Browser**: Ensure you have a modern web browser (e.g., Chrome, Firefox, Safari).
2. **Code Editor**: Optional, but recommended for editing and customizing code (e.g., Visual Studio Code, Atom).

### Steps to Run Locally

1. **Clone the Repository**:

   Open your terminal (Command Prompt, PowerShell, or any terminal of your choice) and run the following command to clone the repository:

   ```bash
   git clone https://github.com/yourusername/weather-dashboard.git
   cd weather-dashboard
   ```

   Replace `yourusername` with your actual GitHub username or the appropriate repository link.

2. **Obtain an API Key**:

   Sign up for an API key at [OpenWeather](https://openweathermap.org/api) and replace the `apiKey` variable in `script.js` with your key:

   ```javascript
   const apiKey = {API_KEY}; // Replace YOUR_API_KEY with your actual API key
   ```

3. **Open the Project in a Browser**:

   - You can open the `index.html` file directly in your web browser. To do this, navigate to the cloned folder and double-click on `index.html`.

   - Alternatively, for a better experience (especially if you're using AJAX requests), you can serve the files using a local server. Here are two simple ways to do this:


   - **Using Live Server extension in Visual Studio Code**:

     If you are using Visual Studio Code, you can install the **Live Server** extension. Once installed, right-click on `index.html` and select "Open with Live Server".

## Usage

- Use the search bar to look up weather information for different locations.
- Toggle between Celsius and Fahrenheit using the unit switch.
- View detailed weather data in the table view.
- Use the chatbot for natural language queries about weather conditions.

## Customization

- You can customize the CSS in `styles.css` to modify the appearance of the dashboard.
- Adjust the chart configurations and data processing logic in `script.js` as needed.

## Contact

If you want to contact me, you can reach me at `i222711@nu.edu.pk`.

## Acknowledgements

- OpenWeatherMap for providing the weather data API
- Google for the Gemini AI API
- Chart.js for the charting library
