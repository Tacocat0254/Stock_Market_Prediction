<H1>Stock Market Analysis and Prediction Using Deep Learning</H1>
This project explores the use of deep learning—specifically Long Short-Term Memory (LSTM) networks—to analyze and forecast stock market trends. It covers:

- Historical stock data retrieval and visualization
- Data preprocessing for sequential modeling
- Implementation of an LSTM model for next-day price prediction

<H2>Data Sources</H2>
Historical stock data was obtained for the following companies:

- Google (GOOG) – 2006–2024
- Microsoft (MSFT) – 2006–2024
- IBM (IBM) – 2006–2024
- Amazon (AMZN) – 2006–2024
- Meta (META, used to be Facebook) – 2016–2024
- Apple (AAPL) – 2006–2024
- Netflix (NFLX) – 2006–2024
- Tesla (TSLA) – 2010–2024
  
Each dataset includes the data with the following attributes:

- Open Price
- High Price
- Low Price
- Close Price
- Volume


<H2>How to Run</H2>

Clone the repo:
```
git clone https://github.com/Tacocat0254/Stock_Market/edit/
cd stock-lstm-forecasting
```

Install dependencies:
```
pip install -r requirements.txt
```
Run the notebook:
```
jupyter notebook stock_forecasting.ipynb
```
