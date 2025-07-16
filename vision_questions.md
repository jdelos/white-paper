
# Calçotada Protocol Vision Questions

## Your First Answer

**Valuation calculation methods** -> I am using a Discounted Cash Flows as industry standard for early startups. This is my proposal, the difference here is that we can embed a mechanism that provides buy backs on the current company performance based on these valuations. This sets a standard for the future large investments and also provide early liquidity.

---

## On Composability

### 1. What specific components should be standardized?

- Valuation calculation methods? [ANSWERED: DCF-based valuations]
- Buyback mechanisms?
  The buy bak meachanims are defined by DCF valuations where the extnal parmaetes like industry multplier and WACC should come from and oracle base on our current performances.

Based on this valutions I provide early exits with buy backs.
you can finde them in the ./Tokenomics RMSC.ods file.

The buys backs are defined buy a SAFE + I (interest model) based on the EPOS contract.
Valuation = (1+Interest)^year/(1-Discount)
Tk_ROI = MAX( Valuation, Valuation/ValuationCap)
This ROI multiplier is abased on the AVRG_RMSC mint price
TK_BUY_BACK_PRICE = TK_ROI \* Price_at_mint_avg

- Estimated Results 

### 📈 Revenue Projections (€)

| Year         | 2026     | 2027      | 2028      | 2029      | 2030      | 2031      | 2032       |
|--------------|----------|-----------|-----------|-----------|-----------|-----------|------------|
| Revenues     | –        | 1         | 2         | 3         | 4         | 5         | 6          |
| Pesimistic   | 741,173  | 1,870,436 | 2,825,513 | 3,774,639 | 5,298,227 | 8,087,980 | 13,573,855 |
| Standard     | 741,173  | 2,924,814 | 4,402,150 | 5,732,910 | 7,658,323 |10,850,040 | 16,737,653 |
| Optimistic   |1,384,738 | 6,799,688 |10,627,446 |13,565,859 |17,098,776 |21,898,100 | 29,393,358 |

---

### 💰 Valuation (€)

| Year         | 2026     | 2027      | 2028      | 2029      | 2030      | 2031      | 2032       |
|--------------|----------|-----------|-----------|-----------|-----------|-----------|------------|
| Pesimistic   | –        |   182,967 | 3,125,648 | 6,039,629 |12,148,253 |24,700,368 | 52,152,995 |
| Standard     | –        | 5,015,056 |10,921,515 |16,294,714 |25,042,521 |40,398,542 | 70,916,098 |
| Optimistic   | –        |22,840,861 |38,165,310 |53,474,493 |72,064,740 |97,056,476 |137,585,150 |

---

### 💶 Valuation for RMSC (€)

| Year         | 2026     | 2027      | 2028      | 2029      | 2030      | 2031      | 2032       |
|--------------|----------|-----------|-----------|-----------|-----------|-----------|------------|
| Pesimistic   | –        |   182,967 | 3,125,648 | 6,039,629 |12,148,253 |24,700,368 | 25,000,000 |
| Standard     | –        | 5,015,056 |10,921,515 |16,294,714 |25,000,000 |25,000,000 | 25,000,000 |
| Optimistic   | –        |22,840,861 |25,000,000 |25,000,000 |25,000,000 |25,000,000 | 25,000,000 |

---

### 🧮 RMSC Prices (Model-Based)

| Year         | 2026   | 2027   | 2028   | 2029   | 2030   | 2031   | 2032 |
|--------------|--------|--------|--------|--------|--------|--------|-------|
| Pesimistic   | 0.655  | 0.694  | 0.736  | 0.780  | 0.827  | 1.095  | –     |
| Standard     | 0.655  | 0.694  | 0.736  | 0.780  | 0.848  | 1.489  | –     |
| Optimistic   | 0.655  | 0.801  | 1.123  | 1.513  | 2.038  | 2.889  | –     |

---

### 🎯 Target RMSC Prices

| Year         | 2026 | 2027 | 2028 | 2029 | 2030 | 2031 |
|--------------|------|------|------|------|------|------|
| Pesimistic   | 1.2  | 1.3  | 1.4  | 1.5  | 1.6  | 2.1  |
| Standard     | 1.2  | 1.3  | 1.4  | 1.5  | 1.6  | 2.8  |
| Optimistic   | 1.2  | 1.5  | 2.1  | 2.9  | 3.9  | 5.5  |


