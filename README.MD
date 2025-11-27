<div align="center">

# 🌍 Country & Weather Explorer

### Discover the World with Real-Time Information

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

[Features](#-features) •
[Demo](#-demo) •
[Installation](#-installation) •
[Usage](#-usage) •
[API References](#-api-references) •
[Contributing](#-contributing)

![Project Banner](https://via.placeholder.com/800x400/667eea/ffffff?text=Country+%26+Weather+Explorer)

</div>

---

## 📋 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [Usage](#-usage)
- [API References](#-api-references)
- [Screenshots](#-screenshots)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🎯 About

**Country & Weather Explorer** is a modern, interactive web application that combines country information and real-time weather data in one seamless experience. Built with vanilla JavaScript, this project demonstrates clean code practices, responsive design, and API integration.

### 🌟 Why This Project?

- 🔍 **Comprehensive Information**: Get detailed country statistics and current weather conditions
- 🎨 **Dynamic Backgrounds**: Weather-based background themes that change with conditions
- 📱 **Fully Responsive**: Perfect experience on desktop, tablet, and mobile devices
- 🌓 **Dark Mode Support**: Toggle between light and dark themes
- ⚡ **Fast & Lightweight**: No heavy frameworks, pure vanilla JavaScript

---

## ✨ Features

### 🗺️ Country Explorer

- 🏴 **Country Information**: Search for any country and get detailed data
- 📊 **Comprehensive Stats**: 
  - Population statistics
  - Capital city information
  - Regional data
  - Currency details
  - Official languages
  - Time zones
- 🛡️ **Visual Elements**: National flags and coat of arms
- 🗺️ **Interactive Maps**: See country locations on embedded maps

### 🌤️ Weather Explorer

- ⛅ **Real-Time Weather**: Current weather conditions for any location
- 🌡️ **Detailed Metrics**:
  - Temperature (actual & feels like)
  - Humidity levels
  - Wind speed & direction
  - Atmospheric pressure
  - UV index
  - Visibility
  - Cloud cover
- 🌬️ **Air Quality**: Real-time air quality information
- 🎨 **Dynamic Backgrounds**: Background changes based on weather conditions:
  - ☀️ Sunny/Clear
  - ☁️ Cloudy
  - 🌧️ Rainy
  - ❄️ Snowy
  - ⛈️ Thunderstorm
  - 🌫️ Foggy/Misty

### 🎨 UI/UX Features

- 🌓 **Theme Toggle**: Switch between light and dark modes
- 📱 **Responsive Design**: Optimized for all screen sizes
- 🎭 **Smooth Animations**: Elegant transitions and effects
- 🔍 **Smart Search**: Search by country name or city
- 📐 **Modern Layout**: Clean, card-based interface
- 🎯 **Intuitive Navigation**: Easy-to-use navigation menu

---

## 🛠️ Technologies Used

<div align="center">

| Technology | Purpose |
|------------|---------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Structure & Markup |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Styling & Animations |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | Functionality & Logic |
| ![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=flat-square&logo=google&logoColor=white) | Typography |
| ![SweetAlert2](https://img.shields.io/badge/SweetAlert2-7952B3?style=flat-square) | Beautiful Alerts |

</div>

---

## 📦 Installation

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS/JavaScript (for development)
- API keys (see [API References](#-api-references))

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/country-weather-explorer.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd country-weather-explorer
   ```

3. **Set up API keys**
   - Open `js/app.js`
   - Add your API keys:
     ```javascript
     const WEATHER_API_KEY = 'your_weather_api_key';
     const COUNTRY_API_KEY = 'your_country_api_key'; // if required
     ```

4. **Open the application**
   - Open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx http-server
     ```

5. **Start Exploring!** 🚀

---

## 🚀 Usage

### Country Search

1. Navigate to the **Country Explorer** section
2. Enter a country name in the search box
3. Click the **Search** button or press Enter
4. View detailed country information including:
   - Flag and coat of arms
   - Population and capital
   - Languages and currency
   - Interactive map

### Weather Search

1. Go to the **Weather Explorer** section
2. Enter a city or country name
3. Click **Search Weather**
4. Get real-time weather data:
   - Current temperature
   - Weather conditions
   - Humidity, wind, pressure
   - Air quality index
5. Watch the background change to match the weather! 🌈

### Theme Toggle

- Click the 🌙/☀️ icon in the navigation bar
- Switch between dark and light themes
- Preference is saved automatically

---

## 🔌 API References

This project uses the following APIs:

### 1. REST Countries API
- **Purpose**: Country information
- **Documentation**: [restcountries.com](https://restcountries.com)
- **Endpoint**: `https://restcountries.com/v3.1/`
- **Free**: ✅ Yes
- **Authentication**: ❌ Not required

### 2. Weather API (WeatherAPI.com or OpenWeatherMap)
- **Purpose**: Real-time weather data
- **Documentation**: [weatherapi.com](https://www.weatherapi.com/docs/)
- **Free Tier**: ✅ Available
- **Authentication**: ✅ API Key required
- **Sign up**: [Get Free API Key](https://www.weatherapi.com/signup.aspx)

### 3. Map Integration (Optional)
- **Purpose**: Interactive maps
- **Options**: 
  - Google Maps API
  - Leaflet.js with OpenStreetMap
  - Mapbox

---

## 📸 Screenshots

<div align="center">

### Hero Section
![Hero Section](https://via.placeholder.com/800x400/667eea/ffffff?text=Hero+Section)

### Country Explorer
![Country Explorer](https://via.placeholder.com/800x400/764ba2/ffffff?text=Country+Explorer)

### Weather Dashboard
![Weather Dashboard](https://via.placeholder.com/800x400/4b6cb7/ffffff?text=Weather+Dashboard)

### Dark Mode
![Dark Mode](https://via.placeholder.com/800x400/2c3e50/ffffff?text=Dark+Mode)

</div>

---

## 📁 Project Structure

```
wether-app/
│
├── index.html              # Landing page
├── home.html              # Main application page
├── README.MD              # Project documentation
│
├── css/
│   └── styles.css         # Main stylesheet
│
├── js/
│   └── app.js             # Application logic
│
└── assets/                # Images and icons (if any)
    ├── images/
    └── icons/
```

---

## 🎨 Color Scheme

The project uses dynamic weather-based color schemes:

| Weather | Colors |
|---------|--------|
| ☀️ Sunny | `#667eea` → `#764ba2` |
| ☁️ Cloudy | `#bdc3c7` → `#2c3e50` |
| 🌧️ Rainy | `#4b6cb7` → `#182848` |
| ❄️ Snowy | `#e6dada` → `#274046` |
| ⛈️ Thunder | `#2c3e50` → `#000000` |
| 🌫️ Foggy | `#757f9a` → `#d7dde8` |

---

## 🤝 Contributing

Contributions are what make the open-source community amazing! Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### 💡 Ideas for Contribution

- [ ] Add 7-day weather forecast
- [ ] Implement geolocation for automatic weather detection
- [ ] Add more weather animations
- [ ] Create country comparison feature
- [ ] Add historical weather data
- [ ] Implement unit tests
- [ ] Add accessibility improvements
- [ ] Create mobile app version

---

## 📝 License

Distributed under the MIT License. See `LICENSE` file for more information.

---

## 👨‍💻 Author

### WasuVa Creation

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourusername)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/yourhandle)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://yourwebsite.com)

</div>

---

## 🙏 Acknowledgments

- [REST Countries API](https://restcountries.com) for country data
- [WeatherAPI.com](https://www.weatherapi.com) for weather information
- [Google Fonts](https://fonts.google.com) for Inter font family
- [SweetAlert2](https://sweetalert2.github.io) for beautiful alerts
- All open-source contributors

---

## 📊 Project Stats

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/yourusername/country-weather-explorer?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/country-weather-explorer?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/yourusername/country-weather-explorer?style=social)

</div>

---

<div align="center">

### ⭐ Star this repository if you found it helpful!

**Made with ❤️ by WasuVa Creation**

© 2025 Country & Weather Explorer. All Rights Reserved.

</div>
