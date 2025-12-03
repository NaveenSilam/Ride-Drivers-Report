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

