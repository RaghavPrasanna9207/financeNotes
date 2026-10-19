# Chapter 2.3: Debt Funds and Hybrid Funds

> **What you'll learn:** how debt funds make (and lose) money, the key debt metrics (YTM, modified duration, Macaulay duration, average maturity, credit rating), every SEBI debt category and what to use it for, lessons from past debt-fund blowups, hybrid fund categories, and how all of these are taxed.

---

## Part A: Debt funds

## 1. What a debt fund does

A debt fund pools money and **lends it** by buying fixed-income securities:
- **Government securities (G-Secs)** and **Treasury Bills** (central government)
- **State Development Loans (SDLs)** (state governments)
- **Corporate bonds and debentures** (companies)
- **Commercial Paper (CP)** (short-term company borrowing) and **Certificates of Deposit (CD)** (short-term bank borrowing)
- **TREPS / repo** (very short-term secured lending)

### Where returns come from
1. **Interest (accrual):** the coupon or interest income from the securities held. This is the steady part.
2. **Price changes (mark-to-market):** bond prices change daily with interest rates and credit perceptions (Chapter 1.3).
   - Rates fall → bond prices rise → NAV gets a boost
   - Rates rise → bond prices fall → NAV takes a hit
   - A bond is downgraded or defaults → its price collapses → NAV falls, sometimes sharply

Unlike an FD, **a debt fund's NAV can fall**. It's not guaranteed.

---

## 2. Key debt fund metrics

You'll see these on every debt fund factsheet.

### YTM (Yield to Maturity)
- The return the portfolio would earn **if every bond were held to maturity** and all payments came on time, at today's prices.
- Your expected return ≈ **YTM − expense ratio**, *if* interest rates don't change much and nothing defaults.
- **A high YTM is not automatically good.** It usually means either longer maturity (more rate risk) or lower credit quality (more default risk).

### Average maturity
- The weighted average time until the portfolio's bonds mature.

### Macaulay duration
- The weighted average time to receive all cash flows (coupons plus principal). Measured in years.

### Modified duration: the most important number
- Measures **sensitivity to interest-rate changes**.
- **Rule:** `% change in NAV ≈ − Modified duration × Change in interest rates`
- **Example:** modified duration of 6 years and rates rise by 0.5% → NAV falls about **3%**. If rates fall by 1% → NAV rises about **6%**.
- Liquid fund: duration of a few weeks → nearly immune. Gilt fund: duration of 6–10 years → very sensitive.

### Credit quality / rating profile
- The % of the portfolio in **Sovereign** (government), **AAA**, AA, A and below.
- Ratings come from agencies such as CRISIL, ICRA, CARE, India Ratings and Acuité.
- **AAA = highest safety among corporate bonds. Sovereign = no credit risk.**
- AA and below means meaningful default risk.

### Example of reading these together
| Fund | YTM | Mod. duration | Credit | What it means |
|---|---|---|---|---|
| Liquid fund | 6.8% | 0.1 yrs | 100% Sovereign/A1+ | Very safe, very stable. Your emergency fund. |
| Corporate bond fund | 7.3% | 2.5 yrs | 95% AAA | Some rate risk, low credit risk. Good for 2–4 year goals. |
| Gilt fund | 7.0% | 8 yrs | 100% Sovereign | No credit risk, **large rate risk**. NAV can swing ±8% a year. |
| Credit risk fund | 8.8% | 2 yrs | 30% AAA, 70% AA and below | Extra 1.5% yield for **real default risk** |

---

## 3. SEBI's debt fund categories

Categories are defined mainly by **Macaulay duration** or by the **type of security**.

### By duration (time)
| Category | Rule | Rate risk | Typical use |
|---|---|---|---|
| **Overnight Fund** | Securities maturing in **1 day** | Negligible | Parking cash for days. Corporate treasuries. |
| **Liquid Fund** | Securities up to **91 days** maturity | Very low | **Emergency fund**, parking money for weeks or months |
| **Ultra Short Duration** | Macaulay duration **3–6 months** | Low | Money needed in 3–12 months |
| **Low Duration** | Duration **6–12 months** | Low | 6–18 months |
| **Money Market** | Money market instruments up to **1 year** | Low | 6–12 months |
| **Short Duration** | Duration **1–3 years** | Moderate | 1–3 year goals |
| **Medium Duration** | Duration **3–4 years** | Moderate–high | 3–5 years |
| **Medium to Long Duration** | Duration **4–7 years** | High | Rate-view investors |
| **Long Duration** | Duration **> 7 years** | Very high | Rate-view investors |

