# Time Series Analysis in R

This repository showcases my understanding of time series analysis using R, demonstrated through a series of challenging assignments. It contains eight key files—four for assignment questions and four for their corresponding solutions—each focusing on real-world datasets and applying advanced statistical and spectral analysis techniques.


## Assignment Breakdown

### **Assignment 1: Exchange Rates & CO₂ Trends**
- **Files:** `a1_questions.R` and `a1_solutions.R`
- **Overview:**  
  - **Exchange Rates:** Analysis of daily Canadian/U.S. dollar exchange rates using log transformations, differencing, correlograms, and periodograms to evaluate autocorrelation, spectral properties, and the random walk hypothesis.
  - **CO₂ Trends:** Investigation of average monthly atmospheric CO₂ concentrations at Mauna Loa. This includes spectral analysis to identify seasonal peaks and detrending to emphasize seasonality.
- **Key Techniques:**  
  - Data transformation (log scale, differencing)  
  - Autocorrelation analysis via correlograms and periodograms  
  - Trend estimation and detrending  
  - Spectral density estimation

### **Assignment 2: Stationarity Testing & Tidal Analysis**
- **Files:** `a2_questions.R` and `a2_solutions.R`
- **Overview:**  
  - **Exchange Rate Stationarity:** Application of the Augmented Dickey-Fuller (ADF) test to assess unit roots, along with Ljung-Box and Bartlett tests on first differences and absolute returns to check for white noise properties.
  - **Tidal Data Analysis:** Analysis of hourly tide heights from Sooke Basin by fitting AR models with order selection via AIC, and verifying residuals to ensure robust spectral density estimation.
- **Key Techniques:**  
  - Unit root testing (ADF test)  
  - White noise testing (Ljung-Box, Bartlett tests)  
  - AR and ARMA model fitting  
  - Model diagnostics and spectral analysis

### **Assignment 3: Seasonal Adjustment & Speech Signal Processing**
- **Files:** `a3_questions.R` and `a3_solutions.R`
- **Overview:**  
  - **Traffic Fatalities:** Seasonal adjustment of monthly traffic fatality data in Ontario using STL decomposition. This includes isolating trend, seasonal, and irregular components, and evaluating the irregular component against white noise.
  - **Speech Signal Analysis:** High-frequency analysis of a speech signal (sampled at 10,000 Hz) using various spectral density estimation techniques—AR-based, multitaper, and Parzen lag window methods—to identify dominant frequencies.
- **Key Techniques:**  
  - STL decomposition for seasonal adjustment  
  - Evaluation of seasonal, trend, and irregular components  
  - Advanced spectral density estimation  
  - Frequency domain analysis

### **Assignment 4: Stock Price Modeling & Volatility Analysis**
- **Files:** `a4_questions.R` and `a4_solutions.R`
- **Overview:**  
  - **Stock Price Modeling:** Analysis of daily stock prices (log-transformed) for Barrick Gold using ARIMA models (ARIMA(0,1,1) and ARIMA(0,1,2)) to capture non-stationary behavior and trends.
  - **Volatility Analysis:** Application of ARCH and GARCH models to the residuals from the preferred ARIMA model, comparing model performance to capture volatility dynamics accurately.
- **Key Techniques:**  
  - ARIMA modeling for non-stationary data  
  - Volatility modeling using ARCH and GARCH  
  - Residual analysis and model diagnostics

## Technical Competencies Demonstrated

- **Data Transformation & Preprocessing:** Expertise in log transformations, differencing, and detrending to stabilize time series data.
- **Exploratory Analysis & Visualization:** Proficient in using correlograms and periodograms to understand autocorrelation and spectral properties.
- **Statistical Testing & Model Validation:** Advanced skills in applying ADF, Ljung-Box, and Bartlett tests to ensure model reliability.
- **Model Fitting & Forecasting:** Strong experience in fitting AR, ARMA, ARIMA, ARCH, and GARCH models for trend analysis and volatility forecasting.
- **Spectral Analysis:** Proficient in multiple spectral density estimation techniques to uncover periodic patterns and dominant frequencies.
- **R Programming:** Reproducible, efficient, and well-documented analysis using R and its extensive suite of statistical packages.


Thank you! 

