# Weather App  

A simple weather application that displays current weather conditions for any city worldwide, along with live date and time.  

![Weather App Screenshot](images/demo-example) *(Replace with actual screenshot after uploading)*  

---  

## Features  
- Real-time weather data (temperature, humidity, wind speed, conditions)  
- Live updating date and time  
- Responsive design (mobile & desktop friendly)  
- Error handling for invalid city names  
- Weather icons matching current conditions  

## Technologies Used  
- **HTML5, CSS3, JavaScript (ES6)**  
- **OpenWeatherMap API** (for weather data)  

---  

## API Key Setup & Security  

### How to Get an API Key  
1. Go to [OpenWeatherMap](https://openweathermap.org/)  
2. Sign up for a **free account**  
3. Navigate to the **API Keys** section in your dashboard  
4. Generate a new key (it may take a few minutes to activate)  

### Important Security Note  
🔒 **Never expose your API key in client-side code in production!**  
- In this demo, the API key is hardcoded in `index.js` **for testing only**.  
- For security, in a real-world app:  
  - Use **environment variables** (e.g., `.env` file + backend proxy)  
  - Or deploy with **server-side API calls** (Node.js, Firebase, etc.)  

### How to Use the Key in This Project  
1. Open `index.js`  
2. Replace `'your_real_api_key'` with your actual OpenWeatherMap API key:  
   ```js
   const apiKey = 'paste_your_key_here'; // 🔑 Replace this!
   ```
3. **Do NOT commit this key to GitHub!** (Use `.gitignore` for security)  

---  

## Setup & Usage  

### Local Setup  
1. Clone the repo:  
   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
   ```  
2. Add your API key as instructed above  
3. Open `index.html` in a browser  

### How to Use  
- Type a city name (e.g., "London")  
- Press **Enter** or click the search button  
- View live weather data!  

---  

## Project Structure  
```
weather-app/  
├── index.html          # Main HTML file  
├── style.css           # Styling  
├── index.js            # Weather logic + API calls  
├── images/             # Weather icons  
│   ├── clouds.png  
│   ├── clear.png  
│   └── ...  
└── README.md           # This guide  
```  

---  

## Future Improvements  
- [ ] 5-day forecast  
- [ ] Geolocation (auto-detect user’s weather)  
- [ ] Celsius/Fahrenheit toggle  
- [ ] Animated weather icons  

---  

## License  
MIT License. **Use responsibly — keep your API key secure!**  

---  

**⚠️ Reminder:** Always hide API keys in production. This demo is for learning purposes only.  
