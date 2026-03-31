# Prometheus_Quant_Analyst_Assignment
This repository contains the solution to the quantitative analyst assignment from Prometheus Capital. Prometheus provided the dataset used in the analysis; however, all code, modeling choices and implementation are not affiliated with Prometheus Capital.

The project presents an empirical volatility forecasting methodology aimed at producing one-month-ahead equity volatility estimates using high-frequency price data and a HAR-RV (Heterogeneous AutoRegressive Realised Volatility) regression framework.

**Documentation**

A full write-up of the methodology, assumptions and results is included in the repository:

Quant_assignment_documentation.pdf - documentation report.

**Project Summary**

1. Clean and align high-frequency price data.
2. Compute intraday log returns.
3. Build realised variance (RV) from intraday returns.
4. Construct HAR features (daily, weekly and monthly components).
5. Fit the HAR-RV regression model.
6. Generate one-month-ahead volatility forecast path.
7. Report and visualise realised vs. forecasted volatility.

**Output**

For each stock _i_, the notebook produces:
1. Daily realised variance and realised volatility series.
2. HAR features (daily, weekly and monthly RV components).
3. One-month-ahead predicted volatility path.
4. Summary statistics of predicted volatility.
5. Plots comparing historical realised volatility and forecasted volatility.
