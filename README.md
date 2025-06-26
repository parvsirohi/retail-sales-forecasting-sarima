# 📈 Retail Sales Forecasting with Time Series

This project forecasts monthly retail sales using time series analysis techniques like ARIMA and SARIMA. The aim is to support inventory decisions by predicting future sales trends.

---

## 🔍 Problem Statement

Retail businesses face challenges in managing inventory efficiently. By forecasting future sales, companies can:
- Reduce overstock and stockouts
- Optimize supply chain planning
- Make data-driven decisions

---

## 📦 Dataset

- **Source**: Simulated retail transaction data
- **Period**: Jan 2023 – Jan 2024
- **Fields**:
  - Transaction ID
  - Date
  - Product Category
  - Total Amount
  - Customer Demographics

---

## ⚙️ Tech Stack

- Python 3.x
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `sklearn`

---

## 🧠 Methodology

1. **Data Aggregation** – Monthly total sales
2. **EDA** – Trend & seasonal insights using visualizations
3. **Decomposition** – Time series split into trend, seasonal, residual
4. **Stationarity Check** – ADF test
5. **Modeling** – SARIMA
6. **Forecasting** – Predict next 6 months
7. **Evaluation** – MAPE score

---

## 📊 Output

output/forecast_plot.png

---

## 📁 Project Structure

```
Retail-Sales-Forecasting/
├── retail_sales_dataset.csv
├── Retail_Sales_Forecasting.ipynb
├── README.md
├── requirements.txt
├── output/
│   └── forecast_plot.png
```

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/parvsirohi/retail-sales-forecasting.git
cd retail-sales-forecasting

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook Retail_Sales_Forecasting.ipynb
```

---

## 📌 MAPE Score

The model achieved a **Mean Absolute Percentage Error (MAPE)** of approximately **72.20%**, highlighting opportunities for improvement with more data.

---

## 📬 Contact

Made by Parv Sirohi – feel free to reach out on [LinkedIn](www.linkedin.com/in/parv-sirohi-)
