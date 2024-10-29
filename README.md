### Project Overview

This project automates standby duty planning for rescue drivers at Berlin’s Red Cross, addressing challenges of unpredictable driver availability due to sickness or increased emergency calls. The primary goal is to develop a predictive model that optimizes standby driver allocation, ensuring efficient staffing and reducing the need for on-call drivers on their scheduled days off.

### Objectives

- Forecast Driver Demand: Use time series and regression models to accurately predict daily standby driver needs, based on historical data and seasonal trends.
- Optimize Resources: Minimize overstaffing and understaffing through reliable standby driver estimates.
- Improve Decision-Making: Enable HR teams to create efficient schedules by the 15th of each month for the following month, with a user-friendly interface to incorporate manual adjustments if needed.

### Solution Approach

- Data Preparation and Analysis: Cleaned and preprocessed historical data, exploring patterns with exploratory data analysis and seasonal decomposition.
- Model Development: Implemented and tested several predictive models (ARIMA, SARIMA, Random Forest, XGBoost) to find the most accurate model for daily predictions.
- Deployment: Developed a GUI to assist HR in managing daily standby driver planning by inputting factors like expected emergency calls and anticipated sick leaves.

### Key Results

-  Best Model: A tuned XGBoost model with an 80/20 train-test split was selected, offering superior performance with low error rates.
- Operational Efficiency: The model supports dynamic staffing needs, reducing operational stress and improving response rates to emergencies.

This project enhances Berlin’s Red Cross operations by providing a reliable, data-driven solution to standby duty planning.
