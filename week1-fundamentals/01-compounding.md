# Chapter 1.1: Compounding: The Engine Behind All Wealth

> **Core**

> **What you'll learn:** what compounding is and why it's exponential rather than linear, the formulas you need (and how to run them in a spreadsheet), the Rule of 72, why *time* matters more than *amount*, how compounding works in reverse (costs and debt), and the behavioral trap that kills compounding.

---

## 1. Simple interest vs compound interest

Start with the difference between two ways money can grow.

**Simple interest:** you earn interest only on the *original* amount you put in.

**Compound interest:** you earn interest on the original amount *plus* all the interest you've already earned. Your returns start generating returns of their own.

### Worked example: ₹1,00,000 at 10% a year

| Year | Simple interest: balance | Compound interest: balance | Interest earned that year (compound) |
|---|---|---|---|
| 0 | 1,00,000 | 1,00,000 | — |
| 1 | 1,10,000 | 1,10,000 | 10,000 |
| 2 | 1,20,000 | 1,21,000 | 11,000 |
| 3 | 1,30,000 | 1,33,100 | 12,100 |
| 5 | 1,50,000 | 1,61,051 | 14,641 |
| 10 | 2,00,000 | 2,59,374 | 23,579 |
| 20 | 3,00,000 | 6,72,750 | 61,159 |
| 30 | 4,00,000 | 17,44,940 | 1,58,631 |

Look at the last column. In year 1 you earned ₹10,000. In year 30 you earned ₹1,58,631 in a *single year*, on the same original ₹1 lakh, at the same 10% rate. Nothing about the investment changed. The only difference is that by year 30, the pile earning interest is 17× bigger.

- With **simple interest**, growth is a **straight line** (+₹10,000 every year).
- With **compound interest**, growth is a **curve that keeps getting steeper** (exponential).

In the early years the two look almost identical: after 3 years the gap is only ₹3,100. That's why people underestimate compounding. The magic is invisible at first and overwhelming later.

---

## 2. The formulas

### 2.1 Lump sum (one-time investment)

