📈 Stock Price Prediction using Machine Learning

This project demonstrates how to predict stock prices using Linear Regression in Python.
We use yfinance to fetch real stock data, process it with pandas/numpy, build a machine learning model with scikit-learn, and finally visualize the predictions with matplotlib.

🚀 Project Workflow

1.Data Collection

-Downloaded Google stock price data (GOOG) from Yahoo Finance using yfinance.

2.Data Preprocessing

-Selected only date and closing price.

3.Scaled data using sklearn.preprocessing.

-Created training and testing sets.

4.Model Training

-Used Linear Regression model from scikit-learn.

5.Trained the model on historical prices.

6.Model Evaluation

-Calculated R² Score to evaluate accuracy.

-Forecasted the next 5 days of stock prices.

7.Visualization

-Plotted actual stock prices vs forecasted prices.

-Highlighted predictions in red.

🛠️ Tech Stack

-Python

-NumPy

-Pandas

-Scikit-learn

-Matplotlib

-yfinance

📊 Example Results

Model Accuracy (R² Score):

0.94


Forecasted Prices (next 5 days):

[786.54, 788.13, 781.84, 779.65, 769.04]


Visualization:
(Insert your plot here after running the notebook)

📂 Project Structure
├── stock_price_prediction.ipynb   # Main notebook with code
├── README.md                      # Project documentation

🔮 Future Improvements

Try more advanced models like Random Forest or LSTM (Deep Learning).

Add multiple features (volume, open, high, low) instead of just closing price.


---
Deploy as a web app using Streamlit or Flask.

<img width="1241" height="705" alt="Screenshot 2025-09-02 214536" src="https://github.com/user-attachments/assets/98cdde54-604e-4c0b-8a92-bedc5595002b" />