- Financial reporting formats?
  Today accountancy is dependent of the intragtaion of you bankc with the dedicated tool that you accountant decides. All this data is centralized and coded in the standrasts.
  An on-chain accountancy would allow a reliabile inmutable records easy adutiable and the creation of new accountacy DAPPs.

### 2. How do you envision other projects using these components?

- Could any startup create their own equity-pegged token using your framework?
  That's is the purpose of creating a protocol. Provide a fast standart for new projects and the composability for VC DAO-DEFIs

- Would there be a "Calçotada Standard" like ERC-20?
  Could evolve in a standard could evolve in a dedicated network, for PEG coins.

## TDB with the onboarding team.

## On Oracle Integration

### 3. What specific fiat transactions need validation?

- Company revenue streams?
  We need to have access to the Free Cash Flows

The question is what is not worthy to have on chain. All the guarantees transparency but does not feeds competition.

- Operating expenses?
- Bank account balances?
- Customer payments?

### 4. How would you handle privacy vs. transparency?

- What financial data should be public?
  What is today's the standats for companies and required for the tax office.

- What needs to remain confidential?
- How to verify without revealing sensitive information?
  Integration hyperger for condetial data that could harm copany competition https://en.wikipedia.org/wiki/Hyperledger

## Gurantee transparency towards users by means of smart contract accountacy auditors. Can see and guarantee the right accountability.

## On the Meme Coin to PEG Coin Transition

### 5. What attracts meme coin investors that PEG coins can capture?

First, this is a crypto comunty already used to investments and purchase of coins.
A part of this people is educated enought to explore new currencies and open to high risk.

- High risk/reward potential?
  With a combiation of shortem liquidit for a 20% early rewards for flippers and a potentila long term rewards ranging from x2 worst case and x5.5 good case.

- Community engagement?
- Viral marketing potential?
- Quick liquidity?
  Early creation of Liquidty Pool with Tax for ealry floppers, and as a measure to enable long term believers access to profits.

### 6. How do you educate these investors?

- What's the learning curve from meme coins to understanding equity pegs?
- What incentives help them make this transition?

---

## On Building Trust

### 7. What are the key trust barriers you're solving?

Stablishing a foundation of trust in the equity borrowed is fundamental for composability.
Buy having trust proof that RMSC are bough back as defined on chain with no human factors involved.

We can with the easy of access and trade that crypt allows be participating to the SEED capital, with guaranteed returns on the investment.

- Trust in startup valuations?
  By predefining a future valuation with a model in advance is the first step in the model.
  The extra factors like cost of credit etc can be provided by oracles.
- Trust in buyback commitments?
  The buy back comitements can be directly executed by a smart contract accountacy with a public reserves.
- Trust in governance processes?

- Trust in crypto generally?

### 8. How does standardization increase trust?

- Through predictability?
  Deterministic mathematical expressions
- Through auditability?

- Through community verification?

---

## On Broader Impact

### 9. Who is the "broader audience" you want to reach?

- Retail investors currently in meme coins?
  Yes exactly
- Traditional investors new to crypto?
  Onboard a new wave of interest among young professionals.
  Use a onbarding system to incetivize the comunity wit refeal system 5RMS each
- Young investors without accredited status?

### 10. What does success look like in 5 years?

The Calçotada Company operating in eruope full scale.

- 3 patents published
- Prfitable from yer 3
- Buy back working
- RMSC tokens accepted in Maker Daw etc.

---

Question to be answered after the MVP

- How many companies using the protocol?
- What total value locked?
- What geographic reach?
- What regulatory recognition?

---

## Additional Vision Questions

### 11. On DCF Implementation

- How frequently would valuations be updated?

- What discount rates would be used for early-stage companies?
- How would you handle pre-revenue startups?
- Would the DCF model be adjustable by governance?

### 12. On Early Liquidity

- What triggers a buyback event?
- How much liquidity is "early" - 6 months? 1 year? 2 years?
- What percentage of profits goes to buybacks vs. reinvestment?
- How do you balance founder liquidity needs with investor returns?
