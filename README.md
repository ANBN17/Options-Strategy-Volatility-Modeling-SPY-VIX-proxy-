# Options-Strategy-Volatility-Modeling-SPY-VIX-proxy-
Modeled option payoffs and Greeks using Black–Scholes, analyzed implied versus realized volatility using a VIX-based proxy, and evaluated volatility risk premium dynamics through a systematic ATM straddle backtest.

Project 4: Options Strategy & Volatility Modeling

This project explores the relationship between implied volatility and realized volatility and its implications for options-based trading strategies. Using SPY as the underlying asset and the VIX index as a proxy for implied volatility, the project estimates realized volatility from historical returns and evaluates the resulting volatility risk premium (IV − RV) across market regimes.

A full Black–Scholes framework is implemented to price European ATM call and put options and compute key Greeks, including Delta, Gamma, Vega, and Theta, enabling sensitivity analysis to changes in price, volatility, and time decay. Building on this framework, a simplified 30-day ATM long straddle strategy is backtested, where option premiums are set using implied volatility and payoffs are settled at intrinsic value at expiration.

The strategy is evaluated using normalized returns, cumulative equity curves, drawdowns, and volatility regime analysis. This project demonstrates core options-market intuition, volatility modeling, and risk–reward assessment consistent with professional options trading and quantitative derivatives research.

Key Features

Black–Scholes option pricing and Greeks computation

Realized volatility estimation from historical returns

Implied volatility proxy using VIX

Volatility risk premium (IV − RV) analysis

Systematic ATM straddle backtest

Equity curve, drawdown, and Greeks visualization
