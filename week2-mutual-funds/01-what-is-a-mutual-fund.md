# Chapter 2.1: What a Mutual Fund Is and How It Works

> *Based on the mutual fund chapters of Zerodha Varsity's Personal Finance module.*
>
> **What you'll learn:** what a mutual fund is and why it exists, the legal structure that protects your money, how NAV is calculated, how units are bought and redeemed (cut-off times, settlement), open-ended vs closed-ended funds, ETFs and index funds, growth vs IDCW options, NFOs, and how to actually invest (platforms, KYC, CAS).

---

## 1. The idea

A **mutual fund (MF)** collects money from thousands of investors and pools it into one large portfolio. A professional **fund manager** invests that pool in stocks, bonds, gold or a mix, according to the fund's stated **objective** (e.g. "invest in the 50 companies of the Nifty 50" or "invest in high-quality short-term bonds").

Each investor receives **units** in proportion to the money they put in. If the portfolio grows 10%, every unit grows 10%, so every investor gains 10% on their money.

### Why mutual funds exist (what they solve)
| Problem for an individual | How a mutual fund solves it |
|---|---|
| Buying 50 stocks needs lakhs of rupees | You can start with ₹100–500 |
| You don't have time or skill to research companies or bonds | A professional manages it, or an index rule does |
| Owning a few stocks is risky | One fund holds 30–500 securities: instant diversification |
| Bonds are hard for retail investors to buy | Debt funds give easy access to government and corporate bonds |
| Tracking, rebalancing, collecting dividends | Handled for you |
| Liquidity | Open-ended funds can be redeemed on any business day |

### The cost of the solution
You pay an annual fee, the **expense ratio** (Chapter 2.5), and you accept the fund's choices.

### Scale in India
The Indian MF industry manages tens of lakh crores of rupees (well over ₹70 lakh crore in 2025–26) across 40+ fund houses, and monthly SIP inflows are now above ₹25,000 crore. The "**Mutual Funds Sahi Hai**" campaign by AMFI has made mutual funds mainstream.

---

## 2. The legal structure: why your money is safe from the fund house

Indian mutual funds are set up as **trusts** under SEBI (Mutual Funds) Regulations, 1996. The structure separates the people who **manage** the money from the people who **hold** and **oversee** it.

```
                ┌─────────────────────────┐
                │   SPONSOR               │  e.g. HDFC Bank, ICICI Bank +
                │   (promoter of the MF)  │  Prudential, SBI + Amundi
                └───────────┬─────────────┘
                            │ creates
                ┌───────────▼─────────────┐
                │   MUTUAL FUND TRUST     │  ← legally owns all the fund's
                │   overseen by TRUSTEES  │     assets on behalf of investors
                └──┬──────────┬────────┬──┘
         appoints  │          │        │ appoints
     ┌─────────────▼──┐ ┌─────▼──────┐ ┌▼──────────────────┐
     │      AMC       │ │ CUSTODIAN  │ │  RTA (Registrar)  │
     │ manages money, │ │ holds the  │ │ CAMS / KFintech:  │
     │ fund managers, │ │ securities │ │ investor records, │
     │ research       │ │ safely     │ │ unit allotment    │
     └────────────────┘ └────────────┘ └───────────────────┘
```

| Entity | Role |
|---|---|
| **Sponsor** | The financial institution that sets up the mutual fund. Must meet SEBI's net worth and track record criteria. |
| **Trust / Trustees** | Hold the assets **in trust for unit holders**. Trustees (a majority must be independent) supervise the AMC to make sure it follows regulations and acts in investors' interest. |
| **AMC (Asset Management Company)** | Runs the schemes: fund managers, research, operations, marketing. Earns the management fee. Examples: SBI Funds Management, HDFC AMC, ICICI Prudential AMC, Parag Parikh (PPFAS), UTI AMC. |
| **Custodian** | A separate regulated entity (often a bank) that physically holds the securities. The AMC can't touch them directly. |
| **RTA (Registrar & Transfer Agent)** | Maintains records of who owns how many units, processes purchases, redemptions and address changes. India's two main RTAs are **CAMS** and **KFintech**. |
| **SEBI** | Regulates everything: what funds can invest in, disclosures, expense caps, categorisation. |
| **AMFI** | The industry association. Registers distributors (ARN codes), publishes NAVs and data, runs investor education. |

