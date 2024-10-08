Name:V.Bharath.<br/>
Company:CODTECH IT SOLUTIONS<br/>
ID:CT08D58466<br/>
Domain:Data Science<br/>
Duration:September 25/9/2024 to October 25/10/2024<br/>
Mentor:Muzammil<br/>



Overview of Stock Market Prediction Using ARIMA and LSTM Models<br/>
Objective:<br/>
The primary goal of this script is to predict future stock prices using time series analysis techniques. The script utilizes two models, ARIMA and LSTM, to forecast future stock prices based on historical data. The objective is to compare the performance of both models in capturing trends and predicting future stock prices.<br/>

Key Activities:<br/>
Data Collection:<br/>

Fetches historical stock price data from Yahoo Finance using the yfinance library.
The stock data is collected over a specified time period for a given stock (e.g., Apple Inc., AAPL).<br/>
Exploratory Data Analysis (EDA):<br/>

Visualization: Plots the closing price of the stock to understand historical trends.<br/>
Stationarity Check (ADF Test): Performs the Augmented Dickey-Fuller (ADF) test to check if the time series data is stationary, an essential requirement for ARIMA modeling.<br/>
ARIMA Modeling:<br/>

Data Transformation: Applies differencing to make the data stationary if necessary.<br/>
Model Building: Builds and trains an ARIMA model with parameters (p, d, q) to capture the linear trends and seasonal behavior of the stock prices.<br/>
Forecasting: Forecasts stock prices for the next 30 days and plots the results, comparing actual historical prices with predicted prices.<br/>
LSTM Modeling:<br/>

Data Preprocessing:<br/>
Scales the data using MinMaxScaler to bring values between 0 and 1, a requirement for neural networks like LSTM.
Splits the data into training and testing sets.
Converts the data into sequences to capture temporal relationships for LSTM modeling.<br/>
Model Building: Constructs a two-layer LSTM model to predict future stock prices. LSTM, a type of recurrent neural network (RNN), is used to model time-dependent and sequential data.<br/>
Training: Trains the LSTM model using the training data.

Technologies and Libraries Used:<br/>
Python: Programming language used for data manipulation, modeling, and visualization.<br/>

Libraries:<br/>

yfinance: For downloading historical stock price data from Yahoo Finance.<br/>
pandas: For data manipulation and handling time series data.<br/>
numpy: For numerical operations and array manipulations.<br/>
matplotlib and seaborn: For plotting and visualizing data trends.<br/>
statsmodels: For implementing ARIMA modeling and statistical tests.<br/>
scikit-learn: For data scaling and evaluation metrics like RMSE.<br/>
keras and tensorflow: For building and training the LSTM neural network model.<br/>
![Screenshot 2024-10-08 112258](https://github.com/user-attachments/assets/71039544-40e1-4770-852a-bcee96f48925)
![Screenshot 2024-10-08 112329](https://github.com/user-attachments/assets/25555760-4a01-47d0-8a84-5e96b339f9d2)
