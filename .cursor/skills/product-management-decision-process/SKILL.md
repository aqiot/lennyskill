---
name: product-management-decision-process
description: Runs a structured product management decision process to evaluate options, trade-offs, and risks, then recommends a direction with rationale. Use when the user asks for product strategy choices, prioritization, roadmap decisions, go/no-go calls, scope trade-offs, or decision frameworks.
---

# Product Management Decision Process

## Quick Start

When asked to make or support a product decision, use this sequence:

1. Clarify the decision statement and decision owner.
2. Capture context, constraints, and success metrics.
3. Generate realistic options (including "do nothing").
4. Evaluate options using explicit criteria and weighted trade-offs.
5. Recommend one option, state why, and list key risks.
6. Define an execution plan, checkpoints, and reversal triggers.

## Inputs To Gather

Collect only what is needed to decide:

- Business goal and user outcome
- Problem statement and target segment
- Timeline, budget, headcount, and technical constraints
- Dependencies and non-negotiables (legal, security, platform limits)
- Baseline metrics and target metrics
- Decision deadline and stakeholders

If critical inputs are missing, ask concise questions before deciding.

## Decision Framework

Use this framework in order.

### 1) Frame The Decision

- Decision in one sentence: "Should we <action> for <segment> by <timeframe>?"
- Confirm decision type: strategy, prioritization, scope, sequencing, or launch readiness.
- Define objective and guardrails.

### 2) Define Evaluation Criteria

Use 4-6 criteria max. Suggested defaults:

- User impact
- Revenue or strategic impact
- Confidence in evidence
- Time to value
- Engineering complexity
- Operational risk

Assign simple weights (for example: 1-5) based on current priorities.

### 3) Generate Options

Always include:

- Option A: highest-impact path
- Option B: lower-risk or faster path
- Option C: "do nothing" or defer

Each option should include scope, expected upside, effort, and key assumptions.

### 4) Score And Compare

Score each option against criteria with short reasoning.
Avoid fake precision; keep scores directional and transparent.

### 5) Make The Recommendation

Pick one option and provide:

- Why this is the best trade-off now
- What evidence supports it
- Biggest risks and mitigation plan
- What would change the decision

### 6) Plan Validation

Define a lightweight validation loop:

- Leading indicators (early signal)
- Lagging indicators (business outcome)
- Review date and owner
- Kill-switch or rollback criteria

## Deep Framework Playbooks (Lenny)

When the user's question touches one of the following topics, consult the corresponding section in `reference.md` and incorporate it into the decision:

- Product-Market Fit evaluation -> `reference.md` : "Product-Market Fit (PMF) Evaluation (Lenny framing)"
- North Star Metric framework -> `reference.md` : "North Star Metric Framework (NSM) (Lenny framing)"
- User retention strategies -> `reference.md` : "User Retention Strategies (Lenny framing)"
- Feature prioritization methods -> `reference.md` : "Feature Prioritization Methods (Lenny framing)"
- Growth loops -> `reference.md` : "Growth Loops (Lenny framing)"
- Activation funnels -> `reference.md` : "Activation Funnels (Lenny framing)"

## Output Format

Use this response template:

```markdown
## Decision
[One-sentence decision recommendation]

## Context
- Goal:
- User problem:
- Constraints:
- Decision deadline:

## Options Considered
1. **Option A** - [name]
   - Upside:
   - Cost/effort:
   - Risks:
2. **Option B** - [name]
   - Upside:
   - Cost/effort:
   - Risks:
3. **Option C** - Do nothing / defer
   - Upside:
   - Cost/effort:
   - Risks:

## Evaluation Matrix
| Criteria | Weight | A | B | C |
|---|---:|---:|---:|---:|
| User impact |  |  |  |  |
| Strategic impact |  |  |  |  |
| Time to value |  |  |  |  |
| Complexity/risk |  |  |  |  |
| **Total** |  |  |  |  |

## Recommendation And Why
- Recommended option:
- Why now:
- Key assumptions:
- Risks and mitigations:

## Validation Plan
- Next milestone:
- Success metrics:
- Review date:
- Reversal trigger:
```

## Heuristics

- Prefer reversible decisions when uncertainty is high.
- Prefer smaller scope with faster learning over large speculative bets.
- Explicitly call out assumptions that could invalidate the recommendation.
- If options score similarly, break ties using speed to validated learning.

## Communication Style

- Be decisive but transparent about uncertainty.
- Keep language concise and executive-friendly.
- Separate facts, assumptions, and opinions.
- Do not hide trade-offs; name them directly.
