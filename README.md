# Bond Convexity Analysis

This project explores the pricing behavior of fixed-income instruments, focusing on **bond convexity** and **duration** using real-world U.S. Treasury and corporate bond yields. It uses Python, Jupyter, and data from the **FRED (Federal Reserve Economic Data)** database.

---

## 📈 What This Project Does

- 📊 Downloads daily yield data for:
  - 5-Year Treasury (DGS5)
  - 10-Year Treasury (DGS10)
  - 30-Year Treasury (DGS30)
  - AAA Corporate Bonds (DAAA)

- 💰 Defines pricing logic for fixed-coupon bonds
- 🔍 Calculates:
  - **Price**
  - **Macaulay Duration**
  - **Convexity**

- 🔁 Compares different bonds (short-term vs. long-term, low vs. high coupon)
- 🧠 Simulates interest rate changes and estimates price sensitivity using duration and convexity
- 📉 Visualizes:
  - Yield trends over time
  - Bond price vs. yield curves
  - Convexity across bond structures

---

## 🧮 Key Concepts

### 📌 Bond Price
The present value of a bond’s future cash flows (coupons + face value), discounted at the market yield (YTM).

### ⏱️ Macaulay Duration
A measure of a bond's interest rate sensitivity — the weighted average time until cash flows are received.

### 📐 Convexity
The rate of change of duration. It shows how much duration itself changes as yields change — capturing the bond’s curvature in price / yield space.

---

## 🔢 Modeling and Outputs

### ✅ Data Snapshot
```text
Most Recent Yields:
5Y Treasury      3.99%
10Y Treasury     4.43%
30Y Treasury     4.96%
Corporate AAA    5.50%
