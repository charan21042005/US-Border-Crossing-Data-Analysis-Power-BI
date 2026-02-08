#  US Border Crossing Data Analysis Dashboard (Power BI)

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![DAX](https://img.shields.io/badge/DAX-Advanced-blue)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-success)
![Forecasting](https://img.shields.io/badge/Forecasting-Time%20Series-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

An **end-to-end Power BI analytics dashboard** analyzing **U.S. Border Crossing Entry Data** to uncover  
**traffic patterns, port performance, transport mode behavior, seasonal trends, and future outlook using forecasting**.

This project demonstrates **data modeling, DAX proficiency, analytical reasoning, and dashboard storytelling**  
using a **real-world U.S. government dataset**.

---

## 📌 Project Overview

This dashboard provides a **comprehensive analytical view** of U.S. border crossings across:

- 🇺🇸 **U.S.–Mexico & U.S.–Canada borders**
- 🚢 **Ports of entry**
- 🚗 **Transport modes** (personal vehicles, trucks, pedestrians, trains, buses)
- 📆 **Temporal trends** (monthly, yearly, seasonal)
- 📈 **Rolling averages & YoY growth**
- 🔮 **Forecasting & future outlook**
- ⚠️ **Operational risk & performance insights**

🎯 **Goal:**  
Support **operational planning, infrastructure optimization, risk monitoring, and data-driven decision-making**  
for cross-border transportation and policy analysis.

---

## 🧩 Dashboard Pages

1. **🏠 Landing Page**  
   Project introduction, dataset source, GitHub & LinkedIn links, and dashboard navigation.

2. **🧭 Contents & Navigation**  
   Structured overview of all analytical sections with direct page navigation.

3. **📊 Overview Dashboard**  
   High-level KPIs, top ports, geographic distribution, and long-term trends.

4. **🚢 Port & Border Deep-Dive Analysis**  
   Port-level performance, traffic concentration (Pareto analysis), and geographic hotspots.

5. **🚗 Transport Mode & Measure Analysis**  
   Contribution and trends of transport modes across borders.

6. **📆 Temporal & Seasonal Analysis**  
   Month-wise seasonality, YoY trends, rolling averages, and seasonal rank shifts.

7. **🔮 Forecasting & Future Outlook**  
   Time-series forecasting with confidence intervals and trend indicators.

8. **⚙️ Operational Insights & Recommendations**  
   Volatility analysis, risk quadrants, and operational benchmarking.

9. **📋 Results Summary & Key Insights**  
   Consolidated matrices, performance summaries, and comparative insights.

10. **🧠 Executive Summary & Strategic Recommendations**  
    Business-focused insights and actionable recommendations for stakeholders.

---

## 📊 Key Analytical Highlights

- 🇲🇽 **U.S.–Mexico border** accounts for the majority of total crossings.
- 📌 **Pareto effect** observed: a small number of ports handle most traffic.
- 🚗 **Personal vehicles** dominate overall border crossings.
- 📆 Clear **seasonal patterns** with peak activity during mid-year months.
- ⚠️ Sharp decline around **2020**, followed by gradual recovery.
- 🔮 Forecasting indicates **continued upward recovery** with moderate volatility.

---

## 🛠 Tools & Skills Used

### 🔧 Tools
- **Power BI Desktop**
- **Microsoft Bing Maps**

### 🧠 DAX Concepts
- `CALCULATE`, `FILTER`
- Year-over-Year (YoY) Growth %
- Rolling Averages (3M, 6M, 12M)
- Pareto & cumulative share logic
- Time intelligence functions

### 🧱 Data Modeling
- **Star Schema**
- Fact & dimension tables
- Optimized relationships

### 📊 Visualizations
- KPI Cards
- Bar & Column Charts
- Line & Area Charts
- Donut & Stacked Bar Charts
- Maps
- Scatter Plots
- Decomposition Tree
- Forecasting visuals
- Matrix visuals

---

## 📂 Dataset

📦 The dataset used in this project is included as a ZIP file:

- `Border_Crossing_Entry_Data_DataSet.zip`

📍 **Source:**  
U.S. Bureau of Transportation Statistics – Border Crossing Entry Data  
(U.S. Government Open Data Portal)

---

## 📁 Repository Structure

```text
US-Border-Crossing-Data-Analysis-PowerBI/
├── Dashboard_Screenshots/
│   ├── 1.Screenshot_Overview.png
│   ├── 2.Screenshot_Contents.png
│   ├── 3.Screenshot_Overview_Dashboard.png
│   ├── 4.Screenshot_Port_Analysis.png
│   ├── 5.Screenshot_Transport_Mode.png
│   ├── 6.Screenshot_Temporal_Analysis.png
│   ├── 7.Screenshot_Forecasting.png
│   ├── 8.Screenshot_Operational_Insights.png
│   ├── 9.Screenshot_Results_Summary.png
│   └── 10.Screenshot_Executive_Summary.png
│
├── Dataset/
│   └── Border_Crossing_Entry_Data_DataSet.zip
│
├── Report/
│   └── US_Border_Crossing_Analysis_Report.pdf
│
├── US_Border_Crossing_Dashboard.pbix
├── README.md
└── .gitignore
```

---

## 📊 Dashboard Pages Preview

### Page 1: Landing Page – Project Overview
![Page 1](Dashboard%20Screenshots/1.Screenshot%202025-12-15%20210654.png)

### Page 2: Dashboard Contents & Navigation
![Page 2](Dashboard%20Screenshots/2.Screenshot%202025-12-15%20210707.png)

### Page 3: US Border Crossing Overview
![Page 3](Dashboard%20Screenshots/3.Screenshot%202025-12-15%20210720.png)

### Page 4: Port-Level Traffic Analysis
![Page 4](Dashboard%20Screenshots/4.Screenshot%202025-12-15%20210734.png)

### Page 5: Border-wise & Transport Mode Analysis
![Page 5](Dashboard%20Screenshots/5.Screenshot%202025-12-15%20210746.png)

### Page 6: Temporal & Seasonal Trends
![Page 6](Dashboard%20Screenshots/6.Screenshot%202025-12-15%20210756.png)

### Page 7: Forecasting & Future Outlook
![Page 7](Dashboard%20Screenshots/7.Screenshot%202025-12-15%20210805.png)

### Page 8: Operational Insights & Risk Analysis
![Page 8](Dashboard%20Screenshots/8.Screenshot%202025-12-15%20210817.png)

### Page 9: Results Summary & Key Insights
![Page 9](Dashboard%20Screenshots/9.Screenshot%202025-12-15%20210829.png)

### Page 10: Executive Summary & Strategic Recommendation
![Page 10](Dashboard%20Screenshots/10.Screenshot%202025-12-15%20210842.png)

---

## 📈 Strategic Recommendations

- Prioritize **infrastructure & staffing** at high-volume ports.  
- Implement **seasonal resource planning** to handle predictable traffic surges.  
- Monitor **high-volatility ports** for operational risk mitigation.  
- Use **forecast insights** to support short-term capacity planning.

---

## 🚀 How to Use

1. Download the repository or clone it.
2. Extract the dataset ZIP file if required.
3. Open `US_Border_Crossing_Dashboard.pbix` using **Power BI Desktop**.
4. Interact with slicers to explore insights across borders, ports, time, and transport modes.

---

## ⚠️ Limitations

- Forecasting is based solely on **historical patterns** present in the data.  
- **External policy changes** and geopolitical events are not explicitly modeled.  
- Data accuracy depends on **government-reported records**.

---

## 🔮 Future Enhancements

- Advanced forecasting models (**ARIMA / Prophet**).  
- **Real-time data integration** and automated pipelines.  
- **Power BI Service deployment** with scheduled refresh.  
- **Role-based access control (RLS)** and enhanced security.

---

## 🙏 Acknowledgements

Special thanks to **Jaffar Amin** for guidance and mentorship in Power BI and data analytics.

---

## 👤 Author

**Sri Charan**  
B.Tech CSE – Lovely Professional University  

📧 Email: **tokachichusricharan2005@gmail.com**  
🔗 LinkedIn: [Tokachichu Sri Charan – Power BI Project Post](https://www.linkedin.com/posts/tokachichu-sricharan_powerbi-dataanalytics-datavisualization-activity-7406358334343118848-LTI2)





