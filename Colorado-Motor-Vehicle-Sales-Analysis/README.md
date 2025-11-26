# Colorado Motor Vehicle Sales Analysis (Finance Analyst)

This repository contains a complete, reproducible analysis of motor vehicle sales across Colorado counties using Python in **Google Colab**.

## 🎯 Objective
Analyze historical sales to:
- Identify quarterly and county-level **trends**.
- **Forecast** future sales.
- Understand **factors** influencing sales.

## 📁 Project Structure
```
Colorado-Motor-Vehicle-Sales-Analysis/
├── README.md
├── data/
│   └── colorado_motor_vehicle_sales.csv
├── notebooks/
│   └── 01_Colorado_Motor_Vehicle_Sales_Analysis.ipynb
├── scripts/
│   └── utils.py
└── results/
    └── plots/
```
> Note: If the dataset is not public, keep it locally or replace with a link.

## 🧰 Tech Stack
- Python: `pandas`, `numpy`, `matplotlib`, `statsmodels`, `scikit-learn`
- Environment: **Google Colab** / Jupyter

## 🔄 Workflow
1. **Define Scope & Metrics**: Quarterly trends, county-wise analysis, forecasting.
2. **Data Collection**: `colorado_motor_vehicle_sales.csv`.
3. **Data Preparation**: Clean & validate the dataset.
4. **EDA**: Time-series and distribution plots, county rankings.
5. **Statistical Analysis**: Seasonality (decomposition), correlations.
6. **Predictive Modeling**: Baselines (Naive), ARIMA; ML baseline (RandomForest).
7. **Reporting**: Visual insights and a written takeaway section.

## ▶️ Run on Google Colab
1. Open Colab and upload the notebook from `notebooks/01_Colorado_Motor_Vehicle_Sales_Analysis.ipynb`.
2. **Option A (Upload file in Colab)**: Use the upload cell in the notebook.
3. **Option B (Google Drive)**: Mount Drive and place `colorado_motor_vehicle_sales.csv` in a folder of your choice.
4. Execute cells **top to bottom**.

## 📊 Key Questions
- How do sales evolve over time by **quarter**?
- Which **counties** contribute most to sales?
- Is there clear **seasonality**?
- What is a simple **forecast** for next quarters?
- How well can a basic ML model predict sales with limited features? *(demo only)*

## 🧪 Reproducibility
- Random seeds fixed where relevant.
- Outputs (plots) saved in `results/plots/`.

## 📄 License
This project is for educational and internship demonstration purposes.

## 🙌 Acknowledgments
Dataset and project framing inspired by the internship brief provided by the user.
