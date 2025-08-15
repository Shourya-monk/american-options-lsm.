American Option Pricing via Longstaff–Schwartz LSM
Overview

This project implements a robust framework for pricing American options using Monte Carlo simulation combined with the Longstaff–Schwartz Least Squares (LSM) regression method. It also compares Cox-Ross-Rubinstein (CRR) binomial tree convergence with LSM estimates to capture early exercise features accurately.

The project demonstrates advanced quantitative finance techniques, including stochastic modeling, risk-neutral valuation, option Greeks estimation, and sensitivity analysis.

Features

American Option Pricing using LSM Monte Carlo

CRR Binomial Tree price convergence comparison

Polynomial regression for continuation value estimation

High-precision pricing and standard error calculation

Sensitivity analysis across volatility, strike, and interest rate

Reproducible plots for convergence and posterior pricing

Technologies

Python 3

NumPy

Matplotlib

JSON for structured reports

Dataclasses for clean option specifications

Installation

Clone the repository:

git clone https://github.com/Shourya-Monk/american-options-lsm.git
cd american-options-lsm


Install dependencies:

pip install numpy matplotlib

Usage

Run the main script to generate option prices, plots, and a JSON report:

python american_options_lsm.py


Outputs:

CRR vs LSM convergence plot

Price estimates for American options

report.json with detailed pricing results

Project Structure
american-options-lsm/
│
├── american_options_lsm.py   # Main script
├── report.json               # Output JSON report
├── README.md                 # Project description
└── plots/                    # (Optional) saved figures

Results

High-precision American option prices

Visual comparison of CRR convergence vs LSM

Sensitivity insights for volatility, strike, and interest rates

Reliable standard errors for Monte Carlo estimates

References

Longstaff, F. A., & Schwartz, E. S. (2001). Valuing American Options by Simulation: A Simple Least-Squares Approach. Review of Financial Studies.

Cox, J. C., Ross, S. A., & Rubinstein, M. (1979). Option Pricing: A Simplified Approach. Journal of Financial Economics.
