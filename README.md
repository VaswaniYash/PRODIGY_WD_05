# PRODIGY_WD_05
☁️ Weather Web App built with Java, JSP, and Servlets, using OpenWeather API for real-time weather updates.


# 🌦️ Weather Web App

A dynamic and user-friendly **Weather Web Application** that displays real-time weather information using the **OpenWeather API**. This project integrates **Java, JSP, Servlets** with a clean **HTML/CSS/JS** frontend.

## 📌 Features

- 🌐 Get real-time weather for any city
- ☀️ Displays temperature in Celsius
- 💧 Shows humidity and wind speed
- 🕒 Displays current local date and time
- 🔍 Search bar for entering city name
- 🎨 Responsive and intuitive UI

## 🧑‍💻 Tech Stack Used

| Frontend  | Backend       | API              |
|-----------|----------------|------------------|
| HTML      | Java           | OpenWeather API  |
| CSS       | JSP            |                  |
| JavaScript| Servlets       |                  |

## 🛠️ How It Works

1. User enters the city name in the input field.
2. A request is sent to the backend (Servlet).
3. Servlet connects with the OpenWeather API using HTTP request.
4. Weather data (temperature, humidity, wind speed, etc.) is fetched.
5. Servlet sends this data to the JSP page.
6. JSP renders the data and displays it on the UI.

## 📸 Screenshots

![Weather UI](screenshots/screenshot1.png)
![Weather Welcome Page](screenshots/screenshot2.png)

## 🚀 Getting Started

### Prerequisites

- JDK 8 or above
- Apache Tomcat Server
- IDE (Eclipse/IntelliJ)
- Internet Connection (for API)

### Setup Instructions

1. Clone this repository:
   bash
   git clone:-https://github.com/VaswaniYash/PRODIGY_WD_05/tree/main

  2.	Import into your IDE as a Dynamic Web Project.
	3.	Place the project in your webapps folder if using Tomcat.
	4.	Replace the placeholder API key in the servlet with your OpenWeather API key:String apiKey = "YOUR_API_KEY";
  5.	Run the project on server.

5.	Run the project on server.

🔐 API Used
	•	OpenWeatherMap API
	•	Endpoint: https://api.openweathermap.org/data/2.5/weather
	•	Documentation: https://openweathermap.org/current

🙌 Acknowledgements
	•	Thanks to OpenWeather for providing the free API.
	•	UI inspiration from various weather dashboards.
    
