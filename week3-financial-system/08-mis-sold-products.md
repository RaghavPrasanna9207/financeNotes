# Chapter 3.8: Commonly Mis-sold Products: ULIPs, Endowment and Money-Back Plans

> **What you'll learn:** why "insurance + investment" products exist and why they're pushed so hard, how traditional endowment and money-back plans work (sum assured, bonuses, surrender value), how to calculate their real return (IRR) yourself, how ULIPs work and what they charge, "guaranteed" plans, the Buy Term + Invest the Rest comparison with numbers, red-flag sales phrases, and what to do if you already own one.

---

## 1. The core problem

Insurance and investment are **two different jobs**:
- **Insurance** needs to provide a **large payout** if something bad happens (₹1–2 Cr of cover for an earner).
- **Investment** needs **high, flexible, low-cost growth**.

Combination products ("you get insurance AND your money back with returns!") do **both jobs badly**:
- The **insurance cover is tiny** (often only 10× the annual premium), nowhere near what a family needs.
- The **returns are poor** (often 4–6% a year), with **long lock-ins** and **heavy penalties** for leaving early.

### Why they're sold so aggressively
- **High commissions:** agents can earn **15–35% of the first-year premium** on traditional plans, plus renewal commissions. Pure term insurance and direct mutual funds pay little or nothing.
- **They appeal to emotions:** "guaranteed", "tax-free", "your money comes back", "safe for your family", "LIC is government-backed".
- **Cultural trust:** a relative or bank RM selling it; "everyone in the family has one".
- **Complexity hides the cost:** bonuses, loyalty additions and "guaranteed additions" make it hard to see the actual return.
- **Tax season pressure:** bought hastily in February/March for 80C deductions.

---

## 2. Traditional plans: endowment and money-back

### 2.1 Endowment plans
**How they work:**
1. You pay a fixed premium every year for the policy term (e.g. 20 years).
2. If you die during the term, your nominee gets the **sum assured + accumulated bonuses**.
3. If you survive, you get the **sum assured + bonuses** at maturity.

**The bonus system (participating / "with-profit" plans):**
- **Simple reversionary bonus:** declared yearly as ₹X per ₹1,000 of sum assured (e.g. ₹45 per ₹1,000). Added to the policy and paid at maturity or death. **It doesn't compound** (it's simple, not compound).
- **Final additional bonus (FAB):** a one-time bonus at maturity, if declared.
- Bonuses **aren't guaranteed** in advance. They depend on the insurer's declared rates.
- **Non-participating (guaranteed) plans:** fixed "guaranteed additions" instead of bonuses.

### 2.2 Money-back plans
Like endowment, but part of the sum assured is **paid back periodically** during the term (e.g. 15% at years 5, 10 and 15, and the rest plus bonuses at maturity).
- The "money back" feels rewarding, but it's just **your own money being returned** in instalments, and the money paid out early stops earning.
- Returns are typically **even lower** than endowment plans.

### 2.3 Whole life plans
Cover (and premiums) up to age 99 or 100, with bonuses. Similar economics: low returns over very long periods.

