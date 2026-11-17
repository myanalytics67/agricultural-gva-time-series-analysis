
# Agricultural GVA in India: A Time Series Analysis

## Overview
This project examines the growth of India's agricultural sector using annual Gross Value Added (GVA) data for Agriculture, Forestry and Fishing from 1989–90 to 2025–26.

The objective is to understand historical growth patterns and examine whether growth in one year is related to growth in the following year.

## Methodology
- Analysed 37 years of agricultural GVA data.
- Examined trends in real agricultural GVA.
- Tested for stationarity using the Augmented Dickey-Fuller (ADF) test.
- Used ACF and PACF plots to identify an appropriate autoregressive model.
- Estimated an AR(1) model using Ordinary Least Squares (OLS).
- Examined residuals and diagnostic statistics.

## Tools & Packages
- **Software:** R
- **Packages:** `urca` for unit-root testing.
- **Functions:** `lm` for OLS estimation.

## Key Finding
The analysis found a statistically significant negative relationship between consecutive years' agricultural GVA growth. Years with unusually high growth tended to be followed by lower growth in the subsequent year.

## Data Sources
- Reserve Bank of India – Handbook of Statistics on the Indian Economy
- Ministry of Statistics and Programme Implementation (MoSPI) – National Accounts Statistics

## Project Contents
- `README.md` – Project overview and methodology.
- `Agricultural_GVA_Time_Series_Analysis.pdf` – Full research report.
