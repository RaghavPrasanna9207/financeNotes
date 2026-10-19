# Chapter 4.8: Using Screener.in: A Practical Walkthrough

> **Core**, except §3 (building stock screens), which you can skip for now

> **What you'll learn:** how to navigate a company page on Screener.in section by section, what each number means and where it connects to Chapters 4.2–4.7, how to customise ratios, how to use peer comparison, charts, shareholding and documents, how to build stock screens with the query language, and a step-by-step 30-minute analysis routine.

---

## 1. What Screener.in is
- A free website (with an optional paid tier) providing **10–12 years of standardised financial data** for every company listed on NSE and BSE.
- Data comes from company filings (annual reports, quarterly results, shareholding patterns).
- **Create a free account** to customise ratios, save screens and build watchlists.
- Similar tools: Tijori Finance, Trendlyne, Tickertape, Moneycontrol. Screener is the most popular for fundamental analysis.

---

## 2. The company page, section by section

Search for a company (e.g. "Asian Paints"). At the top-right there's a toggle between **Consolidated** and **Standalone** figures. Use **consolidated** in most cases (Chapter 4.1).

### 2.1 Header and top ratios box
| Field | Meaning | Chapter |
|---|---|---|
| **Market Cap** | Price × shares | 1.5 |
| **Current Price**, High/Low | 52-week range | |
| **Stock P/E** | Price / trailing 12-month EPS | 4.5 |
| **Book Value** | Net worth per share | 4.3 |
| **Dividend Yield** | DPS / price | 4.5 |
| **ROCE**, **ROE** | Latest year's returns | 4.5 |
| **Face Value** | Nominal value per share | 4.3 |

**Customise it: click "Edit ratios"** (when logged in) and add:
- `Debt to equity`
- `Pledged percentage`
- `Promoter holding`
- `Sales growth 5Years`, `Profit growth 5Years`
- `Return on equity 5Years` (average)
- `PEG Ratio`
- `Free cash flow 3years` (or `Free cash flow last year`)
- `Interest Coverage Ratio`
- `Price to book value`, `EV/EBITDA`
- `Current ratio`
- `Industry PE` (to compare)

Once saved, these appear for every company you open.

### 2.2 About, Pros and Cons
- A short business description.
- **Pros/Cons:** machine-generated observations such as "Company is almost debt free", "Stock is trading at 8x book value", "Promoter holding has decreased", "Company has a low return on equity of 8% over last 3 years". **A quick starting point only. Always verify.**

### 2.3 Chart
- Price chart with volume. Switch to **"PE Ratio"** to see the P/E history with its **median**, which shows whether the stock is expensive or cheap relative to its own past (Chapter 4.5).
- Other options: EV/EBITDA, Price to Book, Sales and Margin, etc.

### 2.4 Peer comparison
- A table of similar companies in the same industry: **P/E, market cap, dividend yield, profit, sales growth, ROCE**.
- You can **add columns** (Edit columns) such as OPM, D/E, ROE 5Y.
- **Use it to see whether the company is better or worse than peers**, and whether its valuation premium is justified.

### 2.5 Quarterly results
- The **last 12–13 quarters**: Sales, Expenses, Operating Profit, OPM %, Other Income, Interest, Depreciation, PBT, Tax %, Net Profit, EPS.
- **Read YoY** (same quarter last year) because of seasonality.
- Look for **momentum**: are sales and margins improving or deteriorating recently?

### 2.6 Profit & Loss (annual)
- **10–12 years** of annual data: Sales, Expenses, Operating Profit, **OPM %**, Other Income, Interest, Depreciation, PBT, Tax %, **Net Profit**, **EPS**, **Dividend Payout %**.
- Below the table, **summary boxes**:
  - **Compounded Sales Growth:** 10Y / 5Y / 3Y / TTM
  - **Compounded Profit Growth:** 10Y / 5Y / 3Y / TTM
  - **Stock Price CAGR:** 10Y / 5Y / 3Y / 1Y
  - **Return on Equity:** 10Y / 5Y / 3Y / last year
- These four boxes alone give a quick read of **growth, returns and how the stock has rewarded shareholders**.
- Click on a line (e.g. "Expenses +") to expand its breakdown (material cost %, employee cost %, etc.).

### 2.7 Balance sheet
- **10+ years** of: Equity Capital, **Reserves**, **Borrowings**, Other Liabilities, Total Liabilities, **Fixed Assets**, **CWIP**, **Investments**, Other Assets, Total Assets.
- Expand "Other Assets" to see **receivables, inventory and cash**.
- **Checks:**
  - Equity Capital rising → **dilution?** (Chapter 4.7)
  - Borrowings trend vs reserves (D/E)
  - CWIP stuck for years?
  - Reserves growing steadily?

### 2.8 Cash flows
- **10+ years** of: **Cash from Operating Activity**, Investing Activity, Financing Activity, Net Cash Flow.
- Newer versions also show **Free Cash Flow** and **CFO/OP** (operating cash flow as % of operating profit).
- **Checks:**
  - **Sum of CFO vs sum of Net Profit** (Chapter 4.4). Copy both rows into a spreadsheet, or just add them mentally.
  - Pattern of signs (+, −, −) (Chapter 4.4).

### 2.9 Ratios
- Yearly: **Debtor Days, Inventory Days, Days Payable, Cash Conversion Cycle, Working Capital Days, ROCE %**.
- **Look for trends.** Rising debtor days or working capital days is a warning (Chapter 4.7). Stable or high ROCE suggests a moat (Chapter 4.6).