### What this structure means for you
- **The fund's assets are not the AMC's assets.** If the AMC went bankrupt, your fund's securities would still be held by the custodian on behalf of the trust, and you'd still own your units.
- **Fraud risk is low** because of the separation of roles and SEBI supervision. (Contrast this with Ponzi schemes and unregulated "investment" apps.)
- **Market risk is NOT protected.** If the stocks or bonds in the fund fall in value, your units fall too. That's the line on every advertisement: *"Mutual fund investments are subject to market risks, read all scheme-related documents carefully."*

---

## 3. NAV: Net Asset Value

### Definition
**NAV is the per-unit value of a mutual fund scheme.**

```
NAV = (Market value of all securities + Cash + Accrued income − Liabilities − Expenses)
      ─────────────────────────────────────────────────────────────────────────────────
                            Total units outstanding
```

### Worked example
A fund holds:
- Shares worth ₹98 crore
- Cash of ₹2.5 crore
- Liabilities and accrued expenses of ₹0.5 crore
- Units outstanding: 5 crore

NAV = (98 + 2.5 − 0.5) / 5 = 100 / 5 = **₹20 per unit**

If you invest ₹10,000, you get 10,000 / 20 = **500 units**.
If the fund's portfolio rises 5% tomorrow, the NAV becomes about ₹21 and your 500 units are worth ₹10,500.

### Key facts about NAV
- **Calculated once a day**, after the market closes, using closing prices. Published on AMC websites and AMFI by late evening (11 PM).
- Unlike a share price, NAV **doesn't fluctuate during the day**. You can't trade a mutual fund "intraday". (ETFs are different: see section 5.)
- **Expenses are deducted from the NAV daily.** The fund never sends you a bill. The cost is invisible but real.
- **NAV level doesn't tell you whether a fund is cheap or expensive** (Chapter 2.5 explains this in detail).

---

## 4. How buying and selling (redemption) works

### Purchase
1. You place an order and pay through net banking, UPI or a SIP mandate.
2. **Units are allotted at the NAV of the day** the money reaches the fund, provided it arrives before the **cut-off time**.
3. Units appear in your folio (account), and in your CAS, in 1–2 days.

### Cut-off times (applicable NAV)
| Fund type | Cut-off | Rule |
|---|---|---|
| Equity and most debt funds | **3:00 PM** | Funds realised before 3 PM get that day's NAV. Otherwise the next business day's NAV. |
| Liquid and overnight funds | **1:30 PM** | Funds received before 1:30 PM get the **previous day's** NAV |

Since 2021, the NAV applies based on when the **money actually reaches the AMC**, not when you click "buy". UPI and net banking are fastest.

### Redemption (selling units back)
1. You submit a redemption request through the app or AMC.
2. Units are redeemed at the applicable NAV (same cut-off rules).
3. Money reaches your bank account:
   - **Liquid / overnight funds:** T+1 (some offer **instant redemption** up to ₹50,000 or 90% of the value)
   - **Equity funds:** typically **T+2 or T+3** working days
4. Any **exit load** is deducted, and **TDS** applies only for NRIs.

### Folio
A **folio number** is your account number with a specific AMC. All schemes from one AMC can sit in one folio.

---

## 5. Types of fund structures

### Open-ended funds
- **Buy and redeem directly from the AMC on any business day, at NAV.**
- No fixed maturity. Units are created when you invest and cancelled when you redeem.
- **Almost all funds you'll use are open-ended.**

