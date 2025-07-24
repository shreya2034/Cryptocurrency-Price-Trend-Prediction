# 🪙 Cryptocurrency Price Trend Prediction

This project focuses on classifying cryptocurrency price trends as **High** or **Low** using real-time data scraped from **CoinMarketCap**. The goal is to understand crypto market behavior and develop a predictive machine learning model for trend classification.

## 📌 Project Overview

Cryptocurrency markets are highly dynamic and unpredictable. In this project, we:

- Scraped live data of top cryptocurrencies from CoinMarketCap  
- Performed data cleaning, visualization, and analysis  
- Engineered useful features for trend classification  
- Built and evaluated multiple machine learning models to predict price trends

## 📂 Dataset

- **Source**: Live data scraped from [CoinMarketCap](https://coinmarketcap.com/)
- **Key Features**:
  - Coin Name  
  - Price  
  - Market Capitalization  
  - 24h Volume  
  - Price Change (%)  
  - Other derived indicators

## ⚙️ Technologies Used

- **Python**
- **Jupyter Notebook**
- **Libraries**:  
  `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`, `beautifulsoup4`, `requests`

## 📊 Model Building

We built several classification models to predict whether a cryptocurrency’s price trend is **High** or **Low**.

### 🔧 Steps:
- Web scraping and preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature selection and encoding  
- Model training and performance evaluation

### 🧠 Models Used:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- XGBoost  
- Support Vector Machine (SVM)

## 📈 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix

## ✅ Results

The XGBoost classifier showed the best performance, providing accurate predictions of crypto price trends based on real-time features.

## 💡 Key Insights

- Market Cap and 24h Volume are strong indicators of trend direction  
- Ensemble models like Random Forest and XGBoost handle noisy data better  
- Careful feature engineering improves prediction accuracy

## 🚀 Future Improvements

- Include time-series models like LSTM for forecasting  
- Expand to multi-class trend levels (e.g., Very High, Medium, Low)  
- Build an interactive dashboard for real-time predictions

## 🙌 Acknowledgements

- [CoinMarketCap](https://coinmarketcap.com/) for the live cryptocurrency data  
- Open-source ML contributors and Python community

---

> 🚀 Contributions are welcome! Feel free to raise issues or suggest improvements.
