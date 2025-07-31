# 📊 Stock Trading Strategy with ML & Telegram Alerts

This project implements a stock trading strategy using **RSI (Relative Strength Index)** and **50-Day Moving Average**, with **real-time alerts sent to Telegram**. It is designed for educational purposes and can be extended with more features like backtesting, automated trading, etc.

---

## 🚀 Features

- 📉 RSI calculation to detect oversold/overbought conditions
- 📈 50-day Moving Average crossover strategy
- 📲 Real-time Telegram bot alerts for Buy/Sell signals
- 📝 (Optional) Logs trading signals to Google Sheets using Google API

---

## 📁 Files Included

| File Name                                              | Description                                                  |
|--------------------------------------------------------|--------------------------------------------------------------|
| `Stock_Trading_Strategy_with_ML_Telegram_Alerts.ipynb` | Main Jupyter Notebook with trading logic and Telegram setup |
| `stock.json`                                           | 🔐 **DO NOT upload publicly** — Google service account key   |

---

## ⚠️ Important Notes

- **Do not upload `stock.json` to GitHub.** It contains sensitive credentials.
- Add `*.json` to your `.gitignore` file to keep it private.
- Each user must generate their own credentials from [Google Cloud Console](https://console.cloud.google.com).

---

## 💡 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/algo-trading-rsi-ma-telegram.git
   cd algo-trading-rsi-ma-telegram
