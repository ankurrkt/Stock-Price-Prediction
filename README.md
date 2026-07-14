# 📈 Stock Price Prediction using LSTM

## 📌 Overview
This project predicts future stock closing prices using a Long Short-Term Memory (LSTM) neural network. The model learns historical stock price patterns and forecasts future prices to assist investors and analysts in making informed decisions.

---

## 🚀 Features
- Predicts future stock closing prices using LSTM.
- Preprocesses historical stock market data.
- Handles missing values and normalizes data.
- Creates sequential time-series input windows.
- Visualizes actual vs predicted stock prices.
- User-friendly interface built with Django.

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- Django
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📂 Dataset
The project uses historical stock market data containing:
- Date
- Open Price
- High Price
- Low Price
- Close Price
- Adjusted Close Price
- Volume

You can use datasets from:
- Kaggle

---

## ⚙️ Project Workflow

1. Collect historical stock market data.
2. Handle missing values.
3. Normalize the data using MinMaxScaler.
4. Create sequential input windows.
5. Train the LSTM model.
6. Predict future closing prices.
7. Evaluate model performance.
8. Visualize predicted vs actual prices.

---

## 🧠 LSTM Architecture

- Input Layer
- LSTM Layer
- Dropout Layer
- Dense Output Layer

The model captures long-term dependencies in time-series data, making it suitable for stock price prediction.

---

## 📊 Evaluation Metrics

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

---

## 📈 Results

The trained model successfully learns historical trends and generates stock price predictions with good accuracy. The comparison graph between actual and predicted prices demonstrates the model's effectiveness for short-term forecasting.

---

## 📁 Project Structure

```
Stock-Price-Prediction/
│
├── dataset/
├── model/
├── static/
├── templates/
├── prediction.py
├── train_model.py
├── app.py
├── requirements.txt
└── README.md
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Stock-Price-Prediction.git
```

Move to the project folder

```bash
cd Stock-Price-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python manage.py runserver
```

Open your browser

```
http://127.0.0.1:8000/
```

---

## 🎯 Future Enhancements

- Integrate real-time stock data using APIs.
- Predict multiple stocks simultaneously.
- Add technical indicators such as RSI, MACD, and Moving Averages.
- Improve prediction accuracy using GRU or Transformer models.
- Deploy the project on cloud platforms like AWS or Azure.

---

## 📄 License

This project is intended for educational and research purposes.

---
