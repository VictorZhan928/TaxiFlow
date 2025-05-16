# TaxiFlow NYC 🚖  
**Data-Driven Insights for Better Rides in NYC**

## 📘 Overview  
TaxiFlow is a comprehensive analytics dashboard designed to forecast NYC taxi demand and trip durations using real-world data. By integrating weather, event, and trip records, this project provides insights for fleet managers, drivers, transit planners, and rideshare companies to optimize vehicle deployment and improve service.

---

## 🎯 Objectives  
- Predict taxi demand fluctuations and trip durations.
- Quantify impacts of weather conditions and special events.
- Build a scalable data pipeline and intuitive dashboard for stakeholders.

---

## 📂 Data Sources  
- **NYC Taxi Trip Data (3.5 GB)** – Pickup/dropoff times, fares, tips, passenger counts.  
- **NYC Permitted Events (931 MB)** – Records of concerts, parades, sports events.  
- **NOAA Weather (347 KB)** – Hourly weather conditions for 2023.  
- **NYC Taxi Zone Data (8 KB)** – Borough and neighborhood mappings.

---

## 🧼 Data Cleaning Summary  
- Removed duplicates and invalid rows (e.g., negative fares, passenger counts > 6).
- Standardized event categories using keyword matching.
- Engineered `weather_type` (Sunny, Cloudy, Rainy) for readability.
- Linked location IDs to zones and aligned weather/events to trip timestamps.

---

## 🧰 Tech Stack  
- **Python** – Data scraping, cleaning, and batch processing  
- **PostgreSQL** – Central database for trip, zone, weather, and event tables  
- **Streamlit** – Dashboard UI  
- **Spark (planned)** – Scalable ETL for big data ingestion  
- **AWS RDS + S3** – Cloud hosting and storage

---

## 👥 Target Users  
- Taxi Fleet Managers  
- Individual Taxi Drivers  
- Rideshare Companies (Uber, Lyft)  
- City Transit Planners  
- Event Coordinators

---

## 📈 Value Proposition  
- Real-time, location-based insights into city-wide demand  
- Event and weather-aware modeling  
- Visual dashboards tailored to business and city needs

---

## 🚀 Future Plans  
- Automate ETL pipeline with Airflow  
- Enhance ML models for temporal/spatial accuracy  
- Scale Streamlit dashboard for mobile and real-time use

---

## 👤 Contributors  
- Victor Zhan  
- Aimee Bisma  
- Ayu Vidiantiwi  
- Celine Widjaja  
- Ryan Susilo  