### 2.10 Shareholding pattern
- Quarterly (and yearly): **Promoters %, FIIs %, DIIs %, Government %, Public %, number of shareholders**.
- **Checks:**
  - Promoter holding trend (stable is good; steady decline is a concern)
  - **Pledge** (shown separately or via the "Pledged percentage" ratio)
  - FII and DII interest (institutional ownership rising or falling)

### 2.11 Documents
- **Announcements** (exchange filings), **Annual Reports** (by year), **Credit Ratings** (reports from CRISIL, ICRA, CARE, etc.), **Concalls** (transcripts, presentations, recordings, notes).
- **This is where qualitative research happens.** Read at least:
  - The latest **annual report's MD&A** and **auditor's report**
  - The last **one or two concall transcripts**
  - The latest **credit rating report**: it's free and very detailed

---

## 3. Building stock screens

Screener lets you **filter all listed companies** using a simple query language. Go to **"Screens" → "Create new screen"**.

### Syntax
- Use ratio names exactly as Screener lists them (it suggests as you type)
- Operators: `>`, `<`, `=`, `AND`, `OR`
- Values in ₹ crore and % (without the % sign)

### Example 1: quality companies at a glance
```
Market Capitalization > 5000 AND
Return on capital employed > 18 AND
Average return on capital employed 5Years > 18 AND
Debt to equity < 0.3 AND
Sales growth 5Years > 10 AND
Profit growth 5Years > 12 AND
Pledged percentage = 0
```

### Example 2: consistent cash generators
```
Market Capitalization > 2000 AND
Free cash flow 3years > 0 AND
Cash from operations last year > Net profit last year * 0.8 AND
Return on equity > 15 AND
Debt to equity < 0.5
```

### Example 3: reasonable valuation with growth
```
Market Capitalization > 1000 AND
Price to Earning < Industry PE AND
PEG Ratio < 1.5 AND
Profit growth 3Years > 15 AND
Return on capital employed > 15
```

### Using screen results
- Sort by any column. Add columns via "Edit columns".
- **A screen is a starting list, not a buy list.** Every name still needs the full analysis (qualitative, red flags, valuation).
- Explore **public screens** created by other users for ideas, but understand the logic before using one.

---

## 4. Watchlists and alerts
- Add companies to a **watchlist** to track them.
- Set up **email alerts** for new results, announcements and concalls.

---

## 5. A 30-minute company analysis routine

| Step | Time | What to look at | Questions |
|---|---|---|---|
| 1 | 3 min | **About + Pros/Cons + top ratios** | What does it do? Any obvious strengths or warnings? |
| 2 | 5 min | **P&L (annual) + growth boxes** | 10-year sales and profit growth? Steady? OPM stable? |
| 3 | 3 min | **Quarterly results** | Recent momentum, YoY |
| 4 | 4 min | **Balance sheet** | Debt trend, reserves, dilution (equity capital), CWIP |
| 5 | 4 min | **Cash flows** | Cumulative CFO vs PAT. FCF positive? |
| 6 | 3 min | **Ratios tab** | ROCE trend, debtor and working capital days trend |
| 7 | 2 min | **Shareholding** | Promoter %, pledge, trend |
| 8 | 3 min | **Peer comparison** | Better or worse than peers? Valuation premium justified? |
| 9 | 3 min | **Chart → PE ratio vs median** | Expensive or cheap relative to history? |
| + | 30–60 min (separately) | **Documents:** concall transcript, annual report MD&A, auditor's report, credit rating | Qualitative judgement, management candour, red flags |

---

## 6. Common mistakes when using Screener
1. **Using standalone instead of consolidated** for groups with large subsidiaries.
2. **Reading one year or one quarter** instead of 10-year trends.
3. **Trusting Pros/Cons blindly.** They're automated.
4. **Comparing across industries** (a bank's D/E with an FMCG company's).
5. **Running screens and buying the output** without further analysis.
6. **Ignoring the Documents section**, where the qualitative story and red flags often hide.
7. **Mistaking bonus issues and splits for dilution.** Check the announcements for a bonus or split when equity capital changes.

---

## 7. Summary
- Screener gives 10+ years of standardised financials. **Use consolidated figures.**
- Customise the **top ratios** (D/E, pledge, 5-year growth, ROE 5Y, FCF, PEG, interest coverage).
- Walk through: **P&L → Quarterly → Balance sheet → Cash flows → Ratios → Shareholding → Peers → PE chart → Documents.**
- **Screens** filter thousands of companies quickly. Treat them as a starting list only.
- Follow the **30-minute routine**, then read the concall and annual report.

## Self-check questions
1. Which four summary boxes under the P&L give a quick read of a company?
2. How would you check on Screener whether a stock is expensive relative to its own history?
3. Write a simple screen for companies with ROCE above 20%, no pledging and debt-to-equity below 0.2.
4. Where on Screener would you find the latest credit rating report?
5. Equity capital doubled in one year. What should you check before concluding it's dilution?

<details><summary>Answers</summary>

1. Compounded Sales Growth, Compounded Profit Growth, Stock Price CAGR, Return on Equity.
2. Chart → "PE Ratio", and compare the current P/E with the median line.
3. `Return on capital employed > 20 AND Pledged percentage = 0 AND Debt to equity < 0.2`
4. Documents section → Credit Ratings.
5. Whether a bonus issue or stock split happened (announcements). Those change share capital without diluting value.
</details>
