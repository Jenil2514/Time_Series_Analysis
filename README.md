# Time Series Analysis of Sunspot Activity

## Overview

This repository contains a detailed time series analysis of **monthly mean sunspot** data, investigating the long-term behavior and periodic nature of solar activity. The analysis includes stationarity testing, autocorrelation analysis, time series decomposition, and cross-correlation analysis with Earth's surface temperature anomalies.

## Project Description

Sunspots are temporary phenomena on the Sun’s photosphere, and their count can provide valuable insights into solar cycles and their potential impacts on Earth’s climate. This project aims to:
- Analyze sunspot data for temporal trends and seasonal patterns.
- Perform stationarity and autocorrelation analysis to understand underlying dynamics.
- Decompose the time series into trend, seasonal, and residual components.
- Investigate the relationship between sunspot activity and global temperature anomalies using cross-correlation analysis.

## Dataset

The sunspot data used in this analysis is publicly available and can be accessed from the SILSO (Sunspot Index and Long-term Solar Observations) official database:

🔗 [SILSO Data Files – Royal Observatory of Belgium](https://www.sidc.be/SILSO/datafiles)

<p align="center">
  <img src="https://github.com/user-attachments/assets/040e0026-ced1-4cf4-afaf-3ce4005c4a00" width="600"/>

</p>
  <p align="center"><em>Figure 1: Data Visualization </em></p>

## Key Steps and Methods

1. **Data Exploration**: 
   - Histogram visualization of sunspot data to evaluate distribution (skewness and kurtosis).
   - Assessment of statistical metrics like mean, variance, and standard deviation.

2. **Stationarity Analysis**:
   - Use of rolling mean and standard deviation.
   - First-order differencing to stabilize the mean and achieve stationarity.

<p align="center">
  <img src="https://github.com/user-attachments/assets/ec631ecf-69f8-4725-bc3f-6ea1efc4c201" width="500"/>
</p>
<p align="center"><em>Figure 2: After differencing Rolling mean and standard deviation for stationarity analysis.</em></p>


3. **Autocorrelation Function (ACF)**:
   - Computation of autocorrelations at various lags to examine cyclical behavior and seasonal effects.

<p align="center">
  <img src="https://github.com/user-attachments/assets/01a76aed-3179-4096-9d89-c9e4d2eb7dc7" width="500"/>

</p>
  <p align="center"><em>Figure 3: Autocorrelation function (ACF) highlighting periodic patterns in sunspot activity.</em></p>

4. **Time Series Decomposition**:
   - Decomposition into trend, seasonal, and residual components to isolate underlying patterns.

<p align="center">
  <img src="https://github.com/user-attachments/assets/7e45029d-2efa-4361-a110-a28cbc9f026a" width="500"/>
  
</p>
<p align="center"><em>Figure 4: Time series decomposition into trend, seasonal, and residual components.</em></p>

5. **Cross-Correlation Analysis**:
   - Analysis of correlations between sunspot numbers and global temperature anomalies, as well as atmospheric CO2 concentrations.

<p align="center">
  <img src="https://github.com/user-attachments/assets/25811c30-e594-4de2-8bfb-4f7772bb88d1" width="500"/>
</p>
<p align="center"><em>Figure 5: Cross-correlation between sunspot numbers and global temperature anomalies.</em></p>

## Results

- The sunspot data exhibits clear cyclical trends consistent with the 11-year solar cycle.
- Cross-correlation analysis revealed weak correlations between sunspot activity and temperature anomalies, suggesting other factors, such as atmospheric CO2, may play a larger role in influencing global temperature.
