# Prometheus_Quant_Analyst_Assignment
This repository contains the solution to the quantitative analyst assignment from Prometheus Capital. Prometheus provided the dataset used in the analysis; however, all code, modeling choices and implementation are not affiliated with Prometheus Capital.

The project presents an empirical volatility forecasting methodology aimed at producing one-month-ahead equity volatility estimates using high-frequency price data and a HAR-RV (Heterogeneous AutoRegressive Realised Volatility) regression framework.

**Documentation**

A full write-up of the methodology, assumptions and results is included in the repository:

`Quant_assignment_documentation.pdf` 

**Project Summary**

* Clean and align high-frequency price data.
* Compute intraday log returns.
* Build realised variance (RV) from intraday returns.
* Construct HAR features (daily, weekly and monthly components).
* Fitt the HAR-RV regression model.
* Generate one-month-ahead volatility forecast path.
* Report and visualise realised vs. forecasted volatility.

**Output**

For each stock _i_, the notebook produces:
* Daily realised variance and realised volatility series.
* HAR features (daily, weekly and monthly RV components).
* One-month-ahead predicted volatility path.
* Summary statistics of predicted volatility.
* Plots comparing historical realised volatility and forecasted volatility.

_Google drive environment is essential to run this code_
