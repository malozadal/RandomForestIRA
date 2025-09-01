# 📊 Early Detection of Respiratory Diseases with Random Forest  

This project implements a **Random Forest Regressor** for the **early detection of acute respiratory diseases (ARI)** in Peru.  
The model predicts the **weekly incidence rate by region**, using climate and historical case data, while excluding the pandemic years (2020–2021).  

---

## ⚙️ Data used  
- **Time coverage:** 2017–2025 (updated weekly).  
- **Geographic coverage:** 26 regions of Peru (including Callao and Lima Metropolitana).  
- **Variables:**
  - 🌡️ Climate: `tmean`, `tmax`, `tmin`, `humr`, `ptot`.  
  - 🧑‍⚕️ ARI cases: `Casos`.  
  - 👥 Population by region (`population`).  
  - 📊 Derived variables: incidence per 100k inhabitants, predicted rates, alert levels.  

---

## 🧠 Model  
- Algorithm: **RandomForestRegressor** (Scikit-learn).  
