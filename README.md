# Udemy-Projects
Contains notebooks for the 3 Data Science projects completed via Udemy, each covering a different aspect.

**Flight Price Prediction:**
- Worked with a data set containing details on flights across India, including the journey time, destinations, duration, number of stops and price
- Goal was to predict the price of flights based on all factors using ML models
- Extensive data preprocessing and feature engineering completed to convert the dataset in a format suitable for modelling
- After splitting the data into 80% training, 20% testing, multiple ML models including Random Forest, Linear Regression, Decision Tree were fitted and evaluated (automation using custom functions were implemented)
- Models were evaluated using R^2, MAE, RMSE and MAPE
- Random Forest was the best model achieving an R^2 of 0.81
- Some hypertuning was also attempted using Random Search CV

**Password Strength Prediction**
- Data was obtained from an SQLite database
- Goal was to predict strength of password given any input
- Analysed uppercase, lowercase, punctuation, numerical characters, length of characters and their contribution towards password strength
- After determining important features, a multinomial logistic regression was used as the model, achieving a 0.809 accuracy

**Stock Price Prediction**
- Worked with data of one particular company's stock, Bajaj Finance containing opening + closing prices, Volume Weighted Average Price (VWAP), Turnover and other features
- Goal was to implement a time series model that predicts VWAP as accurately as possible
- Data cleaning and feature engineering (adding rolling means + standard deviations for numerical features) was performed to prepare the data for modelling
- After splitting the data into training and testing (80% training, 20% testing), an ARIMA model was implemented using auto_arima to determine the best parameters for the model
- RMSE and MAE were used to evaluate the model, values were 151.9 and 112.7 respectively (roughly 3-4% of the VWAP value)
