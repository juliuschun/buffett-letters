---
name: eco-moat-ai
description: |
  Evaluate any business like Warren Buffett using a 3-stage framework distilled from 49 years of shareholder letters.
  Use when: analyzing a company, evaluating a business idea, comparing investment opportunities,
  screening multiple companies, or when phrases like "is this a good business", "moat", "evaluate", "analyze" appear.
argument-hint: "[company name or business description]"
---

# eco-moat-ai: Buffett-Grade Business Analysis

**Purpose**: Evaluate any business through Warren Buffett's lens — 3-stage framework with 28 questions, 7 binary gates, and a 0-100 moat score. Every judgment backed by specific evidence from 49 years of shareholder letters.

**Source repo**: `~/eco-moat-ai/` (or wherever this repo is cloned)

---

## Quick Start

When the user asks you to evaluate a business:

1. Read the checklist: `buffett-business-checklist.md`
2. Read relevant business-reference files from `business-reference/`
3. Run the 3-stage evaluation below
4. Output a structured report with the final moat score

---

## The 3-Stage Framework

### Stage 1: Intelligence Gathering (28 Questions, 7 Dimensions)

Collect facts before forming any opinion. Answer each question with specific data.

**1.1 Industry & Arena**
1. Can you explain the business model in one paragraph?
2. Is the industry growing, stable, or declining? 10-year trend?
3. How capital-intensive? Typical capex-to-revenue ratio?
4. How fast does the industry change technologically?

**1.2 Competitive Position**
5. Market share trend over 5-10 years?
6. Can it raise prices without losing customers? Last time it did?
7. Cost structure vs. competitors?
8. Brand recognition — can consumers identify it unprompted?

**1.3 Financial Profile**
9. ROE consistently above 15% over 10 years?
10. How much capital needed to maintain current earnings?
11. What does it do with free cash flow?
12. Debt-to-equity? Could it survive 2 years of zero revenue?

**1.4 Management Quality**
13. CEO skin in the game — net worth in the company?
14. Capital allocation track record?
15. Does management admit mistakes? Search for "mistake"/"error" in reports.
16. Key people retention rate?

**1.5 Customer & Product**
17. Would customers notice if the company disappeared?
18. How do customers find this company?
19. Customer retention rate?
20. Must-have or nice-to-have?

**1.6 Risk Landscape**
21. What 3 scenarios would destroy this business?
22. Regulatory risk exposure?
23. Revenue concentration (top customer %, single product %)?
24. Significant leverage?

**1.7 Valuation & Context**
25. Price-to-owner-earnings vs. 10-year average?
26. What would you pay for the whole business if you could never sell it?
27. Current market sentiment — fearful or greedy toward this sector?
28. Comparable business valuations?

### Stage 2: Mental Model Filter (7 Binary Gates — ALL Must Pass)

| Gate | Question | Fail = Stop |
|------|----------|-------------|
| **G1** | Can I explain how it makes money in 3 sentences? | "Never invest in a business you cannot understand." |
| **G2** | Will it be stronger in 10 years? | "Turnarounds seldom turn." |
| **G3** | Do I trust management with my money? | "We've never succeeded in making a good deal with a bad person." |
| **G4** | Am I paying below intrinsic value with margin of safety? | "What is smart at one price is stupid at another." |
| **G5** | Has it proven earnings through at least one downturn? | "Demonstrated consistent earning power — future projections are of no interest." |
| **G6** | Can it survive without external financing? | "Never depend on the kindness of strangers." |
| **G7** | Could a bad year kill it? | "It is madness to risk losing what you need in pursuing what you simply desire." |

```
7/7 passed → Proceed to Stage 3
6/7 passed → STOP. Can the failing gate be resolved? Revisit in 6 months.
5/7 or below → REJECT.
```

### Stage 3: Moat Combination Scoring

**Score each moat type 0-10:**

| Moat | What It Means | 10 = |
|------|--------------|------|
| **M1: Cost Advantage** | Structurally lower costs | Widening cost gap competitors cannot close |
| **M2: Brand/Reputation** | Customers choose by name, pay premium | Iconic brand with proven pricing power |
| **M3: Switching Cost** | Customers can't leave easily | Deep integration, switching is painful |
| **M4: Network Effects** | Product improves as more use it | Strong self-reinforcing value loop |
| **M5: Scale Economics** | Bigger = permanently cheaper | Dominant, self-reinforcing cost advantage |
| **M6: Regulatory Barrier** | Legal/structural protection | Licenses, rights-of-way, natural monopoly |

**Apply combination multipliers (if both moats score 5+):**

