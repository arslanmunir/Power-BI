#Airplay Control Dashboard – Power BI Project

This Power BI dashboard provides detailed insights into the **airplay performance**, **channel activity**, and **metadata completion** for both **Global** and **Regional Channels** over time. The goal is to monitor audio/video track exposure, duration, and metadata quality across multiple sources such as ACR, Manual Logging, Shazam, and Olaf.

---

## Dashboard Overview

### **Key Metrics**
- **Total Channels**: 27  
  - Global Channels: 6  
  - Regional Channels: 21  
- **Total Play Duration**: 8.6K Minutes  
- **ACR Duration**: 7,569.42 Min  
- **Manual Duration**: 849.47 Min  
- **Shazam Duration**: 75.75 Min  
- **Olaf Duration**: 101.18 Min  
- **Meta Completion**: 7.54K Min (≈88%)

---

## Dashboard Features

### Header Summary Cards
- Show key KPIs: total channels, play time, and metadata duration.
- Consistent format with clear numeric values.

### Visualizations

| Chart | Description |
|-------|-------------|
| **Donut Chart** | Compares total time with meta-completed time. Now includes **percentage completed**. |
| **Bar Charts** | Break down time duration across different logging sources (ACR, Manual, Olaf, Shazam). |
| **Treemap** | Shows play duration by individual channels — color-coded by group and type. |
| **Line Chart** | Trend analysis of daily time and metadata completion. Highlights fluctuations across the month. |
| **Pie Chart** | Displays breakdown of total play time by source (ACR, Manual, Olaf, Shazam). |

### Slicers & Filters
- **Channel Type**: Global / Regional
- **Channel Selector**
- **Date Slicer**: Month/year-based filtering

### Interactivity
- Cross-filtering enabled: selecting a visual filters others.
- Tooltips enabled on treemap and bar charts to display full names and precise values.

---

## Enhancements & Custom Features

- **Conditional Formatting** for channel durations (in Channel Table)
- **Tooltips** added to truncated visuals (e.g., long song names)
- **Dynamic Y-Axis Scaling** across charts
- **Page Navigation Tabs** between *Overview* and *Channel Summary*

---

## 📌 Notes

- Dataset simulated for demo purposes.
- Can be extended with:
  - Region-based filtering
  - Artist/Label-wise performance
  - Predictive modeling on metadata completion trends

---

## 👨‍💻 Author

**Arslan Munir**  
Power BI & Data Engineer  
📧 arslan@example.com | 🌐 [LinkedIn](https://www.linkedin.com/in/muhammad-arslan-munir-243a2822/)

