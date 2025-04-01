# 📈 NVDA Moving Average Strategy

This project implements a simple **moving average crossover trading strategy** on NVIDIA (NVDA) stock using Python and historical data.

## 🔍 Strategy Logic

- **Short-term MA**: 50-day moving average  
- **Long-term MA**: 200-day moving average  
- **Buy signal**: 50-MA crosses above 200-MA (Golden Cross)  
- **Sell signal**: 50-MA crosses below 200-MA (Death Cross)  

Backtest simulates $10,000 portfolio with trade-on-signal logic.

## 💻 Tech Stack

- Python  
- `yfinance` to fetch historical data  
- `pandas` for data wrangling  
- `matplotlib` for visualization  
- `numpy` for calculations  

## 📊 Output

- Buy/sell signals visualized on price chart  
- Portfolio value over time  
- Strategy vs Buy & Hold performance  

<img src="https://i.imgur.com/hh9XD3y.png" width="500"/>

## ▶️ How to Run

```bash
git clone https://github.com/HaoyuTu/NVDA-project.git
cd NVDA-project
pip install -r requirements.txt
jupyter notebook nvda_strategy.ipynb
