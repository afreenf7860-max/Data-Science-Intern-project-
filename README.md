# 📊 Trader Performance vs Market Sentiment Analysis

## Data Science Intern – Round 0 Assignment

### 👩‍💻 Author: Afreen Fatima

---

## 🎯 Objective

This project analyzes how Bitcoin Fear/Greed market sentiment impacts trader behavior and performance on Hyperliquid.

The goal is to:
- Compare trader profitability across Fear vs Greed periods
- Identify behavioral changes
- Segment traders into meaningful categories
- Propose actionable trading strategies

---

## 📂 Datasets Used

1. Bitcoin Fear/Greed Index Dataset  
2. Hyperliquid Historical Trader Data  

---

## ⚙️ Methodology

### Part A – Data Preparation
- Loaded and explored both datasets
- Checked missing values and duplicates
- Converted timestamps to daily format
- Merged datasets on Date
- Created key metrics:
  - Daily PnL per account
  - Win rate
  - Average trade size
  - Leverage distribution
  - Trade frequency
  - Long/Short ratio

---

### Part B – Sentiment vs Trader Behavior Analysis

Compared trader performance during Fear vs Greed days using:
- Average PnL
- Win rate
- Trade frequency
- Leverage usage
- Long/Short bias

Segmented traders into:
- High vs Low leverage traders
- Frequent vs Infrequent traders
- Consistent vs Inconsistent performers

---

## 📊 Key Insights

(Replace these with your actual findings)

- Traders used higher leverage during Greed periods.
- Win rate was more stable during Fear periods.
- Trade frequency increased significantly during Greed sentiment.
- Long positions increased during Greed days.
- High leverage traders showed larger PnL volatility.

---

## 🚀 Strategy Recommendations

**Strategy 1:**  
During Greed periods, cap leverage above a certain threshold to reduce drawdown risk.

**Strategy 2:**  
Encourage higher trade participation during Fear periods only for consistent performers.

---

## 🛠️ How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
```

---

## 📌 Repository Structure

```
Data_Science_Intern_project.ipynb
README.md
```
