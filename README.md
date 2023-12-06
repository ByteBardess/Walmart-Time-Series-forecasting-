# Walmart-Time-Series-forecasting-
 ![image](https://github.com/cipherchawla/Walmart-Time-Series-forecasting-/assets/146151444/56d4e980-ac71-4f7b-b258-66c3157bc3ea)

**PROBLEM STATEMENT**

Walmart has multiple outlets across the country and is facing issues in managing the inventory - to match the demand concerning supply. You are a data scientist, who has to come up with useful insights using the data and make prediction models to forecast the sales for 12 weeks 

**PROJECT OBJECTIVE**

I aim to develop a robust forecasting model leveraging time series analysis techniques. The model should accurately predict future sales trends based on historical data. Focusing on Stores 1-5 , I seek to create a model that captures seasonal patterns, fluctuations, and any underlying trends within the sales data.

**DATA DESCRIPTION**
<img width="359" alt="Screenshot 2023-12-06 at 3 54 28 PM" src="https://github.com/cipherchawla/Walmart-Time-Series-forecasting-/assets/146151444/c7295d3c-4fbf-4a96-8bb2-bbad7c9c5c3b">


**DATA PRE-PROCESSING STEPS AND INSPIRATION**

**1.	EDA**
Sales Distribution During Holidays vs. Non-Holidays: Employing box plots, it was evident that there were higher average sales during holiday weeks, signifying the need for potential inventory adjustments or specific promotional strategies during these periods to capitalize on increased sales opportunities.

<img width="443" alt="image" src="https://github.com/cipherchawla/Walmart-Time-Series-forecasting-/assets/146151444/393b023d-c75c-480d-8eb3-04a430cc27e2">

 
Fuel Price: The scatter plot revealed no clear correlation between fuel prices and weekly sales, suggesting that sales strategies might not need significant alterations based solely on fuel price fluctuations.

<img width="479" alt="image" src="https://github.com/cipherchawla/Walmart-Time-Series-forecasting-/assets/146151444/0aebf8bf-da90-4ee7-bcdd-eb0af22ce1f5">

 
Holidays: The bar plot emphasized the importance of tailored holiday-specific marketing strategies and maintaining higher stock inventory during holiday weeks to leverage increased sales opportunities.
<img width="498" alt="image" src="https://github.com/cipherchawla/Walmart-Time-Series-forecasting-/assets/146151444/ec9bea1c-e773-4032-a2a7-ca30b79580fb">


Temperature: A scatter plot depicting Temperature vs. Weekly_Sales highlighted that stocking up inventory before a significant temperature drop might be beneficial. The extreme cold could potentially deter customers from visiting stores, necessitating a proactive approach to ensuring essential goods are available during such weather conditions.

<img width="489" alt="image" src="https://github.com/cipherchawla/Walmart-Time-Series-forecasting-/assets/146151444/1b6cbf9e-2de2-416a-b78d-0f7d09001243">

 
**2.	DATA CLEANING** 
The data underwent meticulous cleaning to ensure accuracy in subsequent analyses. Missing values were handled through a combination of techniques, such as interpolation for time-series data and imputation based on surrounding values where appropriate. The goal was to maintain data integrity without compromising significant insights.
 
**CHOOSING THE ALGORITHM AND ITS MOTIVATION**
ARIMA and SARIMA Models: 
•	Rigorous testing and evaluation were conducted on both ARIMA and SARIMA models. 
•	While both models exhibited competence in capturing time series characteristics, ARIMA demonstrated superior performance in forecasting sales. 
•	The decision to opt for ARIMA was influenced by its simplicity, interpretability, and robustness in capturing the dataset's inherent patterns.

**ASSUMPTIONS**
•	Anticipated the continuation of historical sales patterns in future data.
•	Assumed stationarity post-data pre-processing.

**MODEL EVALUATION AND TECHNIQUE**
•	Model Evaluation:
•	Assessed multiple ARIMA configurations using RMSE as the primary metric.
•	Iteratively optimized model parameters to achieve better accuracy.
•	Enhancement Techniques:
•	Proposed enhancements included:
•	Cross-validation for robustness.
•	Ensemble methods for improved accuracy.

**FUTURE POSSIBILITIES OF THE PROJECT**

•	Integration of external variables like promotional activities, economic indicators, or competitor data.
•	Exploration of advanced machine learning algorithms like LSTM or Prophet for more accurate forecasting.
•	Automation and optimization of hyperparameters to improve model performance

**CONCLUSION AND INFERNECES **
•	Forecasted Observations:
•	Predictions suggest an increasing trend in sales for the upcoming weeks.
•	Higher sales are expected during holiday seasons and warmer weather.
•	Conclusion:
•	Accurate sales forecasting is crucial for effective resource allocation and inventory management.
•	The ARIMA model showcased reliability in capturing sales patterns, contributing to informed decision-making for Walmart stores.

**REFERENCES**
1.	IITM professor’s recorded lectures 
2.	Sci-kit learn documentation: Link
3.	Investopedia for CPI: Link
