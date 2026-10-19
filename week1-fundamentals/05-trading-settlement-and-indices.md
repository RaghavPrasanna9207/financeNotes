# Chapter 1.5: Trading, Settlement, Corporate Actions and Indices

> *Based on Zerodha Varsity's "Introduction to Stock Markets" module.*
>
> **What you'll learn:** what happens step by step when you place an order, market timings and order types, T+1 settlement, all the charges on a trade, corporate actions (dividends, bonus, splits, rights, buybacks) and how they affect you, market capitalisation, and what stock market indices are, how they're built and why they matter.

---

## 1. The life of a trade: step by step

Say you buy 10 shares of a company at ₹1,500 on Monday at 11 AM.

1. **You place the order** in your broker's app.
2. **The broker checks** that you have ₹15,000 + charges available (upfront margin rules require the full amount for delivery purchases).
3. **The order goes to the exchange** (NSE or BSE).
4. **The exchange matching engine** finds a matching sell order: price–time priority (best price first; if prices are equal, earlier order first).
5. **Trade executed:** you get a confirmation in seconds. By the end of the day, the broker emails you a **contract note** listing every charge.
6. **Clearing:** the clearing corporation calculates who owes what to whom.
7. **Settlement (T+1):** on Tuesday, the shares are credited to your demat account and the seller receives the money.

### T+1 settlement
- **T** = trade day. **T+1** = one working day later.
- India moved fully to **T+1 in January 2023** in phases. It's one of the fastest settlement cycles among major markets (the US moved to T+1 in May 2024).
- SEBI has also introduced an optional **T+0 (same-day) settlement** for a limited set of stocks.
- When you **sell**, the money (minus charges) reaches your trading account on T+1 and can be withdrawn to your bank.

### Market timings (equity segment, NSE/BSE)
| Session | Time |
|---|---|
| Pre-open session (order entry and price discovery) | 9:00 – 9:15 AM |
| **Normal trading** | **9:15 AM – 3:30 PM** |
| Closing session / post-close | 3:40 – 4:00 PM |
- Trading days: Monday to Friday, except exchange holidays (published annually).
- Special **Muhurat trading** session on Diwali evening.
- **Circuit limits:** individual stocks have daily price bands (2%, 5%, 10% or 20%). Market-wide circuit breakers halt trading if the index falls 10%, 15% or 20% in a day.

---

## 2. Order types

| Order | What it does | When to use |
|---|---|---|
| **Market order** | Buys or sells immediately at the best available price | Liquid stocks and ETFs where the spread is tiny |
| **Limit order** | Buys only at your price **or lower** (sells at your price **or higher**). May not execute. | Default for most purchases. Gives you price control. |
| **Stop-loss (SL) order** | Becomes an order once a "trigger price" is hit. Used to limit losses. | Mainly for traders |
| **GTT (Good Till Triggered)** | A broker feature: an order that waits for days or months until a price is reached | Buying at a target price without watching the screen |
| **AMO (After Market Order)** | Placed outside market hours, sent at the next open | Convenience |

### Product types
- **CNC / Delivery:** you buy and the shares go into your demat account. You can hold them indefinitely. **This is investing.**
- **MIS / Intraday:** must be squared off the same day. Brokers offer leverage. **This is trading, and most retail intraday traders lose money.** Skip it.
- **NRML:** for derivatives (futures and options) carried overnight. Skip for now.

### Bid, ask and spread
- **Bid:** the highest price a buyer is willing to pay right now.
- **Ask (offer):** the lowest price a seller is willing to accept.
- **Spread:** the gap between them. Liquid large-cap stocks have tiny spreads (a few paise). Illiquid small caps can have large spreads, which is a hidden cost when you trade.
- The **market depth** (order book) in your app shows the top 5 bids and asks.

---

## 3. The charges on a trade

Your contract note will list:

| Charge | Who collects | Rough size |
|---|---|---|
| **Brokerage** | Broker | ₹0 (equity delivery at many discount brokers) to 0.5% at full-service brokers |
| **STT (Securities Transaction Tax)** | Government | 0.1% on both buy and sell for delivery |
| **Exchange transaction charges** | NSE/BSE | A few thousandths of a percent |
| **SEBI turnover fee** | SEBI | ₹10 per crore |
| **Stamp duty** | State government | 0.015% on buy (delivery) |
| **GST** | Government | 18% on brokerage + exchange charges + SEBI fee |
| **DP charges** | Depository + DP | Flat ~₹13–20 per stock per sell day (not per share) |

