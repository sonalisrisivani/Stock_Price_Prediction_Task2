# Stock_Price_Prediction_Task2
TASK 1 : STOCK PREDICTION
PURPOSE : TO PREDICT THE STOCK PRICE OF A COMPANY USING LSTM.
ABOUT DATASET
Google Stock Prediction
This dataset contains historical data of Google's stock prices and related attributes. It consists of 14 columns and a smaller subset of 1257 rows. Each column represents a specific attribute, and each row contains the corresponding values for that attribute.

The columns in the dataset are as follows:

Symbol: The name of the company, which is GOOG in this case.
Date: The year and date of the stock data.
Close: The closing price of Google's stock on a particular day.
High: The highest value reached by Google's stock on the given day.
Low: The lowest value reached by Google's stock on the given day.
Open: The opening value of Google's stock on the given day.
Volume: The trading volume of Google's stock on the given day, i.e., the number of shares traded.
adjClose: The adjusted closing price of Google's stock, considering factors such as dividends and stock splits.
adjHigh: The adjusted highest value reached by Google's stock on the given day.
adjLow: The adjusted lowest value reached by Google's stock on the given day.
adjOpen: The adjusted opening value of Google's stock on the given day.
adjVolume: The adjusted trading volume of Google's stock on the given day, accounting for factors such as stock splits.
divCash: The amount of cash dividend paid out to shareholders on the given day.
splitFactor: The split factor, if any, applied to Google's stock on the given day. A split factor of 1 indicates no split.
The dataset is available at Kaggle : https://www.kaggle.com/datasets/shreenidhihipparagi/google-stock-prediction

STEPS INVOLVED :
1 . IMPORTING LIBRARIES AND DATA TO BE USED
2. GATHERING INSIGHTS
3. DATA PRE-PROCESSING
4. CREATING LSTM MODEL
5. VISUALIZING ACTUAL VS PREDICTED DATA
6. PREDICTING UPCOMING 15 DAYS
