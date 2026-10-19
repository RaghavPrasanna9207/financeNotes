# Chapter 1.6: Week 1 Output: SIP Compounding Spreadsheet

> **Core**

> **Goal:** build a spreadsheet that shows how a monthly SIP grows over 10 and 20 years, next to what that money is *actually* worth after inflation. Building it yourself makes Chapters 1.1 and 1.2 concrete.

Use Excel or Google Sheets. Allow 40–60 minutes.

---

## Part A: Yearly summary table (uses the `FV` function)

### Step 1: Input cells
Put your assumptions at the top so you can change them and watch everything update.

| Cell | Label (column A) | Value (column B) |
|---|---|---|
| A1 / B1 | Monthly SIP (₹) | 5000 |
| A2 / B2 | Expected annual return | 12% |
| A3 / B3 | Inflation | 6% |
| A4 / B4 | Annual SIP step-up | 10% |

### Step 2: Table headers (row 6)
| A | B | C | D | E | F |
|---|---|---|---|---|---|
| Year | Total invested | Portfolio value | Value in today's ₹ | Gain (₹) | Gain (%) |

### Step 3: Formulas (row 7, then fill down to year 20 in row 26)
| Column | Formula in row 7 | Meaning |
|---|---|---|
| A | `1` (then `=A7+1` below) | Year number |
| B | `=$B$1*12*A7` | Total money you've put in |
| C | `=FV($B$2/12, A7*12, -$B$1, 0, 1)` | Value of the SIP after that many years |
| D | `=C7/(1+$B$3)^A7` | Same value deflated to today's purchasing power |
| E | `=C7-B7` | Profit in rupees |
| F | `=E7/B7` | Profit as % of invested |

**About the `FV` function:** `FV(rate, nper, pmt, pv, type)`
- `rate` = monthly rate = annual / 12
- `nper` = number of months
- `pmt` = monthly SIP, **negative** because it's money leaving your pocket
- `pv` = 0 (no starting lump sum)
- `type` = 1, because SIPs are invested at the **start** of each month

### Reference results (₹5,000/month, 12%, 6% inflation, no step-up)
| Year | Invested | Portfolio value | In today's ₹ |
|---|---|---|---|
| 5 | ₹3.0 L | ₹4.12 L | ₹3.08 L |
| 10 | ₹6.0 L | ₹11.6 L | ₹6.5 L |
| 15 | ₹9.0 L | ₹25.2 L | ₹10.5 L |
| 20 | ₹12.0 L | ₹50.0 L | ₹15.6 L |

If your numbers match these, your formulas are right.

---

## Part B: Month-by-month sheet with step-up

`FV` can't handle a SIP that increases every year, so build a second sheet with one row per month.

| A: Month | B: SIP this month | C: Portfolio value | D: Total invested |
|---|---|---|---|
| 1 | `=Sheet1!$B$1*(1+Sheet1!$B$4)^INT((A2-1)/12)` | `=(0+B2)*(1+Sheet1!$B$2/12)` | `=B2` |
| 2 | (fill down) | `=(C2+B3)*(1+Sheet1!$B$2/12)` | `=D2+B3` |

Fill down to month 240 (20 years).
- Column B raises the SIP by the step-up % every 12 months.
- Column C adds this month's SIP to last month's value and grows it by one month's return.

Compare the month-240 value with and without the step-up (set B4 to 0%). With a 10% annual step-up, the 20-year corpus is about **₹99 L instead of ₹50 L**, roughly double, because the step-up also keeps your investing in line with your rising income and with inflation.

---

## Part C: Comparison columns
Add these next to Part A to make the lessons obvious:
1. **Same SIP in an FD at 7%:** `=FV(7%/12, A7*12, -$B$1, 0, 1)`. Watch the gap open up after year 10.
2. **FD post-tax (30% slab):** use rate `7%*(1-30%)`.
3. **Real return %:** `=(1+$B$2)/(1+$B$3)-1`
4. **Different equity returns:** a scenario table at 8%, 10%, 12% and 14% (Data → What-If Analysis → Data Table in Excel).

## Part D: Optional chart
Select columns A, B, C and D and insert a line chart. Three lines (invested, nominal value, real value) show compounding's curve and inflation's drag clearly.

---

## What to write down when you're done
Answer these in 2–3 lines each, under the table:
1. How much did years 11–20 add compared with years 1–10? Why? (Expected: years 11–20 add about ₹38 L vs ₹11.6 L for years 1–10, about 3×, even though you invested the same ₹6 L in each decade.)
2. What's the gap between the nominal and real value at year 20? What does that mean for goal planning?
3. How much difference did the 10% step-up make?
4. Equity (12%) vs FD (7%) at year 20: what's the difference in rupees? (Expected: about ₹50 L vs ₹26 L, before the FD's tax.)