### 2.4 Surrender value: the trap
If you stop paying premiums early:
- In the **first 2–3 years**, you may get **nothing or very little** back (surrender value is low or zero).
- The **guaranteed surrender value** is a small % of premiums paid (excluding the first year's premium in many older policies). The **special surrender value** is somewhat better, but still a big loss in the early years.
- IRDAI has revised surrender value rules (from 2024) to make early exits less punitive, but early surrender still usually loses money.
- That's why people "keep paying because they've already paid so much" (the **sunk cost fallacy**).

---

## 3. How to find the real return: calculate the IRR

Never trust "you get ₹20 lakh!" Calculate the **IRR (Internal Rate of Return)**, the actual annual compounded return of the cash flows.

### Using Excel / Google Sheets
1. Column A: year 0, 1, 2, … 20.
2. Column B: cash flows. **Premiums as negative** (paid at the start of each year), **payouts as positive**.
3. `=IRR(B1:B21)`. If the cash flows are on specific dates, use `=XIRR(values, dates)`.

### Worked example: a typical endowment plan
- Age 25, sum assured **₹10 L**, term **20 years**
- Annual premium: **₹52,000** (₹10.4 L paid in total)
- Bonus assumption: ₹45 per ₹1,000 SA per year → ₹45,000 × 20 = ₹9 L, plus a final additional bonus of ₹1.5 L
- **Maturity value: ₹20.5 L** ("You double your money!")

| Year | Cash flow |
|---|---|
| Start of years 1–20 | −52,000 each |
| End of year 20 | +20,50,000 |

**IRR ≈ 6.1% a year.** And that's with a fairly generous bonus assumption. Many policies come in at **4–5.5%**.

Compare:
- **PPF** (7.1%, tax-free, sovereign): the same ₹52,000/year for 20 years → about **₹23.1 L**
- **Inflation** (~6%): the endowment's real return is about **zero**
- **Life cover:** only **₹10 L** (+ bonuses) during the term. Far too little for a family.

### Rule of thumb
If someone says "you'll get 2× your total premiums back after 20 years", that's roughly a **6% IRR**. "1.5× after 15 years" is about **5%**.

---

## 4. ULIPs (Unit Linked Insurance Plans)

### How they work
- Part of your premium pays for **life cover** (mortality charge); the rest is invested in **market-linked funds** (equity, debt, balanced) that you choose.
- Your money buys **units**, with an NAV like a mutual fund.
- **5-year lock-in** (no withdrawals before year 5).
- You can **switch** between the ULIP's funds (often a few free switches a year).

### The charges
| Charge | What it is |
|---|---|
| **Premium allocation charge** | % deducted from premiums before investing (higher in early years in older ULIPs; many new-age ULIPs have zero) |
| **Mortality charge** | The cost of life cover, deducted monthly (by cancelling units). Rises with age. |
| **Policy administration charge** | Fixed monthly fee |
| **Fund management charge (FMC)** | Up to **1.35% a year** (IRDAI cap) |
| **Discontinuance charge** | If you stop within 5 years |
| **Switching / partial withdrawal charges** | Beyond free limits |

**Old ULIPs (pre-2010)** were notorious: very high upfront charges ate 20–60% of the first-year premium. **IRDAI reforms in 2010** capped charges and introduced the 5-year lock-in. **New-age online ULIPs** are much cheaper.

### Why they're still not ideal
1. **Low life cover:** typically 10× the annual premium, far below what a family needs.
2. **Lock-in of 5 years**, and they're designed for 10–15+ years to make sense.
3. **Mortality charges** reduce investment returns. A separate term plan is usually cheaper per rupee of cover.
4. **Complexity and less transparency** than mutual funds. Fund performance data is harder to compare.
5. **Limited fund choice:** you're stuck with that insurer's funds.
6. **Tax change:** ULIP maturity proceeds are tax-free only if **total annual premiums across ULIPs are ≤ ₹2.5 L** (for policies issued after 1 February 2021). Above that, they're taxed like equity/debt funds.

**Verdict:** a well-chosen low-cost ULIP isn't a disaster, but **term insurance + an index fund** is simpler, more flexible, more transparent and usually better.

---

## 5. "Guaranteed return" and "child" / "pension" plans from insurers

- **Guaranteed income / guaranteed return plans (non-par):** a fixed payout schedule. The IRR is typically **5–6.5%**, locked for 10–15+ years. Tax-free maturity is subject to limits (since April 2023, policies with annual premiums over ₹5 L have taxable maturity, except on death).
- **Child plans:** marketed with emotional appeal ("secure your child's future"). Usually an endowment or ULIP with a premium-waiver rider. **Better alternative:** term insurance on the parent + SSY/PPF + an equity index fund for the child's goal.
- **Pension / annuity plans:** deferred annuities with low returns and taxable annuity income. **Better alternative:** EPF/PPF/NPS + equity funds during your working years; consider annuities only at retirement for part of the corpus.

**Always ask for the benefit illustration and calculate the IRR.**

---

## 6. Buy Term + Invest the Rest (BTIR)

Compare spending the same ₹52,000/year two ways.

**Option 1: endowment plan**
- Premium ₹52,000/year for 20 years
- Life cover: ₹10 L (+ bonuses)
- Maturity: ~₹20.5 L (IRR ~6%)

**Option 2: term plan + index fund**
- Term plan: **₹1 Cr cover** for ~₹12,000/year (age 25, non-smoker)
- Invest the remaining **₹40,000/year** in a Nifty 50 index fund

| | Endowment | Term + index fund (at 10%) | Term + index fund (at 11%) |
|---|---|---|---|
| Life cover | **₹10 L** | **₹1 Cr** | **₹1 Cr** |
| Value after 20 years | ~₹20.5 L | **~₹25.2 L** | **~₹28.5 L** |
| Liquidity | Locked; surrender penalties | Full (index fund) | Full |
| Transparency | Bonuses unclear in advance | Daily NAV | Daily NAV |
| Flexibility | Must keep paying for 20 years | Change SIP any time | |

**Option 2 gives 10× the life cover AND more money at the end.** Even if equity returns only 8%, the outcome is similar to the endowment, with 10× the cover and full liquidity.

**The trade-off:** BTIR requires **discipline**, because you must actually invest the difference and not panic-sell. That's why SIPs and automation matter (Chapter 2.6).

---

## 7. Red-flag phrases from sellers

| They say | What it usually means |
|---|---|
| "Guaranteed returns" / "assured returns" | Low returns (4–6.5% IRR), long lock-in |
| "Your money comes back" / "nothing is wasted" | You're paying for an investment, and the cover is tiny |
| "Tax-free" | True for some, but tax-free 5–6% is still poor. Check the ₹2.5 L / ₹5 L premium limits. |
| "Your one-time investment doubles in 20 years" | ≈ 3.5% a year (72/20). Terrible. |
| "Limited period offer / NFO" | Sales pressure |
| "Better than FD" | Usually compared pre-tax, ignoring lock-in and surrender loss |
| "It's like a mutual fund plus insurance" | A ULIP with mortality charges and lock-in |
| "Bonus of ₹X per thousand" | A simple (not compound) bonus, which sounds bigger than it is |
| "Pay for only 5–10 years, get benefits for 25" | Calculate the IRR. Often around 5%. |

**Mis-selling remedies:** use the **free look period** (15 days, or 30 days for policies bought online/at a distance) to cancel for a refund. Complaints can go to the insurer's grievance cell, then **Bima Bharosa** and the **Insurance Ombudsman**.

---

## 8. Already have one? What to do

**Don't cancel in a panic.** Do the maths:

### Step 1: Get the facts
Ask the insurer for:
- The current **surrender value**
- The **paid-up value** (if you stop paying premiums but keep the policy until maturity, the sum assured is reduced proportionately and accrued bonuses remain)
- The projected **maturity value** if you continue

### Step 2: Ensure adequate term cover first
If the policy is your only life cover and you have dependents, **buy a proper term plan first**, before surrendering or making it paid-up.

### Step 3: Compare three options
| Option | What happens |
|---|---|
| **Continue** | Pay remaining premiums, get the maturity value. Calculate the IRR of **future premiums vs the future maturity value** (ignore past premiums, which are sunk costs). |
| **Make it paid-up** | Stop paying. Get a reduced maturity value at the end. Your future money goes to better investments. |
| **Surrender** | Take the surrender value now and invest it elsewhere |

### Step 4: Decide
- **Early in the policy (years 1–5)** with low returns: often better to **surrender or make paid-up** despite the loss, and redirect premiums to term + index funds.
- **Late in the policy** (e.g. 15 of 20 years done): the remaining premiums may earn a reasonable *marginal* IRR (because the maturity bonus is close), so **continuing** can make sense. Calculate it.
- **ULIP past its 5-year lock-in:** compare its funds' costs and performance with index funds. Surrendering after 5 years has no penalty.
- **Rule: decide based on future cash flows only, never on what you've already paid.**

---

## 9. Summary
- **Never mix insurance and investment.** Combination products give **too little cover** and **poor returns**.
- Endowment and money-back plans typically return **4–6% IRR**, about **zero real return**, with long lock-ins and big early-surrender losses.
- **ULIPs:** better after the 2010 reforms, but still low cover, a lock-in and extra charges. Tax-free only up to ₹2.5 L annual premium.
- **Always calculate the IRR** with Excel's `IRR`/`XIRR`.
- **Buy Term + Invest the Rest** gives ~10× the cover and usually more wealth.
- Existing policies: get term cover first, then compare **continue / paid-up / surrender** using **future** cash flows only.

## Self-check questions
1. Why do agents push endowment plans harder than term insurance?
2. A plan says you pay ₹1 L a year for 10 years and get ₹15 L at the end of year 15. How would you calculate the return? Is it good?
3. What's the difference between a simple reversionary bonus and compounding?
4. You've paid 3 of 20 years' premiums on an endowment plan. What should you do first?
5. Why are past premiums irrelevant to the continue-or-surrender decision?

<details><summary>Answers</summary>

1. Much higher commissions (15–35% of the first-year premium vs little on term plans).
2. Cash flows: −1 L in years 0–9, 0 in years 10–14, +15 L in year 15, then `=IRR()`. It works out to about 3.9%, below inflation, so it's poor.
3. A simple bonus is a fixed amount per ₹1,000 of the original sum assured each year, with no growth on past bonuses. Compounding earns returns on past returns.
4. Make sure you have adequate term cover, then get the surrender and paid-up values and compare the options using future cash flows.
5. They're sunk costs. They're gone whatever you decide. Only future premiums and future payouts differ between the options.
</details>
