# 🌍 Soil Carbon Sequestration Monitoring Dashboard 
This repository contains two major works:  
1. **Soil Carbon Sequestration Monitoring Dashboard** – a DBMS project implemented using Flask, MySQL, Leaflet.js, and Chart.js.  
2. **Research Paper: Role of AI in Cryptocurrency and Soil Carbon Monitoring** – exploring how AI can augment SOC monitoring and forecasting.

---

## 📌 Project 1: Soil Carbon Sequestration Monitoring Dashboard
### Overview
Soil organic carbon (SOC) is a critical component of soil health and plays a major role in mitigating climate change.  
This dashboard allows **real-time monitoring, visualization, and analysis** of SOC.

### 🚀 Features
- Input soil parameters (site, coordinates, depth, bulk density, % carbon).  
- Automatic SOC stock calculation:
- #SOC = Bulk Density × Depth × (Carbon% / 100  
- Real-time visualization with **Leaflet.js** (maps).  
- Charts and analytics with **Chart.js**.  
- Export results in **CSV & PDF**.  
- Session management & admin logs.  

### 🛠️ Tech Stack
- **Backend:** Flask (Python)  
- **Database:** MySQL (via HeidiSQL)  
- **Frontend:** HTML, CSS, Leaflet.js, Chart.js  
- **Reporting:** ReportLab Toolkit  \
  Soil-Carbon-Sequestration-Monitoring-Dashboard/
│── app/ # Flask backend code
│── templates/ # HTML templates
│── static/ # CSS, JS, images
│── database/ # MySQL schema & seed data
│── reports/ # Final DBMS project report (PDF)
│── docs/ # ER diagrams, methodology
│── requirements.txt # Python dependencies
│── README.md # Project documentation