### By type of security
| Category | Rule | Notes |
|---|---|---|
| **Corporate Bond Fund** | ≥ **80% in AA+ and above** corporate bonds | High credit quality. Good core debt fund. |
| **Banking & PSU Fund** | ≥ **80%** in banks, PSUs, public financial institutions | High quality, quasi-government |
| **Gilt Fund** | ≥ **80% in government securities** | **No credit risk**, high rate risk |
| **Gilt Fund with 10-year constant duration** | ≥80% G-Secs, portfolio duration ~10 yrs | Very rate-sensitive |
| **Credit Risk Fund** | ≥ **65% in AA and below** | **High default risk. Avoid.** |
| **Dynamic Bond** | Any duration; the manager decides | Depends on the manager's rate calls |
| **Floater Fund** | ≥ **65% in floating-rate instruments** | Benefits when rates rise |

### Passive debt options
- **Target Maturity Funds (TMFs):** index funds or ETFs that hold bonds (G-Secs, SDLs, PSU bonds) **maturing in a specific year** (e.g. 2030). If you hold to that year, your return is close to the YTM at purchase, a bit like a **tradable, diversified FD with no credit risk** (for G-Sec/SDL TMFs).
- **Bharat Bond ETF:** a TMF of AAA PSU bonds.
- **Liquid ETFs / Nifty 1D Rate ETFs:** for parking cash in a demat account.

---

## 4. Lessons from debt-fund accidents

Debt funds are **not** "safe FDs with better returns". Real examples:

1. **IL&FS (2018):** a AAA-rated infrastructure lender defaulted suddenly. Funds holding its paper took immediate NAV hits.
2. **DHFL, Essel group, Vodafone Idea (2019):** more defaults and downgrades. Some funds **"side-pocketed"** the bad paper, separating it from the rest so new investors didn't benefit unfairly and existing investors would get any later recovery.
3. **Franklin Templeton (April 2020):** **six debt schemes worth about ₹26,000 crore were wound up** because they held illiquid, lower-rated papers and couldn't meet redemptions during COVID. Investors' money was locked for months and returned in instalments over years.

### The lessons
- **Yield = risk.** Extra yield always comes from either longer duration or lower credit quality.
- **For safety, stick to:** overnight, liquid, money market, short-duration **corporate bond / banking & PSU** funds with mostly **AAA/Sovereign** holdings, or **gilt / target-maturity** funds if you can accept rate swings.
- **Avoid credit risk funds** and any debt fund chasing yield.
- After 2020, SEBI introduced stricter rules on liquidity, risk-o-meters and the **Potential Risk Class (PRC) matrix** (below).

### Potential Risk Class (PRC) matrix
Every debt fund now discloses the **maximum** credit and interest-rate risk it can take:

| | Credit risk: Low (A) | Moderate (B) | High (C) |
|---|---|---|---|
| **Rate risk: Low (I)** | A-I (safest) | B-I | C-I |
| **Moderate (II)** | A-II | B-II | C-II |
| **High (III)** | A-III | B-III | C-III |

A liquid fund is typically **A-I** or B-I. A gilt fund is **A-III**. A credit risk fund is in the **C** column. For conservative goals, prefer the **A** column.

---

## 5. Debt fund taxation (summary; detail in Chapter 3.5)
- For debt fund units **bought on or after 1 April 2023** (funds with ≤35% in Indian equity), **all gains are taxed at your income-tax slab rate**, regardless of how long you hold. No indexation benefit.
- **Advantage vs FD:** **tax deferral**. Tax is due only when you redeem, while FD interest is taxed every year as it accrues. Over many years, deferral helps your money compound.
- **No TDS** for resident investors on debt fund redemptions.

---

## Part B: Hybrid funds

## 6. What hybrid funds are

**Hybrid funds** invest in a **mix of asset classes** (equity, debt, sometimes gold or arbitrage) in one scheme. They give you a ready-made asset allocation.

### SEBI hybrid categories
| Category | Equity | Debt | Notes | Tax treatment |
|---|---|---|---|---|
| **Conservative Hybrid** | 10–25% | 75–90% | Debt-heavy, a small equity kicker | Debt (slab) |
| **Balanced Hybrid** | 40–60% | 40–60% | No arbitrage allowed | Depends on equity % |
| **Aggressive Hybrid** | **65–80%** | 20–35% | The classic "balanced fund" | **Equity** |
| **Dynamic Asset Allocation / Balanced Advantage (BAF)** | 0–100%, varies | Varies | Shifts between equity and debt based on valuations or models. Uses arbitrage to stay taxed as equity. | Usually equity |
| **Multi Asset Allocation** | At least **10% each in 3+ asset classes** (equity, debt, gold/silver, REITs…) | | A "one-fund portfolio" | Depends on mix |
| **Arbitrage Fund** | ≥65% in hedged equity (cash–futures arbitrage) | Rest in debt | Low-risk returns similar to liquid funds | **Equity** |
| **Equity Savings** | Equity + arbitrage + debt (≥65% "equity" including arbitrage) | | Low volatility | Equity |

