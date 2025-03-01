## 🌤️ Climatix – Weather Forecasting App  

**Climatix** is a **Flutter & Dart**-based iOS app that provides **7-day weather forecasts** for any location globally. 🌎☀️🌧️ The app fetches real-time weather data using the **OpenWeather API** and presents it with an intuitive and interactive UI.  

---

## 🚀 Key Features  

✅ **7-day weather forecast** for any city  
✅ **Real-time temperature, humidity, and wind speed**  
✅ **Beautiful and interactive UI** optimized for iOS  
✅ **Search feature** to find weather details of any city  
✅ **Smooth performance** and optimized API calls  

---

## 🛠 Technologies Used  

💙 **Flutter & Dart** – For cross-platform app development  
🌍 **OpenWeather API** – For live weather data  
📡 **HTTP package** – To fetch weather details via API  
⚡ **Provider** – For state management  

---

## 📦 Installation & Setup  

1. **Clone the repository:**  
   ```sh
   git clone https://github.com/prangowda/Climatix.git
   cd Climatix
   ```  
2. **Install dependencies:**  
   ```sh
   flutter pub get
   ```  
3. **Get your OpenWeather API Key:**  
   - Sign up at [OpenWeather](https://openweathermap.org/)  
   - Generate an API key  
   - Add the key in your Flutter project inside `lib/utils/api_keys.dart`:  
     ```dart
     class ApiKeys {
         static const String weatherApiKey = "YOUR_OPENWEATHER_API_KEY";
     }
     ```  
4. **Run the app on iOS:**  
   ```sh
   flutter run
   ```  

---

## 📖 How It Works  

1. Open the **Climatix** app.  
2. Enter a **city name** to get its weather details.  
3. The app fetches **temperature, humidity, wind speed, and a 7-day forecast**.  
4. The UI displays real-time weather updates in an interactive format.

---
## Demo Video 

https://github.com/user-attachments/assets/5afcff9a-99a9-4638-983f-b05c07febfe3



