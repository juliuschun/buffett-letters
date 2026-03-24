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

### The same principle, applied to machines

Buffett's writings make humans wiser — not because they contain secret formulas, but because they are full of *specific stories, specific numbers, and specific reasoning*. A person who reads all 49 letters thinks about business differently than someone who just knows "buy and hold."

The same is true for LLMs. General training gives an AI the equivalent of knowing Buffett's name. This repo gives it the equivalent of having *read every letter, internalized every case study, and built a mental model from 49 years of evidence*. The specificity is what creates depth — not just "moats matter" but "here is exactly how GEICO's cost moat widened from 1986 to 2020, here is the math, here is what it means for your business."

Because the checklist produces a numerical score (0-100), this also enables **large-scale screening**. Feed your AI a list of companies, and it can evaluate each one through the full Buffett framework — consistently, thoroughly, with cited reasoning — at a speed no human analyst can match.

## How to Use This

This repo has two tracks, built for different purposes:

### Track 1: Business Analysis Toolkit — feed it to your AI

The core product. These files turn an LLM into a Buffett-grade business analyst:

| What to Feed Your AI | What It Gets |
|---|---|
| `buffett-business-checklist.md` | The evaluation framework — 28 questions, 7 gates, moat scoring |
| `business-reference/` (7 files) | Deep evidence for every checklist concept — the *why* behind every question, with links to original letters |
| `buffett-field-guide.md` | Practical how-to: where to find data, what numbers to pull, how to interpret |
| `case-studies/` | Worked examples showing the framework in action |

Every claim in the analysis toolkit links back to the original letter via `markdown/buffett-letter-YYYY.md`. When your AI encounters a reference like `[1986](markdown/buffett-letter-1986.md)`, it can read the full original text for deeper context. The chain goes: **checklist question → business-reference evidence → original letter**.

**Minimum viable prompt**: give your AI the checklist + business-reference, then ask it to evaluate any company. It will run the full Buffett analysis — industry, moat, management, risk, valuation — with specific letter references backing every judgment.

**For large-scale screening**: because the checklist outputs a 0-100 score, you can feed a list of companies and get consistent, comparable evaluations across all of them.

### Track 2: Wisdom Library — read it yourself, or let AI absorb it

49 years of the world's greatest investor explaining business in plain English. Great for building general judgment — whether you read it yourself or feed it to an AI for deeper context.

| Document | What It Contains |
|---|---|
| **[15 Themes Synthesis](buffett-business-wisdom-synthesis.md)** | 1,050 lessons organized into 15 enduring themes |
| **[Quotation Collection](buffett-quotations-collection.md)** | 1,262 quotes, 11 categories, Top 25 iconic |
| **[Theme Deep-Dives](themes/)** (16 files) | Full analysis of each theme with stories and examples |
| **[Year-by-Year Lessons](lessons/)** (49 files) | Every lesson from every letter, in chronological context |
| **[Original Letters](markdown/)** (49 files) | The full text of every shareholder letter, 1977-2025 |

These are the files that make humans — and AIs — wiser over time. Not for scoring a specific company, but for building the mental models that make every future analysis sharper.

**Maximum depth**: feed the analysis toolkit *and* the wisdom library together. Your AI now has the structured framework *plus* the deep pattern recognition from 49 years of stories, mistakes, and evolving thinking.

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

## Install as a Claude Skill

If you use Claude Code / Tower, install eco-moat-ai as a skill so it's always available:

```bash
git clone https://github.com/juliuschun/eco-moat-ai.git ~/eco-moat-ai
ln -s ~/eco-moat-ai/.claude/skills/eco-moat-ai ~/.claude/skills/eco-moat-ai
```

Then just say "evaluate [company]" and the skill activates — running the full 3-stage Buffett analysis with moat scoring.

The skill includes the complete evaluation framework inline, references the deep-dive files for evidence, and links through to original letters when needed. It also supports batch screening mode for comparing multiple companies at once.

## How This Was Made

AI agents (Claude) analyzed all 49 letters in parallel — downloading, converting, extracting lessons, collecting quotes, synthesizing themes, and building the evaluation framework. The original letters are publicly available at [berkshirehathaway.com](https://www.berkshirehathaway.com/letters/letters.html).

## License

The original shareholder letters are the property of Berkshire Hathaway Inc.
The analysis, extraction, and synthesis are provided for educational purposes.

---

*Built by [Moat AI](https://github.com/juliuschun) — because the best investment advice has been free and public for 49 years.*
