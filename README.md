# 📊 Trader Performance vs. Market Sentiment Analysis

This project explores the relationship between **Bitcoin market sentiment** (Fear & Greed Index) and **trader performance** on the Hyperliquid platform. The goal is to uncover patterns that can drive smarter trading decisions.

---

## 📁 Datasets Used

### 🧾 Bitcoin Market Sentiment Dataset
- **Columns**: `date`, `classification` (Fear, Greed, etc.)
- **Source**: Fear & Greed Index values over time

### 🧾 Historical Trader Data (Hyperliquid)
- **Columns include**: `Account`, `Execution Price`, `Size USD`, `Side`, `Closed PnL`, `Leverage`, `Timestamp IST`, etc.
- **Source**: Trade-level execution logs

---

## 🧠 Objective

To analyze how **trader performance metrics** (like PnL, trade volume, and active accounts) vary across different **market sentiment states**, and identify trends that could inform trading strategy development.

---

## ✅ Key Steps

### 📌 Data Preprocessing
- Convert timestamps and align both datasets on date
- Merge market sentiment labels with trade records

### 📌 Analysis
- Group trader data by sentiment classification
- Compute key metrics: average PnL, total traded volume, number of unique traders

### 📌 Visualization
- Create bar plots to illustrate the effect of sentiment on performance

---

## 📈 Sample Insights

- Traders recorded **higher average profits during Extreme Greed**.
- **Fear days** had the **highest total trading volume**, indicating increased activity.
- **Extreme Fear and Neutral** days showed **lower profitability** on average.
