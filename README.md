# 📈 Bitcoin Market Sentiment & Trader Performance Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 🚀 Project Overview
This project explores the hidden correlation between **Bitcoin Market Sentiment (Fear & Greed Index)** and **Trader Profitability**. By analyzing over **26,000 high-frequency trades**, we uncovered behavioral patterns distinguishing "Whales" (Smart Money) from Retail Traders.

The analysis disproves the common "Buy the Fear" advice for small traders and proposes a data-backed **"Shorting in Fear"** strategy that historically yields **3x higher returns**.

---

## 📊 Key Findings (The "Alpha")

### 1. The "Retail Trap" 💀
* **Observation:** Retail traders (Small Size) aggressively **BUY** during 'Extreme Fear'.
* **Result:** This contrarian attempt fails, resulting in an average **loss of -$31 per trade**.
* **Insight:** Catching the "falling knife" is statistically a losing strategy for retail accounts.

### 2. The "Whale" Strategy 🐋
* **Observation:** Large volume traders (Whales) significantly increase their activity during 'Fear'.
* **Strategy:** Unlike retail, Whales tend to **Short Sell** during these periods.
* **Result:** This yields a massive average profit of **+$137.49 per trade**.

### 3. Long vs. Short Performance Table
| Market Sentiment | Buy (Long) Avg PnL | Sell (Short) Avg PnL | Winning Strategy |
| :--- | :--- | :--- | :--- |
| **Extreme Fear** | -$31.21 (Loss) | **+$39.26** | ✅ Short Sell |
| **Fear** | +$2.39 | **+$97.11** | ✅ Short Sell |
| **Greed** | -$15.01 (Loss) | **+$56.47** | ✅ Short Sell |
| **Extreme Greed** | +$20.40 | **+$70.28** | ✅ Short Sell |

---

## 🛠️ Tech Stack
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Data Source:** Hyperliquid Historical Data & Alternative.me Fear & Greed Index

---

## 📂 Project Structure
```text
├── Code/
│   └── main_analysis.py       # The main Python script for analysis
├── Data/
│   ├── historical_data.csv    # Raw trader data
│   └── fear_greed_index.csv   # Sentiment data
├── Images/                    # Generated charts (Heatmaps, Strategy Graphs)
└── Report/
    └── analysis_report.pdf    # Final detailed report

�‍💻 Author
**Anshu Kumar**
* [GitHub Profile](https://github.com/Anshu404)
