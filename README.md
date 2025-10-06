# Geometric Brownian Motion & Random Walk – Stock Price Simulation

This repository contains Python notebooks demonstrating **stochastic models for stock price movements**.

## 📈 Projects
1. **GeometricBrownianMotion.ipynb**
   - Simulates stock price paths using the Geometric Brownian Motion model:
     \[
     S_t = S_0 e^{\left(\mu - \frac{1}{2}\sigma^2\right)t + \sigma W_t}
     \]
   - Includes calibration of drift (μ) and volatility (σ) from historical NIFTY50 data.
   - Visualizes multiple simulated price paths.

2. **RandomWalk.ipynb**
   - Simulates random walk price paths:
     - Without drift (pure symmetric walk)
     - With upward drift using biased probabilities
   - Compares how drift affects long-term price trends.

## 🛠 Tech Stack
- Python
- NumPy
- Pandas
- Matplotlib

> ⚠️ **Disclaimer:** Educational use only — not investment advice.
