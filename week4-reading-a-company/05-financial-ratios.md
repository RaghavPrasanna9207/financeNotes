# Chapter 4.5: Financial Ratios: The Five That Matter (and Their Supporting Cast)

> *Based on Varsity's Fundamental Analysis module (financial ratio chapters).*
>
> **What you'll learn:** how to use ratios properly, the five core ratios from the plan (revenue growth, ROE, debt-to-equity, P/E, free cash flow) in depth, with ABC Paints as the worked example, supporting ratios (ROCE, margins, interest coverage, efficiency ratios, P/B, EV/EBITDA, PEG, dividend yield), the DuPont breakdown of ROE, industry-specific ratios, and a ratio scorecard.

---

## 1. How to use ratios

A ratio relates two numbers so you can judge **performance, health and valuation** quickly. Rules:
1. **A single ratio in isolation means little.** Always compare:
   - **Over time:** the company's own 5–10 year trend
   - **Against peers:** companies in the same industry
2. **Industry context matters.** A 10% margin is excellent for a retailer and poor for a software firm.
3. **Ratios are clues, not conclusions.** An odd number is a reason to dig into the statements and notes.
4. **Use consolidated figures** and consistent periods.

### ABC Paints: the inputs (₹ crore, from Chapters 4.2–4.4)
| Item | Value | Item | Value |
|---|---|---|---|
| Revenue (latest) | 10,000 | Net worth (equity) | 6,750 |
| Revenue (previous year) | 8,800 | Total borrowings | 500 |
| Revenue (4 years ago) | 6,000 | Cash | 600 |
| EBITDA | 2,000 | Total assets | 10,000 |
| EBIT | 1,850 | Inventory | 1,800 |
| Interest | 50 | Receivables | 1,200 |
| PAT | 1,350 | Payables | 1,500 |
| PAT (4 years ago) | 750 | COGS (materials) | 5,500 |
| EPS | ₹13.50 | CFO | 1,500 |
| Dividend per share | ₹5.40 | Capex | 800 |
| Share price | ₹540 | Shares | 100 Cr |
| Market cap | 54,000 | Book value per share | ₹67.50 |

---

## 2. Core ratio 1: Revenue growth ("Is the business getting bigger?")

### Formulas
```
YoY revenue growth = (Revenue this year − Revenue last year) / Revenue last year
Revenue CAGR (n years) = (Revenue now / Revenue n years ago)^(1/n) − 1
```

### ABC Paints
- YoY: (10,000 − 8,800) / 8,800 = **13.6%**
- 4-year CAGR: (10,000 / 6,000)^(1/4) − 1 = **13.6%**
- Profit (PAT) 4-year CAGR: (1,350 / 750)^(1/4) − 1 = **15.8%**

### How to interpret
- **Benchmark:** India's nominal GDP grows about 10–12% a year. A company growing revenue consistently **faster** than that is gaining share or riding a growing industry.
- **Consistency beats spikes.** 12–15% every year is better than +40%, −10%, +30%, −5%.
- **Quality of growth:**
  - **Volume vs price:** growth from selling more units is healthier than growth purely from price hikes.
  - **Organic vs acquired:** growth through acquisitions can mask a stagnant core business.
- **Profit growth vs revenue growth:**
  - Profit growing **faster** than revenue → margins expanding (operating leverage, pricing power).
  - Profit growing **slower** → margins shrinking (competition, cost pressure).
- Screener shows "Compounded Sales Growth" and "Compounded Profit Growth" for 3, 5 and 10 years.

---

## 3. Core ratio 2: ROE, Return on Equity ("How well does it use shareholders' money?")

### Formula
```
ROE = Net profit (PAT) / Shareholders' equity (net worth)
```
(Analysts often use **average** equity of the opening and closing balance sheets.)

### ABC Paints
ROE = 1,350 / 6,750 = **20%**

For every ₹100 of shareholders' money in the business, ABC earns ₹20 of profit a year.

### Why ROE matters so much
- A company that can **reinvest** its profits at a high ROE grows its equity, and therefore its earnings, quickly **without needing outside money**.
- **Sustainable growth rate ≈ ROE × (1 − dividend payout ratio)**
  - ABC: 20% × (1 − 0.40) = **12%**. ABC can grow about 12% a year from internal funds alone.
- Over long periods, a stock's return tends to track the company's ROE (if bought at a reasonable valuation). Charlie Munger made this point about long-term holdings.

### Benchmarks
- **≥ 15%** consistently: good
- **≥ 20% for 10 years:** excellent (a sign of a moat)
- **< 10%:** poor. Below the cost of equity, which destroys value.
- Compare with the **cost of equity** (~12–14% in India): ROE below that means shareholders would be better off in an index fund.

