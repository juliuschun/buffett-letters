# eco-moat-ai

### Give it to your AI. Make them run decisions like Buffett.

> *"It is not necessary to do extraordinary things to get extraordinary results."*
> — Warren Buffett, 1987 Shareholder Letter

49 years of Berkshire Hathaway shareholder letters (1977-2025), distilled into structured knowledge that turns any LLM into a world-class business analyst.

**[한국어 버전 (Korean)](ko/)**

---

## Why This Exists

LLMs already know who Warren Buffett is. They can quote him. But knowing *about* Buffett and thinking *like* Buffett are completely different things.

This repo bridges that gap. It gives your AI:

- **1,091 specific lessons** extracted from every letter, with year, context, and application
- **A 3-stage evaluation checklist** (28 questions, 7 binary gates, 6 moat types with combination scoring)
- **7 deep-dive reference files** linking each checklist concept to the exact passages in the letters
- **Real case studies** showing how the framework applies to GEICO, See's Candies, and failed acquisitions
- **1,262 curated quotes** organized by theme, not just the famous ones

The difference: an LLM without this repo gives you generic business advice. An LLM with this repo tells you *exactly which Buffett principle applies to your situation, why he believed it, which company proved it, and what year he said it* — then scores your business on a 100-point moat scale.

## How to Use This

### For AI — the primary use case

Drop these files into your AI's context. The more you include, the sharper the analysis:

| What to Feed Your AI | What It Gets |
|---|---|
| `buffett-business-checklist.md` | The evaluation framework — 28 questions, 7 gates, moat scoring |
| `business-reference/` (7 files) | Deep evidence for every checklist concept — the *why* behind every question |
| `buffett-field-guide.md` | Practical how-to: where to find data, what numbers to pull, how to interpret |
| `case-studies/` | Worked examples showing the framework in action |
| `themes/` (16 files) | Full thematic analysis — your AI absorbs 49 years of pattern recognition |
| `lessons/` (49 files) | Year-by-year lessons — maximum context for maximum depth |

**Minimum viable prompt**: give your AI the checklist + business-reference, then ask it to evaluate any company. It will run the full Buffett analysis — industry, moat, management, risk, valuation — with specific letter references backing every judgment.

**Maximum depth**: feed everything. Your AI now has more structured Buffett knowledge than any human analyst, cross-referenced across 49 years.

### For Humans — still great on its own

Read it yourself. This is 49 years of the world's greatest investor explaining business in plain English, organized so you can find what you need:

- **[15 Themes Synthesis](buffett-business-wisdom-synthesis.md)** — the big picture
- **[Quotation Collection](buffett-quotations-collection.md)** — 1,262 quotes, 11 categories, Top 25 iconic
- **[Business Checklist](buffett-business-checklist.md)** — evaluate any business in 3 stages
- **[Field Guide](buffett-field-guide.md)** — practical how-to with real examples

---

## What's Inside

| | Count |
|---|---|
| **Letters analyzed** | 49 (1977-2025) |
| **Business lessons extracted** | 1,091 |
| **Quotes collected** | 1,262 |
| **Thematic categories** | 15 |
| **Years of wisdom** | 49 |

## Repository Structure

```
eco-moat-ai/
├── README.md
├── buffett-business-checklist.md        # 3-stage evaluation framework
├── buffett-field-guide.md               # Practical application guide
├── buffett-business-wisdom-synthesis.md  # 15 themes across 49 years
├── buffett-quotations-collection.md      # 1,262 curated quotes
├── business-reference/                   # Evidence base for the checklist
│   ├── 01-competitive-moats.md
│   ├── 02-pricing-power-and-brand.md
│   ├── 03-cost-advantage-and-scale.md
│   ├── 04-capital-allocation.md
│   ├── 05-management-quality.md
│   ├── 06-risk-leverage-survival.md
│   └── 07-acquisition-discipline.md
├── case-studies/                          # GEICO, See's, failed acquisitions
├── themes/                               # 16 deep-dive theme analyses
├── ko/                                   # Korean translations
├── markdown/                             # All 49 letters in Markdown
└── lessons/                              # Per-year lesson extraction (49 files)
```

## The 15 Themes

1. **Competitive Moats & Durable Advantage** — Build the moat, then widen it every day
2. **Management Quality & the Owner-Operator Mindset** — Hire well, manage little
3. **Capital Allocation** — The CEO's most important (and often neglected) job
4. **Industry Economics** — Choose your arena; tailwinds beat talent
5. **Pricing Power & Cost Discipline** — The capital-light ideal
6. **Long-Term Thinking & Compounding** — Time is the friend of the wonderful business
7. **Risk Management & Financial Fortitude** — Build the ark before the rain
8. **The Insurance Model & Float** — Money that works for you while you hold it
9. **Acquisition Discipline** — Better wonderful at fair than fair at wonderful
10. **Honest Accounting & Transparency** — Sunlight is the best disinfectant
11. **Corporate Governance & Incentive Design** — You get what you pay for
12. **Mistakes & Humility** — The only unforgivable error is failing to learn
13. **The Institutional Imperative** — How organizations destroy rationality
14. **Valuation** — The timeless math of investing
15. **American Optimism** — Never bet against the long game

## The Checklist

| Stage | What It Does | Output |
|-------|-------------|--------|
| **Stage 1: Intelligence Gathering** | 28 questions across 7 dimensions | Raw facts about the business |
| **Stage 2: Mental Model Filter** | 7 binary gates from Buffett's core criteria | Pass / Fail decision |
| **Stage 3: Moat Combination Scoring** | 6 moat types x synergy multipliers | Score out of 100 |

**[Checklist](buffett-business-checklist.md)** | **[Field Guide](buffett-field-guide.md)** | **[Evidence Base](business-reference/)**

## Greatest Hits

> *"Be fearful when others are greedy, and greedy when others are fearful."* — [1986]

> *"It's far better to buy a wonderful company at a fair price than a fair company at a wonderful price."* — [1989]

> *"Time is the friend of the wonderful business, the enemy of the mediocre."* — [1989]

> *"Price is what you pay. Value is what you get."* — [2008]

> *"Only when the tide goes out do you discover who's been swimming naked."* — [1992]

[All 1,262 quotes →](buffett-quotations-collection.md)

## How This Was Made

AI agents (Claude) analyzed all 49 letters in parallel — downloading, converting, extracting lessons, collecting quotes, synthesizing themes, and building the evaluation framework. The original letters are publicly available at [berkshirehathaway.com](https://www.berkshirehathaway.com/letters/letters.html).

## License

The original shareholder letters are the property of Berkshire Hathaway Inc.
The analysis, extraction, and synthesis are provided for educational purposes.

---

*Built by [Moat AI](https://github.com/juliuschun) — because the best investment advice has been free and public for 49 years.*
