## Product-Market Fit (PMF) Evaluation (Lenny framing)

### Core idea

PMF is about whether the product creates enough value that users come back.

In this repo's recurring Lenny framing: PMF is often treated as a *single dominant metric* (retention), because if users don't return, you are not creating value.

### What to measure

- **Retention (primary PMF signal)**: pick a retention definition that matches your product's "repeat value cycle" (daily/weekly/monthly/cohort retention, or retained sessions/users after onboarding).
- **Time to value (supporting signal)**: how fast users reach the "aha" or must-have experience.
- **Expansion (secondary)**: for subscriptions/paid plans, track conversion and expansion rates, but only after you have evidence users retain.

### PMF evaluation workflow

1. **Define the "repeat" moment**
   - What is the unit of repeat value for your product? (Return to a workflow, complete a task cycle, use a key feature again.)
   - Translate "repeat value" into a retention definition you can compute.
2. **Run the PMF question**
   - Ask: "If users could no longer use this product, would they be very disappointed?"
   - Use responses to identify your "must-have users" and the experience that earns repeat usage.
3. **Validate with behavior**
   - Check whether cohorts who reach the must-have experience actually retain.
   - Compare retention across segments: new vs power users, channels, onboarding variations, etc.
4. **Avoid false positives**
   - High conversion with low retention is not PMF.
   - High activation with shallow retention is not PMF (activation can be "interesting," not "must-have").
5. **Decision outcomes**
   - If retention is weak: prioritize value creation, onboarding/activation, and core experience fixes.
   - If retention is strong: shift from "create value" to "grow value delivery" (North Star, scaling, loops, experimentation).

### PMF outputs to produce

- A single recommended retention metric definition (and cohort window).
- The must-have experience description (the specific "when/what" users do).
- A segmentation view: which segments show retention and why.
- Clear go/no-go guidance:
  - "We have PMF enough to scale X"
  - or "We do not yet have PMF; invest in Y"

---

## North Star Metric Framework (NSM) (Lenny framing)

### Core idea

The North Star Metric:
- Captures *units of value delivered* (often tied to product-market fit experience).
- Is usually **one, sometimes two**.
- Should be understandable and motivating.
- Should have a path from team actions to the NSM (teams need "direct impact," plus translation layers when needed).

### What makes a "good" North Star

- **Value-based**: reflects the product experience users care about.
- **Actionable**: the growth/product org can influence it (at least partially).
- **Common currency**: helps prioritize across teams.
- **Measurable**: not just "a story," but something you can track reliably.

### Translation layers (for multiple teams)

When many teams work on different components, each may optimize a local metric.

To keep focus:
- Use local metrics for day-to-day ownership.
- Convert local metrics into a single NSM via:
  - translation factors,
  - models, or
  - staged attribution logic.

This prevents "each team has its own KPI" from fragmenting prioritization.

### North Star workflow

1. **Pick the NSM**
   - Prefer NSM candidates that represent: activation-to-value -> retention (or another repeat value proxy).
2. **Name the value delivery engine**
   - Diagram how you grow the NSM:
     - onboarding / time to value,
     - activation,
     - engagement loop,
     - referral/network effects (if present),
     - reactivation/saves.
3. **Build the measurement model**
   - Define inputs (events), the conversion logic, cohort rules, and measurement caveats.
4. **Set team-level metrics**
   - For each team, define a metric they can influence.
   - Add a translation step so everything rolls up to NSM.
5. **Experiment with guardrails**
   - NSM experiments should avoid "improving vanity metrics" that don't move NSM.

### NSM outputs to produce

- One NSM definition (what it counts, for whom, and when).
- A "value delivery engine" diagram in words (activation/onboarding + loop + referral if any).
- Team local metrics + translation approach (high-level).

---

## User Retention Strategies (Lenny framing)

### Core idea

Retention is the ultimate evidence that the product creates value.

Common retention levers show up in Lenny's recurring themes:
- get users to the "aha" moment faster and more reliably,
- reduce friction at key transition points,
- ensure the product is used often enough to create compounding effects,
- design engagement loops and triggers that bring users back.