**Practical implications:**
- Buying and holding long term is cheap. Total costs are typically around 0.2–0.25% per round trip, mostly STT and stamp duty.
- **Frequent trading** multiplies these costs, plus short-term taxes, which is one reason traders struggle to profit.
- **Selling small quantities** is inefficient because of the flat DP charge.

---

## 4. Corporate actions

Companies take actions that change the shares you hold. Know these so you're not confused when your holdings or prices change.

### Dividends
- A share of profit paid out in cash per share (e.g. ₹15/share).
- **Key dates:**
  - **Record date:** the date on which the company checks who its shareholders are.
  - **Ex-dividend date:** with T+1 settlement, this is the same as the record date. You must hold the shares *before* the ex-date to get the dividend.
- On the ex-date, the share price **falls by roughly the dividend amount**. You haven't gained wealth; part of your investment has been handed back to you in cash.
- **Dividends are taxed at your income slab.** Companies deduct TDS if a shareholder's dividends from that company exceed ₹10,000 in a year.

### Bonus issue
- The company gives free extra shares from its reserves, e.g. **1:1 bonus** = 1 extra share for every 1 held.
- The share count doubles and the **price halves**. **Your total value is unchanged.**
- Done to signal confidence and improve liquidity (a lower price per share).

### Stock split
- One share is split into several of smaller face value, e.g. a ₹10 face value share split into 5 shares of ₹2 face value.
- Like a bonus: more shares at a lower price, **same total value**.
- Difference from a bonus: a split changes the face value, while a bonus capitalises reserves. For you as an investor, the economic effect is the same.

### Rights issue
- The company offers existing shareholders the **right to buy new shares**, usually at a discount, in proportion to their holding (e.g. 1 for every 5 held).
- You can subscribe, **sell your rights entitlement** (it trades separately for a while), or let it lapse. **If you ignore it, your ownership gets diluted.**
- Frequent rights issues can be a red flag that the company keeps needing cash (Week 4).

### Buyback
- The company **buys back its own shares**, usually at a premium to the market price, which reduces the share count.
- It signals the company has excess cash and believes the shares are undervalued.
- Remaining shareholders own a slightly larger percentage of the company.
- Tax treatment of buybacks has changed in recent budgets; proceeds are now taxed in the shareholder's hands.

### Mergers, demergers, delisting
- **Merger:** your shares in Company A are converted into shares of Company B at a swap ratio.
- **Demerger:** a company spins off a division, and you receive shares in the new company.
- **Delisting:** the company leaves the exchange, usually through an offer to buy out public shareholders.

---

## 5. Market capitalisation

```
Market capitalisation = Current share price × Total number of shares outstanding
```
**Example:** 100 crore shares × ₹1,500 = ₹1,50,000 crore market cap.

Market cap is what the **entire company** is worth according to the stock market today. A share's price alone tells you nothing: ₹50,000 per share doesn't make a company "bigger" than one at ₹500 per share. Always compare market caps.

### SEBI's size classification
Based on the **average market cap over 6 months**, published by AMFI every six months (January and July):
- **Large cap:** companies ranked **1–100**
- **Mid cap:** ranked **101–250**
- **Small cap:** ranked **251 onwards**
- (Informally, the bottom tail is called "micro cap".)

**Free-float market cap** counts only the shares available for public trading, excluding promoter holdings and locked-in shares. Most indices use free float, because that's what investors can actually buy.

---

## 6. Stock market indices

### What is an index?
An **index** is a single number that represents the **combined price movement of a selected basket of stocks**. It's a **thermometer** for the market or a segment of it.

When the news says "the Sensex fell 800 points", it means the combined value of the 30 Sensex companies fell by that much, as measured by the index's formula.

### Why indices matter
1. **They show the market's direction and mood** at a glance.
2. **They're benchmarks:** fund managers' performance is measured against them. "Did my fund beat the Nifty 50?"
3. **They're investable:** index funds and ETFs replicate them, so you can own the whole basket cheaply (Week 2).
4. **They're the base for derivatives** (Nifty futures and options).

