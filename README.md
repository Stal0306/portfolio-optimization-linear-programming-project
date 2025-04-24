# portfolio-optimization-linear-programming-project

This repository contains my final MATH 441 project, where I built a portfolio optimization model that allocates daily capital across stocks, bonds, and cryptocurrencies.

The core notebook, [`KDEs.ipynb`](../src/KDEs.ipynb), performs:
- Kernel Density Estimation (KDE) on historical price data to estimate expected closing prices
- Risk calculation using Mean Absolute Deviation (MAD)
- Daily portfolio optimization using Linear Programming
- Evaluation of directional accuracy and feature importance

## 🗂️ Repository Structure

- **`data/`** – Raw price data for each asset (CSV format)
- **`src/`** – Main Jupyter notebook with end-to-end pipeline
- **`reports/`** – Final PDF reports with results and methodology
- **`requirements.txt`** – Required Python packages
- **`.gitignore`** – Ignored files and folders
- **`LICENSE`** – Project license (MIT or your choice)

## 🚀 Quick Start

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

   ```
