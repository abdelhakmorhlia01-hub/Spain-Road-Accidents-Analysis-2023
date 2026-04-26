# 🇪🇸 Spain Road Accidents Analysis 2023

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## 📌 Overview
Exploratory data analysis of **101,306 road accidents** recorded in Spain during 2023, using official microdata from the Dirección General de Tráfico (DGT).

The analysis investigates **where**, **when**, and **under what conditions** road accidents are most likely to turn fatal combining geographic mapping, time series analysis, and 
conditions profiling.

---

## ❓ Key Questions Answered

- Which provinces have the most accidents and highest fatality rates?
- Are interurban roads more deadly than urban roads?
- When do fatal accidents peak — by month, day, and hour?
- Which weather, lighting, and road conditions are most dangerous?
- What is the deadliest accident type?
- Can we identify a high-risk profile from the data?

---

## 🔍 Key Findings

-  **Barcelona and Madrid** lead in total accidents due to 
  population density, but **smaller provinces show higher 
  fatality rates per accident**
- 🌙 **Late-night interurban accidents (00:00–03:00)** are 
  nearly **5x more deadly** than the national average (6.7% vs 1.4%)
- ☀️ **87% of accidents occur in clear weather**  but drivers 
  take more risks in good conditions
- 🚶 **Pedestrian accidents** represent only 7% of incidents 
  but account for **18% of fatalities**
- ⚠️ **Unsignposted curves** are nearly **twice as deadly** 
  as signposted ones

---

## 🗂️ Project Structure

spain-road-accidents-2023/
│
├── spain_road_accidents_2023_analysis.ipynb  ← main notebook
├── TABLA_ACCIDENTES_23.XLSX                  ← raw data (DGT)
├── spain-provinces.geojson                   ← geographic data
├── Diccionario_Tabla_Accidentes.xlsx         ← data dictionary
└── README.md

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|---|---|
| Pandas | Data cleaning & analysis |
| Seaborn / Matplotlib | Charts & visualizations |
| Folium | Interactive choropleth maps |
| GeoPandas | Geographic data processing |

---

## 📊 Analysis Structure

Data Loading & Cleaning
Geography    → province maps, road type, road authority
Time Trends  → monthly, daily, hourly patterns
Conditions   → weather, lighting, road surface, accident type
High-Risk Profile → combined factor analysis
Conclusions & Recommendations


---

## 💡 Recommendations to DGT

1. Install warning signs on all unsignposted rural curves
2. Launch summer road safety campaigns for July–August
3. Prioritize street lighting on interurban secondary roads
4. Strengthen pedestrian infrastructure in urban areas
5. Hold municipalities accountable for road quality 
   46% of accidents occur on municipal roads

---

## 📂 Data Source

**Dirección General de Tráfico (DGT)**  

- Main data: [DGT Microdatos 2023](https://www.dgt.es/menusecundario/dgt-en-cifras/dgt-en-cifras-resultados/dgt-en-cifras-detalle/Ficheros-microdatos-de-accidentes-con-victimas-2023/)
- GeoJSON: [Spain Provinces](https://github.com/codeforgermany/click_that_hood)

> Each row represents one road accident with victims 
> recorded in Spain during 2023.

---

## 👤 Author

**Abdelhak Morhlia**  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdelhak-morhlia-41366a396/)
