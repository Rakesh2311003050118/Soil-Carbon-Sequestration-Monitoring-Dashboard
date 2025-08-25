🌱 Soil Carbon Sequestration Monitoring Dashboard

A web-enabled cross-platform dashboard to monitor and trace real-time Soil Organic Carbon (SOC) levels.
The system is designed for scientists, environmentalists, policymakers, and researchers to track carbon sequestration trends using interactive maps, dynamic charts, and exportable reports.

🚀 Features

🌍 Interactive Maps – Visualize SOC data using Leaflet.js

📊 Dynamic Graphs – Plot SOC trends, histograms, and comparisons with Chart.js

⚡ Real-Time SOC Calculation – Compute SOC stock based on soil parameters

🔍 Filtering & Search – Filter by location, depth, density, and carbon %

📥 Export Options – Download results in CSV (Pandas) and PDF (ReportLab)

🗄️ Scalable Backend – Flask + MySQL (HeidiSQL)

🔮 Future Ready – Supports AI models, IoT sensors, and satellite integration

🛠️ Tech Stack

Backend: Flask (Python)

Frontend: HTML, TailwindCSS, Chart.js, Leaflet.js

Database: MySQL (via HeidiSQL)

Export Tools: Pandas, ReportLab

📊 SOC Calculation Formula
𝑆
𝑂
𝐶
 
𝑆
𝑡
𝑜
𝑐
𝑘
 
(
𝑀
𝑔
/
ℎ
𝑎
)
=
𝐵
𝑢
𝑙
𝑘
 
𝐷
𝑒
𝑛
𝑠
𝑖
𝑡
𝑦
 
(
𝑔
/
𝑐
𝑚
3
)
×
𝐷
𝑒
𝑝
𝑡
ℎ
 
(
𝑐
𝑚
)
×
𝐶
𝑎
𝑟
𝑏
𝑜
𝑛
 
%
100
SOC Stock (Mg/ha)=Bulk Density (g/cm
3
)×Depth (cm)×
100
Carbon %
	​

📦 Installation
# Clone repo
git clone https://github.com/yourusername/Soil-Carbon-Sequestration-Monitoring-Dashboard.git
cd Soil-Carbon-Sequestration-Monitoring-Dashboard

# Create virtual environment
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt

# Setup database
mysql -u root -p < database/schema.sql
mysql -u root -p < database/seed_data.sql

# Run Flask server
python backend/app.py
