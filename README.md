# Sunny 🌞

A modern weather application that provides real-time weather information for any city worldwide. Built with React.js and powered by the OpenWeatherMap API.

## 🚀 Features

✅ Search for any city's current weather  
✅ Displays:
- City name
- Weather condition (e.g., Clear, Clouds, Rain)
- Temperature in °C  
✅ Clean, minimalistic design  
✅ Fully responsive  

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (Latest LTS version recommended)
- npm (comes with Node.js)
- OpenWeatherMap API key (free tier available)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
cd sunny
```

2. Install dependencies:
```bash
npm install
```

3. Set up OpenWeatherMap API:
- Sign up at [OpenWeatherMap](https://openweathermap.org/api)
- Generate your free API key
- In `src/components/Weather.js`, replace:
```javascript
const API_KEY = "YOUR_API_KEY";
```

4. Start the development server:
```bash
npm start
```

The application will be available at [http://localhost:3000](http://localhost:3000).

## ⚙️ Tech Stack

- **Frontend:** React.js  
- **API:** OpenWeatherMap API  
- **Styling:** CSS  

## 🏗️ Available Scripts

In the project directory, you can run:

### `npm start`
Runs the app in development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm run build`
Builds the app for production to the `build` folder.\
The build is optimized for the best performance.

## 📦 Project Structure

```
sunny/
├── public/          # Static files
├── src/            # Source files
│   ├── components/ # React components
│       └── Weather.js
├── node_modules/   # Dependencies
└── package.json    # Project configuration
```

## 👥 Authors

- BinuriManodya - Initial work

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.