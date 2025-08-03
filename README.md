# 🔌 EV Vehicle Charging Demand Prediction
This repository contains the end-to-end machine learning project developed as part of my **internship at ShellGreen x AICET x EDUNET FOUNDATION**.
The objective is to forecast electric vehicle (EV) adoption trends across counties in Washington State using historical registration data. The predictions aim to support EV infrastructure planning — especially for anticipating charging station demand.

---

## 🎯 Project Objectives

- Analyze EV growth patterns using real-world vehicle registration data
- Clean and preprocess the dataset for modeling
- Engineer lag-based time-series features for forecasting
- Train a machine learning model (Random Forest Regressor)
- Forecast EV adoption for the next 36 months
- Build a Streamlit-based interactive web app for visualization
- Enable county-level EV adoption comparisons and growth insights

---

## 🧰 Tools & Technologies Used

- **Language**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels  
- **Model**: RandomForestRegressor  
- **App Framework**: Streamlit  
- **IDE**: Goggle collab + VS Code  
- **Version Control**: Git + GitHub  

---

## 📁 Project Structure


---

## 📁 Project Structure

EV_Vehicle_Charge_Demand/
├── EV_Vehicle_Charging_Demand_Prediction.ipynb # Jupyter Notebook
├── app.py # Streamlit App
├── forecasting_ev_model.pkl # Trained model
├── preprocessed_ev_data.csv # Cleaned dataset
├── ev-car-factory.jpg # UI image

---

## 📈 How It Works

- Data grouped by county and model year
- Features like `lag1`, `rolling mean`, `percent change`, `growth slope` created
- Random Forest model trained on historical EV totals
- Forecast horizon: 36 months into the future
- Streamlit app allows selecting counties and viewing EV adoption projections

---
<img width="647" height="848" alt="image" src="https://github.com/user-attachments/assets/c72746e0-851b-4d04-abc6-5902ae8da063" />
