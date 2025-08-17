# NYC Taxi Trip Duration Prediction 🚕

## 📌 Overview
This project predicts **NYC taxi trip durations** using machine learning regression models.  
We leverage trip details such as pickup/dropoff times, passenger count, and GPS coordinates to estimate the travel time.

---

## 📊 Dataset
- **Source**: NYC Taxi dataset  
- **Features**:
  - Pickup & dropoff datetime
  - Passenger count
  - Pickup/dropoff latitude & longitude
  - Vendor ID, store-and-forward flag
- **Target**: `trip_duration` (in seconds)

---

## ⚙️ Models Used
- Linear Regression
- Ridge Regression
- Random Forest Regressor

---

## 🏆 Results
- Best model: **Random Forest Regressor**
- Metrics:
  - **R² Score**: ~0.72
  - **RMSE**: ~380 seconds  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/nyc-trip-duration.git
   cd nyc-trip-duration

### Install dependencies:
    pip install -r requirements.txt

###Run the notebook:
   jupyter notebook nyc_trip_duration.ipynb
