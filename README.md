# Correlation Prediction with ARIMA-LSTM Hybrid Model
I have  applied an ARIMA-LSTM hybrid model to predict future price correlation coefficients of two assets

 1. DATASET FILES

(1) SP500_list.csv : The list of S&P500 firms and their tickers. I scraped the data from wikipedia

(2) SP500_index.csv : The market value corresponding to the time span used in my research

(3) stock08_price.csv : The final price dataset after preprocessing

(4) train_dev_test folder : All the train / development / test1 / test2 datasets needed for each step

(5) stock_data folder : Individual stock price data downloaded


2. ARIMA MODEL SECTION

(6) Data_Scraping_Codes.ipynb : Web scraping code to get data in need

(7) DATA_PREPROCESSING.ipynb : Data preprocessing codes such as NA imputation, reshaping etc..

(8) ARIMA_MODELING.ipynb : The ARIMA codes to compute the residual values

(9) NEW_ASSET_ARIMA_MODELING.ipynb : After generating model, we test on different assets iteratively. This is the ARIMA section of it

 3. LSTM-CELL RNN MODEL SECTION

(10) raw_python_codes folder : The python codes used to model the LSTM RNN 

(11) models folder : The LSTM models saved for each epoch + The evaluated metric values for each epoch

(12) MODEL_EVALUATOR.ipynb : The model performance is tested against other financial models

