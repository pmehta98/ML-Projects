# 🏡 Airbnb Booking Demand Prediction

## 📌 Project Overview
Understanding **Airbnb booking demand** is essential for **hosts, property managers, and pricing strategists** to optimize occupancy rates and maximize revenue. This project focuses on **predicting the number of days a listing will be booked in the next 30 days** using **machine learning techniques** applied to real Airbnb data from Los Angeles.

By analyzing **listing attributes, host characteristics, availability trends, and seasonality factors**, this model provides **valuable insights to improve pricing strategies, manage inventory, and forecast future demand**.

---

## 📊 Dataset
The dataset consists of **real Airbnb listings from Los Angeles**, providing key details about **listing characteristics, host reliability, geographical location, and historical booking patterns**.

### **🔑 Key Features Used**
- **Listing Attributes:** Price, number of bedrooms, bathrooms, accommodates, property type, etc.
- **Host Information:** Superhost status, number of reviews, response time, etc.
- **Geographical Data:** Neighborhood, latitude, longitude.
- **Availability Trends:** `availability_30` and historical booking patterns.
- **Seasonality Factors:** Day of the week, holidays, and event-based demand fluctuations.

---

## 🛠️ Methodology

### **1️⃣ Data Preprocessing & Feature Engineering**
- **Handled missing values** through imputation strategies.
- **Created new features** such as:
  - `price_per_person` for affordability insights.
  - `booking_ratio` to capture availability trends.
  - **One-hot encoding** for categorical variables.
  - **Time-based features** to model seasonality and demand shifts.

### **2️⃣ Model Selection & Training**
- **Evaluated multiple machine learning models**:
  - Linear Regression  
  - Decision Trees  
  - Random Forest  
  - XGBoost  
  - LightGBM  
- **Used cross-validation** to optimize hyperparameters and reduce overfitting.
- **Final model selection** was driven by predictive performance and feature interpretability.

### **3️⃣ Feature Importance Analysis**
- Applied **SHAP values** and **permutation importance** to identify the most significant predictors.
- **Key drivers of demand** included:
  - **Price Sensitivity** – Listings with optimal pricing showed higher bookings.
  - **Location Factors** – Proximity to hotspots influenced demand.
  - **Host Credibility** – Superhost status and response rate impacted trust and bookings.
  - **Historical Trends** – Prior availability patterns strongly correlated with future bookings.

---

## 📈 Results & Insights
- The model demonstrated **strong predictive performance**, accurately capturing booking trends.
- Feature importance analysis highlighted **pricing, location, and availability trends** as key drivers of demand.
- The approach provides **data-driven insights** to help hosts optimize listing performance.

---