### The retention playbook

#### 1) Compress time to value (activation-to-retention bridge)

- Identify the shortest path to the must-have experience.
- Reduce steps, remove blockers, and improve onboarding reliability.

If new users fail onboarding once, they're at high risk of churning (onboarding is often a top leverage retention investment).

#### 2) Engineer "escape velocity" / first repeat value

Activation should be framed as:
- how quickly a user reaches meaningful repeat usage.

Examples of "first repeat value thresholds" that appear in Lenny-style conversations:
- reach "X in Y days" events (e.g., friends added),
- or "X orders in the first month,"
- or "the set of events in the first 30 days."

#### 3) Build engagement loops (so return becomes the default)

Retention typically improves when:
- a loop exists that repeatedly rewards the user for taking the next step,
- the product provides prompts or makes the next action obvious,
- and the loop reinforces the user's must-have context.

#### 4) Segment by who actually retains

Don't treat retention as one number:
- compare retention by onboarding path, acquisition channel, persona, feature usage, etc.

Then tailor:
- onboarding experiences,
- prompts/messages,
- and feature prioritization based on the segments that demonstrate retention.

#### 5) Reduce churn risk at moments of skepticism

Users are often most at risk:
- after they're intrigued enough to try,
- but before they experience the must-have moment.

So the funnel should focus on:
- reducing friction,
- matching expectations (messaging),
- and ensuring they hit the must-have experience quickly.

### Retention outputs to produce

- Your retention definition + cohort window.
- The must-have experience and the path to reach it.
- Top churn points in onboarding/activation (where users drop).
- A prioritized list of retention experiments tied to retention metric movement.

---

## Feature Prioritization Methods (Lenny framing)

### Core ideas

In Lenny-style product discussions, prioritization frameworks are most useful when:
- goals are clear,
- impact is defined relative to the goal one level down,
- and uncertainty is handled honestly (without premature de-prioritization).

### Framework menu

#### A) RICE (Reach, Impact, Confidence, Effort)

How to apply it in Lenny's "anti-trap" way:
- RICE is directional and robust, but **confidence and effort can hide high-reach/high-impact bets** early.

Recommended process:
1. **Stage 1 (Idea triage):** score Reach and Impact; temporarily de-emphasize Confidence/Effort.
2. **Stage 2 (Fair shot):** for high Reach/Impact candidates, run a short "design + engineering attempt" to learn confidence/effort.
3. **Stage 3 (Finalize):** add Confidence/Effort back in and re-rank.

Output goal:
- a balanced portfolio:
  - innovative bets,
  - incremental improvements,
  - and necessary debt/maintenance work.

#### B) ICE (Impact, Confidence, Ease)

Use ICE when:
- speed matters,
- you need a simple comparative tool for a queue of experiments or feature ideas.

Key rule:
- impact should map to progress toward a goal (and should be one level removed from top KPIs).

ICE should support a high-velocity testing program:
- you need a systematic idea intake,
- and you need to be able to explain decisions back to the organization.

#### C) Shape Up / "Appetite over estimates"

Use when:
- you want to stop false planning certainty,
- you can enforce complete "in an appetite window" scope.

Recipe:
- pick a realistic appetite/timebox,
- force scope to something complete inside that window,
- then "what changes if we had less/more time" to explore the efficient frontier.

#### D) MoSCoW (Must/Should/Could/Won't)

Use when:
- you need stakeholder alignment quickly,
- scope decisions are driven by requirements categories.

MoSCoW is especially useful once you have:
- candidate requirements,
- and you need clear trade-offs about what won't ship.

### Feature prioritization workflow for this skill

1. **Define goal and the "impact target"**
   - Identify which goal (NSM or local metric) the feature influences.
2. **Pick the framework based on situation**
   - RICE for portfolio + reach-heavy bets.
   - ICE for speed and comparative triage.
   - Shape Up for scope discipline.
   - MoSCoW for requirement alignment.
3. **Decide the scoring rules**
   - Explicitly state how you treat uncertainty (especially Confidence/Effort).