```
FV = PV × (1 + r)^n
```
- **FV** = future value (what you'll have)
- **PV** = present value (what you invest today)
- **r** = rate of return per period (as a decimal: 12% = 0.12)
- **n** = number of periods

**Example:** ₹1,00,000 for 20 years at 12%:
FV = 1,00,000 × (1.12)^20 = 1,00,000 × 9.646 = **₹9,64,629**

**Spreadsheet:** `=100000*(1+12%)^20`, or `=FV(12%, 20, 0, -100000)`

### 2.2 Regular monthly investment (SIP)

When you invest the same amount every month, each instalment compounds for a different length of time: the first for the whole period, the last for just one month. The formula adds all of these up:

```
FV = P × [((1 + i)^n − 1) / i] × (1 + i)
```
- **P** = monthly investment
- **i** = monthly rate = annual rate / 12
- **n** = number of months
- The final `× (1 + i)` is there because SIPs are paid at the **start** of each month, so each instalment gets one extra month of growth.

**Spreadsheet:** `=FV(12%/12, 20*12, -5000, 0, 1)` gives the value of ₹5,000/month for 20 years at 12% (≈ ₹49.96 lakh).

### 2.3 Working backwards: how much do I need to invest?

If you know the target, find the required monthly SIP:
`=PMT(12%/12, 15*12, 0, -5000000, 1)` gives the monthly SIP needed to reach ₹50 lakh in 15 years at 12% (≈ ₹9,900/month).

### 2.4 Finding the return: CAGR

**CAGR (Compound Annual Growth Rate)** is the steady yearly rate that would take you from a starting value to an ending value.

```
CAGR = (Ending value / Starting value)^(1/years) − 1
```
**Example:** a fund's NAV went from ₹50 to ₹120 in 7 years.
CAGR = (120/50)^(1/7) − 1 = (2.4)^0.1429 − 1 = **13.3% a year**

Why not just say "it went up 140%"? Because 140% over 7 years and 140% over 15 years are completely different results. CAGR puts everything on a per-year basis so you can compare investments fairly.

**Spreadsheet:** `=(120/50)^(1/7)-1`, or `=RRI(7, 50, 120)`

> **XIRR:** for SIPs, where money goes in on many dates, CAGR doesn't work directly. You use **XIRR** (`=XIRR(values, dates)`), with each investment as a negative number and the current value as a positive number on today's date. Mutual fund apps show XIRR for your SIP portfolio.

---

## 3. The three levers of compounding

Look at the formula `FV = PV × (1 + r)^n`. There are exactly three things you can change:

### Lever 1: Time (n), the most powerful
Time is the **exponent**, so it has an outsized effect.

₹1,00,000 invested once:
| Years | At 8% | At 12% |
|---|---|---|
| 10 | ₹2.16 L | ₹3.11 L |
| 20 | ₹4.66 L | ₹9.65 L |
| 30 | ₹10.06 L | ₹29.96 L |
| 40 | ₹21.72 L | ₹93.05 L |

At 12%, going from year 30 to year 40 adds **₹63 lakh**, more than double everything accumulated in the first 30 years. **The last decade does most of the work.** That's why you can't "catch up" later by investing harder: you can't buy back the final years.

### Lever 2: Rate of return (r)
Small differences in the rate become huge over long periods. In the table above, 12% vs 8% over 40 years is **₹93 L vs ₹22 L**, more than 4× more money from a 4-percentage-point difference.

This works in reverse too: **costs reduce r**. A fund charging 1.5% instead of 0.2% cuts your effective rate by 1.3% every year, and over 25–30 years that compounds into lakhs of rupees (see Chapter 2.5).

### Lever 3: Amount (PV or P)
This is the one you directly control today: your savings rate. It's linear. Investing twice as much gives you twice as much, no more. It matters, but it can't make up for lost time.

---

## 4. Case study: the early starter vs the late starter

Three friends each invest ₹5,000 a month into an equity index fund earning 12% a year. Everyone stops looking at age 60.

| | Invests from | Invests until | Years investing | Total invested | Value at 60 |
|---|---|---|---|---|---|
| **Asha** | 22 | 32, **then stops** and lets it grow | 10 | ₹6 L | **₹3.29 Cr** |
| **Bharat** | 32 | 60 | 28 | ₹16.8 L | **₹1.38 Cr** |
| **Chitra** | 22 | 60 | 38 | ₹22.8 L | **₹4.67 Cr** |

**Asha invested about a third of what Bharat did, and ended with about 2.4× as much.** Her ₹11.6 L at age 32 had 28 extra years to compound (monthly, at 12%). Bharat can never catch up, because he can't buy those years back.

Chitra, who started early *and* kept going, ends with the most by far.

### The cost of delay
₹10,000/month at 12% until age 60:
- Start at **25** (35 years): **₹6.50 Cr**
- Start at **35** (25 years): **₹1.90 Cr**

To end with the same ₹6.5 Cr, the person starting at 35 would need to invest about **₹34,200/month**, nearly 3.5× as much, every month, for 25 years.

**Lesson: a 10-year delay is not a 10-year problem. It's a 3.5× problem.**

---

## 5. The Rule of 72: compounding in your head

```
Years to double ≈ 72 ÷ annual rate (%)
```

| Rate | Years to double |
|---|---|
| 3% (savings account) | 24 |
| 6% | 12 |
| 7% (FD) | ~10 |
| 9% | 8 |
| 12% (equity, long run) | 6 |
| 18% | 4 |
| 36% (credit card interest) | 2 |

**Using it in reverse:** to double your money in 5 years you'd need about 72/5 = 14.4% a year. If someone promises to double your money in 2 years (36% a year), be extremely suspicious.

**Chained doubling:** at 12%, money doubles every 6 years. In 36 years that's 6 doublings: 2^6 = **64×**. ₹1 lakh becomes about ₹64 lakh (the exact figure is about ₹59 L; the rule is an approximation).

**For inflation:** at 6% inflation, prices double every 12 years. Your ₹50,000/month lifestyle will cost ₹1 lakh/month in 12 years, and ₹2 lakh/month in 24 years.

---

## 6. Compounding frequency

Interest can compound yearly, quarterly, monthly or daily. More frequent compounding gives slightly more.

12% compounded monthly = (1 + 0.01)^12 − 1 = **12.68%** effective annual rate.

That's why banks quote a *nominal* FD rate (e.g. 7%, compounded quarterly) that's slightly lower than the **effective annual yield** (≈7.19%). For long-term thinking, the difference is small compared with time and rate. Just know that it exists.

---

## 7. Compounding in reverse: debt and costs

Compounding doesn't care whose side it's on.

### Credit cards
Unpaid credit card balances in India typically carry **3–3.75% interest per month (36–45% a year)**, compounded monthly. At 42%, debt doubles in under 2 years. Paying only the "minimum due" (usually 5%) can keep you in debt for years.
**Rule:** never carry a credit card balance. No investment reliably earns 40%.

### Personal loans, Buy-Now-Pay-Later, consumer EMIs
Rates of 12–24% are common. "No-cost EMI" often hides the cost in the product price or a processing fee.

### Fees on investments
A 2% annual fee on a portfolio doesn't cost you "2%". Over 30 years, it compounds into a loss of roughly **a third or more of your final corpus** compared with a near-zero fee.

---

## 8. The behavioral trap: interrupting compounding

Compounding only works if it's **left alone for a long time**. The ways people interrupt it:
1. **Panic selling during crashes.** They lock in losses and miss the recovery. The best days in the market usually come right after the worst ones, and missing just the 10 best days over 20 years can roughly halve your returns.
2. **Withdrawing for consumption:** using investments for a phone, car or vacation.
3. **Stopping SIPs** when markets fall, which is exactly when SIPs buy the most units.
4. **Constant switching** between funds or "hot" themes. Each switch can trigger tax and exit loads, and resets your patience.
5. **Choosing dividend (IDCW) options** that pay money out instead of reinvesting it.

Charlie Munger: *"The first rule of compounding: never interrupt it unnecessarily."*

---

## 9. Common misconceptions

| Myth | Reality |
|---|---|
| "I'll start investing when I earn more." | Time is worth more than amount. ₹2,000/month from 22 nearly matches ₹10,000/month from 35 by age 60 (₹1.87 Cr vs ₹1.90 Cr at 12%), on a fifth of the monthly amount. |
| "12% a year means I'll see 12% every year." | 12% is a long-run *average*. Individual years can be +40% or −30%. |
| "Compounding is about getting high returns." | It's about *reasonable* returns for an *unusually long* time. |
| "A few years' delay doesn't matter." | It costs you the *final* years of compounding, which are the biggest ones. |

---

## 10. Summary

- Compound growth is **exponential**: slow at first, then explosive.
- Key formulas: `FV = PV(1+r)^n`, the SIP formula, `CAGR = (End/Start)^(1/n) − 1`, and the spreadsheet functions `FV`, `PMT`, `RRI`, `XIRR`.
- **Time > rate > amount.** Start early, keep costs low, keep going.
- **Rule of 72:** years to double ≈ 72 / rate.
- Compounding works *against* you through debt and fees.
- The biggest risk to compounding is **your own behavior**.

## Self-check questions
1. ₹2 lakh grows to ₹5 lakh in 8 years. What's the CAGR?
2. Using the Rule of 72, how long does money take to double at 9%? At 4%?
3. Why does starting 10 years later need *more than* 2× the monthly investment to catch up?
4. Name two ways compounding works against you.
5. What does the final `× (1+i)` in the SIP formula represent?

<details><summary>Answers</summary>

1. (5/2)^(1/8) − 1 ≈ 12.1%
2. 8 years; 18 years
3. Because the lost years are the final, largest years of growth, and growth is exponential, not linear.
4. Credit card or loan interest; fund expense ratios and fees (also inflation).
5. SIPs are paid at the start of each month, so every instalment gets one extra month of growth.
</details>
