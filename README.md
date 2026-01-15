# 📊 Mutual Fund Analysis – High ROI & Low Risk Strategy

## 📌 Project Overview
This project demonstrates a **data-driven approach to mutual fund portfolio creation** by selecting stocks that provide **high returns (ROI)** with **low risk (volatility)**.  
Using Python and Pandas, we analyze historical stock price data, allocate investments using a risk-aware strategy, and simulate long-term SIP growth.

The goal of this project is to show how **data analytics techniques** can be applied to a **real-life investment problem**.

---

## 🎯 Objectives
- Analyze stock returns and risks using historical price data
- Select stocks with **high ROI and low volatility**
- Allocate investment using **inverse volatility weighting**
- Simulate SIP investment growth over different time horizons
- Visualize insights using meaningful business-friendly graphs

---

## 🛠 Tools & Libraries Used
- **Python**
- **Pandas** – data manipulation and analysis  
- **NumPy** – numerical calculations  
- **Matplotlib** – data visualization  
- **Google Colab** – development environment  

---

## 📂 Dataset
- Historical **NIFTY 50 closing price data**
- Data includes daily closing prices for multiple stocks
- Date column is used as a time index for return calculations

---

## 🔍 Methodology

### 1️⃣ Data Preparation
- Converted date column to datetime format
- Set date as index for time-series analysis
- Removed missing values to ensure clean calculations

### 2️⃣ Return & Risk Calculation
- **Daily Returns** calculated using percentage change
- **Annual ROI** computed using average daily return
- **Volatility (Risk)** measured using standard deviation of returns

### 3️⃣ Stock Selection Strategy
- Selected stocks with:
  - ROI above the median
  - Volatility below the median
- This ensures **better returns with controlled risk**

### 4️⃣ Investment Allocation
- Used **inverse volatility weighting**
- Stocks with lower risk receive higher allocation
- Ensures portfolio stability and diversification

### 5️⃣ SIP Growth Simulation
- Monthly SIP investment of ₹5000
- SIP amount increases by **10% every year**
- Investment growth simulated for:
  - 1 year
  - 3 years
  - 5 years
  - 10 years

---

## 📊 Key Visualizations

### 🔹 Risk vs Return Scatter Plot
- Helps identify stocks with high return and low risk
- Commonly used in portfolio analysis

### 🔹 Investment Allocation Pie Chart
- Shows how funds are distributed among selected stocks
- Based on inverse volatility logic

### 🔹 SIP Growth Bar Chart
- Shows final accumulated value over different time periods
- Includes percentage growth labels to highlight compounding effect

---

## 📈 Key Insights
- Stocks with lower volatility provide more stable long-term returns
- Inverse volatility allocation helps reduce overall portfolio risk
- SIP investment benefits significantly from **long-term compounding**
- Increasing SIP amount annually accelerates wealth creation

---

## 📁 Project Structure