4. **Portfolio balance check**
   - Ensure you're not only picking incremental or only speculative.
5. **Instrumentation plan**
   - Define events/metrics to measure impact on the north star or relevant retention/activation signals.

---

## Growth Loops (Lenny framing)

### Core idea

Growth loops work best when they're aligned with:
- product network effects (if present),
- and user behaviors that create word-of-mouth or sharing.

In Lenny-style conversations, a recurring emphasis is:
- product network effects are usually present from inception and are hard to manufacture later.
- if inherent network effects exist (or the product is beloved), then layering referrals/virality can compound.

### Growth loop types to check

#### 1) Inherent product network effects -> referral/viral loops

Decision questions:
- Does user utility increase as more relevant users join?
- Is the product inherently collaborative / multi-user / marketplace-like?

If yes:
- prioritize referral mechanics and incentives that make sharing natural.

#### 2) Frequency-based word-of-mouth

Word-of-mouth tends to work when:
- users have high frequency of use,
- and they reach a moment where sharing becomes natural.

So loop design should align with usage cadence.

#### 3) Content/SEO as a compounding loop

Decision questions:
- Is there a long-tail of search demand?
- Do users generate templates/content that naturally ranks?

SEO is often a slower return horizon; it can still be the winning loop if it compounds and is defensible.

#### 4) Black loop / blue loop (Coda-style viral spread)

Example loop structure:
- **Black loop**: a user creates something and shares it with a group -> subset creates new artifacts -> repeat.
- **Blue loop**: a user publishes to the world (public gallery/URL) -> broader distribution -> repeat.

This is a useful mental model:
- "does the product spread within teams (black) or to the public ecosystem (blue)?"

### Growth loop workflow

1. **Find the compounding mechanism**
   - network effects,
   - sharing/referral,
   - content generation,
   - or audience capture (SEO, communities).
2. **Identify loop participants**
   - who creates,
   - who shares,
   - who adopts.
3. **Measure the loop**
   - virality coefficient / referral conversions,
   - time-to-next-user exposure,
   - and retention of loop-generated cohorts.
4. **Stress test assumptions**
   - will users share without heavy prompting?
   - does sharing bring the right users (who actually retain)?

### Growth loop outputs to produce

- Loop diagram in words (creator -> share -> exposure -> adoption -> repeat).
- Metrics for loop health (activation, retention of referred cohorts, share rates).
- Prioritized loop experiments tied to retention/NSM.

---

## Activation Funnels (Lenny framing)

### Core idea

Activation is not "did they sign up?"

Activation is the point where users experience enough value to become likely retained users.

Lenny-style emphasis:
- the must-have moment (or aha moment) often occurs before users churn risk spikes down the funnel.
- you should intentionally pick an experience-based activation definition.

### Activation definition workflow

1. **Pick the must-have experience threshold**
   - Choose an experience-based "tastable value" event or set of events.
2. **Align activation with retention**
   - Prefer definitions that correlate with retention, but are operationally actionable.
3. **Choose an activation "escape velocity" threshold**
   - define "X achieved in Y time" where X = meaningful product actions.

### Funnel levers: desire and friction

Common Lenny/Growth-leader levers:
- Increase the right desire (messaging/targeting)
- Reduce friction to reach the aha moment (onboarding, guidance, prompts)

If friction is too high, users never experience the must-have value and must be reacquired.

### Activation funnel instrumentation

Define your funnel as:
- acquisition/landing -> onboarding -> activation (aha threshold) -> retention outcome.

For each step:
- define events,
- define drop-off points,
- and decide the highest-leverage interventions.

### Activation "high risk" moment guidance

Until users reach the must-have experience:
- they are skeptical and at high risk of disappearing.

So the product should:
- guide users to the must-have moment faster,
- collapse time to value,
- and use the right prompts.

### Activation outputs to produce

- Activation definition (events + time window).
- A funnel table: step, metric, and expected impact on retention/NSM.
- Top onboarding or product blockers to remove (highest drop-off points).
- A set of activation experiments (with success criteria).

