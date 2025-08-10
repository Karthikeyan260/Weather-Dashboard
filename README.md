# 🌤️ Weather Dashboard

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![OpenWeatherMap](https://img.shields.io/badge/OpenWeatherMap-FF8C00?style=for-the-badge&logo=weather&logoColor=white)](https://openweathermap.org/)

A modern, responsive weather dashboard application that provides real-time weather information for any city worldwide. Built with vanilla JavaScript and powered by the OpenWeatherMap API.

## ✨ Features

- 🔍 **City Search**: Search for weather information by city name
- 🌡️ **Real-Time Data**: Get current temperature and weather conditions
- 📅 **Date Display**: Shows current date with day, month, and year
- 🎨 **Modern UI**: Clean and intuitive user interface with smooth animations
- 📱 **Responsive Design**: Works seamlessly across different screen sizes
- ⚡ **Fast Loading**: Optimized for quick weather data retrieval
- 🎭 **Error Handling**: User-friendly error messages for invalid city names

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5** | Structure and markup |
| **CSS3** | Styling, animations, and responsive design |
| **Vanilla JavaScript** | Dynamic functionality and API integration |
| **OpenWeatherMap API** | Real-time weather data source |
| **Font Awesome** | Icons and visual elements |

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for API calls
- OpenWeatherMap API key (free registration required)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Karthikeyan260/Weather-Dashboard.git
   cd Weather-Dashboard
   ```

2. **Get your API key**
   - Visit [OpenWeatherMap](https://openweathermap.org/api)
   - Sign up for a free account
   - Generate your API key

3. **Configure API key**
   - Open `script.js`
   - Replace the existing API key with your own:
   ```javascript
   const apiKey = 'YOUR_API_KEY_HERE';
   ```

4. **Launch the application**
   - Open `index.html` in your web browser, or
   - Use a local server (recommended):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

5. **Access the application**
   - Open your browser and navigate to `http://localhost:8000`

## 🎯 Usage

1. **Search for Weather**
   - Enter a city name in the search input field
   - Click the "Submit" button or press Enter
   - View the current weather information

2. **Default Location**
   - The app loads with Visakhapatnam as the default city
   - Weather data updates automatically on page load

3. **Weather Information Displayed**
   - Current temperature in Celsius
   - Weather condition (e.g., Clear, Cloudy, Rainy)
   - City name and current date

## 📁 Project Structure

```
Weather-Dashboard/
├── index.html          # Main HTML file
├── style.css           # CSS styles and animations
├── script.js           # JavaScript functionality
├── images/             # Image assets
│   ├── bg.png         # Background image
│   └── main.png       # Main decorative image
└── README.md          # Project documentation
```

## 🔧 API Configuration

The application uses the OpenWeatherMap API. Here's how to set it up:

1. **API Endpoint**: `https://api.openweathermap.org/data/2.5/weather`
2. **Parameters**:
   - `q`: City name
   - `appid`: Your API key
3. **Response Format**: JSON
4. **Rate Limits**: Free tier allows 1,000 calls/day

### Example API Call
```javascript
const apiUrl = `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${apiKey}`;
```

## 🎨 Customization

### Styling
- Modify `style.css` to change colors, fonts, or layout
- The design uses CSS Flexbox for responsive layout
- Custom animations with CSS transitions

### Functionality
- Add more weather parameters (humidity, wind speed, etc.)
- Implement 5-day forecast
- Add geolocation support
- Include weather icons

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Development Guidelines
- Follow existing code style and formatting
- Test your changes thoroughly
- Update documentation if needed
- Ensure responsive design compatibility

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Karthikeyan260**
- GitHub: [@Karthikeyan260](https://github.com/Karthikeyan260)
- Project Link: [Weather Dashboard](https://github.com/Karthikeyan260/Weather-Dashboard)

## 🙏 Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather API
- [Font Awesome](https://fontawesome.com/) for the icons
- The open-source community for inspiration and resources

## 📞 Support

If you encounter any issues or have questions:
- Open an [issue](https://github.com/Karthikeyan260/Weather-Dashboard/issues)
- Check existing issues for solutions
- Contact the author through GitHub

---

⭐ **Don't forget to star this repository if you found it helpful!**
