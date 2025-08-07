## ✈️ Airline Forecasting and Optimization Model – Datathon Winner 🏆

This project was developed during a datathon in collaboration with **VivaAerobus**, where we tackled real-world aviation challenges. Competing against nearly **100 teams**, our team secured **1st place** by building a robust predictive and optimization system for airline operations.

We worked with **millions of flight and sales records** to forecast passenger volume and onboard product demand, then optimized cargo logistics across routes and aircrafts.

---

### 🎯 Challenge Overview

The goal was to:
- Predict the **number of passengers** per flight (based on historical bookings).
- Estimate the **demand for onboard products** (like Coca-Cola, sandwiches, etc.).
- Build an **inventory optimization model** to plan when and where to restock, maximizing efficiency.

---

### 🧠 Techniques Used

- **Data Preprocessing**: Cleaning millions of records, handling missing and outlier data.
- **Machine Learning Models**:
  - Gradient Boosting (LightGBM) for passenger prediction.
  - XGBoost for onboard product sales forecasting.
- **Optimization Model**:
  - Developed a custom simulation-based model to plan **restocking operations** across airports.
  - Considered constraints like **shelf life**, **inventory levels**, and **loading points**.
  
---

### 📊 Dataset

- +2 million records covering flight schedules, aircraft types, bookings, and in-flight sales.
- Included temporal, geographic, and categorical variables.
- Data grouped by **flight number, date, and aircraft** for accurate modeling.

---

### 📈 Outcome

- Passenger and item demand models with **high accuracy**.
- Optimization model that **reduced restocking events** while maintaining availability.
- Demonstrated a scalable, data-driven approach to inventory and demand planning in aviation.

---

### 🧪 Notebooks

- [`PassengerForecasting.ipynb`](PassengerForecasting.ipynb) – Passenger prediction per flight.
- [`PassengerForecastingBookings.ipynb`](PassengerForecastingBookings.ipynb) – Passenger forecast from booking trends.
- [`ItemDemandPrediction.ipynb`](ItemDemandPrediction.ipynb) – Forecasting in-flight product demand.
- [`ModeloOptimizacion_EN.ipynb`](ModeloOptimizacion_EN.ipynb) – Inventory optimization model.

---

### 👥 Team

- José Ignacio Polanco García  
*(Lead ML Engineer – Demand Modeling & Optimization)*

---

### 🏁 Datathon

Organized by: **[Confidential Airline Partner: VivaAerobus]**  
Participation: **~100 teams**  
Award: **🥇 1st Place**
