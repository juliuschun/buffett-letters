---
name: eco-moat-ai
description: |
  Evaluate any business like Warren Buffett using a 3-stage framework distilled from 49 years of shareholder letters.
  Supports three modes: quick (gates only), standard (full evaluation), deep (with original letter evidence).
  Use when: analyzing a company, evaluating a business idea, comparing investment opportunities,
  screening multiple companies, or when phrases like "is this a good business", "moat", "evaluate", "analyze" appear.
argument-hint: "[company name or business description]"
---

# eco-moat-ai: Buffett-Grade Business Analysis

**Purpose**: Evaluate any business through Warren Buffett's lens — 3-stage framework with 28 questions, 7 binary gates, and a 0-100 moat score. Every judgment backed by specific evidence from 49 years of shareholder letters.

**Source repo**: `~/eco-moat-ai/` (or wherever this repo is cloned)

---

## Modes

Detect the mode from the user's prompt, or ask if unclear.

| Mode | Trigger Phrases | What You Do | When to Use |
|------|----------------|-------------|-------------|
| **Quick** | "빠르게", "quick", "screen", "스크리닝", "간단히" | Stage 2 only (7 gates) | Screening 10+ companies fast |
| **Standard** | "평가해줘", "evaluate", "analyze" (default) | Full Stage 1-2-3 | Evaluating a single company |
| **Deep** | "깊이", "deep", "철저히", "원문까지" | Full Stage 1-2-3 + read reference files + cite original letters | Due diligence on a serious candidate |

---

## Quick Mode

Run only the 7 binary gates. Fast, decisive, no scoring.

1. For each gate, give a one-sentence PASS/FAIL with evidence
2. Output the gate table
3. Verdict: Proceed / Revisit / Reject

```markdown
# [Company] — Quick Screen

| Gate | Result | Evidence |
|------|--------|----------|
| G1 Understandable | PASS/FAIL | [one sentence] |
| G2 Long-term prospects | PASS/FAIL | [one sentence] |
| G3 Honest management | PASS/FAIL | [one sentence] |
| G4 Sensible price | PASS/FAIL | [one sentence] |
| G5 Demonstrated earnings | PASS/FAIL | [one sentence] |
| G6 Financial independence | PASS/FAIL | [one sentence] |
| G7 No existential leverage | PASS/FAIL | [one sentence] |

**Result**: X/7 -> [Proceed / Revisit / Reject]
```

---

## Standard Mode (Default)

Full 3-stage evaluation with moat scoring.

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
7/7 passed -> Proceed to Stage 3
6/7 passed -> STOP. Can the failing gate be resolved? Revisit in 6 months.
5/7 or below -> REJECT.
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
| C1 | Cost + Scale | x1.3 | Lower costs -> more customers -> even lower costs |
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

## Deep Mode

Everything in Standard Mode, plus:

1. **Read reference files** before evaluating. Map each dimension to its deep-dive:

| Checklist Section | Read This File |
|-------------------|---------------|
| 1.1 Industry & Arena | `business-reference/03-cost-advantage-and-scale.md` |
| 1.2 Competitive Position | `business-reference/01-competitive-moats.md`, `business-reference/02-pricing-power-and-brand.md` |
| 1.3 Financial Profile | `business-reference/04-capital-allocation.md` |
| 1.4 Management Quality | `business-reference/05-management-quality.md` |
| 1.5 Customer & Product | `business-reference/02-pricing-power-and-brand.md` |
| 1.6 Risk Landscape | `business-reference/06-risk-leverage-survival.md` |
| 1.7 Valuation & Context | `business-reference/07-acquisition-discipline.md` |

2. **Cite original letters** by reading `markdown/buffett-letter-YYYY.md` when a specific principle needs Buffett's exact words
3. **Compare to Buffett's actual cases** — reference GEICO, See's, or failed acquisitions from `case-studies/` where parallels exist
4. **Quote Buffett directly** at least 3 times in the report, with year and context

Deep Mode output adds these sections to the Standard report:

```markdown
## Buffett Parallels
[Which Berkshire company or case study is most similar? Why?]

## Key Letters Referenced
| Year | Relevant Principle | How It Applies |
|------|-------------------|----------------|
| [YYYY](markdown/buffett-letter-YYYY.md) | [principle] | [application to this company] |
```

---

## Output Format (Standard & Deep)

```markdown
# [Company Name] — Buffett Business Evaluation

**Mode**: Standard / Deep
**Date**: [evaluation date]

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

**Result**: [X/7 gates passed -> Proceed / Stop / Reject]

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

1. Run **Quick Mode** for all companies first
2. For those that pass 7/7, run **Standard Mode**
3. Output a comparison table:

```markdown
| Company | G1-G7 | Moat Score | Rating | Key Moat | Key Risk |
|---------|-------|-----------|--------|----------|----------|
| Co A | 7/7 | 82 | Extraordinary | Cost+Scale | Regulatory |
| Co B | 7/7 | 45 | Good | Brand | Tech disruption |
| Co C | 5/7 | -- | Rejected | -- | Failed G3, G7 |
```

4. Rank by moat score and provide commentary on top candidates.

---

## File Map

All paths are relative to the repo root (`~/eco-moat-ai/`).

| Purpose | Path |
|---------|------|
| Evaluation framework | `buffett-business-checklist.md` |
| Practical how-to guide | `buffett-field-guide.md` |
| Deep-dive evidence (7 files) | `business-reference/*.md` |
| Worked case studies | `case-studies/*.md` |
| Original letters (49 files) | `markdown/buffett-letter-YYYY.md` |
| Year-by-year lessons (49 files) | `lessons/lessons-YYYY.md` |
| Theme analyses (16 files) | `themes/*.md` |
| Wisdom synthesis | `buffett-business-wisdom-synthesis.md` |
| Quote collection | `buffett-quotations-collection.md` |
| Korean checklist | `ko/buffett-business-checklist.md` |
| Korean field guide | `ko/buffett-field-guide.md` |

---

## Installation

Clone the repo and symlink into your Claude skills:

```bash
git clone https://github.com/juliuschun/eco-moat-ai.git ~/eco-moat-ai
ln -s ~/eco-moat-ai/.claude/skills/eco-moat-ai ~/.claude/skills/eco-moat-ai
```

Or copy just the skill folder if you prefer.
