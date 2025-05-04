# Applied Master Project: Portfolio Insurance – OBPI vs CPPI

## Group Members

- Ugo ESCATO  
- Aurore CLEVENOT  
- Ludovic VINCENTI  

## Supervisor

**Laurent DEVILLE** – EDHEC Business School

---

## Overview

This repository contains the research and implementation for our Applied Master Project on portfolio insurance strategies. The focus is on comparing **Option-Based Portfolio Insurance (OBPI)** and **Constant Proportion Portfolio Insurance (CPPI)** applied to **Bitcoin** as the underlying asset.

We assess the **risk**, **performance**, and **practical application** of these strategies for investors. The analysis includes both **historical backtesting** and **Monte Carlo simulations**, evaluating performance across varying market regimes and conditions.

---

## Project Scope

### 1. Historical Data Analysis

- Backtesting OBPI and CPPI strategies using historical **Bitcoin data (2016–2023)**
- Evaluation across market regimes:
  - Bull markets  
  - Bear markets  
  - Sideways (flat) markets  
  - Low-volatility periods  
  - High-volatility periods

### 2. Simulated Framework

- Monte Carlo simulations to assess strategy robustness using:
  - Geometric Brownian Motion (GBM)
  - Stochastic Volatility Model
  - Merton Jump Diffusion Model

### 3. Additional Considerations

- Sensitivity analysis on:
  - Rebalancing frequency  
  - Volatility levels  
  - Strike/floor levels  
  - CPPI multiplier values
    
- Strategy enhancements:
  - Maximum-Drawdown CPPI
  - Leveraged OBPI
