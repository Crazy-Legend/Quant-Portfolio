🎲 Monte Carlo Stock Simulation (Single & Multi-Stock)

Simulating single and multiple stock price paths using real market data and Geometric Brownian Motion (GBM).
This project extends Monte Carlo simulation from one stock (AAPL) to multiple real stocks — visualizing how randomness and volatility shape different future outcomes.

🚀 Overview

This repository contains two key simulations:

🧩 1. Single Stock Monte Carlo (AAPL)

Models Apple’s stock (AAPL) over one year (252 trading days) using:

Historical mean return and volatility

50+ simulated price paths

Mean trajectory and uncertainty range visualization

🧩 2. Multi-Stock Monte Carlo

Extends the single-stock model into a multi-asset simulation, modeling multiple real stocks (e.g., AAPL, MSFT, GOOGL, AMZN, NVDA) simultaneously.
Each stock uses its own historical parameters (μ, σ), revealing how volatility drives divergence between assets.

📘 What I Learned

Fetching and processing real financial data with yfinance

Calculating daily returns, mean, and volatility

Understanding and implementing Geometric Brownian Motion (GBM)

𝑆
𝑡
=
𝑆
𝑡
−
1
×
𝑒
(
𝜇
−
0.5
𝜎
2
)
+
𝜎
⋅
𝑁
(
0
,
1
)
S
t
	​

=S
t−1
	​

×e
(μ−0.5σ
2
)+σ⋅N(0,1)

Running Monte Carlo simulations to model randomness

Visualizing uncertainty, mean, and spread with Matplotlib

Scaling from single-stock to multi-stock environments

Building intuition on volatility, randomness, and risk

🧠 Key Concepts
Concept	Description
Monte Carlo Simulation	Repeated random sampling to estimate possible outcomes
Geometric Brownian Motion (GBM)	Continuous-time stochastic process modeling stock prices
Volatility (σ)	Measure of how much returns fluctuate
Mean Return (μ)	Average expected daily return
Compounding	Captures exponential growth over time
Portfolio Dynamics	How multiple assets evolve under correlated randomness
🧩 Tech Stack

🐍 Python

🔢 NumPy

📊 Matplotlib

💹 yfinance

☁️ Google Colab

🗂️ GitHub (documentation & workflow)

📊 Example Outputs
📈 Single Stock Simulation (AAPL)

Simulated price paths for Apple (AAPL) over 252 trading days.
Shows the spread of 50 random paths, mean line, and uncertainty band.

📉 Multi-Stock Simulation

Simulates multiple real-world stocks together (AAPL, MSFT, GOOGL, AMZN, NVDA).
Visualizes how different volatilities lead to divergent outcomes over time.

🧭 Next Steps

Introduce correlation and covariance between assets

Move into Stage 7: Portfolio Simulation and Optimization

Implement Markowitz Efficient Frontier and Sharpe Ratio

Add volatility clustering and stress testing

✨ Author

Viraj Nigwekar
Aspiring Quant Developer | ORFE Path | Python & Quant Finance Learner