### India's major indices
| Index | Exchange | Constituents | What it represents |
|---|---|---|---|
| **Nifty 50** | NSE | 50 large, liquid companies across sectors | The broad large-cap market. Roughly half or more of NSE's free-float market cap. |
| **Sensex (S&P BSE Sensex)** | BSE | 30 large companies | The oldest Indian index (base year 1978–79 = 100) |
| **Nifty Next 50** | NSE | Companies ranked roughly 51–100 | "Future large caps" |
| **Nifty 100** | NSE | Nifty 50 + Next 50 | All large caps |
| **Nifty Midcap 150** | NSE | Mid caps (101–250) | |
| **Nifty Smallcap 250** | NSE | Small caps (251–500) | |
| **Nifty 500** | NSE | Top 500 companies | ~90%+ of market cap. "The whole market". |
| **Sectoral indices** | Both | Nifty Bank, Nifty IT, Nifty Pharma, Nifty FMCG… | Single sectors |
| **Thematic / strategy indices** | Both | Nifty 50 Equal Weight, Nifty Alpha 50, Nifty Low Volatility 30, Nifty 200 Momentum 30… | Rule-based strategies ("smart beta") |
| **India VIX** | NSE | Not stocks: derived from option prices | The "fear index", expected volatility over the next 30 days |

### How an index is constructed
1. **Eligibility:** stocks must meet criteria for size, liquidity (trading frequency and impact cost) and free float.
2. **Weighting:** most Indian indices are **free-float market-cap weighted**. Bigger companies get bigger weights. In the Nifty 50, the top 10 companies often make up more than half the index.
3. **Base value:** the index starts at a base (e.g. the Nifty 50 at 1,000 in November 1995) and moves proportionally with the total free-float market cap of its constituents.
4. **Rebalancing:** reviewed **every six months** (March and September). Companies that shrink, become illiquid or lose eligibility are **removed**, and rising companies are **added**.

### The self-cleansing property
Because of rebalancing, **an index automatically drops losers and adds winners**. Companies like Yes Bank or Jet Airways (when it was large) got removed as they declined, while rising companies got added. An index fund investor benefits from this without making any decisions. That's one reason index investing works so well over the long run (Week 2).

### Price index vs Total Return Index (TRI)
- The **price index** (the number you see on the news) only tracks price changes.
- The **Total Return Index (TRI)** also assumes dividends are reinvested. Over long periods, TRI is meaningfully higher (by roughly 1–1.5% a year).
- **Mutual funds must benchmark against TRI**, which is the fair comparison because funds receive dividends too.

### How to read index levels
- Index *points* aren't comparable across indices or time. Use **percentage change**.
- "Sensex at 80,000" vs "Nifty at 24,000" says nothing about which is better. They just have different bases.

---

## 7. Summary

- A trade goes: you → broker → exchange matching → clearing corporation → settlement on **T+1**.
- Use **limit orders** and **delivery (CNC)**. Skip intraday and F&O.
- Trading costs are small for long-term investors but add up fast for frequent traders.
- **Bonus and split:** more shares, same value. **Dividend:** price drops by the payout, and it's taxable. **Rights:** subscribe or get diluted. **Buyback:** the company retires shares.
- **Market cap = price × shares.** Large cap = top 100, mid = 101–250, small = 251+.
- **Indices** (Nifty 50, Sensex, etc.) measure the market, serve as benchmarks, self-cleanse through rebalancing, and can be bought through index funds.

## Self-check questions
1. You buy shares on Wednesday. When do they reach your demat account?
2. A stock trading at ₹2,000 announces a 1:1 bonus. What happens to the price and your holding value?
3. Why do mutual funds benchmark against the TRI instead of the price index?
4. How often is the Nifty 50 rebalanced, and why does that help long-term index investors?
5. Company A's share price is ₹40,000; Company B's is ₹400. Which company is bigger?

<details><summary>Answers</summary>

1. Thursday (T+1), assuming it's a working day.
2. The price roughly halves to about ₹1,000, the number of shares doubles, and your total value is unchanged.
3. TRI includes reinvested dividends, which funds also receive, so it's the fair comparison.
4. Twice a year (semi-annually). Declining companies are removed and rising ones added automatically.
5. You can't tell. You need market cap (price × number of shares).
</details>
