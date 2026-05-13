# Ari Jain

UCSD Mathematics & Computer Science + International Business, June 2026.
Interested in quantitative research — signal construction, statistical
modeling, and rigorous out-of-sample evaluation on noisy financial data.

## Featured research

### 📈 [Cross-Sectional Momentum Signal Research](https://github.com/aj80457/momentum-signal-research)
End-to-end study of a classic 12-1 month equity momentum signal on a
50-name US large-cap universe, 2005–2024. Constructs the signal,
backtests long-short quintile portfolios with turnover-aware transaction
costs, evaluates information coefficient with Newey-West-adjusted
t-statistics, and discusses the limits of the result honestly (mean IC
≈ 0.01, t-stat &lt; 1 — consistent with published findings of post-2010
arbitrage erosion).

**Stack:** Python, pandas, NumPy, scikit-learn, statsmodels.
**Highlights:** unit-tested no-lookahead invariant, in-sample / OOS
split at 2018, 5-bps turnover-weighted cost model, executed notebook
with full diagnostics.

### 📉 [Volatility Forecasting: HAR-RV vs GARCH(1,1) vs Random Forest](https://github.com/aj80457/volatility-forecasting)
Walk-forward out-of-sample comparison of three models for SPY 5-day
realized variance, 2010–2024. Evaluates under RMSE, proxy-noise-robust
QLIKE loss, and Mincer-Zarnowitz regression, with a Newey-West-adjusted
Diebold-Mariano test for equal predictive accuracy. HAR-RV wins (DM t ≈
−1.7 vs Random Forest), consistent with the published literature that
ML flexibility does not help at daily frequency without richer features.

**Stack:** Python, pandas, NumPy, statsmodels, `arch` (GARCH),
scikit-learn (Random Forest).
**Highlights:** common `.fit / .predict` interface across model
families, 8 unit tests including proxy-loss identities, executed
notebook with regime-by-regime diagnostics.

## Core skills

- **Languages:** Python (primary), C++, R, SQL
- **Quant stack:** NumPy, pandas, scikit-learn, statsmodels, `arch`, SciPy
- **Methods:** time-series modeling, hypothesis testing, regression /
  classification, optimization, walk-forward CV, robust loss functions
- **Coursework:** Probability &amp; Statistics, Machine Learning,
  Optimization, Algorithms, Graph Theory, Macroeconomics

## What I'm looking for

Quantitative research roles — trading-signal development, statistical
modeling, applied-math problems on data-intensive systems. Graduating
June 2026; available for full-time and summer 2026 internships.

## Contact

📧 ari.j41771@gmail.com · 📞 408-406-8929

---

*Disclosure: research in this profile uses public market data only and
is not investment advice.*
