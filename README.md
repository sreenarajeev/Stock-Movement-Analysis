# Stock-Movement-Analysis
This project involves:
1. Scraping messages from a public Telegram channel (e.g.Stocktwits India) using the Telethon library.
2. Performing sentiment analysis on the scraped messages.
3. Training a regression model to predict stock price movements based on sentiment data.

---

## Folder Structure
- `README.md`: This file, which explains the project setup and usage.
- `requirements.txt`: A list of required Python libraries.
- `stock_scraper.ipynb`: Jupyter Notebook for scraping Telegram messages and performing sentiment analysis.
- `prediction_model.ipynb`: Jupyter Notebook for training and evaluating a stock movement prediction model.

---

## Features
- Scrapes messages from public Telegram channels.
- Preprocesses and analyzes the sentiment of messages using TextBlob.
- Builds and evaluates a simple regression model based on simulated stock price data.

---

## Setup Instructions

### 1. Install Dependencies
Run the following command to install the required libraries:
pip install -r requirements.txt

### 2. Set Up Telegram API Credentials
1. Go to [Telegram API](https://my.telegram.org/auth) and log in.
2. Create a new app to get your API ID and API Hash.
3. Replace the placeholders in `stock_scraper.ipynb` with your API ID and API Hash.

### 3. Run the Jupyter Notebooks
- Open `stock_scraper.ipynb` to scrape data and analyze sentiment.
- Open `prediction_model.ipynb` to train and evaluate the machine learning model.

---

## Important Notes
- Only scrape data from public channels to comply with Telegram's Terms of Service.
- Replace simulated stock price data with real stock data for production use.
- Use `.env` files or other secure methods to protect your API credentials.

---

## Dependencies
The required libraries are listed in `requirements.txt` and include:
- `telethon`
- `textblob`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `nest-asyncio`