### The DuPont breakdown: *why* is ROE high?
```
ROE = Net profit margin × Asset turnover × Equity multiplier
    = (PAT / Revenue) × (Revenue / Total assets) × (Total assets / Equity)
```
| Component | Formula | ABC Paints | What drives it |
|---|---|---|---|
| Net profit margin | PAT / Revenue | 1,350 / 10,000 = **13.5%** | Pricing power, cost efficiency |
| Asset turnover | Revenue / Total assets | 10,000 / 10,000 = **1.0×** | How efficiently assets generate sales |
| Equity multiplier (leverage) | Total assets / Equity | 10,000 / 6,750 = **1.48×** | How much debt and other liabilities fund the assets |
| **ROE** | | 13.5% × 1.0 × 1.48 = **20%** | |

**Why this matters:** two companies can have the same 20% ROE for completely different reasons:
- Company X: high margins, low debt → **quality ROE**
- Company Y: thin margins, high debt (equity multiplier of 4) → **risky ROE**. If business slows, debt magnifies the damage.

**Always check ROE together with debt-to-equity.**

### ROE traps
- **High debt** inflates ROE (less equity in the denominator).
- **Buybacks or accumulated losses** shrink equity and can make ROE look artificially high.
- **One-time gains** inflate PAT.
- **Negative equity** makes ROE meaningless.

### ROCE: the debt-neutral sibling
```
ROCE = EBIT / Capital employed
Capital employed = Shareholders' equity + Total debt  (or Total assets − Current liabilities)
```
- ABC: 1,850 / (6,750 + 500) = **25.5%**
- ROCE measures return on **all** capital (equity + debt) and uses EBIT (before interest), so it **isn't distorted by leverage**.
- **Better than ROE for comparing companies with different debt levels**, and for capital-heavy industries.
- Benchmark: **> 15–20%** is good. ROCE should be well above the interest rate the company pays.

---

## 4. Core ratio 3: Debt-to-equity ("How much is borrowed?")

### Formula
```
Debt-to-equity (D/E) = Total borrowings / Shareholders' equity
```

### ABC Paints
D/E = 500 / 6,750 = **0.07**. Almost debt-free. In fact, cash (600) exceeds debt (500), so it's **net cash**.

### Benchmarks (non-financial companies)
| D/E | Interpretation |
|---|---|
| 0 – 0.3 | Conservative, very safe |
| 0.3 – 1.0 | Moderate. Fine for stable businesses. |
| > 1.0 | High. Risky, especially for cyclical businesses. |
| > 2.0 | Very high. Vulnerable to downturns and rate rises. |

### Why debt is dangerous
- **Interest must be paid in good years and bad.** Equity holders can wait for dividends; lenders can't be made to wait.
- In a downturn, high-debt companies can be forced to sell assets cheaply, dilute shareholders heavily, or go bankrupt. Equity can go to zero (e.g. Jet Airways, IL&FS, DHFL, Videocon).
- Morgan Housel's warning: **leverage turns ordinary risks into ruin.**

### Supporting debt ratios
| Ratio | Formula | ABC Paints | Benchmark |
|---|---|---|---|
| **Interest coverage ratio** | EBIT / Interest | 1,850 / 50 = **37×** | > 5× comfortable. < 2× dangerous. |
| **Net debt** | Debt − Cash & liquid investments | 500 − 600 = **−100** (net cash) | Negative = net cash |
| **Net debt / EBITDA** | Net debt / EBITDA | Negative | < 2× comfortable. > 4× risky. |
| **Current ratio** | Current assets / Current liabilities | (1,800 + 1,200 + 600 + 150) / (200 + 1,500 + 800) = 3,750 / 2,500 = **1.5** | > 1.2–1.5 means short-term obligations are covered |
| **Quick ratio** | (Current assets − Inventory) / Current liabilities | 1,950 / 2,500 = **0.78** | > 1 is conservative. Lower is OK if inventory sells quickly. |

### Exceptions
**Banks and NBFCs** borrow to lend. High leverage is their business model. For them, look at capital adequacy ratio (CAR), gross/net NPA, CASA ratio, net interest margin (NIM), credit costs, and ROA instead.

---

## 5. Core ratio 4: P/E, Price to Earnings ("How expensive is the stock?")

### Formula
```
P/E = Share price / EPS          (= Market cap / Net profit)
```

### ABC Paints
P/E = 540 / 13.50 = **40×**

You're paying ₹40 for every ₹1 of ABC's current annual profit. Put another way, at current profits it would take 40 years of earnings to "pay back" the price.

### Earnings yield: the inverse
```
Earnings yield = EPS / Price = 1 / P/E = 1 / 40 = 2.5%
```
Compare with the ~7% government bond yield: investors accept a 2.5% earnings yield only because they expect ABC's earnings to **grow** strongly for many years.

