# 🌤️ Lahore Weather Analyzer (Python)

## 📌 Project Overview
This is a Python script that connects to the **Open-Meteo API** to fetch historical weather data for Lahore, Pakistan. It retrieves the past 30 days of data and analyzes it to find key weather records, including the hottest day, coldest night, rainiest day, and any days with high wind speeds.

## ⚙️ How It Works
1. **API Request:** The script sends a GET request to the Open-Meteo API using specific coordinates for Lahore (Latitude: 31.55, Longitude: 74.35).
2. **Data Parsing:** It extracts daily weather variables: Maximum Temperature, Minimum Temperature, Precipitation Sum, and Maximum Wind Speed.
3. **Data Analysis:** It loops through the 30 days of data to track:
   * The highest maximum temperature (Hottest Day)
   * The lowest minimum temperature (Coldest Night)
   * The highest precipitation amount (Rainiest Day)
   * Days where wind speed exceeded 30 km/h (Windy Days)
4. **Output:** It prints a daily weather log to the console, followed by a final weather summary.

 **Key Insights Generated**
* Identifies extreme temperature days.

* Flags heavy rain events.

* Alerts for high wind days (useful for aviation, agriculture, or event planning).

**🚀 Future Improvements**
* Add a feature to export the data to a CSV file.

* Create a simple bar chart using matplotlib to visualize the temperature trends.

* Allow the user to input their own city coordinates via the command line.
