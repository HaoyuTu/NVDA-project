# NVDA Moving Average Crossover Strategy

This project implements a basic **moving average crossover trading strategy** for NVIDIA (NVDA) stock using Python. The goal is to simulate and compare the performance of two strategies:

1. **MA50/MA200 Crossover Strategy** (Classic golden/death cross)
2. **MA20/MA50 Crossover Strategy** (Shorter-term trend-following)

Both strategies are benchmarked against a **Buy & Hold** baseline.

---

## 💡 Why this project?

I’m passionate about data-driven decision making and wanted to explore how simple technical indicators perform when applied to real historical data. This also served as an opportunity to practice:
- Financial data collection and manipulation
- Strategy logic design
- Portfolio simulation and performance analysis
- Data visualization and storytelling

---

## 📈 Strategy Logic

- **Buy signal**: Short-term MA crosses **above** long-term MA (Golden Cross)
- **Sell signal**: Short-term MA crosses **below** long-term MA (Death Cross)
- **Simulation**: Starts with $10,000, trades 1:1 on each signal

---

## 📊 Tools Used

- `yfinance`: Download historical stock data
- `pandas` & `numpy`: Data wrangling and calculations
- `matplotlib`: Strategy and signal visualization
- `quantstats`: Generate full performance metrics report (optional)

---

## 🔍 Key Findings

- MA20/50 often reacts faster but may lead to more false signals
- MA50/200 is more conservative, trades less frequently
- Both strategies were compared against Buy & Hold to observe long-term value impact

---

## 📂 Files Included

- `trading_nvda_like_a_pro.ipynb`: Main notebook
- `nvda_strategy_report.html`: (Optional) Generated QuantStats performance report
- `README.md`: You're reading it!


---

Feel free to fork this repo, try your own tweaks, or contact me if you’re working on similar projects!
