# Brent Oil Price Analysis: Change Point Detection & Statistical Modeling

## Overview

This project focuses on analyzing the relationship between key political, economic, and technological events and Brent crude oil prices. The primary goal is to detect change points in time series data and model the impact of significant events such as political decisions, conflicts, sanctions, and OPEC policy shifts on oil prices. Through this analysis, we aim to provide insights that can inform investment strategies, policy decisions, and operational planning for stakeholders in the energy sector.

The project utilizes statistical modeling, Bayesian inference, and time series analysis to uncover hidden patterns and generate actionable insights for better decision-making in the global energy market.

## Business Objective

The key business objective is to understand how important events have historically affected Brent oil prices. We will focus on:

- Identifying key events that significantly impacted Brent oil prices.
- Measuring the magnitude of these impacts.
- Offering data-driven insights to guide investors, policymakers, and energy companies.

The analysis will assist stakeholders in navigating the complexities of the volatile oil market by providing deeper insights into price fluctuations and their causes.

## Key Dates

- **Discussion on the case**: Wednesday, 19 Feb 2025  
- **Interim Solution Submission**: Friday, 21 Feb 2025, 20:00 UTC  
- **Final Submission**: Tuesday, 25 Feb 2025, 20:00 UTC

## Learning Outcomes

### Skills:
- Statistical modeling using time series analysis techniques.
- Implementing Bayesian inference with PyMC3.
- Developing Python-based models for predictive analysis.
- Communicating insights effectively to stakeholders and decision-makers.

### Knowledge:
- Time series models like ARIMA and GARCH for analyzing price movements.
- Bayesian modeling and Monte Carlo Markov Chains for forecasting.
- Policy analysis for understanding market behavior in response to external events.

### Communication:
- Reporting insights and analysis results to government bodies and stakeholders.
- Creating interactive dashboards for better visualizations and decision support.

## Tasks

### Task 1: Data Analysis Workflow & Model Understanding
- Define the analysis steps.
- Understand the input, assumptions, and limitations of the models.
- Explore ARIMA, GARCH, and other time series models.

### Task 2: Advanced Analysis of Brent Oil Prices
- Apply time series models to analyze historical Brent oil prices.
- Explore additional econometric and machine learning models (e.g., LSTM, VAR).
- Assess the influence of external factors (e.g., GDP, sanctions, oil production technologies).

### Task 3: Building an Interactive Dashboard
- Develop a dashboard with Flask (backend) and React (frontend) to visualize the analysis results.
- Enable features for users to explore how political events and market conditions correlate with price movements.

## Technologies Used

- **Python**: PyMC3, Pandas, Numpy, Statsmodels
- **Flask**: For backend development of APIs
- **React**: For frontend visualization and dashboard creation
- **Time Series Models**: ARIMA, GARCH, LSTM, Markov Switching ARIMA
- **Data Visualization**: D3.js, Recharts, React Chart.js 2

## Dataset

The dataset includes historical daily Brent oil prices from **May 20, 1987, to September 30, 2022**, and it contains the following fields:

- **Date**: The date the price was recorded (e.g., 20-May-87).
- **Price**: Brent crude oil price (USD per barrel).

## Approach

1. **Data Collection**: Gather data on economic indicators, technological advancements, and political events that may influence oil prices.
2. **Data Preprocessing**: Clean the data to handle missing values and outliers.
3. **Exploratory Data Analysis (EDA)**: Identify trends and correlations.
4. **Model Building**: Use time series models and econometric models for forecasting.
5. **Model Evaluation**: Assess models using RMSE, MAE, and R-squared.
6. **Insight Generation**: Provide actionable recommendations based on model outputs.

## How to Use This Repository

1. **Clone the repository**:
    ```bash
    git clone https://github.com/<username>/brent-oil-price-analysis.git
    ```

2. **Install dependencies**:
    Navigate to the project folder and install the required libraries.
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Flask API**:
    ```bash
    python app.py
    ```

4. **Start the React dashboard**:
    ```bash
    npm start
    ```

## Contributing

We welcome contributions from the community! If you'd like to improve the analysis or add new features to the dashboard, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

- **References**:
    - [Change Point Analysis](https://towardsdatascience.com/change-point-detection-a-bayesian-approach-8eb3cfca4a6e)
    - [Bayesian Inference and MCMC](https://warwick.ac.uk/fac/sci/statistics/staff/academic-research/steel/steel_homepage/bayesiantsrev.pdf)
    - [Data Science Workflow](https://www.datascience-pm.com/data-science-workflow/)

