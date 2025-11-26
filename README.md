End-to-end analysis of Colorado Motor Vehicle Sales data, including data cleaning, EDA, trend analysis, county comparisons, forecasting readiness, and Power BI–style dashboard visualization.


Colorado Motor Vehicle Sales Analysis
This repository contains a complete data analysis project on Colorado Motor Vehicle Sales, covering multiple years and counties.
The goal is to explore sales patterns, understand regional variations, and prepare the data for advanced forecasting and BI-style visualization.

🔍 Project Overview
This project includes:
Data Cleaning & Preparation
Exploratory Data Analysis (EDA)
Quarterly Time Series Construction
County-Level Comparative Analysis
Sales Trend Visualization
Forecasting Model Readiness (SARIMAX / ETS)
Metallic UI Power BI–style LinkedIn Dashboard

📁 Dataset
The dataset includes the following columns:
Column	Description
year	Year of the sales record
quarter	Quarter (1–4)
county	Colorado county name
sales	Dollar value of motor vehicle sales
Total rows: 501
Time period: 32 quarters (2008–2015)

🛠 Technologies Used
Python
Pandas
NumPy
Matplotlib / Seaborn
Statsmodels (SARIMAX, ETS ready)
Jupyter Notebook / Google Colab
Power BI–style visualization (custom PNG)


📊 Key Insights
1️⃣ Total Sales
$88.20 Billion total across all counties & years
2️⃣ Quarterly Sales Pattern
Q1: $20.4B
Q2: $22.3B
Q3: $23.9B
Q4: $21.6B
Q3 consistently shows the highest activity, confirming seasonal behavior.
3️⃣ Top 5 Counties
Arapahoe – $20.1B
El Paso – $11.9B
Jefferson – $9.1B
Adams – $8.9B
Denver – $6.8B
Arapahoe leads by a significant margin.
📈 Forecasting Readiness
The time series created is suitable for:
SARIMAX (Seasonal ARIMA)
ETS (Exponential Smoothing)
Naive / Baseline Models
Clear seasonal structure makes this dataset ideal for quarterly forecasting.
🖥 Dashboard Visualization (Metallic UI)
A Power BI–style metallic dashboard was designed to visualize:
Total sales
Trend line
Quarterly KPIs
County comparison
This PNG is included in the repo for showcasing on LinkedIn or portfolios.
🚀 How to Run the Notebook
Open the notebook in Jupyter or Google Colab
Upload the dataset (CSV) or update the path
Run all cells to produce EDA and charts
Export or modify dashboard outputs


📌 Project Structure
📂 colorado-motor-vehicle-sales-analysis
 ├── data/
 │    └── colorado_motor_vehicle_sales.csv
 ├── notebooks/
 │    └── Colorado_Motor_Vehicle_Sales_Analysis.ipynb
 ├── visuals/
 │    └── metallic_dashboard.png
 ├── README.md
 └── requirements.txt

🧠 Recommendations
Develop a live dashboard in Power BI or Tableau
Train SARIMAX/ETS forecasting models
Add external economic indicators
Segment counties using clustering techniques
Build prediction models using Random Forest / XGBoost
🙌 Acknowledgment
Project completed by Premkumar, under mentorship from Unified Mentor.