### What a P/E means
- A **high P/E** means the market expects **high future growth** and/or sees **high quality and safety** (strong brand, high ROE, low debt).
- A **low P/E** means the market expects **low growth, high risk, or problems**, or the stock may be genuinely undervalued.

### How to judge whether a P/E is reasonable
1. **Against the company's own history:** compare the current P/E with its 5- and 10-year median (Screener's chart → "PE ratio").
2. **Against peers:** other paint companies, or the same industry.
3. **Against the market:** the Nifty 50's P/E has historically averaged around 20–22×.
4. **Against growth (PEG ratio):**
   ```
   PEG = P/E / Expected annual EPS growth (%)
   ```
   ABC: if EPS growth is expected at about 15%, PEG = 40 / 15 = **2.7**. A PEG around 1 or below is often considered reasonable. Above 2 means you're paying a lot for the growth.

### P/E traps
| Trap | Explanation |
|---|---|
| **Value trap** | A low P/E because the business is in structural decline (earnings will keep falling) |
| **Cyclical trap** | Cyclicals (steel, metals, cement, sugar) look **cheapest at peak earnings** (low P/E) and **most expensive at the bottom** (high P/E on depressed earnings). For cyclicals, buying on low P/E often means buying at the top. |
| **One-time earnings** | Exceptional gains inflate EPS, making the P/E look low |
| **Loss-making companies** | P/E is meaningless (negative). Use other metrics. |
| **Trailing vs forward P/E** | Trailing P/E uses the last 12 months' EPS. Forward P/E uses estimates, which may be too optimistic. |

### Other valuation ratios
| Ratio | Formula | ABC Paints | Best used for |
|---|---|---|---|
| **P/B (Price to Book)** | Price / Book value per share | 540 / 67.5 = **8×** | Banks, NBFCs, asset-heavy companies |
| **EV/EBITDA** | Enterprise value / EBITDA, where EV = Market cap + Debt − Cash | (54,000 + 500 − 600) / 2,000 = **27×** | Comparing companies with different debt levels |
| **Price to Sales (P/S)** | Market cap / Revenue | 54,000 / 10,000 = **5.4×** | Early-stage or loss-making companies |
| **Dividend yield** | Dividend per share / Price | 5.40 / 540 = **1.0%** | Income-focused investors |
| **Dividend payout ratio** | Dividends / PAT | 540 / 1,350 = **40%** | Sustainability of dividends |
| **FCF yield** | FCF / Market cap | 700 / 54,000 = **1.3%** | Cash-based valuation |

**Remember:** a great business at a terrible price can be a poor investment. A P/E of 40 requires many years of strong growth to justify. If growth disappoints, both earnings *and* the P/E multiple can fall (a "de-rating"), which is a double hit.

---

## 6. Core ratio 5: Free cash flow ("Is real cash left over?")

### Formula
```
FCF = Cash from operations (CFO) − Capital expenditure (capex)
```

### ABC Paints
FCF = 1,500 − 800 = **₹700 Cr**

### Related measures
| Measure | Formula | ABC Paints | Healthy |
|---|---|---|---|
| **CFO / PAT** | CFO / Net profit | 1,500 / 1,350 = **111%** | ≥ 90–100% over 5–10 years |
| **FCF / PAT** | FCF / Net profit | 700 / 1,350 = **52%** | Positive. Higher = less capital-intensive. |
| **FCF yield** | FCF / Market cap | **1.3%** | Higher = cheaper |
| **Capex / Depreciation** | 800 / 300 = **2.7×** | > 1 = investing for growth (not just maintenance) | |

