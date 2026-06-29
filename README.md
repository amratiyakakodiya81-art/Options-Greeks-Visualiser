# Options Greeks Calculator & Visualiser
### By: Amartiya Kakodiya | IIT Kharagpur

## Overview
This project computes and visualises all 5 Options Greeks 
(Delta, Gamma, Theta, Vega, Rho) using the Black-Scholes 
pricing model built from scratch. Analyses how each Greek 
behaves across different stock prices and volatility levels 
through 2D plots, 3D sensitivity surfaces and Call vs Put 
comparison.

## Tools
Python | NumPy | Matplotlib | SciPy

## Methodology
1. Built Black-Scholes pricing formula from scratch
2. Derived all 5 Greeks analytically
3. Plotted Greeks vs Stock Price (2D)
4. Plotted Greeks vs Volatility (2D)
5. Built 3D sensitivity surfaces for Delta and Gamma
6. Compared Call vs Put Greeks side by side

## Key Results
- All 5 Greeks computed analytically for ATM option
- Delta: 0.6368 | Gamma: 0.0188 | Theta: -0.0176
- Vega: 0.3752 | Rho: 0.5323
- 3D surfaces reveal simultaneous sensitivity across 
  stock price and volatility dimensions
- Put-Call Parity verified across all Greeks

## Key Insights
- Gamma peaks at ATM — highest uncertainty around strike
- Theta is most negative ATM — time decay highest there
- Vega is identical for calls and puts
- Delta converges to 0.5 at high volatility for ATM options
