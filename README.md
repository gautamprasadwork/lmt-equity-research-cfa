# Lockheed Martin — CFA-Framework Equity Research Model

> **Equity Research Assignment** | MSc Quantitative Finance | PUEB | 2025  
> **Author:** Gautam Prasad | [LinkedIn](https://linkedin.com/in/gautamprasadwork)

---

## What This Project Is About

A **9-sheet CFA-framework equity research model** for **Lockheed Martin Corporation (NYSE: LMT)** — the world's largest defense contractor ($71.1B revenue, FY2024). Built using the CFA Institute's equity analysis framework, the model performs:

- Comprehensive financial statement analysis
- 20+ financial ratios including DuPont decomposition
- Altman Z-Score credit risk assessment
- Peer benchmarking across 4 major defense contractors
- Red flags analysis for earnings quality

**Key finding:** LMT's 81% ROE is driven by financial leverage, not operational efficiency — flagged as a structural risk signal. Stock concluded **~12% overvalued** relative to sector median EV/EBITDA.

---

## Repository Structure

```
lockheed-martin-equity-research/
│
├── LMT_Equity_Research.xlsx    # 9-sheet CFA model (see sheet breakdown below)
└── README.md
```

### Excel Workbook — Sheet Structure

| Sheet | Contents |
|---|---|
| **Cover** | Overview, ticker, analyst, date |
| **Income Statement** | Consolidated P&L (USD Millions), FY2022–2024 |
| **Balance Sheet** | Assets, liabilities, equity — 3-year history |
| **Efficiency & Cash Flow** | Operating efficiency metrics, FCF analysis |
| **Ratio Analysis** | 20+ financial ratios across profitability, liquidity, leverage, efficiency |
| **DuPont Analysis** | 3-stage DuPont decomposition: Net Margin × Asset Turnover × Equity Multiplier |
| **Red Flags Analysis** | CFA earnings quality framework — accruals, quality of earnings |
| **Peer Comparison** | Benchmarking vs RTX, NOC, GD, BA on key multiples |
| **IFRS vs GAAP** | Lockheed Martin (US GAAP) vs BAE Systems (IFRS) accounting differences |

---

## Key Findings

### DuPont Decomposition — The 81% ROE Signal

```
ROE = Net Profit Margin × Asset Turnover × Equity Multiplier
    = 9.8%           × 1.34           × 6.18
    = 81.0%
```

**Interpretation:** LMT's extremely high ROE is **not** driven by superior profitability margins or asset efficiency — it is almost entirely a function of **high financial leverage** (Equity Multiplier = 6.18x). This is a red flag: if leverage is reduced (e.g., by debt repayment), ROE collapses significantly.

### Altman Z-Score

| Score Range | Interpretation |
|---|---|
| > 2.99 | Safe zone |
| 1.81 – 2.99 | Grey zone |
| < 1.81 | Distress zone |

LMT's Z-Score analysis is documented in the Ratio Analysis sheet.

### Peer Benchmarking — Defense Contractors (FY2024)

| Metric | LMT | RTX | NOC | GD | BA |
|---|---|---|---|---|---|
| EV/EBITDA | [in model] | [in model] | [in model] | [in model] | [in model] |
| Net Margin | ~9.8% | — | — | — | — |
| ROE | ~81% | — | — | — | — |
| Debt/Equity | High | — | — | — | — |

Detailed peer data is available in the **Peer Comparison** sheet of the workbook.

### Valuation Conclusion

- Based on sector median **EV/EBITDA** multiple applied to LMT's EBITDA
- LMT appears approximately **12% overvalued** relative to peer group median
- Recommendation consistent with a **SELL / UNDERPERFORM** signal at prevailing price

---

## What This Model Demonstrates

| Skill | Where It Appears |
|---|---|
| Financial statement analysis | Income Statement, Balance Sheet sheets |
| Ratio analysis (20+ ratios) | Ratio Analysis sheet |
| DuPont decomposition | DuPont Analysis sheet |
| Earnings quality / red flags | Red Flags Analysis sheet |
| Relative valuation | Peer Comparison sheet |
| Cross-accounting framework knowledge | IFRS vs GAAP sheet |
| Excel modelling (linked formulas) | All sheets — all figures linked from source data |

---

## Data Sources

- **LMT Financial Statements:** FY2024 10-K filing (SEC EDGAR)
- **Peer Data:** Bloomberg / company annual reports (FY2024)
- **Sector Multiples:** Damodaran dataset, CFA Institute research standards

---

## Tools Used

- **Microsoft Excel** — CFA-framework 9-sheet model with linked cell references and dynamic ratio calculations

---

## Author

**Gautam Prasad**  
MSc Quantitative Finance — PUEB, Poznań, Poland  
[linkedin.com/in/gautamprasadwork](https://linkedin.com/in/gautamprasadwork)