### Closed-ended funds
- Money is raised only during the **NFO** period. After that, the fund is closed to new investment and **you can't redeem until maturity** (e.g. 3–5 years).
- They're listed on an exchange for liquidity, but trading volumes are usually tiny and units trade at a discount to NAV.
- Examples: Fixed Maturity Plans (FMPs), some older equity funds.
- Generally **avoid** them as a beginner. You lose flexibility for no clear benefit.

### Interval funds
- A hybrid that allows purchases and redemptions only during specific intervals. Rare and niche.

### ETFs (Exchange Traded Funds)
- A fund whose units are **listed and traded on the stock exchange** like shares, through your **demat account and broker**.
- Most ETFs are **passive**: they track an index (Nifty 50, Nifty Bank, gold, Nifty 1D Rate/liquid, etc.).
- **Price vs NAV:** the ETF's market price is set by buyers and sellers during the day and can deviate slightly from its actual NAV (the "iNAV", indicative NAV). For popular ETFs the gap is tiny. For illiquid ETFs it can be 0.5–2%, which is a hidden cost.
- **Market makers** provide liquidity, and authorised participants create or redeem units with the AMC to keep the price close to NAV.
- **Costs:** usually the lowest expense ratios, but you pay brokerage, STT on sell, DP charges and the bid–ask spread.
- **Check before buying:** daily traded volume and the price deviation from iNAV.

### Index funds
- **Open-ended mutual funds** that hold the same stocks as an index in the same weights.
- Bought and redeemed **directly from the AMC at NAV**. **No demat or broker needed**, no spread issues, and SIPs are easy.
- Slightly higher expense ratio than the equivalent ETF, but more convenient for most SIP investors.

### ETF vs index fund: which?
| | Index fund | ETF |
|---|---|---|
| Account needed | MF account (any platform) | Demat + trading |
| Price | Exact NAV once a day | Market price during the day (may deviate from NAV) |
| SIP | Automatic, easy | Manual buying, or broker-specific "stock SIP" |
| Expense ratio | Slightly higher | Lowest |
| Liquidity risk | None (the AMC always redeems) | Depends on trading volume |
| **Best for** | **Most beginners, SIP investors** | People who already trade on an exchange, larger lump sums |

### Fund of Funds (FoF)
- A fund that invests in **other mutual funds or ETFs**.
- Common uses: **international funds** (e.g. a US Nasdaq 100 FoF that buys a US-listed ETF), **gold funds** (which buy gold ETFs), multi-asset FoFs.
- You pay the FoF's expense ratio **plus** the underlying fund's.

---

## 6. Plan and option choices

When you pick a fund, you choose a **plan** and an **option**. The same scheme exists in several variants, each with a *different NAV*:

### Plan: Direct vs Regular
- **Direct:** bought directly, with no distributor commission and a lower expense ratio. **Always choose this.**
- **Regular:** bought through a distributor, with commission built into the expense ratio.
- (Full detail in Chapter 2.5.)

### Option: Growth vs IDCW
- **Growth:** all profits stay invested and show up as a rising NAV. Nothing is paid out. **Choose this** for long-term wealth building, because it maximises compounding.
- **IDCW (Income Distribution cum Capital Withdrawal):** formerly called the "dividend" option. The fund periodically pays out cash to you.
  - SEBI renamed it because the payout is **partly your own capital being returned**, not "extra" profit. After each payout, the NAV falls by exactly the amount paid.
  - **IDCW payouts are taxed at your income slab** in the year you receive them, while growth-option gains are taxed only when you sell, often at lower capital-gains rates.
  - **IDCW reinvestment** means the payout is reinvested into more units. It's pointless: it creates tax events with no benefit.
  - **Avoid IDCW.** If you need regular income, use a **SWP** (Systematic Withdrawal Plan) from the growth option instead.

---

## 7. NFOs (New Fund Offers)

An **NFO** is the launch of a new scheme, usually at **₹10 per unit**.

**Common misconceptions:**
- "₹10 is cheap, so I'll get more units." Wrong. The number of units is irrelevant. A ₹10 NAV fund and a ₹500 NAV fund holding the same portfolio give identical returns (Chapter 2.5).
- "It's like an IPO, so there might be listing gains." Wrong. There's no listing pop. The money is simply invested in the market at market prices.

