# ✈️ Aviation Accident Data Analysis

### Enhancing Flight Safety Through Data-Driven Insights  
_A Deep Dive into NTSB Aviation Accident Reports (1962–Present)_  
📊 By [Jeffrin Webster](https://github.com/Jeffrin-Webster)

---

## 📁 Project Overview

This project analyzes aviation accident data from the **National Transportation Safety Board (NTSB)** to uncover patterns, identify risk factors, and suggest safety improvements in the aviation industry. The dataset spans from **1962 to the present**, focusing on U.S. civil aviation incidents and select global events.

---

## 🔍 Objectives

- Understand **temporal trends**, **location-based risks**, and **accident severity**
- Analyze the impact of **weather**, **flight phases**, and **aircraft models** on accident outcomes
- Identify key contributors: **human error**, **mechanical failure**, and **environmental factors**
- Examine the role of **technology** and **future advancements** in aviation safety

---

## 📊 Tools & Technologies

- **Python** (Pandas, Matplotlib, Seaborn)
- **Tableau** (Data visualizations, dashboards)
- **Excel** (Initial cleaning and exploration)
- **Streamlit** *(optional, for interactive dashboards)*

---

## 📂 Dataset

**Source:** [NTSB Aviation Accident Database](https://www.ntsb.gov/)  
- Covers: Civil aviation accidents from **1962 onwards**
- Key Features:
  - Event ID, Aircraft Model, Weather Condition, Flight Purpose, Location
  - Injury Severity, Phase of Flight, Aircraft Damage, etc.

---

## 🧠 Key Insights

- **Personal flights** account for 84% of accidents — most vulnerable during **takeoff and landing**
- **IMC (poor weather)** incidents are less frequent but **more fatal**
- **Boeing 737** models historically show **higher casualty counts** than Airbus
- **Technology adoption** (ADS-B, GPS, EGPWS) is reducing accident rates
- **Accidents dropped** from ~3,000/year in the 1980s to under 500 by 2020

---

## 📌 Notable Visualizations

- 📍 Geographic heatmaps (fatal injuries by state)
- 📈 Temporal trends (accidents per year/month)
- 🧭 Phase of flight vs. injury severity
- ⚠️ IMC vs. VMC weather impact comparison
- 🛫 Aircraft model damage & passenger injury analysis

> **Bonus:** Included recent accident references, e.g., _Air India Flight AI 171 (Ahmedabad, 2025)_ for real-world context.

---

## 🔮 Future Scope

- Add **predictive modeling** to forecast accident probabilities based on conditions
- Build a **Streamlit app** to let users interactively explore NTSB accident data
- Integrate **machine learning** to cluster accident types and detect anomalies

---

## 📸 Demo Snapshots

> *(Insert screenshots of Tableau dashboards or plots here)*  
> Example: `images/heatmap_fatal_injuries.png`

---

## ✅ How to Use

1. Clone the repository  
```bash
git clone https://github.com/Jeffrin-Webster/aviation-accident-analysis.git
cd aviation-accident-analysis
