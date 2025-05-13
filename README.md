# 🏦 J.P. Morgan Quantitative Finance Virtual Experience (Forage)

This repository contains my solutions to the **Quantitative Finance Virtual Internship** offered by **J.P. Morgan & Co. via Forage**. It simulates real-world tasks performed by a quant analyst working on a trading desk, focusing on **time series forecasting** and **commodity pricing models**.

---

## 📌 Overview

### ✅ Task 1 – Natural Gas Price Forecasting

**Objective:**  
Estimate and extrapolate the purchase price of natural gas using historical data.

**Deliverables:**
- Loaded and cleaned monthly natural gas price data (from Oct 2020 to Sep 2024).
- Conducted exploratory data analysis (EDA) to observe seasonal patterns and trends.
- Built a **SARIMA model** to forecast gas prices.
- Performed **hyperparameter tuning** for optimal performance.
- Extrapolated prices for an additional **12-month period** to support long-term contract pricing.
- Created a function to return predicted price based on any date input.

### 📈 Key Skills:
`Time Series Analysis`, `SARIMA`, `EDA`, `Forecasting`, `Matplotlib`, `Pandas`, `Statsmodels`

---

### ✅ Task 2 – Gas Storage Contract Pricing Model

**Objective:**  
Build a prototype pricing model for gas storage contracts by simulating various injection and withdrawal scenarios.

**Approach:**
- Developed a pricing function that accounts for:
  - Injection and withdrawal dates
  - Commodity price on those dates
  - Flow rates (injection/withdrawal)
  - Storage limits
  - Storage cost
- Simulated **cash flows** for various strategies and calculated the **contract value**.
- Assumed ideal market conditions (no transport delays, zero interest rate, no holidays).
- Designed logic for both **manual scenario testing** and **future automation**.

### 💡 Key Skills:
`Pricing Models`, `Time Series Analysis`, `Python`, `Machine-Learning`

---

## 🚀 How to Use This Repository

You can run this project directly on **Google Colab** without setting up anything locally:

### ✅ Steps:
  Download the datset, from the link beleow....
1. **Clone the repository** to your system:
   ```bash
   git clone <repository-url>
   ```
   Replace `<repository-url>` with the actual link to this repo.

2. Go to [Google Colab](https://colab.research.google.com/)

3. Click on **File > Upload notebook**  
   and upload the `.ipynb` file from the cloned folder and run the file

   -----------------
   **DATASET**
   --
      
      https://drive.google.com/file/d/1-tWYPmv9bD8VXKCthHEaU1UHsbJeWSA6/view?usp=drive_link

