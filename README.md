# 📈 AI-Powered Sales Forecasting System

An end-to-end machine learning project that predicts future sales using
time-series forecasting techniques and visualizes business insights
using interactive Power BI dashboards.

---

## 📌 Project Overview

Accurate sales forecasting is essential for inventory planning, marketing
strategy, and revenue optimization. This project analyzes historical retail
sales data, identifies trends and seasonality, and predicts future monthly
sales using time-series modeling.

The final output is an automated forecasting pipeline with business-ready
visual dashboards built using Power BI.

---

## 🎯 Objective

- Predict future monthly sales using historical data  
- Identify long-term trends and seasonal patterns  
- Evaluate forecasting accuracy using statistical metrics  
- Visualize insights in a Power BI dashboard for business users  

---

## 🗂 Dataset Description

The dataset contains retail transaction data with the following key fields:

- Order Date  
- Sales  
- Product and Category details (optional)  

Data is aggregated to monthly level for time-series forecasting.

---

## ⚙️ Tech Stack

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib  
- **Time Series Model:** Prophet  
- **Visualization:** Power BI  
- **Notebook Environment:** Jupyter Notebook  

---

## 🔍 Methodology

### 1. Data Preprocessing
- Converted order date into datetime format
- Aggregated daily sales into monthly total sales
- Handled missing values and extreme outliers using IQR method

### 2. Feature Transformation
- Applied log transformation to stabilize variance
- Prepared dataset in Prophet format (`ds`, `y`)

### 3. Model Training
- Trained Prophet time-series forecasting model
- Captured trend and seasonal components

### 4. Forecast Generation
- Generated future sales predictions with confidence intervals
- Converted predictions back to original scale

### 5. Model Evaluation
- Evaluated using:
  - RMSE (Root Mean Square Error)
  - MAPE (Mean Absolute Percentage Error)

### 6. Business Visualization
- Exported forecast results to CSV
- Built interactive Power BI dashboards

---

## 📈 Results & Forecast Analysis

The model successfully captures:

- Upward and downward sales trends
- Seasonal spikes during peak business months

Evaluation metrics indicate reasonable forecasting accuracy for
business planning and inventory estimation.

---

## 📊 Power BI Dashboard

The dashboard includes:

- Actual vs Forecast Sales Trend Line
- Monthly Sales Distribution
- Forecast Confidence Range
- KPI Cards for key metrics

This enables stakeholders to make data-driven decisions easily.

---

## 💡 Business Insights

- Sales show strong seasonality during festive months  
- Forecast suggests demand increase in upcoming peak season  
- Inventory planning should increase ahead of high-demand periods  
- Marketing campaigns can be aligned with predicted growth months  

---

## ▶️ How to Run This Project

### Step 1: Clone Repository
```bash
git clone https://github.com/rohitkedare2830/ai-sales-forecasting-system.git
cd ai-sales-forecasting-system
