# 🦠 COVID-19 Data Analysis & Dashboard - Kenya, Tanzania, Uganda

## 📊 Project Overview
This project focuses on end-to-end COVID-19 data analysis for Kenya, Tanzania, and Uganda. Using Python for data wrangling, exploratory analysis, correlation studies, and visualizations, and Power BI for interactive dashboards, the project provides actionable insights for policymakers and public health officials.

---

## ✅ Project Workflow

### Data Collection
- Source: Our World in Data - COVID-19 Dataset  
- Supplemented by WHO reports & country-specific data.

### Data Cleaning & Preprocessing (Python)
- Handled missing values, duplicates, and inconsistencies.  
- Created calculated fields like vaccination rates per capita.

### Exploratory Data Analysis (EDA) (Python)
- Time-series analysis of cases & deaths.  
- Correlation analysis between vaccination & outcomes.  
- Heatmaps & geospatial analysis.

### Visualizations (Python)
- Seaborn & Plotly for graphs & maps.  
- Folium for interactive geospatial maps.

### Interactive Dashboard (Power BI)
- Final report built in Power BI for interactivity & presentation.

---

## 🛠️ Tech Stack
- Python (Pandas, Seaborn, Matplotlib, Plotly, Folium)  
- Power BI (Dashboard building & reporting)  
- Git & GitHub (Version control)  
- Jupyter Notebook (For analysis & reporting)

---

## 📂 Project Structure
📦 COVID-19-Analysis-East-Africa
┣ 📂 data
┃ ┣ raw_data.csv
┃ ┣ cleaned_data.csv
┣ 📂 notebooks
┃ ┣ covid_analysis.ipynb # Full EDA & Visualizations in Python
┣ 📂 visuals
┃ ┣ time_series_cases.png
┃ ┣ vaccination_heatmap.png
┃ ┣ choropleth_vaccination.html
┣ 📂 reports
┃ ┣ COVID-19_Report.pdf
┣ 📂 powerbi_dashboard
┃ ┣ COVID-19_Dashboard.pbix
┣ 📄 README.md
┣ 📄 requirements.txt

yaml
Copy
Edit

---

## 📊 Key Insights

### 1. Key Findings

#### 🦠 Infection Trends
- Kenya experienced significant peaks in COVID-19 cases, reflecting multiple waves.  
- Tanzania showed stable but persistent infection rates.  
- Uganda maintained lower but fluctuating case numbers.  
- Data gaps (e.g., missing dates) hinder precise event correlation.

#### ⚰️ Mortality Patterns
- Fluctuating death rates observed across all countries.  
- Kenya showed higher fatality peaks, mirroring case surges.  
- Reporting inconsistencies suggest data validation is required.

#### 💉 Vaccination Outcomes
- Strong negative correlation between vaccination rates & deaths.  
- Weaker correlation with new cases, highlighting that vaccines reduce severity, not infections.  
- Raw data can be misleading without normalization (population bias).

#### 🗺️ Geospatial Insights
- Choropleth maps revealed variations in vaccination coverage.

---

## 🎯 Recommendations
- Implement real-time mortality tracking systems.  
- Normalize metrics per capita to avoid misleading interpretations.  
- Strengthen vaccination campaigns, especially in rural areas.  
- Foster regional data sharing & collaboration.  
- Enhance public communication to combat misinformation.

---

## 🚀 How to Run Locally

### Clone the repo:
```bash
git clone https://github.com/oumaouma20/COVID-19-Analysis-East-Africa.git
cd COVID-19-Analysis-East-Africa
Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt
Open the notebook:
bash
Copy
Edit
jupyter notebook notebooks/covid_analysis.ipynb
For the Power BI dashboard:
Open powerbi_dashboard/COVID-19_Dashboard.pbix in Power BI Desktop.

📊 Sample Visualization
(Insert screenshots of python-visualization.png and powerbi-dashboard.png)

markdown
Copy
Edit
![Python Visualization](visuals/python-visualization.png)
![Power BI Dashboard](visuals/powerbi-dashboard.png)
📄 License
MIT License. Feel free to use and modify with proper attribution.

🙌 Acknowledgements
Our World in Data

WHO COVID-19 Dashboard

Power BI & Python communities

🔗 Connect
GitHub: oumaouma20

LinkedIn: Emmanuel Ouma

Email: emmanuelouma2000@gmail.com
