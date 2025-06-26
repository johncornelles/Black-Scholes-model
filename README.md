
```markdown
# 📈 Black-Scholes Option Pricing Model

This project implements a complete Black-Scholes option pricing model from scratch using Python. It includes:

- European call and put option pricing
- Greeks (Delta, Gamma, Vega, Theta, Rho)
- Dividend-adjusted Black-Scholes pricing
- Monte Carlo simulation for option valuation
- Implied volatility estimation
- Ready-to-run notebook format

---

## 🧠 What's Inside

### ✅ Black-Scholes Formula

Mathematically correct closed-form solution for pricing European options:

- Call:  
 
  C = S \Phi(d_1) - K e^{-rT} \Phi(d_2)


- Put:  

  P = K e^{-rT} \Phi(-d_2) - S \Phi(-d_1)


### ✅ Greeks

- 📐 **Delta** – sensitivity to price
- 📉 **Gamma** – curvature (second derivative)
- 🔊 **Vega** – sensitivity to volatility
- ⏳ **Theta** – time decay
- 🏦 **Rho** – sensitivity to interest rates

### ✅ Dividends

Supports continuous dividend-paying assets via `q` (dividend yield).

### ✅ Monte Carlo Simulation

Simulates option prices using risk-neutral GBM with thousands of paths.

### ✅ Implied Volatility Estimation

Numerically solves for implied volatility using Brent’s method.

---
