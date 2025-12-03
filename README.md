# Ride-Drivers-Report

## 📊 Project Overview
This project presents an **interactive Power BI dashboard** based on RideIT Drivers data sourced from Kaggle.  
The dashboard provides insights into:
- Majority of revenue is driven by a few high-performing drivers  
- Cancellations are concentrated within a small driver group  
- High gold-level score correlates with more earnings  
- Certain cities show higher ride demand  
- Active drivers generate 85–90% of all bookings

## 📜 Dataset Source
The dataset used in this project was taken from Kaggle: 
- <a href="https://github.com/NaveenSilam/Ride-Drivers-Report/blob/main/rideit_drivers.csv">Dataset</a>

## 🧰 Tools & Technologies
- **Microsoft Excel** – Data cleaning and preprocessing  
- **Power BI** – Data visualization and dashboard creation
- **DAX**  
- **Kaggle Dataset** – Source of raw Olympic data

- Dashboard Interaction <a href="https://github.com/NaveenSilam/Ride-Drivers-Report/blob/main/Ride_Driver_Dashboard_preview.png">View Dashboard</a>

## ⚙️ Data Preparation
- Imported the raw datasets (rideit_drivers.csv and rideit_drivers_activity.csv) into Power BI
- Cleaned missing values and removed duplicates using Power Query
- Standardized data types (dates, numbers, text) for consistent analysis
- Corrected formatting issues such as inconsistent city names and trimmed extra spaces
- Created calculated columns such as Cancellation Rate, Earnings per Hour, and Gold Flag
- Merged both tables using driver_id to create a one-to-many relationship
- Added a Date Table for time-based analysis
- Validated data quality by checking totals, row counts, and relationship accuracy
- Loaded the cleaned dataset into Power BI for modelling and dashboard development

## Dashboard 
<img width="559" height="313" alt="Ride_Driver_Dashboard_preview" src="https://github.com/user-attachments/assets/577f5331-a13f-4775-9579-5de24934af4a" />

## 📊 Published Dashboard
Dashboard Interaction <a href="https://app.powerbi.com/groups/me/reports/f0a71ebd-40db-4a4c-9955-6d0baa45851c/88316fa7b9755790e85c?experience=power-bi">🌐 View the Dashboard Online</a>

## 📈 Key Insights
- The platform shows a steady increase in active drivers from 2011 to 2020, with peak growth during 2018–2019.
- Passenger cancellation rate (10.56%) is higher than the driver cancellation rate (8%), highlighting rider-side issues.
--Average driver rating is 4.89, with most ratings between 4.7–5.0, reflecting high service quality.
- Taxi service dominates the driver base with 31,120 drivers, compared to 5,450 PHV drivers.
- Friday and Saturday have the highest bookings, while Monday shows the lowest demand.
- Spain contributes 69.62% of drivers, making it the platform’s strongest market, followed by Germany (30.38%).
- 71.06% of drivers join organically, showing strong brand reach and low marketing dependency.
- A strong positive correlation between bookings and rides indicates efficient matching and high operational effectiveness.

## 🏁 Final Conclusion
The platform is growing well, drivers provide good service, and most bookings turn into completed rides. Taxi drivers and Spain make up most of the activity. The only main issue is that passengers cancel more often, which can be improved. Overall, the system works smoothly and is performing strongly.
