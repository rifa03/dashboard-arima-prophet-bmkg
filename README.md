# Temperature Forecasting Analysis Using ARIMA and Prophet: BMKG Weather Data
This project analyzes and compares ARIMA and Prophet time series forecasting models to predict temperature trends using BMKG weather data. The results are presented through an interactive dashboard for easier interpretation.

## Business Problem
Accurate temperature forecasting can support weather monitoring and operational planning. This project aims to identify the forecasting model that provides better prediction performance between ARIMA and Prophet.

## Objectives
- Analyze temperature patterns from BMKG weather data.
- Build forecasting models using ARIMA and Prophet.
- Compare model performance using evaluation metrics.
- Develop an interactive dashboard to communicate forecasting results.

## Methodology
1. Data collection from BMKG weather prediction data.
2. Data preprocessing and transformation.
3. Exploratory Data Analysis (EDA).
4. Time series forecasting using ARIMA and Prophet.
5. Model evaluation and comparison.
6. Dashboard development.

## Model Evaluation

The model performance was evaluated using three evaluation metrics: **Mean Absolute Error (MAE)**, **Root Mean Square Error (RMSE)**, and **Mean Absolute Percentage Error (MAPE)**.

| Model | MAE (°C) | RMSE (°C) | MAPE (%) |
|---|---:|---:|---:|
| ARIMA | 1.3542 | 1.6448 | 5.5527 |
| Prophet | 2.6221 | 2.6777 | 10.6783 |

### Evaluation Result

Based on the evaluation results, **ARIMA achieved lower prediction errors compared to Prophet across all evaluation metrics.**

- **MAE:** ARIMA achieved an average prediction error of **1.3542°C**, lower than Prophet (**2.6221°C**).
- **RMSE:** ARIMA produced an error value of **1.6448°C**, indicating smaller prediction deviations compared to Prophet (**2.6777°C**).
- **MAPE:** ARIMA achieved a prediction error percentage of **5.5527%**, while Prophet resulted in **10.6783%**.

Overall, **ARIMA was selected as the best forecasting model for this dataset due to its better prediction performance.**

The ARIMA model achieved the best performance on:
- **28 out of 28 sub-districts analyzed.**
- **109 out of 112 testing points.**

## Dashboard Preview

#![Dashboard Preview](images/dashboard.png)
