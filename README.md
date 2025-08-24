
# AI-in-Trading-Centrale

## 📌 Overview

This repository contains research notebooks exploring advanced concepts in **algorithmic trading** and **market microstructure modeling**.
The focus is on simulating and analyzing financial market dynamics using **stochastic processes** and **agent-based models**.

---

## 📂 Contents

### 1. `Analyse_modele_zero-intelligence.ipynb`

This notebook explores the **Zero-Intelligence Trader Model**, a foundational agent-based market model introduced by Gode and Sunder (1993).
The model assumes traders submit orders **randomly** without strategic optimization, allowing us to study the impact of **market structure** and **price formation rules** without behavioral biases.

**Key features:**

* Simulation of a continuous double auction with zero-intelligence agents.
* Analysis of order book dynamics and price evolution.
* Comparison of simulation results to theoretical expectations.
* Insights into how market efficiency can emerge without rational behavior.

---

### 2. `simulation_Hawkes_process.ipynb`

This notebook focuses on simulating **Hawkes Processes**, a class of **self-exciting point processes** widely used in **high-frequency trading** and **order book modeling**.

**Key features:**

* Mathematical formulation of univariate and multivariate Hawkes processes.
* Simulation of arrival times for market events (e.g., trades, order placements).
* Analysis of clustering effects and market activity bursts.
* Potential applications in modeling order flow and predicting short-term volatility.

---

## 🎯 Research Relevance

Both models serve as **building blocks** for more complex algorithmic trading research:

* The **Zero-Intelligence Model** provides a benchmark for market behavior without strategic agents.
* The **Hawkes Process** captures the temporal clustering observed in real financial markets.

These methods are valuable for:

* Understanding market microstructure.
* Designing simulation environments for **reinforcement learning agents**.
* Stress-testing trading strategies under different market conditions.

---

## 📦 Requirements

```bash
pip install numpy pandas matplotlib
pip install statsmodels
pip install tick  # For Hawkes process simulation
```


If you want, I can also **add diagrams** to visually show how the Zero-Intelligence model and Hawkes process work, so the README is more engaging on GitHub.
Do you want me to make those?
