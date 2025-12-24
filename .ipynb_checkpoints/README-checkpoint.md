# NYC Safety Analytics: A Spatiotemporal Investigation

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![PostGIS](https://img.shields.io/badge/PostGIS-Enabled-green)

## 📌 Project Overview
**NYC Safety Analytics** is a spatial data science project that investigates homicide patterns in New York City. Unlike traditional analysis that focuses solely on crime *volume*, this project utilizes **Spatial Intensity Metrics (Incidents per km²)** to reveal hidden high-risk zones.

---

## 🔍 Key Findings & Insights

### 1. The Density Paradox
* **The Insight:** High crime volume does not always equal high risk.
* **The Data:** While large neighborhoods like **Bedford-Stuyvesant** have the highest *total* count, small neighborhoods like **Yorkville** exhibit shocking **Intensity Density (327 incidents/km²)**, making the "risk per step" significantly higher.

### 2. The Weekend Effect
* **The Insight:** Violence follows a strict temporal cycle tied to social friction.
* **The Data:** **35%** of all recorded incidents occur specifically on **Saturday and Sunday**, with a sharp drop-off on Mondays (-40%).

### 3. The Heat Hypothesis (Seasonality)
* **The Insight:** Crime follows the thermometer.
* **The Data:** Homicides consistently spike in **July (400+ incidents)**, correlating with high temperatures and overcrowding.

### 4. Infrastructure Risk Factors
* **The Insight:** Transit proximity is a major risk factor.
* **The Data:** **62.7%** of all homicides occur within **Immediate Access (<150m)** of a subway station, suggesting a "Getaway" correlation.

---

## Repository Structure

```text
├── notebooks/           
│   ├── 01_non_spatial_analysis.ipynb   
│   └── 02_spatial_analysis.ipynb     # spatial analysis & Interactive Dashboard
├── presentation/          
│   └── NYC_Safety_Presentation.pdf    # Final Slide with Recommendations
└── README.md                          # Project Documentation