### How to interpret
- **Consistently positive and growing FCF** = the business funds itself and can return cash to shareholders.
- **Cumulative 10-year FCF** should be a meaningful share of cumulative 10-year PAT. If a company reports ₹5,000 Cr of profits over 10 years but generates zero FCF, where did the money go? (Usually into working capital or capex that didn't produce returns.)
- **Negative FCF** is acceptable during a **productive** expansion phase. Check that the capex later shows up in **revenue and profit growth**.
- **Capital-light businesses** (software, brands, platforms) convert most profit to FCF. **Capital-heavy ones** (telecom, steel, power) need constant reinvestment, so FCF is lower.

---

## 7. Efficiency (operating) ratios

| Ratio | Formula | ABC Paints | Interpretation |
|---|---|---|---|
| **Asset turnover** | Revenue / Total assets | **1.0×** | Higher = more sales per rupee of assets |
| **Fixed asset turnover** | Revenue / Net fixed assets | 10,000 / 4,000 = **2.5×** | |
| **Inventory days** | Inventory / COGS × 365 | **~119 days** | Lower = faster-moving stock |
| **Debtor (receivable) days** | Receivables / Revenue × 365 | **~44 days** | Lower = faster collection |
| **Payable days** | Payables / COGS × 365 | **~100 days** | Higher = more supplier credit |
| **Cash conversion cycle** | Inv. days + Debtor days − Payable days | **~63 days** | Lower is better. Negative is excellent. |
| **Working capital days** | (Current assets − Current liabilities) / Revenue × 365 | Screener shows this | A rising trend is a warning |

Watch **trends**: rising debtor days or inventory days over several years is a classic early warning.

---

## 8. Industry-specific ratios (a glimpse)
| Industry | Key metrics |
|---|---|
| **Banks / NBFCs** | NIM, Gross/Net NPA, CASA ratio, capital adequacy (CAR), ROA (≥ 1% good), credit cost, P/B |
| **IT services** | Revenue per employee, attrition, deal wins (TCV), utilisation, constant-currency growth |
| **Retail** | Same-store sales growth, revenue per sq ft, store count growth |
| **Telecom** | ARPU (average revenue per user), subscriber growth, churn |
| **Cement / steel** | Capacity utilisation, EBITDA per tonne, realisation per tonne |
| **FMCG** | Volume growth, distribution reach, ad spend as % of sales |
| **Insurance** | Embedded value, VNB margin, persistency, solvency ratio |

---

## 9. The ratio scorecard

| Category | Ratio | Green flag | Red flag | ABC Paints |
|---|---|---|---|---|
| Growth | Revenue CAGR (5–10y) | > 10–12%, steady | Erratic / declining | 13.6% ✅ |
| Growth | PAT CAGR | ≥ revenue growth | Far below revenue growth | 15.8% ✅ |
| Profitability | OPM | Stable or rising, ≥ peers | Falling | 20%, stable ✅ |
| Returns | ROE | > 15% for 5+ years | < 10%, or high only due to debt | 20% ✅ |
| Returns | ROCE | > 15–20% | < cost of debt | 25.5% ✅ |
| Leverage | D/E | < 0.5 | > 1, rising | 0.07 ✅ |
| Leverage | Interest coverage | > 5× | < 2× | 37× ✅ |
| Cash | CFO / PAT (cumulative) | ≥ 90% | < 60% | 111% ✅ |
| Cash | FCF | Positive, growing | Negative for years | ₹700 Cr ✅ |
| Efficiency | Cash conversion cycle | Low / falling | Rising | 63 days (watch) |
| Valuation | P/E vs history and peers | Near or below the median | Far above median, slowing growth | 40× ⚠️ (expensive) |
| Valuation | PEG | ≤ 1–1.5 | > 2.5 | 2.7 ⚠️ |

**Verdict on ABC Paints:** an **excellent business** (growth, ROE, no debt, strong cash), but at a **rich valuation**. It's a great company. Whether it's a great *investment* at ₹540 depends on whether it can sustain about 15%+ earnings growth for many years.

---

## 10. Summary
- Compare ratios **over time** and **against peers**. They're clues, not conclusions.
- **Revenue growth:** consistent and above GDP. Check volume vs price, and profit vs revenue growth.
- **ROE:** > 15% consistently. Use **DuPont** to see whether it comes from margins, efficiency or debt. **ROCE** is the debt-neutral version.
- **D/E:** < 0.5 for most companies. Check **interest coverage** (> 5×). Banks are different.
- **P/E:** compare with history, peers and growth (**PEG**). Beware **value traps** and **cyclical traps**.
- **FCF = CFO − capex:** positive and growing. **CFO/PAT ≈ 100%** over time.
- A **great business ≠ a great investment** at any price.

## Self-check questions
1. Company A: ROE 22%, D/E 2.5. Company B: ROE 18%, D/E 0.1. Which ROE is higher quality? Why?
2. A stock trades at ₹300 with EPS of ₹12. Expected EPS growth is 20%. Calculate the P/E and PEG.
3. Why do cyclical companies often look "cheapest" at the worst time to buy?
4. A company's ROE is 20% and it pays out 25% of profits as dividends. What's its sustainable growth rate?
5. Calculate the interest coverage: EBIT ₹600 Cr, interest ₹250 Cr. Is it comfortable?

<details><summary>Answers</summary>

1. B. A's ROE is boosted by heavy debt (risky), while B earns a high ROE with almost no debt.
2. P/E = 300 / 12 = 25. PEG = 25 / 20 = 1.25.
3. At the cycle's peak, earnings are temporarily very high, which makes the P/E look low just before earnings fall.
4. 20% × (1 − 0.25) = 15%.
5. 600 / 250 = 2.4×. Thin: a moderate fall in EBIT would make interest hard to cover.
</details>
