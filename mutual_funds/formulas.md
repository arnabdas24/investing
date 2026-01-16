# Investment Return Metrics  
**Absolute Return | CAGR | XIRR | Rolling Returns**

This document explains the most commonly used return metrics in investments, with **plain mathematical formulas** and **simple examples**.

---

## 1. Absolute Return

### Definition
Absolute Return measures the **total percentage gain or loss** on an investment over a period, without considering the time taken.

### Formula
Absolute Return = (Ending Value − Beginning Value) ÷ Beginning Value

### Example
- Investment Amount: ₹1,00,000  
- Ending Value: ₹1,30,000  

Absolute Return  
= (1,30,000 − 1,00,000) ÷ 1,00,000  
= **30%**

### Key Characteristics
- Does **not** consider time
- Easy to calculate
- Can be misleading for long-term investments

### Best Used When
- Investment duration is **less than one year**
- A quick performance check is needed

---

## 2. CAGR (Compound Annual Growth Rate)

### Definition
CAGR represents the **annualized growth rate** of an investment, assuming it grows at a steady rate every year.

### Formula
CAGR = (Ending Value ÷ Beginning Value)^(1 ÷ n) − 1  

Where:  
n = number of years

### Example
- Investment Amount: ₹1,00,000  
- Ending Value after 3 years: ₹1,50,000  

CAGR  
= (1,50,000 ÷ 1,00,000)^(1 ÷ 3) − 1  
≈ **14.47% per year**

### Key Characteristics
- Considers time
- Assumes lump-sum investment
- Ignores volatility in between

### Best Used When
- Comparing **long-term lump-sum investments**
- Comparing funds over the same time period

---

## 3. XIRR (Extended Internal Rate of Return)

### Definition
XIRR calculates the **annualized return** for investments made at **different times and amounts**, accounting for the time value of money.

### Formula
Sum of all cash flows discounted to present value = 0

Mathematically:  
Σ [ Cᵢ ÷ (1 + r)^(tᵢ) ] = 0

Where:  
- Cᵢ = cash flow (investment is negative, final value positive)  
- r = XIRR  
- tᵢ = time in years from the first investment  

### Example (SIP)
| Date | Cash Flow |
|----|----|
| Jan 2022 | −10,000 |
| Feb 2022 | −10,000 |
| Mar 2022 | −10,000 |
| Jan 2025 | +38,000 |

The value of **r** that satisfies the equation is the **XIRR**.

### Key Characteristics
- Considers exact dates of investment
- Most realistic return measure
- Handles SIPs and irregular cash flows

### Best Used When
- SIP investments
- Portfolios with multiple transactions
- Real investor performance analysis

---

## 4. Rolling Returns

### Definition
Rolling Returns measure returns over **overlapping fixed periods**, instead of one start and end date.

### Formula (Rolling CAGR)
Rolling Return = (Value at End of Period ÷ Value at Start of Period)^(1 ÷ n) − 1  

Where:  
n = rolling period in years (e.g., 1-year, 3-year, 5-year)

### Example (3-Year Rolling Return)
Assume NAV data from 2015 to 2025:

- 2015 → 2018 return = 12%  
- 2016 → 2019 return = 9%  
- 2017 → 2020 return = 15%  
- 2018 → 2021 return = 11%  

These multiple observations together form **rolling returns**.

### Key Characteristics
- Removes timing bias
- Shows consistency
- Highlights risk and volatility

### Best Used When
- Comparing mutual funds
- Studying performance across market cycles

---

## Comparison Summary

| Metric | Considers Time | Cash Flow Type | Shows Consistency | Best Use Case |
|------|---------------|---------------|------------------|--------------|
| Absolute Return | No | Single | No | Short-term return |
| CAGR | Yes | Lump sum | No | Long-term comparison |
| XIRR | Yes | Multiple | No | SIP / portfolio return |
| Rolling Returns | Yes | Lump sum | Yes | Consistency & risk |

---

## Key Takeaways

- **Absolute Return** is simple but incomplete  
- **CAGR** is useful but hides volatility  
- **XIRR** reflects the true investor experience  
- **Rolling Returns** reveal stability and risk over time
