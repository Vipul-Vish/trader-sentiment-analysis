# Trader Performance vs Market Sentiment Analysis

## 📊 Project Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear/Greed) and trader performance using historical trading data from Hyperliquid.

The goal is to understand how market emotions influence trading behavior and profitability.

---

## 📁 Dataset Used

1. **Market Sentiment Data**
   - Columns: Date, Classification (Fear / Greed / Extreme Fear / Extreme Greed / Neutral)

2. **Trader Data**
   - Includes: Account, Coin, Execution Price, Size, Side, Timestamp, Closed PnL, etc.

---

## 🛠️ Steps Performed

### 1. Data Cleaning
- Handled timestamps
- Converted date formats
- Checked missing values and duplicates

### 2. Data Merging
- Merged trader data with sentiment data on Date

### 3. Feature Engineering
- Daily PnL per trader
- Win rate calculation
- Average trade size
- Trade frequency per day
- Long/Short analysis

---

## 📈 Analysis Done

- Performance comparison across Fear vs Greed days
- Trade behavior changes based on sentiment
- Trader segmentation:
  - Frequent vs Infrequent traders
  - Consistent vs Inconsistent traders

---

## 🔑 Key Insights
- Trader performance varies significantly across market sentiment
- Trading activity increases during Greed phases
- Risk-taking behavior changes with sentiment shifts

---

## 📌 Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 🚀 How to Run
1. Clone repository
2. Install dependencies
3. Open `analysis.ipynb`
4. Run all cells

---
