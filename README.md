
## 📘 Course Summary: Econometrics for Economics and Finance Professionals

This course provides both theoretical and practical knowledge in financial econometrics, including:

---

### 📈 Asset Pricing Models
- **CAPM**: Estimates expected return based on systematic risk.
- **Fama-French 3-Factor Model**: Extends CAPM by adding:
  - SMB (Small Minus Big): firm size factor
  - HML (High Minus Low): value factor
- Applied to real-world stock data (e.g., Disney, GE).

---

### 🐍 Practical Implementation with Python
- Tools: `pandas`, `matplotlib`, `statsmodels`
- Tasks:
  - Compute excess returns and perform regressions
  - Visualize price and return trends
  - Compare model fit using R², AIC, BIC

---

### 💼 Modern Portfolio Theory (Markowitz Model)
- Constructs optimal portfolios balancing risk and return
- Concepts:
  - Efficient Frontier & Capital Allocation Line (CAL)
  - Sharpe Ratio & diversification
- Quantifies portfolio risk using variance-covariance

---

### 📊 Analytical Findings
- **Disney**: Positive Alpha, moderate aggressiveness (Beta ≈ 1.1), less sensitive to SMB/HML
- **GE**: Insignificant Alpha, highly aggressive (Beta ≈ 1.23), strongly influenced by SMB/HML
- **Investment Strategy**:
  - Disney suits conservative investors
  - GE suits risk-tolerant investors
  - Diversification balances risk/reward

---
"""

# Ghi nội dung vào cuối file README.md
with open("README.md", "a", encoding="utf-8") as f:
    f.write("\n")
    f.write(summary)
