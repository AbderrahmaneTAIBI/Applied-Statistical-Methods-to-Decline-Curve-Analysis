# Report: Applied Statistical Methods to Decline Curve Analysis

This Jupyter notebook provides a comparison of the application of Statistical Methods ARIMA/SARIMA for decline production study in reservoir engineering for shale gas study. The dataset used in this analysis is "HS01DataCummulativeNonZeros.csv."

## Tools and Libraries Used

* pandas: Used for data manipulation and analysis
* numpy: Used for numerical operations
* matplotlib: Used for data visualization
* seaborn: Used for data visualization
* statsmodels: Used for statistical analysis and modeling
* pyramid: Used for time series modeling
* sklearn: Used for performance metrics

## Analysis
The notebook starts with importing the necessary libraries and loading the dataset. The dataset is then preprocessed and cleaned for analysis.

The next step is to conduct exploratory data analysis to understand the trends and patterns in the data. The trends and seasonality in the data are analyzed using the seasonal decomposition technique.

The ARIMA and SARIMA models are then fitted to the dataset, and the performance of these models is compared using various metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), Median Absolute Error (MedAE), and R-squared.

Finally, the performance of the best model is evaluated using a rolling forecast mechanism and compared with the actual values.

## Conclusion

This notebook provides a detailed analysis of the application of ARIMA/SARIMA models in decline production study for shale gas study. The results suggest that the SARIMA model outperforms the ARIMA model in predicting the decline in shale gas production. The notebook can be used as a reference for anyone interested in conducting similar analyses or working in the field of reservoir engineering.



