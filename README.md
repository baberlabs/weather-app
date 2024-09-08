# Weather App

A simple and intuitive weather application built with React that allows users to check current weather conditions and forecasts for any location.

## Deployed Site

Visit [weather-by-baberr.netlify.app](https://weather-by-baberr.netlify.app/)

## Features

-   Search for weather information by location
-   Display current weather conditions including temperature, humidity, wind speed, and UV index
-   Show a 3-day weather forecast
-   Provide detailed hourly weather information for the current day
-   Responsive design for various screen sizes

## Technologies Used

-   React
-   Material-UI
-   Axios for API requests
-   Weather API (weatherapi.com)

## Installation

1. Clone the repository:
    ```
    git clone https://github.com/baberlabs/weather-app.git
    ```
2. Navigate to the project directory:
    ```
    cd weather-app
    ```
3. Install dependencies:
    ```
    npm install
    ```
4. Create a `.env` file in the root directory and add your Weather API key:
    ```
    VITE_API_KEY=your_api_key_here
    ```
5. Start the development server:
    ```
    npm run dev
    ```

## Usage

1. Enter a location in the search bar on the home page.
2. Click the "Search" button or press Enter to view the current weather and forecast.
3. Click "More Details" to see hourly weather information for the current day.
4. Use the "Go Back" button to return to previous screens.

## Screenshots

![image](https://github.com/user-attachments/assets/c387fc66-0f71-4fb1-9d02-511dec8fd955)

![image](https://github.com/user-attachments/assets/af0a71d9-24d0-4364-9865-2c716193d024)

![image](https://github.com/user-attachments/assets/368c567f-7fa4-4ad6-8ecb-1a8af9ac6a2f)

![image](https://github.com/user-attachments/assets/5b337ce4-da7e-41ac-9941-545d64b09329)

## Components

-   `App.jsx`: Main component managing the application state and rendering child components
-   `Search.jsx`: Handles user input for location search
-   `WeatherData.jsx`: Displays current weather conditions and 3-day forecast
-   `MoreDetails.jsx`: Shows detailed hourly weather information for the current day

## API

This application uses the [Weather API](https://www.weatherapi.com/) to fetch weather data. You'll need to sign up for a free API key to use this application.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
