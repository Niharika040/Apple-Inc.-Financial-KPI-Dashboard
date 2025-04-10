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
\[
\text{Net Profit Margin} = \left(\frac{\text{Net Income}}{\text{Total Revenue}}\right) \times 100
\]

### 📊 Debt-to-Asset Ratio
\[
\text{Debt to Asset Ratio} = \frac{\text{Total Liabilities}}{\text{Total Assets}}
\]

### 💵 Free Cash Flow
\[
\text{Free Cash Flow} = \text{Operating Cash Flow} - \text{Capital Expenditures}
\]

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


## ▶️ How to Run

```bash
# Clone this repository
git clone https://github.com/Niharika040/apple-financial-dashboard.git
cd apple-financial-dashboard

# Install dependencies
pip install pandas matplotlib seaborn yfinance

# Open and run the notebook
jupyter notebook apple_financial_analysis.ipynb
