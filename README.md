# Crypto Price Prediction 📈

Crypto Price Prediction is the webapp based on Machine Learning model that predicts the future closing price.

# Authors ✒️

- Hitesh Krishnani

---

# Language/Libraries used? 👨‍💻

⚬ API/ Web Scraper: Yfinance python scraper scraped the data from CoinMarketCap

⚬ **Data Wrangling**: Pandas, Numpy

⚬ **Data Visualisation**: Matplotlib, Seaborn

⚬ **Data Modeling**: Scikit: Learn, TensorFlow, Keras

⚬ **Webapp**: Streamlit

⚬ **IDE**: Jupyter Notebook/ PyCharm

---

# Which Machine Learning Model is used in this webapp? 🌐

LSTM is used in this webapp.

LSTMs are widely used for sequence prediction problems and have proven to be extremely effective. The reason they work so well is that LSTM is able to store past information that is important and forget the information that is not.

LSTM has three gates:

a. The input gate: The input gate adds information to the cell state.

b. The forget gate: It removes the information that is no longer required by model.

c. The output gate: The output Gate at LSTM selects the information to be shown as output This deep learning model has done some work here.

---

# What is the accuracy of the model? ✅

It has recognized all the potential upward and downtrends in stock prices. It is much more efficient compared to all other different ML models and the **Accuracy of the model is 97%**.

---

# Run Locally 👨‍💻

Install packages

```bash
  pip install -r requirements.txt
```

After installing all the packages

Run the webapp

```bash
streamlit run Home.py

```

This will open the webapp in your default browser
