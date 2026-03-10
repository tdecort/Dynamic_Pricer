# 💻 Dynamic Pricer
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)

A real-time quantitative finance web application built with Dash and Plotly. This tool allows users to dynamically price and structure complex financial derivatives (Partially Principal Protected Notes and Airbag Notes) by connecting directly to live market option chains.

## ✨ Key Features

* **Live Market Data Integration:** Fetches real-time stock prices, dividend yields, risk-free rates, and option chains (bid/ask/IV) via the Yahoo Finance API (`yfinance`).
* **Advanced Quantitative Engine:** * Calculates theoretical option prices using the **Black-Scholes** model.
    * Simulates underlying asset trajectories using **Monte Carlo** simulations.
    * Solves for optimal commercial parameters based on a target banking margin.
* **Structured Products Supported:**
    * **PPPN (Partially Principal Protected Note):** Capital guarantee with upside participation.
    * **Airbag Note:** Optimized participation with downside protection up to a specific barrier.
* **Interactive 3D Risk Surfaces:** Visualizes Mark-to-Market (MtM) valuations across varying spot prices and time to maturity.
* **"Cyber-Quant" UI:** A modern, dark-themed Glassmorphism interface built with Dash.

## 📸 Screenshots
<img width="2522" height="820" alt="image" src="https://github.com/user-attachments/assets/b2181ef6-823a-4563-8b55-3e583350d15a" />

<img width="2505" height="1023" alt="image" src="https://github.com/user-attachments/assets/4ae82cc1-ae70-4a9f-a9ea-740fbb757f7c" />

<img width="2507" height="1032" alt="image" src="https://github.com/user-attachments/assets/fb8d0b89-6d33-4b0b-ba56-a5bc97519245" />


## 🚀 Installation & Setup

1. **Install the latest version of Python and the packages**
  python -m pip install dash dash-bootstrap-components plotly pandas numpy scipy yfinance
2. **run using :"python app.py"**
  
