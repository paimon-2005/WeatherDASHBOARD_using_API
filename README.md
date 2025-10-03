# 🌤️ Weather App
This project is a Weather App built using HTML, CSS, and JavaScript. It provides real-time weather updates for any city, including temperature, humidity, wind speed, and a 5-day forecast. The app features a clean and modern UI with interactive elements, such as a search bar and dynamic weather icons. The goal of this project was to practice front-end development skills while creating a functional, real-world inspired application.

## here the preview link - 

## 📝 Important Note on Forecast Dates and Timezones
This weather application relies on the OpenWeatherMap forecast API, which mandates that all data be provided in Coordinated Universal Time (UTC). Our code uses this data stream to show a daily forecast summarized at the 12:00:00 UTC time slot.

Because India Standard Time (IST) is UTC+5:30, the 12:00:00 UTC time slot corresponds to 5:30 PM IST on the same calendar day.

If the user opens the app before 5:30 PM IST, the 12:00:00 UTC forecast for the current day (Oct 04) has not passed yet, so it is correctly shown in the first column. The subsequent columns (Oct 05, Oct 06) show the 12:00:00 UTC forecast for the next two days.

This design ensures the forecast is always showing the next three daily summaries available from the API, starting from the closest 12:00:00 UTC point, which provides a consistent and accurate view across all timezones.