### 6.1 How arbitrage funds work
An arbitrage fund simultaneously **buys a stock in the cash market** and **sells its futures contract** at a slightly higher price. At expiry the two prices converge, and the fund locks in the small difference. Since the position is fully hedged, there's **no market risk**, and returns resemble liquid funds (about 6–7.5%).

**Why use one?** It's **taxed as equity** (STCG 20% under 12 months, LTCG 12.5% above ₹1.25 L after 12 months). For someone in the **30% tax bracket** parking money for **more than a year**, an arbitrage fund can beat a liquid fund or FD **after tax**. For low-bracket investors, there's little benefit.

### 6.2 Balanced Advantage Funds (BAF)
- They raise equity exposure when markets are cheap and reduce it when they're expensive, based on a model (P/E, P/B, trend, etc.).
- Aim: smoother returns and smaller drawdowns.
- Reality: performance varies widely by AMC model. It's a decent "one fund" option for nervous first-time equity investors, but less transparent.

### 6.3 Multi-asset allocation funds
- Hold equity + debt + gold (sometimes silver, REITs).
- They rebalance automatically inside the fund (no tax event for you).
- Good for people who want **one fund** and no rebalancing work.

### 6.4 Aggressive hybrid
- 65–80% equity, the rest debt.
- Taxed as equity. Falls less than pure equity in crashes.
- A reasonable choice for medium-to-long horizons if you want built-in balance.

### Hybrid funds vs building your own mix
| | Hybrid fund | DIY (index fund + debt fund) |
|---|---|---|
| Rebalancing | Automatic, inside the fund (no tax to you) | You do it, possibly triggering tax |
| Cost | Higher expense ratio (active management) | Lower |
| Control | Fund decides | You decide exact allocation |
| Simplicity | One fund | Two or three funds |
| Taxation | Depends on equity % (can be favourable) | Debt part taxed at slab |

Both approaches are fine. Many experienced investors prefer DIY for control and cost. Hybrids suit people who value simplicity and won't rebalance themselves.

---

## 7. Which debt or hybrid fund for which need?

| Need | Suitable fund(s) |
|---|---|
| Emergency fund | **Liquid fund** or overnight fund (+ some cash in savings) |
| Parking money for 3–12 months | Liquid, ultra short, money market |
| Parking > 1 year, 30% tax bracket | **Arbitrage fund** |
| Goal in 1–3 years | Short duration, corporate bond, banking & PSU, or a target maturity fund matching the goal year |
| Goal in 3–5 years | Target maturity fund, corporate bond + some equity (conservative or balanced hybrid) |
| Long-term debt allocation | EPF/PPF first, then gilt / target-maturity / corporate bond funds |
| "I want one fund for everything" | Multi-asset allocation or aggressive hybrid / BAF |
| **Never needed** | Credit risk funds, long-duration funds (unless you have a strong rate view) |

---

## 8. Summary

- Debt funds earn **interest + price changes**. NAV can fall from **rate rises** (duration) or **defaults** (credit).
- Key metrics: **YTM** (expected yield), **modified duration** (rate sensitivity), **credit quality** (default risk).
- Use **liquid funds** for emergencies and **short-duration, high-quality** funds for short goals. **Avoid credit risk funds.**
- Debt funds bought after April 2023 are taxed at slab, but tax is **deferred** until you redeem.
- **Hybrid funds** offer ready-made allocation. **Arbitrage funds** are taxed as equity and are useful for high-bracket short-term parking.

## Self-check questions
1. A debt fund has a modified duration of 3 and a YTM of 7.4%. Interest rates rise by 1% the next day. What happens to the NAV, approximately?
2. Why is a high YTM not automatically a good thing?
3. What happened with Franklin Templeton in 2020, and what's the lesson?
4. How does an arbitrage fund make money, and why is it taxed as equity?
5. What does "A-I" in the PRC matrix mean?

<details><summary>Answers</summary>

1. It falls by about 3%.
2. It usually comes from more duration (rate risk) or lower credit quality (default risk).
3. Six debt schemes were wound up because they held illiquid, low-rated papers. Lesson: don't chase yield, and prefer high-quality, liquid portfolios.
4. It buys stocks in the cash market and sells the futures, locking in the spread. It's taxed as equity because more than 65% is held in (hedged) equity.
5. Low credit risk and low interest-rate risk, the safest box.
</details>