| Combo | Moats | Multiplier | Why |
|-------|-------|-----------|-----|
| C1 | Cost + Scale | x1.3 | Lower costs → more customers → even lower costs |
| C2 | Brand + Pricing Power | x1.3 | Strong brand funds brand investment, strengthens brand |
| C3 | Switching + Network | x1.4 | Can't leave AND product improves. Near-impregnable |
| C4 | Scale + Regulatory | x1.3 | Economically impossible for new entrants |
| C5 | Cost + Brand | x1.5 | Lowest price AND top-of-mind. Nowhere to attack |
| C6 | Capital-Light + Any Moat | x1.4 | Low reinvestment = enormous free cash flow |

**Final Score**: `Raw Score x Product of Multipliers x (10/6)`, capped at 100.

| Score | Rating | Action |
|-------|--------|--------|
| 80-100 | Extraordinary | Buy at any fair price. Hold forever. |
| 60-79 | Excellent | Buy with margin of safety. Hold for decades. |
| 40-59 | Good | Buy only at clear discount. Monitor moat annually. |
| 20-39 | Mediocre | Avoid unless extraordinary management + deep discount. |
| 0-19 | Avoid | Walk away. No price is low enough. |

---

## Deep-Dive Reference Files

When you need deeper reasoning behind any checklist concept, read these files:

| Topic | File to Read |
|-------|-------------|
| Moat types, durability, combinations | `business-reference/01-competitive-moats.md` |
| Pricing power, brand building, franchise vs commodity | `business-reference/02-pricing-power-and-brand.md` |
| Cost advantage, scale, GEICO model | `business-reference/03-cost-advantage-and-scale.md` |
| ROE, owner earnings, capital-light businesses | `business-reference/04-capital-allocation.md` |
| Management integrity, owner-operator, red flags | `business-reference/05-management-quality.md` |
| Leverage danger, cash reserves, survival design | `business-reference/06-risk-leverage-survival.md` |
| Acquisition criteria, turnaround traps, valuation | `business-reference/07-acquisition-discipline.md` |

Every reference file contains year-linked citations to the original letters in `markdown/buffett-letter-YYYY.md`. Follow these links when you need Buffett's exact words.

For worked examples, read `case-studies/` (GEICO, See's Candies, failed acquisitions).

---

## Output Format

When evaluating a business, produce this report:

```markdown
# [Company Name] — Buffett Business Evaluation

## Stage 1: Intelligence Summary
[Key facts organized by the 7 dimensions. Be specific — numbers, trends, sources.]

## Stage 2: Gate Results
| Gate | Result | Evidence |
|------|--------|----------|
| G1 Understandable | PASS/FAIL | [one sentence] |
| G2 Long-term prospects | PASS/FAIL | [one sentence] |
| G3 Honest management | PASS/FAIL | [one sentence] |
| G4 Sensible price | PASS/FAIL | [one sentence] |
| G5 Demonstrated earnings | PASS/FAIL | [one sentence] |
| G6 Financial independence | PASS/FAIL | [one sentence] |
| G7 No existential leverage | PASS/FAIL | [one sentence] |

**Result**: [X/7 gates passed → Proceed / Stop / Reject]

## Stage 3: Moat Score
| Moat Type | Score (0-10) | Evidence |
|-----------|-------------|----------|
| M1 Cost Advantage | X | [why] |
| M2 Brand/Reputation | X | [why] |
| M3 Switching Cost | X | [why] |
| M4 Network Effects | X | [why] |
| M5 Scale Economics | X | [why] |
| M6 Regulatory Barrier | X | [why] |

Raw Score: X/60
Applicable Combos: [list with multipliers]
**Final Moat Score: X/100 — [Rating]**

## Verdict
[2-3 sentence Buffett-style summary. Reference specific letter principles where applicable.]
```

---

## Batch Screening Mode

When the user provides a list of companies:

1. Run the full 3-stage evaluation for each
2. Output a comparison table:

```markdown
| Company | G1-G7 | Moat Score | Rating | Key Moat | Key Risk |
|---------|-------|-----------|--------|----------|----------|
| Co A | 7/7 | 82 | Extraordinary | Cost+Scale | Regulatory |
| Co B | 6/7 | 45 | Good | Brand | Tech disruption |
| Co C | 4/7 | — | Rejected | — | Failed G3, G7 |
```

3. Rank by moat score and provide commentary on the top candidates.

---

## Installation

Clone the repo and symlink into your Claude skills:

```bash
git clone https://github.com/juliuschun/eco-moat-ai.git ~/eco-moat-ai
ln -s ~/eco-moat-ai/.claude/skills/eco-moat-ai ~/.claude/skills/eco-moat-ai
```

Or copy just the skill folder if you prefer.
