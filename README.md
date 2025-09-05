# Pairs Trading Using Cointegration

This repository contains the resources and code necessary to understand and implement a **Pairs Trading strategy using cointegration**. It includes both a Jupyter Notebook for hands-on implementation and a PowerPoint presentation that explains the underlying concepts and methodology.

---

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Results](#results)

---

## Introduction
Pairs trading is a **market-neutral trading strategy** that seeks to profit from the relative movement between two correlated assets. By identifying pairs that share a **long-term equilibrium relationship (cointegration)**, traders can build more reliable trading signals compared to simple correlation-based approaches.  

This project demonstrates how to:
- Collect and prepare financial data
- Identify cointegrated asset pairs using the **Engle-Granger test**
- Generate trading signals
- Backtest the strategy to evaluate performance

---

## Project Structure

- [Pairs_Trading_Cointegration.ipynb](https://github.com/diya17agarwal/PairsTrading-and-Cointegration-Strategy/blob/main/PairsTrading.ipynb): The Jupyter notebook containing the code for the pairs trading strategy.
- [Pairs_Trading_Presentation.pptx](https://github.com/diya17agarwal/PairsTrading-and-Cointegration-Strategy/blob/main/Pairs%20Trading%20and%20Cointegration%20Strategy.pdf): A PowerPoint presentation explaining the concepts and methodology of the pairs trading strategy using cointegration.

---

## Dependencies
Make sure you have the following Python libraries installed:

- `numpy`
- `pandas`
- `statsmodels`
- `matplotlib`
- `seaborn`

---

## Usage
Open the Jupyter notebook `Pairs_Trading_Cointegration.ipynb` to explore the code and run the cells step-by-step. The notebook covers the following steps:

1. **Data Collection**: Importing and preparing the data for analysis.
2. **Cointegration Testing**: Performing the Engle-Granger cointegration test to identify cointegrated pairs.
3. **Signal Generation**: Generating trading signals based on the cointegration relationship.
4. **Backtesting**: Evaluating the performance of the pairs trading strategy using historical data.

---

## Results
The results of the pairs trading strategy, including the performance metrics and visualizations, are documented in the Jupyter notebook. Additionally, the PowerPoint presentation provides a detailed explanation of the methodology and findings.
