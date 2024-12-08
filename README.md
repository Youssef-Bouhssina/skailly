# Skailly Weather Dashboard 🌦️

## Overview

Skailly is a responsive and interactive weather dashboard built as a capstone project for front-end software development. The application provides real-time weather information and forecasts for locations worldwide, demonstrating modern web development techniques and API integration.

## Project Goals

The primary objectives of this project were to:
- Create a robust, user-friendly weather dashboard
- Enhance skills in React and modern front-end technologies
- Practice responsive design and state management
- Gain hands-on experience with API integration

## Technologies Used

- **React**: For building a component-based, dynamic user interface
- **Tailwind CSS**: For rapid, utility-first styling and responsive design
- **OpenWeatherMap API**: For retrieving current weather and forecast data
- **Vite**: For project initialization and development environment
- **Git & GitHub**: For version control and project management

## Features

- 🌍 Global weather data for cities worldwide
- 🌡️ Current weather conditions display
- 📅 5-day/3-hour weather forecast
- 🔍 City search functionality
- 📱 Fully responsive design
- 🌈 Weather condition icons
- 📍 Geolocation support (optional feature)

## Key Learning Outcomes

Throughout this project, I focused on improving:
- React component development
- State management with `useState` and `useEffect`
- Tailwind CSS styling techniques
- API interaction and error handling
- Responsive web design principles

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or yarn package manager

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/Youssef-Bouhssina/skailly.git
   ```

2. Install dependencies
   ```bash
   cd skailly
   npm install
   ```

3. Create a `.env` file and add your OpenWeatherMap API key
   ```
   REACT_APP_WEATHER_API_KEY=your_api_key_here
   ```

4. Start the development server
   ```bash
   npm run dev
   ```

## Project Structure

```
skailly/
│
├── src/
│   ├── components/
│   │   ├── App.css
│   │   ├── App.jsx
│   │   ├── index.css
│   │   └── main.jsx
│   ├── assets/
│   │   └── images and other static assets
│   ├── styles/
│   │   └── Tailwind CSS configuration and custom styles
│   └── utils/
│       └── API calls and helper functions
│
├── public/
│   └── index.html
│
├── .gitignore
├── ChangeLogs.md
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── postcss.config.js
├── README.md
├── tailwind.config.js
└── vite.config.js
```

## API Reference

This project uses the OpenWeatherMap API with the following key endpoints:
- Current Weather Data
- 5-day/3-hour Forecast
- Supports metric, imperial, and standard units

## Deployment

Deployed on Netlify/Vercel/GitHub Pages (choose one)

## Future Enhancements

- [ ] City name autocomplete
- [ ] Advanced error handling
- [ ] User preference storage
- [ ] Additional weather visualizations

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Youssef-Bouhssina/skailly/issues).

## License

[Specify your license here, e.g., MIT]

## Contact

Youssef Bouhssina - [Your Email or LinkedIn]

---

**Happy Weather Tracking! 🌞🌧️**