**Why so many NFOs?** AMCs launch them partly for marketing and asset gathering, often in "hot" themes (manufacturing, defence, PSU, consumption) near the top of a cycle.

**Should you invest in an NFO?** Generally only if it offers something genuinely **new and useful** that doesn't already exist (a new low-cost index, a new asset class). Otherwise, an existing fund with a track record is better.

---

## 8. SIP, STP and SWP: the three systematic plans

| Plan | What it does | Typical use |
|---|---|---|
| **SIP (Systematic Investment Plan)** | Invests a fixed amount every month from your bank | Building wealth from salary (Chapter 2.6) |
| **STP (Systematic Transfer Plan)** | Moves a fixed amount every week or month from one fund (usually liquid) to another (usually equity) in the same AMC | Gradually investing a lump sum |
| **SWP (Systematic Withdrawal Plan)** | Redeems a fixed amount every month from a fund to your bank | Regular income in retirement, more tax-efficient than IDCW |

---

## 9. How to actually invest

### Step 1: KYC
- One-time, with PAN + Aadhaar + bank details. Done online (eKYC) through any platform.
- KYC status is shared across all AMCs through KRAs.

### Step 2: Choose a platform for direct plans
| Platform | Notes |
|---|---|
| **AMC websites / apps** | Direct from the fund house. One AMC per account. |
| **MF Central** | Run by CAMS and KFintech together. View and transact across all AMCs. |
| **MF Utility** | Industry platform, one account for most AMCs |
| **Zerodha Coin, Groww, Kuvera, Paytm Money, ET Money, INDmoney** | Popular apps offering direct plans (check that it says "Direct" in the scheme name) |

### Step 3: Set up the SIP
- Choose the scheme (**Direct, Growth**), amount and date.
- Register an **auto-debit mandate** (UPI AutoPay or e-NACH).
- **Add nominees.** SEBI requires you to nominate or opt out.

### Step 4: Track
- **CAS (Consolidated Account Statement):** emailed monthly by NSDL/CDSL or CAMS/KFintech, it lists all your mutual fund holdings across all AMCs and platforms. Request one any time from the CAMS or MF Central websites.
- Look at **XIRR** to judge your SIP's returns, not simple "absolute return".

---

## 10. Summary

- A mutual fund pools money, invests it professionally, and gives you units valued at **NAV**.
- **Trust structure:** sponsor → trust (trustees) → AMC (manages) + custodian (holds) + RTA (records). Your assets are protected from the AMC's own failure, **but not from market falls**.
- **NAV** is calculated once a day. Cut-off is 3 PM (1:30 PM for liquid funds). Money must reach the AMC in time.
- Prefer **open-ended** funds, the **Direct plan**, and the **Growth option**. Avoid IDCW and closed-ended funds. Be sceptical of NFOs.
- **Index fund vs ETF:** index funds are simpler for SIPs. ETFs are slightly cheaper but need a demat account and attention to liquidity.

## Self-check questions
1. If an AMC goes bankrupt, what happens to the money invested in its schemes? Why?
2. A fund has ₹500 Cr in assets, ₹2 Cr in liabilities and 20 Cr units. What's its NAV?
3. You invest in an equity fund at 4 PM on Tuesday. Which day's NAV do you get?
4. Why did SEBI rename the "dividend" option to IDCW?
5. Give two differences between an index fund and an ETF.

<details><summary>Answers</summary>

1. The securities are held by the custodian on behalf of the trust, not the AMC, so they remain the investors' property.
2. (500 − 2) / 20 = ₹24.90
3. Wednesday's NAV (after the 3 PM cut-off), assuming the money reaches the AMC by then.
4. Because the payout is partly the investor's own capital, not extra profit. The NAV drops by the payout amount.
5. ETFs trade on the exchange at market prices and need a demat account. Index funds are bought from the AMC at NAV. ETFs can have liquidity and spread issues and slightly lower expense ratios.
</details>
