# 📦 iot-data-viz-atienza

## 🧠 Overview  
This project focuses on cleaning, transforming, and visualizing IoT sensor data. The dataset includes raw readings like temperature, humidity, and energy from different devices, recorded in mixed formats (e.g., `22.5°C`, `18.3 kWh`, `45%`). The goal is to prepare the data for accurate trend analysis by handling missing values, standardizing units, and resampling over time.

---

## 🛠 Features  
- ✅ Load and inspect raw IoT data  
- ✅ Clean column names and handle missing values  
- ✅ Extract numeric values from strings with units  
- ✅ Convert timestamps and set datetime index  
- ✅ Pivot sensor types into separate columns  
- ✅ Resample data hourly for trend analysis  
- ✅ Detect duplicates and outliers  
- ✅ Visualize time-series trends per sensor

---

## 📂 Files  
- `iot_data_transformation.ipynb` — Main notebook  
- `raw_iot_data.csv` — Raw IoT sensor data  
- `cleaned_hourly_iot_data.csv` — Output: cleaned and resampled data

---

## 👩‍💻 Author  
**Trisha Mei Atienza**  
