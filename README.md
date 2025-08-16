# JetVision: Somali Jet and Indian Summer Monsoon Analysis

## 📌 Project Overview
This project analyzes **62 years of atmospheric wind and rainfall data (1962–2023)** to study the behavior of the **Somali Jet (at 850 hPa)** and its relationship with the **Indian Summer Monsoon (ISM)**.  
The goal is to understand historical wind patterns, rainfall variability, and climate drivers like ENSO and IOD.

## 🚀 Features & Objectives
- Process and analyze **wind (Somali Jet) and rainfall datasets** from IMD and reanalysis sources.  
- Study **seasonal Somali Jet intensity, direction, and variability**.  
- Identify the **sea areas affected by high-speed winds (>30 knots)**.  
- Explore correlations between Somali Jet variability and **Indian Monsoon rainfall**.  
- Examine the influence of **ENSO and IOD events** on Somali Jet and rainfall anomalies.  
- Apply **clustering techniques (KMeans, DBSCAN)** to categorize wind patterns.  
- Build **visualizations** for seasonal, inter-annual, and long-term variability.  

## 📂 Dataset
- **Wind Data:** Somali Jet winds at 850 hPa (NetCDF format).  
- **Rainfall Data:** IMD gridded rainfall dataset (1962–2023).  
- **Climate Indices:** ENSO and IOD phases (external datasets).  

## 🛠️ Tech Stack
- **Python Libraries:** `xarray`, `netCDF4`, `numpy`, `pandas`, `matplotlib`, `scikit-learn`  
- **Data Handling:** NetCDF climate data files  
- **Clustering:** KMeans, DBSCAN for wind pattern classification  
- **Visualization:** Time-series plots, anomaly maps, correlation graphs  

## 📊 Key Analyses
1. **Somali Jet Variability**
   - Seasonal cycle of jet strength (May–September).  
   - Inter-annual variability across 62 years.  

2. **High-Speed Wind Areas**
   - Detection of regions with wind speeds >30 knots.  
   - Sea vs Land separation in jet impact zones.  

3. **Rainfall Variability**
   - Indian Summer Monsoon rainfall patterns.  
   - Correlation with Somali Jet anomalies.  

4. **ENSO & IOD Influence**
   - Study of El Niño/La Niña and positive/negative IOD events.  
   - Impact on jet strength and rainfall anomalies.  

5. **Clustering of Wind Patterns**
   - Grouping years into clusters of similar jet behavior.  
   - Identification of anomalous years.

## 📈 Visual Outputs
- Seasonal Somali Jet wind intensity plots.  
- Monsoon rainfall correlation maps.  
- Jet stream anomaly detection figures.  
- Clustering results for wind regimes.  

## 🔮 Future Scope
- Incorporate **multi-level wind datasets** (e.g., 700 hPa, 200 hPa jets).  
- Expand correlation analysis with **global climate teleconnections**.  
- Use **deep learning models** for monsoon rainfall prediction.  

## 🤝 Contributors
- **Mansi** – Research Intern, India Meteorological Department (IMD)  
- Guided by IMD scientists and mentors  

---

📢 *This project is part of my research internship at IMD, focused on climate variability and monsoon dynamics.*
