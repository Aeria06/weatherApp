# WeatherApp

WeatherApp is a React-based weather application that fetches real-time weather data using the OpenWeatherMap API. It allows users to search for a location and displays the current weather conditions, including temperature, weather type, and other details.

---

## Features

- Search for weather by city name
- Displays the temperature in Celsius
- Shows weather conditions like clouds, rain, etc.
- User-friendly design with dynamic date display

---

## Setup Instructions

Follow these steps to set up the WeatherApp on your local machine:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/weatherApp.git
cd weatherApp
```

### 2. Install Dependencies

Install the necessary packages using npm or yarn:
```bash
npm install
# or
yarn install
```

### 3. Generate Your OpenWeatherMap API Key

1. Go to [OpenWeatherMap.org](https://openweathermap.org/)
2. Create an account or log in.
3. Navigate to the **API Keys** section ("My Keys").
4. Create a new API key by providing a name.
5. Copy the generated key.

### 4. Add Your API Key

Update the `api` object in the `Climate.jsx` file with your API key:

```javascript
const api = {
    key: "YOUR_API_KEY_HERE",
    base: "https://api.openweathermap.org/data/2.5/"
};
```

Replace `YOUR_API_KEY_HERE` with the API key you generated.

### 5. Run the Application

Start the development server:
```bash
npm start
```
The application will be available at `http://localhost:3000`.

---

## File Structure

```plaintext
weatherApp/
|-- src/
|   |-- components/
|   |   |-- Climate.jsx     # Main weather app component
|   |-- App.css             # Global styling
|   |-- index.js            # Entry point
|-- public/
|   |-- index.html          # HTML template
|-- package.json            # Dependencies and scripts
```

---

## Technologies Used

- **React**: Frontend framework
- **OpenWeatherMap API**: To fetch weather data
- **CSS**: For styling

---

## Example API Call

Below is an example API request used in the application:

```bash
GET https://api.openweathermap.org/data/2.5/weather?q=delhi&units=metric&appid=YOUR_API_KEY
```

---

## Screenshots

### for cold Weather
![image](https://github.com/user-attachments/assets/84f25c17-08f6-4140-8634-663b7b79ff4d)


### for warm weather
![image](https://github.com/user-attachments/assets/2cba7477-eb8e-4922-b08a-f8becdc81048)



---

## Contribution

Contributions are welcome! If you'd like to contribute:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Create a Pull Request

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather API.

