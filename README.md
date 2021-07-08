# Time Series Analysis

- Based on the p value, both the ARMA and ARIMA models are not a good fit. *(A larger (insignificant) p-value suggests that changes in the predictor are not associated with changes in the response.)*
- The p value for ARMA model is 0.422
- The p value for ARIMA model is 0.652	
- The GARCH model predicts increased volatility values of 7.434048, 7.475745, 7.516867, 7.557426, 7.597434.
- Overall, based on this evaluation alone, this particular model is not a good fit for trading. There are many factors involved in the movement of world currencies that are not accounted for such as economies, foreign policies, interest rates, and much more.

# Regression Analysis
- The Out-of-Sample Root Mean Squared Error (RMSE) is 0.4154543718471276
- The In-Sample Root Mean Squared Error (RMSE) is 0.5962037920929946
- Higher RMSE means higher error in predicted values. 
- I recommend more related input features for potential higher model accuracy. 
