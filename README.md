#  Trader Behavior Insights – Junior Data Scientist Assignment

This project explores the relationship between **Bitcoin market sentiment** (Fear vs Greed Index) and **trader behavior** using historical data from Hyperliquid.

##  Objective

To analyze how market sentiment influences:

-  Trader profitability (`closed_pnl`)
-  Risk-taking behavior (`start_position` used as a proxy for missing `leverage`)
-  Trading patterns across different sentiment phases (Fear vs Greed)

---

##  Dataset Overview

### 1. Fear & Greed Sentiment Index
- Columns: `Date`, `Classification` (Fear or Greed)

### 2. Hyperliquid Trader Data
- Columns: `timestamp`, `start_position`, `closed_pnl`, `size_usd`, etc.

---

##  Key Insights

- Trader **profits** tended to vary based on market sentiment.
- Larger **start positions** were generally taken during "Greed" periods.
- Correlation analysis revealed relationships between position size, risk, and profit.

---

##  Visualizations Included

-  Boxplots of Profit/Loss during Fear vs Greed
- Boxplots of Start Position vs Market Sentiment
-  Correlation Heatmap of key metrics

---

##  Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn

---

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Rupali-pragati/trader-behavior-insights.git
