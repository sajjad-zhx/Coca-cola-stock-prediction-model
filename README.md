# Coca-cola-stock-prediction-model
Python project analyzing Coca-Cola (NYSE: KO) — exploring its stock trends, history, and price prediction using data analysis &amp; ML.
🥤 Coca-Cola Stock Analysis & Prediction

This project explores The Coca-Cola Company (NYSE: KO) — one of the world’s most iconic beverage brands — through data analytics and machine learning.
Using real market data from Yahoo Finance, the project analyzes Coca-Cola’s historical stock performance, discovers insights through data visualization, and predicts future prices using regression models.

📖 About The Coca-Cola Company

The Coca-Cola Company is a North American multinational beverage corporation headquartered in Atlanta, Georgia, incorporated under Delaware law.
Founded in 1892 after Asa Griggs Candler acquired John Pemberton’s 1886 Coca-Cola formula, it has grown into a global symbol of refreshment and marketing excellence.

Coca-Cola has been publicly traded since 1919 under the ticker symbol KO, maintaining a strong record of profitability and over half a century of annual dividend increases.

🚀 Project Overview

This project demonstrates how data science techniques can be applied to stock market data.
The main goals include:

📊 Collecting and cleaning Coca-Cola’s historical stock data

📈 Exploring and visualizing long-term stock performance

🧮 Engineering features like moving averages and volatility

🤖 Training a machine learning model to predict closing prices

📉 Evaluating model performance using regression metrics

🧰 Tech Stack
Category	Tools / Libraries
Data Source	Yahoo Finance (yfinance)
Data Analysis	pandas, numpy
Visualization	matplotlib, seaborn
Machine Learning	scikit-learn
Development	Jupyter Notebook / Anaconda
🧪 Features

✅ Fetch Coca-Cola stock data directly from Yahoo Finance
✅ Clean and preprocess large time-series data
✅ Generate moving averages, daily returns, and volatility
✅ Visualize long-term stock performance trends
✅ Build a Random Forest Regressor for stock price prediction
✅ Evaluate accuracy using MAE and MSE

📂 Project Structure
CocaCola_Stock_Analysis/

│

├── data/

│   ├── Coca-Cola_stock_history.csv

│   ├── Coca-Cola_stock_info.csv

│

├── notebooks/

│   └── analysis.ipynb         # Full EDA and ML workflow

│

├── requirements.txt

└── README.md

⚙️ How to Run

1️⃣ Clone the repository

git clone https://github.com/yourusername/CocaCola_Stock_Analysis.git
cd CocaCola_Stock_Analysis


2️⃣ Install required packages

pip install -r requirements.txt


3️⃣ Open the Jupyter notebook

jupyter notebook notebooks/analysis.ipynb


4️⃣ Run all cells to explore data, train the model, and view predictions.

📈 Example Visualization

Coca-Cola closing prices with moving averages:

plt.figure(figsize=(12,6))
plt.plot(data['Date'], data['Close'], label='Close')
plt.plot(data['Date'], data['MA_20'], '--', label='MA 20')
plt.plot(data['Date'], data['MA_50'], '--', label='MA 50')
plt.title('Coca-Cola Stock Prices with Moving Averages')
plt.legend()
plt.show()

🧠 Insights

Coca-Cola’s stock demonstrates long-term growth and stability.

Moving averages highlight consistent upward trends with periodic corrections.

The Random Forest model captures price trends effectively for short-term forecasting.

🤝 Acknowledgements

Data: Yahoo Finance

Libraries: pandas, yfinance, matplotlib, scikit-learn

Inspiration: Financial data analysis and machine learning applications

🧑‍💻 Author

Sajjad ali
sajjad.zhx@gmail.com 
💼 LinkedIn- linkedin.com/sajjad.zhx/
 | 🐙 GitHub- https://github.com/sajjad-zhx/

🏁 Conclusion

This project combines data analytics and machine learning to provide valuable insights into Coca-Cola’s financial trends.
It’s a hands-on example of how historical stock data can be used to understand market behavior and build predictive models for investment analysis.
