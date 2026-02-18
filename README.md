Cross-Border Payments Reconciliation & FX Impact Analysis
Overview

This project simulates a cross-border payments infrastructure workflow and demonstrates transaction-level reconciliation, KPI monitoring, and FX revenue sensitivity analysis using Python and SQLite.

The goal was to model how a fintech platform processes USD pay-ins, converts them to local currency payouts, earns revenue through FX spread, and detects settlement mismatches through structured reconciliation logic.

What I Built

Generated 5,000 synthetic cross-border transactions

Built SQL reconciliation views comparing expected vs. actual payouts

Implemented mismatch detection logic with configurable thresholds

Created monthly operational KPIs (volume, fees, mismatch rate)

Modeled platform revenue derived from FX spread

Conducted FX sensitivity analysis to assess revenue exposure

Applied statistical anomaly detection (z-score)

Tech Stack

Python (pandas, numpy)

SQLite

SQL

Matplotlib / Seaborn

Google Colab

Key Insights

Reconciliation logic can detect payout discrepancies before impacting reporting

FX spread revenue is sensitive to rate movement, creating margin risk

Transaction-level monitoring improves operational visibility

Automated KPI reporting reduces manual reconciliation effort

Files

notebook.ipynb — full analysis workflow

mural_pay_demo.db — SQLite database

monthly_kpi.csv — aggregated performance summary

mismatches_sample.csv — reconciliation exceptions

fx_revenue.csv — FX revenue analysis
