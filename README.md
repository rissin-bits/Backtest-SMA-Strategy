Trading Strategy Backtesting:

Overview:
This project implements and evaluates a trading strategy using historical stock market data.
The goal is to analyze performance metrics such as returns, Sharpe ratio, and drawdowns, while also visualizing strategy behavior compared to a benchmark (e.g., S&P 500).


Features:
Data collection via Yahoo Finance (yfinance)
Technical indicators (Moving Average)
Signal generation (buy/sell rules)
Backtesting engine


Performance metrics:
1. Total Returns
2. Annualized Returns
3. Sharpe Ratio
4. Maximum Drawdown
5. CAGR
6. Alpha (excess returns)


Visualization of:
1. Equity Curve
2. Drawdown Curve
3. PnL Per Trade
4. Cumulative Returns vs Benchmark (S&P 500)
5. Risk/Reward Scatter (Holding Period vs PnL %)
6. Win/Loss Pie Chart
7. Common inferences from all Graphs

Tech Stack:
Python (3.8+)


Libraries:
yfinance – stock data
pandas / numpy – data processing
matplotlib – visualization
scikit-learn (optional, for ML-based signals)
plotly - interactive, dynamic graphs


Project Structure:

├──Backtest_SMA_Strategy #Contains everything

├── data                 # Raw or processed stock data

├── graphical-analysis   # Contains various plots used for analysis

├── notebooks            # Jupyter notebooks with analysis  

├── results/             # Performance reports & plots


Usage:
1. Clone repository:
git clone https://github.com/rissin-bits/trading-strategy-backtest.git
cd trading-strategy-backtest
2. Run backtest:
python notebooks/backtest.py
3. View results:
Results will be displayed when you run the backtest
Still, the results have been compiled under branches graphical-analysis and results


Future Improvements:
1. Add more technical indicators (RSI, Bollinger Bands)
2. Portfolio-level backtesting (multiple assets)
3. Transaction costs & slippage modeling
4. Hyperparameter optimization for strategy tuning
5. Deploy as a web app (Streamlit/Dash)


Contributing:
Pull requests are welcome! Please open an issue to discuss changes before submitting.

License:
This project is licensed under the MIT License.

Happy contributing and growing!
