# The Buffett Business Evaluation Field Guide

> *"Risk comes from not knowing what you're doing."* — [1992]

The [checklist](buffett-business-checklist.md) tells you WHAT to evaluate. This field guide tells you **WHERE to look, WHAT numbers to pull, and HOW to interpret them** — with real examples from Buffett's own analysis of GEICO, See's Candies, Coca-Cola, and his biggest mistakes.

**[한국어 버전 (Korean)](buffett-field-guide-ko.md)**

---

## How This Guide Works

Each section maps a checklist item to:

1. **Exactly where to find the data** (free sources, with URLs)
2. **What specific numbers to pull** (the metrics Buffett actually tracked)
3. **How Buffett did it** (real case study with real numbers)
4. **Red flags and green flags** (pattern recognition from 49 years)
5. **AI-assisted analysis prompt** (copy-paste prompts for AI research)

---

## Stage 1: Intelligence Gathering — The Practical Playbook

### 1.1 Industry & Arena

#### What to collect:

| Data Point | Where to Find It (Free) | What to Look For |
|-----------|------------------------|-----------------|
| Business model description | Company's 10-K, "Business" section (Item 1) | Can you explain the revenue model in 3 sentences? |
| Industry growth rate (10yr) | [Macrotrends](https://macrotrends.net), [Statista](https://statista.com), KIET (Korea) | CAGR > 3% = tailwind; < 0% = headwind |
| Capex-to-revenue ratio | 10-K Cash Flow Statement | < 5% = capital-light (dream); > 15% = capital-hungry |
| Technology disruption pace | Industry trade press, earnings call transcripts | Stable for 10+ years = Buffett's preference |

#### How Buffett did it — The Textile vs. Insurance Test [1977]:

Buffett's very first letter contrasts two industries side by side:

| Metric | Berkshire Textiles | National Indemnity (Insurance) |
|--------|-------------------|-------------------------------|
| Capital required | Heavy (looms, inventory, plant) | Light (float is other people's money) |
| Pricing power | Zero (commodity fabric) | Possible (when disciplined) |
| Industry trend | Secular decline (imports) | Growing (more assets to insure) |
| Best-case outcome | Survival | Wealth creation |

**The verdict**: "I was not smart enough to make money in the textile business, so I moved to insurance where I didn't have to be smart." The industry you choose matters more than how well you play.

#### How Buffett did it — The Airline Graveyard [1992, 2007]:

> *"If a farsighted capitalist had been present at Kitty Hawk, he would have done his successors a huge favor by shooting Orville down."*

The airline industry has had insatiable growth — and destroyed capital the entire time:
- Enormous capex (planes)
- Zero pricing power (commodity seats)
- "Walking dead" competitors with nothing to lose on pricing
- Even brilliant management earns "survival, not prosperity"

**Field test**: If even after 100 years of growth, the industry has never produced a durable high-return business, the arena is wrong.

#### AI-assisted analysis prompt:

```
Analyze the industry economics of [COMPANY/INDUSTRY]:
1. What is the 10-year revenue CAGR for the industry?
2. What is the typical capex-to-revenue ratio?
3. Has any company sustained >15% ROE for >10 years in this industry?
4. What are the major sources of disruption risk?
5. Is this a "tailwind" or "headwind" industry?
Cite specific data sources.
```

---

### 1.2 Competitive Position (The Moat)

#### What to collect:

| Data Point | Where to Find It (Free) | What to Look For |
|-----------|------------------------|-----------------|
| Market share (5-10yr trend) | 10-K, industry reports, [TIKR](https://tikr.com) | Stable or growing = working moat |
| Pricing power evidence | Earnings call transcripts on [Seeking Alpha](https://seekingalpha.com) | "We raised prices X% with minimal volume impact" |
| Operating expense ratio vs. competitors | 10-K + competitor 10-Ks, [Macrotrends](https://macrotrends.net) | Structural gap = cost moat |
| Brand recognition | Google Trends, app store reviews, NPS data | Top 3 in category = strong brand |
| Customer concentration | 10-K "Risk Factors" section (Item 1A) | Top customer < 10% of revenue = diversified |

#### How Buffett measured it — GEICO's Moat Dashboard:

Buffett tracked GEICO's moat with a specific set of metrics over 44 years. This is literally the dashboard he used:

| Metric | 1986 | 1995 | 2008 | 2015 | What It Told Him |
|--------|------|------|------|------|-----------------|
| **Expense ratio** | 23.5% | 23.6% | ~15% | 14.7% | Moat is WIDENING (competitors stuck at 25-40%) |
| **Market share** | ~2% | 2.5% | 7.7% | 11.4% | Cost advantage converting to growth |
| **Combined ratio** | 96 | <100 | <100 | <100 | Underwriting profitable (industry avg >100) |
| **Policies per employee** | — | — | 439 | — | Productivity improving (was 299 in 2003) |
| **Ad spend** | — | $31M | $751M | $900M+ | Investing savings into growth, not margins |
| **Customer referrals** | — | — | 1M+/yr | — | Organic growth engine = brand strength |

**The key insight**: Buffett didn't just measure the moat — he measured whether it was **widening or narrowing**. The gap between GEICO's expense ratio and competitors' was the moat width. It went from 15 points (1986) to 25+ points (2015).

#### How Buffett measured it — See's Candies Pricing Power Test:

Three tests Buffett used to confirm See's had a "consumer franchise" [1983, 1991]:

**Test 1 — The Price Increase Test**:
- See's raised prices every single year for 50 years
- In an industry with zero unit growth, ALL earnings growth came from pricing
- Pre-tax earnings: $4.2M (1972) → $42.4M (1991) → $83M (2011)
- Volume barely changed; price did all the work

**Test 2 — The Customer Protest Test**:
- When See's was about to close its Albuquerque store, 263 customers wrote letters to save it
- If customers fight to keep you, you have a franchise

**Test 3 — The Tax Cut Test** [1983]:
- When corporate taxes are cut, does the company KEEP the savings (franchise) or PASS them to customers (commodity)?
- See's kept every penny → franchise confirmed
- Textile mills passed savings through → commodity confirmed

**Field test you can do today**: Search for "[Company] price increase customer reaction" — if customers complain but stay, that's pricing power. If they leave, it's not.

#### AI-assisted analysis prompt:

```
Evaluate the competitive moat of [COMPANY]:
1. What is their market share and how has it changed over 5 years?
2. Compare their operating expense ratio to top 3 competitors
3. When did they last raise prices? What was the customer/volume impact?
4. What is their Net Promoter Score or app store rating vs. competitors?
5. What would a new entrant need to spend to replicate their position?
Rate each moat type (cost, brand, switching, network, scale, regulatory) 0-10.
```

---

### 1.3 Financial Profile

#### What to collect:

| Data Point | Where to Find It (Free) | Buffett's Benchmark |
|-----------|------------------------|-------------------|
| ROE (10 years) | [Macrotrends](https://macrotrends.net/stocks/charts/TICKER/return-on-equity) | > 15% consistently, without leverage tricks |
| Owner earnings | Calculate from 10-K: Net income + D&A - maintenance capex | Growing faster than reported earnings = hidden value |
| Free cash flow vs net income | [Stock Analysis](https://stockanalysis.com) | FCF > Net income = quality earnings |
| Debt-to-equity | [Yahoo Finance](https://finance.yahoo.com) | < 0.5 preferred; > 1.0 = caution |
| Capex as % of earnings | 10-K cash flow statement | < 25% = capital-light; > 50% = capital-hungry |

#### How Buffett calculated Owner Earnings [1986]:

This is the formula Buffett created because he thought GAAP was misleading:

```
Owner Earnings = Reported Earnings
              + Depreciation & Amortization
              + Other non-cash charges
              - Average annual maintenance capex
              - Working capital changes (if needed to maintain volume)
```

> *"References to EBITDA make us shudder — does management think the tooth fairy pays for capital expenditures?"* — [2000]

**The key distinction**: Growth capex (spending to expand) should be EXCLUDED from the deduction. Only maintenance capex (spending to keep the business running at current levels) counts. This is why "cash flow" metrics that add back all depreciation are dangerous — some of that depreciation is REAL.

#### How Buffett did it — See's Capital Efficiency:

| What Average Businesses Need | What See's Needed |
|-----|-----|
| $5 of capital per $1 of additional earnings | $0.63 of capital per $1 of additional earnings |
| $18M in tangible assets to earn $2M | $8M in tangible assets to earn $2M |
| Under inflation: needs $18M MORE capital when prices double | Under inflation: needs only $8M MORE |

**The test**: How much capital must the business reinvest just to maintain its current earnings power? Less = better. Zero = dream.

- See's: $32M reinvested over 35 years, produced $1.35B → **42x return**
- Berkshire Textiles: Millions reinvested annually, produced declining returns → **destroyed capital**

#### How Buffett did it — The Coca-Cola Compounding Machine:

| Year | What $1.3B Investment Produced |
|------|------|
| 1994 (purchase) | $75M annual dividends |
| 2010 | Dividends growing at 7-9% annually |
| 2022 | $704M annual dividends (9.4x the initial) |
| 2023 | Annual earnings share > entire original purchase cost |

After 29 years, Buffett's annual income from Coke **exceeded what he paid for the entire position**. And he never bought or sold a single additional share.

**The field test**: Calculate the dividend yield on your cost basis 10 years from now, assuming current dividend growth rate. If it exceeds 15%, you may have a compounder.

#### AI-assisted analysis prompt:

```
Calculate owner earnings for [COMPANY] for the last 5 years:
1. Start with net income from the income statement
2. Add back depreciation and amortization
3. Estimate maintenance capex (use 60-70% of total capex for mature companies)
4. Subtract maintenance capex
5. Compare owner earnings to reported net income — is the company under or over-earning?
6. Calculate owner earnings yield (owner earnings / market cap)
7. Compare to 10-year Treasury yield — is the spread adequate?
```

---

### 1.4 Management Quality

#### What to collect:

| Data Point | Where to Find It (Free) | What to Look For |
|-----------|------------------------|-----------------|
| CEO/insider ownership | Proxy statement (DEF 14A) on [SEC EDGAR](https://sec.gov/cgi-bin/browse-edgar) | CEO owns > 3% of net worth in company stock |
| Executive compensation | DEF 14A, "Compensation Discussion" section | Simple, tied to controllable metrics |
| Capital allocation track record | Compare 5-year ROE trend to industry; review past acquisitions | Consistent above-industry ROE without leverage |
| Mistake acknowledgment | Search annual reports for "mistake," "error," "wrong" | Buffett used these 16 times in 5 years; most companies: 0 |
| Management tenure | [LinkedIn](https://linkedin.com), proxy statement | Long tenure of key operators = stability |

#### How Buffett evaluated managers — The Four-Trait Test:

From Wells Fargo (1990), comparing Reichardt/Hazen to Murphy/Burke:

| Trait | What to Look For | Where to Find Evidence |
|-------|-----------------|---------------------|
| **Partnership** | CEO + COO stronger together than apart | Board composition, co-leadership history |
| **Pay well, refuse bloat** | Competitive pay for top talent, but lean org | Headcount growth vs. revenue growth (10-K) |
| **Attack costs always** | Cost discipline in good times AND bad | SG&A as % of revenue trend over 10 years |
| **Stick to what they know** | No ego-driven diversification | Acquisition history — related or random? |

#### How Buffett evaluated managers — GEICO's Incentive Design [1996]:

The compensation plan Buffett praised as ideal had exactly TWO variables:

```
Bonus = f(policy growth, underwriting profitability)
```

That's it. Not revenue. Not stock price. Not "adjusted EBITDA." Two things the employee could directly influence. New business acquisition costs were deliberately EXCLUDED so managers wouldn't avoid growth investments.

**The field test**: Read the proxy statement's compensation section. If you can't explain the bonus formula in one sentence, the incentives are probably misaligned.

#### Red flags in management:

| Red Flag | Where to Spot It | Buffett's Warning |
|----------|-----------------|-------------------|
| Adjusted earnings that always beat GAAP | Earnings releases, earnings calls | "When CEOs tout EBITDA, wire them up for a polygraph" [2014] |
| Stock-based comp not expensed | Proxy statement footnotes | "If options aren't compensation, what are they?" [1992] |
| Frequent "one-time" charges | Income statement, year over year | "If there are so many one-time items, they aren't one-time" [1998] |
| CEO predicting 15%+ growth publicly | Earnings calls, press interviews | "Predictions trigger uneconomic maneuvers" [2000] |
| Insider selling during buybacks | [SEC Form 4 filings](https://sec.gov) | Company buying while insiders sell = misalignment |

#### AI-assisted analysis prompt:

```
Evaluate management quality of [COMPANY]:
1. What % of CEO's net worth is in company stock? (Check proxy statement)
2. How is executive compensation structured? Is it simple and tied to operations?
3. Search the last 5 annual reports: how many times do they use "mistake" or "error"?
4. Compare SG&A growth rate to revenue growth rate over 5 years
5. List the last 3 acquisitions — were they related to core business? What was the ROI?
6. Has management consistently under-promised and over-delivered on guidance?
```

---

### 1.5 Customer & Product

#### What to collect:

| Data Point | Where to Find It (Free) | What to Look For |
|-----------|------------------------|-----------------|
| Customer retention / churn rate | Earnings calls, SaaS metrics if applicable | > 90% retention = strong franchise |
| App store ratings | [Apple App Store](https://apps.apple.com), [Google Play](https://play.google.com) | > 4.5 stars with 100K+ reviews |
| Net Promoter Score | Industry benchmarks, company reports | > 50 = excellent; > 70 = world-class |
| Social media sentiment | [Google Trends](https://trends.google.com), Twitter/X search | Trend direction more important than absolute |
| Revenue per customer trend | 10-K segment data, earnings calls | Growing = deepening relationship |

#### Buffett's Franchise Test [1991]:

A "franchise" has ALL THREE:

| Condition | Franchise (See's) | Commodity (Textiles) |
|-----------|-------------------|---------------------|
| Product needed or desired | Chocolate as emotional gift ✅ | Fabric — interchangeable ❌ |
| No close substitute in customer's mind | "See's" IS the gift ✅ | Any fabric works ❌ |
| Not subject to price regulation | Sets own prices freely ✅ | Market sets price ❌ |

**If your target business fails even ONE of these three conditions, it's a commodity, not a franchise.**

#### The "Disappearance Test":

> Would customers notice or care if this company disappeared tomorrow?

- See's: 263 customers wrote letters to save one store → YES
- Berkshire Textiles: Customers immediately switched to cheaper imports → NO
- Coca-Cola: Billions of daily servings; "buy commodities, sell brands" → YES
- Generic airline: Passengers rebook on next cheapest flight → NO

---

### 1.6 Risk Landscape

#### What to collect:

| Data Point | Where to Find It (Free) | What to Look For |
|-----------|------------------------|-----------------|
| Top 3 business destruction scenarios | 10-K Item 1A "Risk Factors" | Company's own list of what could kill it |
| Regulatory dependency | 10-K Item 1, regulatory filings | Single regulatory change = existential? |
| Revenue concentration | 10-K segment data, major customer disclosures | Top customer > 20% = dangerous |
| Debt maturity schedule | 10-K notes to financial statements | Large maturities during potential recession? |
| Insurance/guarantee exposure | Balance sheet footnotes | Off-balance-sheet risks that could surface |

#### Buffett's Inversion Principle [1996]:

> *"Tell me where I'm going to die, so I'll never go there."* — Charlie Munger

Before evaluating upside, list everything that could destroy the business:

**The Reverse Engineering Process:**

```
Step 1: List 3 specific scenarios that would destroy this business
Step 2: Assign probability to each (be honest, not hopeful)
Step 3: Ask: Can the business survive ALL THREE happening simultaneously?
Step 4: If no → the business is fragile regardless of current performance
```

#### How Buffett missed it — The USAir Disaster [1989-1996]:

| What He Evaluated | What He Should Have Evaluated |
|-------------------|------------------------------|
| Long history of profitable operations ✅ | That profitability was under REGULATION 🚫 |
| Senior security (preferred stock) ✅ | That seniority means nothing in bankruptcy 🚫 |
| Brand and route network ✅ | That "walking dead" competitors would destroy pricing 🚫 |

**The lesson**: "A company's track record under one set of industry conditions tells you nothing about its prospects when conditions fundamentally change."

---

### 1.7 Valuation

#### What to collect:

| Data Point | Where to Find It (Free) | Buffett's Approach |
|-----------|------------------------|-------------------|
| Price-to-owner-earnings | Calculate: Market cap ÷ Owner earnings | < 15 = interesting; < 10 = compelling |
| Owner earnings yield vs. Treasury | Calculate: (Owner earnings / Market cap) vs 10yr Treasury | Spread > 3% = adequate margin of safety |
| Historical P/E range | [Macrotrends](https://macrotrends.net) | Current vs. 10-year average |
| DCF value | [GuruFocus](https://gurufocus.com/dcf-calculator), [Fair Value Calculator](https://fairvalue-calculator.com/en/warren-buffett-fair-value) | Margin of safety > 25% |
| "Whole company" price | What would you pay if you could never sell? | Eliminates speculative premium |

#### How Buffett valued Wells Fargo [1990]:

| Factor | What He Saw |
|--------|------------|
| Stock price | Dropped 50% on California real estate fears |
| P/E ratio | Less than 5x after-tax earnings |
| ROE | 20%+ |
| Market sentiment | Maximum fear — "It's optimism that is the enemy of the rational buyer" |
| Management | World-class operators (Reichardt/Hazen) |

**The framework**: When a great business with great management trades at 5x earnings because of temporary industry fear, the math is overwhelming. The key word is "temporary."

#### How Buffett valued Coca-Cola [1988]:

| What He Paid | What He Got |
|-------|------|
| $1.3B total | 44% global soft drink market share |
| ~15x earnings | Product unchanged since 1886 |
| "Fair" price | 50x growth in unit volume since 1938 (after experts said it was saturated) |

He did NOT get a "bargain" price. He paid a fair price for an extraordinary business. The returns came from the business's own compounding, not from multiple expansion.

> *"It's far better to buy a wonderful company at a fair price than a fair company at a wonderful price."* — [1989]

#### The Margin of Safety Calculation:

```
Margin of Safety = (Intrinsic Value - Market Price) / Intrinsic Value × 100

Intrinsic Value = Owner Earnings × (8.5 + 2 × Expected Growth Rate)
                  [Graham's formula, modified by Buffett]

Or: Owner Earnings / Required Return Rate (capitalization method)
```

| Margin of Safety | Buffett's View |
|-----------------|---------------|
| > 50% | Extremely rare; back up the truck |
| 25-50% | Strong buy for high-conviction ideas |
| 15-25% | Adequate for excellent businesses |
| < 15% | Insufficient — wait for a better price |

#### AI-assisted analysis prompt:

```
Value [COMPANY] using Buffett's framework:
1. Calculate owner earnings for the trailing 12 months
2. Apply a 10% discount rate (or current 10yr Treasury + 6%)
3. Estimate sustainable growth rate (use lower of: historical EPS growth, ROE × retention ratio, or GDP+inflation)
4. Calculate intrinsic value using a two-stage DCF (10yr growth + terminal)
5. Compare to current market price — what is the margin of safety?
6. Would you be comfortable buying the ENTIRE company at this price and never selling?
```

---

## Stage 2: The Seven Gates — Red Flags That Kill Deals

For each gate, here's exactly what to check and what disqualifies:

| Gate | The "Instant Kill" Signal | Where to Find It |
|------|--------------------------|-----------------|
| **G1: Understandable** | You can't explain the revenue model after reading the 10-K | Item 1 of any 10-K |
| **G2: Good prospects** | Industry in secular decline; tech disruption within 5 years | Industry reports, patent filings by competitors |
| **G3: Honest management** | "Mistake" or "error" never appears in annual reports; insider selling accelerating | Annual reports word search; SEC Form 4 |
| **G4: Fair price** | P/E above 25 for a slow-growth business; no margin of safety | [Finviz](https://finviz.com), [GuruFocus](https://gurufocus.com) |
| **G5: Proven earnings** | Company has never been profitable through a recession | 10-year income statement spanning 2008-2009 or 2020 |
| **G6: Financially independent** | Negative free cash flow for 3+ consecutive years | Cash flow statement on [Macrotrends](https://macrotrends.net) |
| **G7: No lethal leverage** | Net debt/EBITDA > 4x; single-event wipeout possible | Balance sheet + footnotes |

### Buffett's Actual Disqualification Cases:

| Case | Which Gate Failed | The Specific Evidence |
|------|------------------|---------------------|
| **Berkshire Textiles** | G2 (Prospects) | Imports growing 10% annually; domestic mills closing every year |
| **Dexter Shoes** | G2 (Prospects) | 93% of shoes imported; domestic manufacturing structurally uncompetitive |
| **USAir** | G2 + G7 | Deregulation changed the entire competitive landscape; leverage amplified the damage |
| **Tesco** | G3 (Management) | Market share falling + accounting irregularities = cockroach in the kitchen |
| **Precision Castparts** | G4 (Price) | Wonderful company, but $11B overpayment → "I was simply too optimistic" |
| **Waumbec Mills** | G2 (Prospects) | Doubled down on textiles using "synergy" as justification |

---

## Stage 3: Moat Combination Scoring — Worked Examples

### Example 1: GEICO (Score: 100)

| Moat Type | Score | Evidence |
|-----------|-------|---------|
| M1: Cost Advantage | **10** | Expense ratio 14.7% vs. competitors' 25-40%. Structural, widening. |
| M2: Brand | **8** | $900M+ annual ad spend; top-of-mind awareness; gecko mascot |
| M3: Switching Cost | **3** | Auto insurance is easy to switch; 6-month policy cycles |
| M4: Network Effects | **1** | Minimal network effects in insurance |
| M5: Scale | **9** | #2 U.S. auto insurer; each share point = $1.6B revenue |
| M6: Regulatory | **5** | State insurance regulation creates moderate barriers |

**Raw Score**: 36 / 60

**Combinations**:
- C1 (Cost + Scale): **×1.3** — Lower costs → lower prices → more customers → more scale → lower costs
- C5 (Cost + Brand): **×1.5** — Lowest price AND top-of-mind awareness. Nowhere for competitors to attack.
- C6 (Capital-light + moat): **×1.4** — Float model means the business generates rather than consumes capital

**Final**: 36 × 1.3 × 1.5 × 1.4 × 1.667 = 164 → **capped at 100**

---

### Example 2: See's Candies (Score: 95)

| Moat Type | Score | Evidence |
|-----------|-------|---------|
| M1: Cost Advantage | **4** | Not a low-cost producer; premium positioning |
| M2: Brand | **10** | 50 years of price increases; 263 protest letters; emotional gift product |
| M3: Switching Cost | **5** | Moderate — gifting creates social obligation to specific brand |
| M4: Network Effects | **0** | None |
| M5: Scale | **3** | Regional scale in California/West Coast |
| M6: Regulatory | **0** | No regulatory protection |

**Raw Score**: 22 / 60

**Combinations**:
- C2 (Brand + Pricing Power): **×1.3** — Brand enables annual price increases that fund brand investment
- C6 (Capital-light + moat): **×1.4** — $32M invested, $1.35B returned

**Final**: 22 × 1.3 × 1.4 × 1.667 = 66.7 → **67** (Note: The capital-light amplifier is what makes this score high despite modest raw score)

But wait — this was purchased at 6x pre-tax earnings. The combination of a 67-score moat at a 6x price is what produced the greatest investment in Berkshire's history. **Moat score × valuation = total return.**

---

### Example 3: Berkshire Textiles (Score: 7)

| Moat Type | Score | Evidence |
|-----------|-------|---------|
| M1: Cost | **2** | Some efficiency, but imports always cheaper |
| M2: Brand | **0** | Commodity fabric; no brand recognition |
| M3: Switching | **0** | Zero switching costs |
| M4: Network | **0** | None |
| M5: Scale | **2** | Some scale, but irrelevant against global competition |
| M6: Regulatory | **0** | No barriers to entry or imports |

**Raw Score**: 4 / 60 — No combinations apply.

**Final**: 4 × 1.667 = **7**

> *"About as rewarding as struggling in quicksand."*

---

### Example 4: Dexter Shoes (Score: 12)

| Moat Type | Score | Evidence |
|-----------|-------|---------|
| M1: Cost | **1** | U.S. labor costs couldn't compete with imports |
| M2: Brand | **3** | Some brand, but not enough for pricing power |
| M3: Switching | **1** | Shoes are easily substitutable |
| M4: Network | **0** | None |
| M5: Scale | **2** | Moderate U.S. manufacturing scale |
| M6: Regulatory | **0** | No protection from imports |

**Raw Score**: 7 / 60 — No meaningful combinations.

**Final**: 7 × 1.667 = **12**

Buffett paid $433M (in Berkshire stock!) for a 12-score business. The stock later became worth $5.7B. This is what happens when you pay a wonderful price for a mediocre business — **with your most valuable currency**.

---

## Quick-Start: Your First Analysis in 30 Minutes

```
Step 1 (5 min): Read the company's 10-K Item 1 (Business Description)
               → Can you explain the business model in 3 sentences?

Step 2 (5 min): Pull 10-year ROE from Macrotrends
               → Is it consistently > 15%?

Step 3 (5 min): Calculate owner earnings from the most recent 10-K
               → Net income + D&A - 70% of capex

Step 4 (5 min): Compare operating margins to top 3 competitors
               → Is there a structural gap?

Step 5 (5 min): Search last 3 annual reports for "mistake" and "error"
               → Does management admit failures?

Step 6 (5 min): Calculate margin of safety
               → Owner earnings yield vs. 10-year Treasury + 6%

If any step produces a red flag, STOP. Move on to the next company.
If all six pass, proceed to the full 28-question checklist.
```

---

## Appendix: Free Data Source Quick Reference

| Need | Best Free Source | URL |
|------|-----------------|-----|
| 10-K / Annual Reports | SEC EDGAR (US), DART (Korea) | sec.gov, dart.fss.or.kr |
| 10-year financial data | Macrotrends | macrotrends.net |
| Competitor comparison | TIKR, Stock Analysis | tikr.com, stockanalysis.com |
| Insider ownership | SEC EDGAR (DEF 14A, Form 4) | sec.gov |
| DCF calculator | GuruFocus | gurufocus.com/dcf-calculator |
| Industry data | Statista, KIET (Korea) | statista.com, kiet.re.kr |
| Stock screening | Finviz, TradingView | finviz.com, tradingview.com |
| Earnings transcripts | Seeking Alpha, Motley Fool | seekingalpha.com, fool.com |
| Brand sentiment | Google Trends, App reviews | trends.google.com |
| Credit ratings | Moody's, S&P (free summaries) | ratings.moodys.com |

---

*This field guide is a companion to the [Buffett Business Checklist](buffett-business-checklist.md). All case studies and metrics are extracted from Buffett's shareholder letters (1977-2025). Detailed case studies available in the `/case-studies/` folder.*
