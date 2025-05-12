# 🌍 Global Food Waste & Economic Loss Analysis

This project explores the **relationship between global food waste and economic loss** using publicly available data from 2018 to 2024. The objective is to identify patterns across countries, food categories, and time to determine whether higher levels of food waste directly contribute to greater economic loss.

---

## 📊 Objective

To uncover global trends in food waste and assess their financial implications across:

- Geographic regions  
- Food categories  
- Population size  
- Time (2018–2024)

---

## ❓ Guiding Question

**Does food wastage directly contribute to economic loss?**

**Hypothesis:** Higher levels of food waste are directly linked to increased global economic loss.

---

## 🧪 Analysis Highlights

- **Data Preprocessing**  
  Cleaning, merging, and normalizing international food waste datasets segmented by country, year, and food type.

- **Exploratory Data Analysis (EDA)**  
  - Choropleth maps to assess food waste distribution by country  
  - Scatter plots and correlation matrices to examine variable relationships  
  - Category-level breakdown by food type and waste intensity

- **Linear Regression Modeling**  
  - Regression analysis between Total Waste and Economic Loss  
  - R² = 0.98, strong predictive relationship  
  - Slope = 0.98, indicating a nearly 1:1 increase

- **Clustering (K-Means)**  
  - Clustered countries based on waste and economic loss  
  - Identified key contributors below 150K loss/waste  
  - Population analysis revealed smaller nations may contribute more waste proportionally

- **Time Series Analysis**  
  - Evaluated 6-year trends (2018–2023)  
  - No clear seasonality, minor anomaly in 2022  
  - Data is stationary and suitable for forecasting

---

## 📁 Project Structure
- *01 Project Management
- *02 Data
  - Original Data
  - Prepared Data
- *03 Scripts
- *04 Analysis
  - Reports
  - Test Files
  - Visualizations
- *05 Sent to Client
