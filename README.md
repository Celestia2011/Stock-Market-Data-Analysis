📈 Stock Market Data Analysis

📝 Project Overview

This project performs in-depth analysis of stock market data from various well-known companies such as Netflix, Amazon, Apple, Samsung, and others. The dataset includes critical stock information such as Open, High, Low, Close prices, Volume, Dividends, Stock Splits, and metadata related to each company.
🔑 Key Features:

    Dataset Columns:
        Date, Open, High, Low, Close, Volume, Dividends, Stock Splits, Brand_Name, Ticker, Industry_Tag, Country
    Companies Analyzed:
        Netflix, Amazon, Apple, Samsung, Peloton, etc.

📊 Visualizations

Several visualizations were created to provide insights into the stock data:

    Time Series Plot: Trends of stock prices over time.
    Candlestick Chart: Visually represents the stock's Open, High, Low, and Close prices.
    Box Plot: Illustrates the distribution of stock prices.
    Bar Plot: Depicts categorical data such as stock splits and dividends.
    Correlation Heatmap: Displays correlations between numerical columns (Open, High, Low, Close, Volume).
    Scatterplot: Identifies relationships between stock features.
    Histogram: Displays the distribution of stock prices.
    Confusion Matrix: Used to assess the classification model’s performance.

🎯 Classification Model: Random Forest

A Random Forest classifier was applied to classify the stock data into different categories. Below is the classification report generated by the model:
🧾 Classification Report:

markdown

               precision    recall  f1-score   support

           0       1.00      1.00      1.00      3809
           1       1.00      1.00      1.00      4478
           2       1.00      1.00      1.00      2001
           ...
          21       1.00      1.00      1.00       231
          22       1.00      1.00      1.00     11946

    accuracy                           1.00     55951
    macro avg       1.00      1.00      1.00     55951
    weighted avg       1.00      1.00      1.00     55951

   

✅ Accuracy:

0.9998570177476721
🛠 Tools Used

    Python 🐍
    Pandas for data manipulation 🧮
    Matplotlib and Seaborn for data visualization 📊
    Scikit-learn for Random Forest classification 🧠

🚀 How to Run

    Clone the repository:

    bash

git clone https://github.com/Celestia2011/stock-market-analysis.git

Install the required libraries:

bash

pip install -r requirements.txt

Run the Jupyter notebook or Python script:

bash

    jupyter notebook stock_market_analysis.ipynb

📌 Conclusion

This project provides valuable insights into stock market behaviors using a blend of visualization and classification techniques. The Random Forest classifier performed exceptionally well, achieving a stellar accuracy of 99.99%.

Feel free to explore the analysis and use it as a starting point for further investigations or enhancements!
