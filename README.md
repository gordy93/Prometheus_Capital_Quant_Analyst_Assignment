# Prometheus_Quant_Analyst_Assignment
This repository contains the solution to the quantitative finance assignment by Prometheus Capital. With Prometheus providing the dataset used in the analysis, but all code, modeling choices and implementation in this repository are not related to Prometheus Captial.

The project presents an empirical volatility forecasting methodology aimed at producing one-month-ahead equity volatility estimates using high-frequency price data and a HAR-RV (Heterogeneous AutoRegressive Realized Volatility) regression framework.

**Project Summary**

1. Clean and align high-frequency price data.
2. Compute intraday log returns.
3. Build realized variance (RV) from intraday returns.
4. Construct HAR features (daily, weekly and monthly components).
5. Fit the HAR-RV regression model.
6. Generate one-month-ahead volatility forecast path.
7. Report and visualize realized vs. forecasted volatility.

**Output**

For each symbol _i_, the notebook produces:
1. Daily realized variance and realized volatility series.
2. HAR features (daily, weekly and monthly RV components).
3. One-month-ahead predicted volatility path.
4. Summary statistics of predicted volatility.
5. Plots comparing historical realized volatility and forecasted volatility.
