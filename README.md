# Weather Application 🌤️

A simple and elegant weather application that fetches real-time weather data for any city using the OpenWeatherMap API. Built with HTML, CSS, and JavaScript, this app provides a clean and responsive user interface.

---

## Features ✨

- **Real-Time Weather Data**: Get current weather information for any city worldwide.
- **Dynamic Background**: A gradient background that adapts to the time of day (day/night).
- **Weather Emojis**: Fun and intuitive emojis to represent weather conditions.
- **Responsive Design**: Works seamlessly on both desktop and mobile devices.
- **Error Handling**: Displays user-friendly error messages for invalid inputs or API issues.

---

## Technologies Used 🛠️

- **HTML**: Structure of the application.
- **CSS**: Styling and animations, including fluid typography and hover effects.
- **JavaScript**: Fetching and displaying weather data from the OpenWeatherMap API.
- **OpenWeatherMap API**: Provides real-time weather data.

---

## How to Use 🚀

1. **Enter a City Name**: Type the name of the city you want to check the weather for in the input field.
2. **Submit**: Click the "Get Weather" button or press `Enter`.
3. **View Weather**: The app will display the city name, temperature, humidity, weather description, and a corresponding weather emoji.

---

## Setup Instructions 🛠️

### Prerequisites
- A modern web browser (e.g., Chrome, Firefox, Edge).
- An API key from [OpenWeatherMap](https://openweathermap.org/api).

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app

2. Add Your API Key:

- Open the weather.js file.
- Replace "YOUR_API_KEY_HERE" with your OpenWeatherMap API key:

    ```javascript
    const apiKey = "YOUR_API_KEY_HERE";

3. Run the Application:

Open the index.html file in your browser.

### Code Structure 📂
- index.html: The main HTML file containing the structure of the app.
- style.css: Contains all the styles, including animations and responsive design.
- weather.js: Handles fetching weather data, displaying it, and error handling.

### Customization 🎨
- Change Colors: Modify the CSS variables in the :root selector in style.css to customize the app's color scheme.
- Add Animations: Add or modify animations in the @keyframes section of style.css.
- Extend Features: Add more weather details (e.g., wind speed, sunrise/sunset times) by expanding the displayWeatherInfo function in weather.js.


### Credits 🙌
- OpenWeatherMap: For providing the weather data API.
- Google Fonts: For the Fira Sans and JetBrains Mono fonts.
- You: For using and contributing to this project! 😊