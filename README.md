# 🌾 Seasonal Agriculture Performance Analysis
### VOIS × AICTE Major Data Analytics Project | Batch 1 2026–2027

---

## 📌 Project Overview

This project analyzes agricultural performance across three Indian farming seasons — **Kharif, Rabi, and Zaid** — using a dataset of 4,000 farm records. The goal is to identify meaningful patterns, trends, and differences in agricultural performance through data analytics.

> **Domain:** Agriculture  
> **Type:** Data Analytics (No Machine Learning required)  
> **Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

---

## 🎯 Problem Statement

Agricultural activities are influenced by seasonal variations in environmental conditions, farming practices, resource availability and market conditions. Raw agricultural data does not clearly explain how performance changes across seasons.

This project investigates seasonal differences by identifying meaningful patterns, trends, relationships and variations within the available data.

---

## 📁 Repository Structure

```
Seasonal-Agriculture-Performance-Analysis/
│
├── 📓 Seasonal_Agriculture_Performance_Analysis.ipynb   # Main Jupyter Notebook
├── 📊 seasonal_agriculture_performance_dataset.csv      # Dataset (4000 records)
├── 📄 Major_Project_Seasonal_Agriculture_Performance_Analysis_.pdf  # Project Brief
├── 📑 Seasonal-Agriculture-Performance-Analysis.pptx   # Presentation
└── 📝 README.md                                         # This file
```

---

## 📊 Dataset Information

| Feature | Detail |
|---|---|
| Total Records | 4,000 farm records |
| Total Columns | 28 features |
| Seasons | Kharif (1779), Rabi (1627), Zaid (594) |
| Crops | Wheat, Rice, Maize, Cotton, Chilli, Pulses, Groundnut, Sugarcane |
| States | Andhra Pradesh, Maharashtra, Telangana, Karnataka, Gujarat, Tamil Nadu, Punjab, Madhya Pradesh |
| Missing Values | Rainfall_mm (48), Soil_Moisture_pct (40), Yield_Tonnes_Ha (32) |

### Key Variable Categories
- **Environmental:** Rainfall_mm, Avg_Temperature_C, Humidity_pct, Sunlight_Hours_Day, Soil_pH, Soil_Moisture_pct
- **Operational:** Fertilizer_kg_ha, Pesticide_Litre_ha, Water_Used_m3, Seed_Quality_Score
- **Production:** Yield_Tonnes_Ha, Production_Tonnes
- **Economic:** Total_Cost_INR, Revenue_INR, Profit_INR, Market_Price_INR_Tonne

---

## 🗂️ Notebook Structure (50 Cells)

| Section | Content |
|---|---|
| Title + Sections 1–3 | Introduction, Problem Statement, Objective, Key Questions |
| Section 4 | Initial Data Understanding (head, tail, sample, info) |
| Section 5 | Variable Classification (numerical vs categorical) |
| Section 6 | Data Cleaning (duplicates, data types) |
| Section 7 | Missing Value Analysis & Handling + Statistical Summary |
| Section 8 | Univariate Analysis (pie chart, bar charts) |
| Section 9 | Outlier Analysis (IQR method) |
| Section 10 | Bivariate Analysis (Season vs Yield, Profit, Rainfall, Irrigation) |
| Section 11 | Multivariate Analysis (Heatmaps, Crop × Season × Yield) |
| Section 12 | Seasonal Comparison (Summary metrics table) |
| Section 13 | Student-Designed Analyses (Resource usage + Crop profitability) |
| Section 14 | Key Insights (8 insights with Observation/Evidence/Interpretation/Limitation) |
| Section 15 | Recommendations (6 data-driven recommendations) |
| Section 16 | Conclusion |
| Section 17 | Project Checklist |

---

## 🔍 Key Findings

| Metric | Kharif | Rabi | Zaid |
|---|---|---|---|
| Avg Yield (t/ha) | 5.64 | 5.08 | 4.67 |
| Avg Profit (₹) | 1,78,914 | 87,689 | -24,804 |
| Avg Rainfall (mm) | 852 | 436 | 299 |
| Avg Temperature (°C) | 28.45 | 23.49 | 31.04 |
| Records | 1,779 | 1,627 | 594 |

### Top Insights
1. 🟢 **Kharif** has highest average yield (5.64 t/ha) and profit (₹1,78,914)
2. 🔴 **Zaid** shows negative average profit (–₹24,804) — high temperature, low rainfall
3. 🌧️ Rainfall varies nearly **3×** across seasons (852mm vs 299mm)
4. 📉 Yield decreases progressively: Kharif → Rabi → Zaid
5. 🌡️ Zaid has the highest average temperature (31°C) — linked to lower yields
6. 💧 Resource usage (water + fertilizer) is highest in Kharif
7. 🗺️ Kharif > Rabi > Zaid yield pattern is consistent across most Indian states
8. 📋 Missing data is concentrated in field-measurement columns only

---

## 🛠️ Technologies Used

| Tool | Purpose |
|---|---|
| Python 3 | Programming language |
| Pandas | Data loading, cleaning, manipulation |
| NumPy | Numerical operations |
| Matplotlib | Base visualizations |
| Seaborn | Statistical plots |
| Jupyter Notebook | Development environment |
| GitHub | Version control & submission |

---

## ▶️ How to Run

1. **Clone this repository**
```bash
git clone https://github.com/[your-username]/Seasonal-Agriculture-Performance-Analysis.git
```

2. **Install required libraries**
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. **Open Jupyter Notebook**
```bash
jupyter notebook
```

4. **Run the notebook**
   - Open `Seasonal_Agriculture_Performance_Analysis.ipynb`
   - Make sure `seasonal_agriculture_performance_dataset.csv` is in the same folder
   - Run All Cells: `Kernel → Restart & Run All`

---

## 📈 Visualizations Included

- 🥧 Season Distribution Pie Chart
- 📊 Season & Crop Distribution Bar Charts
- 📦 Yield & Profit Boxplots by Season
- 🔵 Rainfall vs Yield Scatter Plot
- 📊 Average Yield by Irrigation Method
- 🔥 Correlation Heatmap (11 key variables)
- 🗺️ State × Season Yield Heatmap
- 📦 Crop × Season × Yield Multivariate Boxplot
- 📊 Seasonal Comparison Bar Charts (4 metrics)
- 📊 Resource Usage by Season (Fertilizer + Water)
- 📊 Crop Profitability by Season

---

## 🔮 Future Scope

- Integrate real-time weather data for live seasonal monitoring
- Expand dataset to include more Indian states and districts
- Add year-over-year trend analysis for pattern consistency
- Develop a crop recommendation system using Machine Learning
- Include soil test report data for deeper soil-yield analysis
- Build market price forecasting model

---

## 👤 Author

**Chavda Chirag**  
VOIS × AICTE Internship — Batch 1 2026–2027  
AICTE STU ID: STU6960e9dc5b1461767959004
College: Gandhinagar University

---

## 📜 License

This project is submitted as part of the VOIS × AICTE Foundation Internship Major Project.  
Dataset and project brief provided by VOIS for educational purposes.
