# 🌦 Real-Time Weather Report Analytics – Power BI + Weather API

## 📌 Project Overview
An interactive **real-time weather dashboard** built in **Power BI** using **live Weather API data**.  
The project demonstrates **end-to-end integration** — from connecting to a free API and cleaning JSON data, to modeling and visualizing it in a professional, dynamic dashboard.  

This dashboard allows users to **monitor live weather conditions**, **forecast trends**, and **air quality levels** for multiple cities, offering a complete real-time weather monitoring solution.  

---

## ✨ Features
- 🌐 **Live API Integration** – Connects directly to a weather API for live JSON data.  
- 🏙 **Multi-City Support** – View reports for different locations.  
- 📅 **7-Day Forecast** – Displays Monday → Sunday weekly forecast.  
- 📈 **Dynamic Charts** – Temperature trends, rain probability, and AQI indicators.  
- 🎯 **Conditional Formatting** – Color-coded KPIs for quick status checks.  
- 🔍 **Interactive Filtering** – Slicers for city selection and forecast analysis.  
- ☀ **Additional Context** – Sunrise & sunset times, humidity, and wind speed.  

---

## 🛠 Tech Stack
- **Power BI Desktop** – Data modeling & dashboard creation.  
- **Weather API** – Live weather data in JSON format.  
- **JSON** – API response structure.  
- **DAX** – Measures & calculated columns for KPIs.  
- **Power Query** – Data cleaning, transformation & modeling.  

---

## 🔄 Data Workflow
1. **API Registration** → Sign up for a free weather API & get an API key.  
2. **Data Retrieval** → Fetch live JSON data for selected cities via API URLs.  
3. **Data Cleaning** → Use Power Query to transform, split tables, and remove duplicates.  
4. **Data Modeling** → Create relationships between tables (current weather, forecast, air quality).  
5. **Visualization** → Build cards, charts, gauges, and slicers in Power BI.  
6. **Interactivity** → Enable clickable forecast points & drill-through reports.  
7. **Refresh** → Manual refresh in Desktop (can be automated in Power BI Service).  

---

## 📊 Dashboard Details
**KPIs & Cards:**
- Current temperature  
- Chance of rain (%)  
- Air Quality Index (PM10)  
- Sunrise / Sunset times  
- Humidity & wind speed  

**Visuals:**
- 📈 **Temperature Trend Line** – Forecast highs/lows over 7 days.  
- 🌧 **Rain Probability Bar Chart** – Chance of rain (%) by day.  
- 🌫 **AQI Gauge** – Color-coded air quality status.  
- 📅 **Weekly Forecast Tiles** – Day-by-day weather summary.  

---

## 💡 Key Insights (From Current Dashboard Data)
- **🌤 Current Conditions** – Ajmer is partly cloudy with a temperature of **29.9°C** and **58% humidity**.  
- **💨 Wind & Pressure** – Winds are strong at **25.6 km/h**, with pressure at **29.69 inHg**.  
- **🌧 Rain Probability** – Highest rain chance mid-week: **Wednesday (86%)** and **Saturday (85%)**; otherwise mostly dry.  
- **🌡 Forecast Trend** – Temperatures peak at **29.3°C** on Friday, then drop sharply to **25.9°C** by Sunday.  
- **🌫 Air Quality** – AQI (PM10) is **36.63 – Good**, safe for all groups; however, **CO levels (257.15)** are elevated and worth monitoring.  
- **☀ Daylight** – Sunrise at **05:59 AM**, sunset at **07:12 PM**, providing ~13 hours of daylight.  
- **🕶 UV Index** – High at **10.70**, suggesting sun protection measures during peak hours.  

---

## 📁 Repository Structure
| File Name | Description |
|-----------|-------------|
| `Weather Report Data Analytics.pbix` | Power BI dashboard file |
| `Weather Report Data Analytics.png` | Dashboard preview image |
| `README.md` | Project documentation (this file) |

---

## 🚀 How to Use
1. **Get a Weather API Key** – Sign up at your chosen weather API provider.  
2. **Edit API URL in Power BI** – Replace with your API key & desired city codes.  
3. **Load Data** – Use *Get Data → Web* in Power BI Desktop.  
4. **Clean & Model Data** – Create separate tables for current, forecast, and AQI.  
5. **Apply DAX Calculations** – Build measures for KPIs & formatting rules.  
6. **Design Dashboard** – Add visuals, slicers, and conditional formatting.  
7. **Refresh Data** – Click **Refresh** in Power BI Desktop.

---

## 🔮 Future Enhancements
- ⚡ Automatic refresh every 30 min via Power BI Service.  
- 📅 Dynamic forecast starting from **current day** instead of fixed Monday–Sunday.  
- 📱 Mobile-optimized layout for better viewing on phones/tablets.  
- 🌍 More city coverage & multi-language support.  

---

## 📬 Connect With Me
**Name:** Satyam Kumar  
**Email:** [satyamkv123@gmail.com](mailto:satyamkv123@gmail.com)  
**LinkedIn:** [linkedin.com/in/satyam-kumar-5a229222b](http://www.linkedin.com/in/satyam-kumar-5a229222b)  

---
