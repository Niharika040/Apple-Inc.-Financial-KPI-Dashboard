# Apple-Inc.-Financial-KPI-Dashboard

This project performs a detailed financial analysis of **Apple Inc.** using real-time financial statement data pulled from **Yahoo Finance** via the `yfinance` Python library. The focus is on calculating **key financial KPIs** and visualizing Apple’s performance trends using Python.

---

## 🔍 Project Objectives

- ✅ Fetch and transform Apple’s financial statements (income, balance sheet, cash flow)
- ✅ Calculate key financial KPIs:
  - Net Profit Margin (%)
  - Debt-to-Asset Ratio
  - Free Cash Flow
- ✅ Visualize trends using Python libraries (matplotlib & seaborn)
- ✅ Simulate a real-world analyst dashboard workflow

---

## 📚 Tools & Technologies

| Tool          | Purpose                           |
|---------------|-----------------------------------|
| `Python`      | Core programming language         |
| `pandas`      | Data manipulation                 |
| `yfinance`    | Fetching financial data from Yahoo|
| `matplotlib`  | Basic plotting                    |
| `seaborn`     | Enhanced visualization            |
| `Jupyter`     | Interactive notebook environment  |

---

## 💼 Key Performance Indicators (KPIs)

### 📈 Net Profit Margin (%)
Net Profit Margin = Net Income\Total Revenue \times 100

### 📊 Debt-to-Asset Ratio
Debt to Asset Ratio = Total Liabilities\Total Assets

### 💵 Free Cash Flow
Free Cash Flow = Operating Cash Flow - Capital Expenditures

---

## 🧠 Project Workflow

1. **Data Collection:** Used `yfinance.Ticker("AAPL")` to get Apple’s financial data.
2. **Data Transformation:** Transposed data and merged the Income, Balance Sheet, and Cash Flow tables.
3. **KPI Calculation:** Computed profit margins, debt ratios, and free cash flows.
4. **Visualization:** Created the following plots:
    - 📘 Net Income over time
    - 📙 Revenue vs Net Income
    - 📗 Net Profit Margin trends
    - 📕 Debt-to-Asset Ratio
    - 💰 Free Cash Flow trends

---



## 📌 Key Insights / Conclusion

- 📈 **Consistent Revenue Growth**: Apple has demonstrated strong top-line growth year-over-year, with total revenue increasing consistently. This reflects the company’s ability to maintain market dominance, introduce new products, and drive global demand.

- 💹 **High Net Profit Margin**: Apple maintains a healthy **net profit margin**, often above industry averages. This indicates excellent cost control, pricing power, and a scalable business model with high profitability.

- 🧾 **Strong Asset Base with Low Financial Risk**: The **Debt-to-Asset Ratio** remains low, which means Apple has a solid capital structure and is not overly dependent on borrowing. This reduces financial risk and increases investor confidence.

- 💰 **Robust Free Cash Flow (FCF)**: Apple consistently generates large amounts of **free cash flow**, allowing it to invest in R&D, buy back shares, pay dividends, and pursue acquisitions — all without raising external capital.

- 🧠 **Efficient Use of Resources**: Apple's ability to convert revenue into profit and generate cash from operations highlights its operational efficiency and mature financial management.

- 📊 **Recession-Resilient Business Model**: Even in challenging economic periods, Apple's financial statements show resilience, thanks to strong brand loyalty, ecosystem lock-in, and global diversification.

- 📉 **Areas of Monitoring**: While Apple’s financial health is excellent, close monitoring of **capital expenditure trends**, **global market dynamics**, and **product innovation cycles** is essential for sustaining this performance.

---

## 🎯 Business Recommendation
 Based on this financial analysis, Apple Inc. is a financially stable and strategically sound company. Its profitability, liquidity, and efficient asset management make it a strong candidate for long-term investment or strategic partnership.

---
## ▶️ How to Run

```bash
# Clone this repository
git clone https://github.com/Niharika040/apple-financial-dashboard.git
cd apple-financial-dashboard

# Install dependencies
pip install pandas matplotlib seaborn yfinance

# Open and run the notebook
jupyter notebook apple_financial_analysis.ipynb
