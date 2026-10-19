# Chapter 2.7: How to Read a Fund Factsheet (and Value Research)

> **What you'll learn:** where to find factsheets and fund data, every important field on a factsheet and what it tells you, how to read returns correctly (point-to-point vs rolling, CAGR vs XIRR, TRI benchmarks), portfolio analysis, risk metrics (standard deviation, beta, Sharpe, Sortino, alpha, R-squared, drawdown), debt-specific fields, and a step-by-step evaluation checklist.

---

## 1. Where to find fund information

| Source | What you get |
|---|---|
| **AMC monthly factsheet** (PDF on the AMC website) | Official data for all schemes: portfolio summary, returns, risk ratios, expense ratio, managers |
| **SID (Scheme Information Document)** | The legal document: objective, asset allocation limits, risks, exit load, benchmark |
| **KIM (Key Information Memorandum)** | A short summary of the SID |
| **Monthly portfolio disclosure** | The full list of holdings (AMCs must publish it monthly) |
| **Value Research Online** (valueresearchonline.com) | Free fund pages with returns, ranks, risk, portfolio, overlap tool, SIP calculators |
| **Morningstar India** | Fund analysis, ratings, portfolio X-ray |
| **AMFI website** (amfiindia.com) | NAV history, AUM data, **tracking error and tracking difference data** for index funds and ETFs, the riskometer |

---

## 2. Fund basics section

| Field | What it means | What to look for |
|---|---|---|
| **Scheme name** | Including plan and option, e.g. "– Direct Plan – Growth" | Make sure it's **Direct** and **Growth** |
| **Category** | SEBI category | Compare only within the same category |
| **Investment objective** | What the fund aims to do | Should be clear and specific |
| **Benchmark** | The index the fund measures itself against | Should be a **TRI** (Total Return Index) and appropriate to the category |
| **Inception / allotment date** | When the fund (or its direct plan) launched | Direct plans started on 1 Jan 2013. Prefer 5+ years of history for active funds. |
| **Fund manager(s)** | Name, experience, **managing since** | Has the manager behind the track record changed recently? |
| **AUM (Assets Under Management)** | Total money in the scheme | Too small (< ₹100–200 Cr) can mean higher costs or closure risk. Very large AUM can hurt mid- and small-cap funds' agility. |
| **Expense ratio (TER)** | Direct and regular, separately | Lower is better. Compare with category peers. |
| **Exit load** | Early-redemption fee | Note the period |
| **Minimum investment** | Lump sum and SIP minimums | |
| **Riskometer** | SEBI's 6-level risk label (Low → Very High) | Equity funds will be "Very High". Make sure that matches your expectations. |

---

## 3. Returns section: reading it correctly

### 3.1 What's shown
Usually the **CAGR** for 1 year, 3 years, 5 years, 10 years and since inception, **next to the benchmark's returns** (and sometimes an "additional benchmark" like the Nifty 50).

Factsheets also often show "value of ₹10,000 invested" and **SIP returns** (XIRR of a hypothetical monthly SIP).

### 3.2 Common mistakes when reading returns
1. **Looking only at 1-year returns.** One year is noise for equity. Any fund can have a great year. Focus on 5- and 10-year numbers and consistency.
2. **Comparing across categories.** A small-cap fund's 30% return vs a large-cap fund's 15% isn't a fair comparison. The risk was completely different.
3. **Comparing against the price index instead of the TRI.** The TRI includes dividends and is the proper benchmark.
4. **Ignoring the start and end date effect (point-to-point bias).** Returns measured from a market bottom look fantastic. From a market top, terrible. The same fund can look like a star or a dud depending on the dates.

### 3.3 Rolling returns: the better tool
**Rolling returns** compute the return for **every possible period** of a given length. For example, every 5-year window, starting each day or month over the last 10–15 years. They show:
- **Average** 5-year return
- **Minimum** and **maximum** 5-year return
- **% of periods the fund beat its benchmark**
- **% of periods with negative returns** or returns below a threshold (e.g. < 8%)

**Example interpretation:** "Over all 5-year rolling periods since 2010, the fund's average CAGR was 13.5% vs the benchmark's 12.8%. It beat the benchmark in 68% of periods, and its worst 5-year return was 4%."
This tells you much more about **consistency** than "5-year return: 18%".

