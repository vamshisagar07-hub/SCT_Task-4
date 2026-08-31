# Task 04 - Traffic Accident Analysis & Risk Factor Visualization

## 📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) on traffic incident dataset to identify spatial, environmental, and temporal risk factors. The primary objective is to evaluate how road surface conditions, weather patterns, time of day, and geographic hotspots contribute to traffic collisions.

This task was completed as part of the **Data Analytics Internship at SkillCraft Technology**.

---

## 🔑 Key Features & Analyses
* **Spatial Hotspot Analysis:** Identifies regions and states with the highest accident volumes.
* **Behavioral & Contributing Factors:** Evaluates direct drivers behind crashes, such as speeding and drunk driving.
* **Environmental Impact Analysis:** Measures how weather conditions (rain, fog) and road surface states (wet, potholes) influence collision frequency.
* **Risk Matrix Heatmap:** Cross-analyzes weather and road conditions to identify high-risk compounding hazards.
* **Temporal Trend Mapping:** Tracks accident distributions across different time slots (morning peak, evening rush, late night).

---

## 🛠️ Technologies & Libraries Used
* **Language:** Python
* **Environment:** Google Colab / Jupyter Notebook
* **Data Processing:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib

---

## 📊 Key Insights & Findings
1. **Geographic Risk:** States with dense transit networks (such as Tamil Nadu, Maharashtra, and Uttar Pradesh) show the highest concentration of recorded incidents.
2. **Leading Risk Factor:** Speeding remains the primary human cause of collisions, followed by impaired driving and reduced visibility.
3. **Compounding Hazards:** While many accidents occur in clear conditions due to high traffic volume, rainy and foggy weather combined with wet or damaged road surfaces significantly escalate collision severity.
4. **Peak Time Window:** Incident density reaches its highest point during **Evening Peak Hours (5:00 PM – 8:00 PM)** due to heavy commuter traffic, driver fatigue, and shifting daylight conditions.

---

## 💡 Recommendations
* **Dynamic Speed Governance:** Deploy automated LED speed advisories that adjust limits during adverse weather (rain or heavy fog).
* **Targeted Maintenance:** Prioritize road resurfacing, pothole repair, and drainage clearing on identified high-risk state corridors.
* **Strategic Enforcement:** Increase traffic patrol density and speed enforcement during high-risk evening peak hours.

---

## 📁 Repository Structure
```text
├── SCT Task-4.ipynb                          # Main Google Colab / Jupyter Notebook
├── README.md                                 # Project Documentation
├── SCT Task-4 outputs                        # output files
└── assets/                                   # Visualizations and Output Charts

### 📓 Project Notebook
You can view the full code execution and visualizations directly in the repository:
👉 [View Traffic Accident Analysis Notebook](./SCT Task-4.ipynb)
