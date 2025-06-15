# options_pricing
applying multiple option pricing models to price european call and put options
# 📈 Dynamic Delta Hedging & Option Pricing Models

This project is a comprehensive exploration of **option pricing**, **implied volatility**, and **dynamic delta hedging** using both **monte carlo simulation** and **binomial tree models**. It incorporates concepts from financial engineering and derivatives pricing, using Python to simulate strategies and visualize performance under different conditions.

---

## 📚 Key Concepts Covered

### 1. **Historical Volatility Estimation**
- Using log returns of closing stock prices to estimate rolling volatility.
- Annualizing the volatility using a 252 trading-day adjustment.

# 📈 Options Pricing & Hedging Toolkit

This project explores various computational finance techniques to price and hedge European options using Python. It covers theoretical models like Black-Scholes, Binomial Trees, and Monte Carlo simulation, along with real-world applications like dynamic delta hedging and volatility estimation.

---

## 🚀 Key Models & Techniques

### 1. **Black-Scholes Model**
- Closed-form solution for pricing European call and put options.
- Inputs: current price (S), strike (K), time to expiry (T), risk-free rate (r), volatility (σ), and option type (call/put).
- Also used to calculate **Greeks** like delta and vega for hedging.

### 2. **Geometric Brownian Motion (GBM)**

Simulates stock price paths assuming continuous compounding, lognormal distribution.

Forms the basis for Monte Carlo simulations and dynamic delta hedging.
### 3. **Monte Carlo Simulation**

Simulates thousands of GBM paths to approximate expected payoffs.

Helps estimate the price of options under uncertain and stochastic conditions.
### 4. **Binomial Tree Models**

Discrete-time alternatives to BS model:

Cox-Ross-Rubinstein (CRR): Skewed probabilities, recombining tree.

Jarrow-Rudd (JR): Equal probabilities, used for academic comparisons.

Converges to Black Scholes price with enough steps.
### 5. **Dynamic Delta Hedging**

Tracks and adjusts the portfolio's delta exposure over time to remain neutral.

Simulates option and stock P&L over time as delta is rebalanced weekly.

Cashflows, interest earned, and hedging error are tracked in each simulation.