Value Research, Morningstar and other tools (e.g. freefincal's rolling return calculators) show rolling returns.

### 3.4 CAGR vs absolute return vs XIRR
| Measure | Use for |
|---|---|
| **Absolute return** | Total % gain, regardless of time. Only useful for periods under 1 year. |
| **CAGR** | Annualised return for a single lump-sum investment |
| **XIRR** | Annualised return for **multiple cash flows at different dates** (SIPs, top-ups, withdrawals). Use it to judge your own SIP portfolio. |

---

## 4. Portfolio section

| Field | What it tells you |
|---|---|
| **Top 10 holdings (% of assets)** | Concentration. If the top 10 make up more than 50–60%, the fund is concentrated. |
| **Number of stocks** | 25–35 = concentrated. 50–80 = typical diversified. 100+ = very diversified or index-like. |
| **Sector allocation** | Is there a big bet on one sector (e.g. 35% in financials)? Does it match your comfort level? |
| **Market-cap split** (large/mid/small %) | Does it match the label? A "large cap" fund should be ≥80% large. Is a flexi cap secretly a small-cap fund? This is **style drift**. |
| **Cash holding %** | High cash (> 5–10%) means the manager is waiting, which is a form of market timing and creates cash drag in rising markets |
| **Portfolio turnover ratio** | % of the portfolio traded in a year. Low (< 30–50%) = patient, buy-and-hold. High (> 100%) = frequent trading, higher hidden costs. Index funds: low. |
| **Foreign holdings** | Some flexi-cap funds hold international stocks |
| **Portfolio valuation metrics** | Portfolio P/E, P/B, dividend yield. Is the fund holding expensive or cheap stocks relative to the index? |

### Overlap check
If you hold two funds, compare their holdings. Value Research and Morningstar portfolio tools show **overlap %**. Above 50–60% overlap means you're largely duplicating.

### Active share (advanced)
**Active share** measures how much a fund's holdings differ from its benchmark (0% = identical, 100% = no overlap). An active fund with active share below 50–60% is likely a **closet indexer**: you're paying active fees for an index-like portfolio. Not every factsheet shows it, but you can eyeball it by comparing the top holdings with the index.

---

## 5. Risk metrics: what each one means

Factsheets typically compute these over the last 3 years using monthly returns.

### Standard deviation (SD)
- Measures **how widely the returns swing** around their average: **volatility**.
- **Example:** a fund with an average return of 12% and an SD of 15% will, in roughly two-thirds of years, return between −3% and +27%.
- **Lower SD for similar returns = smoother ride.** Compare with category peers and the benchmark.

### Beta
- Measures **sensitivity to the market (benchmark)**.
- **Beta = 1:** moves with the market. **1.2:** about 20% more volatile (if the market falls 10%, it tends to fall 12%). **0.8:** about 20% less volatile.
- An index fund's beta ≈ 1.

### Sharpe ratio
```
Sharpe = (Fund return − Risk-free rate) / Standard deviation
```
- **Return earned per unit of total risk** above the risk-free rate (e.g. T-bill yield).
- **Higher is better.** It compares funds with different risk levels on a level field.
- Example: Fund A returns 14% with an SD of 16%. Fund B returns 13% with an SD of 11%. Risk-free rate is 6%.
  - Sharpe A = (14−6)/16 = **0.50**
  - Sharpe B = (13−6)/11 = **0.64** → B delivered more return per unit of risk.

### Sortino ratio
- Like Sharpe, but uses only **downside deviation** (bad volatility). Investors don't mind upside swings.
- **Higher is better.** Useful for comparing how well funds protect on the downside.

### Alpha
- The return **above (or below) what the fund's beta would predict**, a rough measure of the manager's value added.
- **Positive and consistent alpha** is what active investors pay for. Negative alpha = underperformance after adjusting for risk.
- Treat it with caution: it's backward-looking and sensitive to the period chosen.

### R-squared
- How much of the fund's movement is **explained by the benchmark** (0–100).
- **Index fund:** ~99+. **Active fund with R² of 95+:** probably close to the index (a closet indexer?). **Lower R²:** a genuinely different portfolio.

### Maximum drawdown
- The **largest peak-to-trough fall** in NAV over a period.
- Example: if a fund fell from ₹100 to ₹58 in 2020, its max drawdown was −42%.
- **Ask yourself: could I have held through this?** It's the most intuitive risk measure.

### Upside / downside capture ratio
- **Upside capture of 110%:** when the benchmark rose, the fund captured 110% of the rise.
- **Downside capture of 85%:** when the benchmark fell, the fund fell only 85% as much.
- Ideal: upside > 100, downside < 100.

### Summary table
| Metric | Measures | Better is |
|---|---|---|
| Standard deviation | Total volatility | Lower |
| Beta | Market sensitivity | Depends (≈1 for index funds; < 1 = defensive) |
| Sharpe | Return per unit of total risk | Higher |
| Sortino | Return per unit of downside risk | Higher |
| Alpha | Excess return vs risk-adjusted expectation | Positive, consistent |
| R-squared | Similarity to benchmark | ~100 for index funds |
| Max drawdown | Worst fall | Smaller |
| Downside capture | Fall relative to the market | < 100% |

---

## 6. Index-fund-specific fields

| Field | What to look for |
|---|---|
| **Tracking error** | Lower is better. Good Nifty 50 funds are around 0.02–0.1%. |
| **Tracking difference** (often on AMFI and Value Research rather than the factsheet) | Index return − fund return. Should be close to the expense ratio. Lower is better. |
| **Expense ratio** | The main cost difference between index funds |
| **AUM** | Larger is generally better for index funds (lower impact costs, more stability) |
| **Benchmark** | Make sure it's the exact index you want (Nifty 50 vs Nifty 100 vs Nifty 50 Equal Weight are different) |

---

## 7. Debt-fund-specific fields

| Field | Meaning | Look for |
|---|---|---|
| **YTM** | Portfolio yield if held to maturity | Compare within category. Unusually high = more risk. |
| **Modified duration** | % NAV change per 1% rate change | Match it to your time horizon |
| **Macaulay duration** | Basis for SEBI categories | Within the category limits |
| **Average maturity** | Average time to maturity | |
| **Credit rating breakdown** | % Sovereign / AAA / AA / below | Mostly Sovereign/AAA for safety |
| **PRC matrix cell** | Max credit and rate risk (e.g. A-I, B-II) | The A column for conservative needs |
| **Top issuers** | Concentration in single companies | No large exposures to weaker names |

---

## 8. Step-by-step fund evaluation checklist

**Step 1: Is it the right type of fund?**
- [ ] Category matches my goal and time horizon
- [ ] Direct plan, growth option
- [ ] Riskometer level is acceptable to me

**Step 2: Costs**
- [ ] Expense ratio is low relative to category peers
- [ ] Exit load is acceptable for my horizon

**Step 3: Performance (active funds)**
- [ ] Compared with the correct **TRI** benchmark
- [ ] **Rolling** 3- and 5-year returns: beats the benchmark in most periods
- [ ] 5- and 10-year track record, not just recent returns
- [ ] Same fund manager for most of the track record

**Step 4: Portfolio**
- [ ] Market-cap split matches the label (no style drift)
- [ ] No extreme sector or stock concentration
- [ ] Reasonable turnover. Not a closet indexer.
- [ ] Low overlap with funds I already hold

**Step 5: Risk**
- [ ] SD and max drawdown are tolerable for me
- [ ] Sharpe/Sortino competitive within the category
- [ ] Downside capture < 100% (nice to have)

**Step 6 (index funds): replace Steps 3–4 with:**
- [ ] Lowest tracking difference among peers
- [ ] Low tracking error
- [ ] Large enough AUM, a few years of history

---

## 9. Summary

- Use the **AMC factsheet**, **SID** and **Value Research / Morningstar** pages.
- Compare within the **same category** against the **TRI** benchmark.
- Prefer **rolling returns** over point-to-point returns. Use **XIRR** for SIPs.
- Check the portfolio for **concentration, style drift, turnover and overlap**.
- Key risk metrics: **SD, beta, Sharpe, Sortino, alpha, R², max drawdown**.
- Index funds: **tracking difference, tracking error, TER, AUM**. Debt funds: **YTM, modified duration, credit quality, PRC**.

## Self-check questions
1. Why are rolling returns more informative than a fund's 5-year point-to-point return?
2. Fund A: 15% return, 18% SD. Fund B: 13% return, 12% SD. Risk-free = 6%. Which has the better Sharpe ratio?
3. An active large-cap fund has an R-squared of 98 and a beta of 1.0. What does that suggest?
4. What's style drift, and how would you detect it on a factsheet?
5. What three numbers matter most when comparing two Nifty 50 index funds?

<details><summary>Answers</summary>

1. They show performance across all possible start dates, revealing consistency and removing start/end date bias.
2. A: (15−6)/18 = 0.50. B: (13−6)/12 = 0.58. **B** is better.
3. It behaves almost exactly like the index. It's likely a closet indexer, so an index fund would be cheaper.
4. When a fund's holdings stray from its label (e.g. a large-cap fund holding many mid caps). Check the market-cap split.
5. Tracking difference, tracking error and expense ratio (plus AUM as a sanity check).
</details>
