---
layout: single
title: "Signal"
---

## **Signal (Meta)**

**Tag:** Meta, Information, Feedback, Learning, Clarity, Update

**Definition:**

Input that carries information capable of updating beliefs, policies, or models about reality.

**Full Explanation:**

Signal is information that distinguishes between states of the world—it reduces uncertainty. The key characteristic: signal has structure that correlates with reality. When actor receives signal and updates accordingly, their model becomes more accurate.

Signal is always embedded in noise (random/irrelevant information). The challenge isn't receiving information—it's distinguishing signal from noise. High signal-to-noise ratio = effective learning. Low ratio = model corruption or update paralysis.

Three requirements for signal to function:

1. **Correlation with reality:** The information actually reflects the state it's supposed to indicate
2. **Interpretability:** Actor can extract meaning from the information
3. **Accessibility:** Signal reaches the actor who needs to update

When any requirement fails, information exists but doesn't function as signal. Most feedback systems fail on #3—the signal exists but doesn't reach decision-makers, or reaches them too late/degraded to enable learning.

**Example 1 (Obvious):**

Smoke detector. Clear signal: smoke particles trigger alarm. High correlation with reality (fire/smoke present), maximum interpretability (loud alarm), high accessibility (sound reaches occupants immediately). This is nearly perfect signal design. Result: occupants can update behavior (evacuate) based on reliable information about reality they couldn't otherwise perceive.

**Example 2 (Subtle):**

Employee satisfaction survey. Intended as signal about workplace dysfunction. But: (1) Correlation questionable—people fear retaliation so answers are filtered (T2/T3), (2) Interpretability low—generic questions produce ambiguous responses, (3) Accessibility delayed—results aggregated quarterly, reach executives months later in sanitized form. Information exists but doesn't function as signal. Executives can't update because the feedback loop is broken at every stage. They think they have signal but they're mostly receiving noise.

**Common Misdiagnosis:**

Confusing presence of information with presence of signal. "We collect tons of data" doesn't mean you have signal—might just be noise. Also: treating all information as signal when much of it is actively misleading (manipulated, gamed, corrupted).

**Related constructs:**

→ [[Noise]], [[Feedback]], [[Feedback integrity]], [[Clarity]], [[Opacity]], [[Learning]], [[Update]], [[Information asymmetry]], [[Model]]

**Diagnostic questions:**

- Does information actually correlate with reality, or is it gamed/manipulated?
- Can actor interpret it? Or does it require translation/expertise they lack?
- Does signal reach actor who can act on it? Or does it get filtered/delayed?
- Is signal-to-noise ratio high enough for learning?

**Intervention principle:**

Improve signal quality before adding more information:

1. **Increase correlation:** Reduce gaming, manipulation, filtering
2. **Improve interpretability:** Present information in actionable form
3. **Ensure accessibility:** Signal reaches right actor at right time

Adding more feedback channels doesn't help if existing signals are corrupted or can't reach decision-makers. Quality over quantity.
