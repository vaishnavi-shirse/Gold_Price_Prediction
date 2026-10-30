# 🪙 Gold Price Prediction & Market Insight Engine

A beginner-friendly data science project built in Python (Google Colab) that predicts future gold rates in both **US Dollars ($)** and **Indian Rupees (₹)**. 

Unlike traditional "black-box" models, this project explains the **"why"** behind the price movements using key global economic indicators.

---

## 🚀 Features
* **Live Financial Data Integration:** Automatically pulls historical data from Yahoo Finance (`yfinance`) for Gold, Silver, Oil, and the S&P 500.
* **Dual Currency Output:** Predicts prices in both **USD (per 10g)** and **INR (per 10g)**.
* **Interactive Inputs:** Pauses to let users input live/custom market values to get an instant prediction.
* **Human-Readable Explanations:** Breaks down feature importance (showing how much weight Silver, Oil, and Stocks had on the prediction).
* **Visual Analytics:** Generates side-by-side comparison graphs showing actual vs. AI-predicted prices.

---

## 🧠 Why These Factors?
* **Silver (`SLV`):** Moves hand-in-hand with gold as a precious metal safe-haven asset.
* **S&P 500 (`^GSPC`):** Represents general stock market health and investor risk appetite.
* **Crude Oil (`USO`):** Acts as a primary indicator for global inflation and energy costs.

---

## 🛠️ Tech Stack
* **Language:** Python 3
* **Environment:** Google Colab / Jupyter Notebook
* **Libraries:** `yfinance`, `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

---

## ⚙️ How to Run
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload or copy-paste the code from the notebook into a new cell.
3. Run the cell (`Shift + Enter`), enter your custom market metrics when prompted, and view the AI predictions!
