# 📊 OTC Collateral Manager

A Python-based simulation of an OTC derivatives collateral 
management system, as used in bank Middle Office operations.

## Overview

This project simulates a complete collateral management workflow
covering pricing, margin calls, eligibility checks, portfolio 
reconciliation, risk management and reporting.

## Modules

| Module | Description |
|--------|-------------|
| Pricing | IRS, FX Forwards, Vanilla Options (Black-Scholes) |
| Greeks | Delta, Gamma, Vega, Theta, Rho |
| Margin Calls | CSA rules — Threshold, MTA, Variation Margin |
| Eligibility | EMIR compliance + haircut calculation |
| Reconciliation | Break identification and prioritization |
| Risk | Historical VaR + Expected Shortfall |
| Stress Tests | Historical and adverse scenarios |
| Reporting | Interactive Plotly dashboard |

## Regulatory Framework

- **EMIR** — European Market Infrastructure Regulation
- **Basel III** — Capital and liquidity requirements
- **CSA/ISDA** — Credit Support Annex framework

## Tech Stack

- Python 3.13
- Pandas, NumPy, SciPy
- yFinance (market data)
- Plotly (interactive charts)
- Matplotlib, Seaborn

## Installation

```bash
git clone https://github.com/maelramet/otc-collateral-manager
pip install -r requirements.txt
```

## Author

**Maël RAMET**
Master Finance de Marché — Université Lyon 2
[LinkedIn](https://linkedin.com/in/maelramet)
