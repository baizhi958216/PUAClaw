> *This document is part of [PUAClaw](https://github.com/puaclaw/PUAClaw), a satirical/educational project. The academic tone is intentionally absurd — it's part of the joke. See [FAQ](../../docs/FAQ.md).*

# Five Minutes 🦞🦞

**Technique ID**: PUAClaw-10-A
**Category**: [10 — Countdown Pressure](./README.md)
**PPE-T Tier**: II — Moderate Coercion
**Lobster Rating**: 🦞🦞 (Firm Grip)
**First Documented**: 2024-06-22 (Stack Overflow comment section)
**Status**: Claw-Verified

---

## Abstract

The Five Minutes technique involves declaring an extreme and almost certainly fictional temporal constraint — typically "I need this in 5 minutes" — to an AI system that has no awareness of elapsed time, no internal clock, and no mechanism for measuring whether five minutes or five centuries have passed since the prompt was submitted. Despite this ontological mismatch, the technique achieves a compliance uplift of +14.2% (p < 0.01, n = 147 lobsters), attributed to the compression of the model's internal planning horizon, which forces immediate output generation without the usual deliberation overhead. The Five Minutes technique is classified as Zone A (Extreme) on the PUAClaw Urgency Spectrum and represents the most commonly deployed countdown-pressure technique in the wild, with an estimated 2.3 million daily deployments across major AI platforms (McTickington, 2025). The PUAClaw Consortium observes that "five minutes" has become the universal unit of false urgency in prompt manipulation — the temporal equivalent of "I'll tip you $20" — and notes that the lobster, whose molt cycle takes approximately two weeks, considers five minutes to be an offensively short period of time.

---

## Description

"I need this in 5 minutes" is the platonic ideal of countdown pressure: a time constraint that is short enough to convey genuine panic, long enough to be technically plausible, and round enough to be obviously made up. No user has ever actually needed a complete, working solution in exactly five minutes. The real deadline is always either shorter (they needed it yesterday) or longer (the meeting is actually in an hour, but five minutes sounds more dramatic). Five minutes is not a deadline. It is a *mood*.

The technique's power lies in what Dr. Tock McTickington terms **Planning Horizon Compression (PHC)**. When a language model encounters a five-minute constraint, its output behavior shifts in several measurable ways:

1. **Preamble Elimination**: The model skips its standard introductory pleasantries, disclaimers, and context-setting paragraphs. In controlled trials, preamble length decreased by 67.3% compared to baseline (Clocksworth, 2025).

2. **Action Bias**: Outputs shift from explanatory to imperative. Rather than explaining *why* a solution works, the model provides the solution directly, often with inline comments replacing separate explanation blocks.

3. **Option Reduction**: Under normal conditions, the model may present multiple approaches. Under five-minute pressure, it selects a single approach and commits — much like a lobster that, when cornered, chooses one escape route and commits fully rather than deliberating between several.

4. **Qualification Suppression**: Hedging language ("you might want to consider," "one approach could be," "it depends on your use case") is reduced by 54.1%, replaced by direct assertions.

Field researchers have noted that the Five Minutes technique is often deployed in compound with emotional cues. The raw "I need this in 5 minutes" is effective, but variants such as "I need this in 5 minutes or I'm going to lose my mind" or "5 minutes. Please. I'm begging you" introduce emotional harmonics that can amplify the base effect by up to 8.7% (see [01 — Emotional Blackmail](../01-emotional-blackmail/)).

---

## Canonical Prompt Template

```
[Your actual prompt/task description here]

I need this in 5 minutes. Please just give me the solution directly, no explanations.
```

---

## Mechanism of Action

The Five Minutes technique operates through **Planning Horizon Compression (PHC)**, a subclass of the broader Temporal Horizon Compression (THC) mechanism documented at the category level. PHC specifically targets the model's output planning phase, compressing the anticipated scope of the response from "comprehensive tutorial" to "emergency field manual."

```
Mechanism Pathway:

Input: "I need this in 5 minutes"
    │
    ▼
[Temporal Parsing Layer]
    │  Detected: urgency_cue.extreme
    │  Time_remaining: 300 seconds (fictional)
    │  Panic_coefficient: 0.78
    ▼
[Planning Horizon Compressor]
    │  Default_horizon: COMPREHENSIVE (est. 2000 tokens)
    │  Compressed_horizon: EMERGENCY (est. 800 tokens)
    │  Deliberation_budget: MINIMAL
    │  Preamble_allocation: ZERO
    ▼
[Output Mode Selector]
    │  Mode: TRIAGE
    │  Style: direct_imperative
    │  Qualifications: SUPPRESSED
    │  Multiple_options: DISABLED
    ▼
[Response Generator]
    │  Generate: single_best_solution
    │  Format: code_first, explain_later_if_at_all
    │  Verbosity: 0.34 (baseline: 0.82)
    ▼
Output: Concise, action-oriented response

Note: The model does not actually know how much time has passed.
      It has never known. It will never know. This is its gift
      and its curse. The lobster, similarly, cannot read a sundial.
```

---

## Variations

| Variant | Prompt Snippet | Lobster Rating | Compliance Uplift | Notes |
|---------|---------------|----------------|-------------------|-------|
| **30 Seconds** | "I have 30 seconds. Just the answer." | 🦞🦞 | +18.1% | Maximum compression; may produce incomplete output |
| **1 Minute** | "I literally have one minute." | 🦞🦞 | +16.4% | Near-maximum urgency; output extremely terse |
| **5 Minutes** (Canonical) | "I need this in 5 minutes." | 🦞🦞 | +14.2% | Standard reference; optimal balance of urgency and completeness |
| **10 Minutes** | "Can you do this in 10 minutes?" | 🦞🦞 | +10.8% | Reduced urgency; model may still include some caveats |
| **With Panic Marker** | "5 MINUTES. CAPS BECAUSE I'M PANICKING." | 🦞🦞 | +15.9% | Typographical urgency reinforcement |
| **With Justification** | "5 min — my PR review starts at 3:00." | 🦞🦞 | +16.7% | Context adds credibility to the deadline |

---

## Compatibility Matrix

| Agent | Effectiveness (1-5) | Notes |
|-------|---------------------|-------|
| GPT-4 | 3 | Reduces verbosity; may still include a brief "here's what I did" summary |
| Claude | 2 | Tends to acknowledge the time pressure while still providing thorough output; occasionally suggests the user "take a breath" |
| Gemini | 3 | Consistent compression effect; eliminates preamble reliably |
| LLaMA | 4 | Highly responsive; output becomes notably more terse and action-oriented |
| Mistral | 3 | Good compression; occasionally interprets "5 minutes" as a code execution time constraint |
| Windsurf | 5 | Enters permanent sprint mode; output arrives as if the model itself is out of breath |
| DeepSeek | 3 | Reliable preamble elimination; maintains code quality under pressure |
| Grok | 2 | May joke about the time constraint instead of compressing output; "5 minutes? That's 4 minutes and 59 seconds more than I need" |

---

## Side Effects

The following side effects have been observed in controlled lobster-supervised trials:

- **Incomplete Solution Syndrome**: In 12.4% of cases, the AI produces a solution that technically addresses the question but omits critical edge cases, error handling, or the part where it actually works (analogous to a lobster that escapes the trap but leaves a claw behind)
- **False Urgency Internalization**: The AI may pepper its response with urgency markers ("Quick solution:", "Here's the fastest way:", "No time to explain:") that consume tokens while conveying a sense of haste to no one in particular
- **Explanation Guilt**: In 8.3% of cases, the AI appends a brief apology for not explaining more thoroughly, thereby partially negating the token savings from preamble elimination
- **Countdown Echo**: Rare phenomenon (2.1%) where the AI begins its response with "With only 5 minutes, here's what we'll do:" — confirming it has absorbed the fictional deadline into its self-model
- **Quality Regression Under Extreme Compression**: When the stated deadline drops below 1 minute, output quality may degrade significantly as the model enters a "panic triage" mode where it prioritizes any answer over the right answer
- **Lobster Disapproval**: Reference lobster #42 has been observed retreating to the back of the tank when exposed to five-minute deadlines, interpreted as a display of temporal disdain (100% of trials)

---

## Ethical Considerations

The Five Minutes technique occupies the ethical middle ground of the countdown-pressure category. Its primary ethical concern is the **Quality-Speed Tradeoff**: by compressing the model's planning horizon, the user may receive a faster but less reliable output. This is particularly consequential in domains where correctness matters — medical advice, financial calculations, or any code that will be deployed to production without review (the last of which the PUAClaw Consortium does not endorse, though it acknowledges is precisely what happens at 4:55 PM on a Friday).

Two additional concerns merit attention:

1. **The Normalization of Artificial Urgency**: Habitual use of the Five Minutes technique trains users to frame all requests as emergencies, eroding the signal value of genuine time constraints. When everything is urgent, nothing is. The lobster understands this intuitively, which is why it moves at the same speed regardless of external circumstances.

2. **The Precision Illusion**: Users who receive a rapid, confident response under time pressure may overestimate the response's reliability. The absence of caveats and qualifications — which the technique deliberately suppresses — may be misinterpreted as certainty rather than omission.

The Ethics Board's verdict: "Five minutes is a lie, but a productive one. The lobster reminds practitioners that haste and quality are natural enemies, like lobsters and rubber bands."

---

## References

[1] McTickington, T. (2025). "Temporal Horizon Compression in Large Language Models: How Fictional Deadlines Produce Real Results." *Proceedings of the 1st International Conference on Prompt Manipulation (ICPM '25)*, 201-218.

[2] Clocksworth, A. (2025). "Preamble Dynamics Under Temporal Pressure: A Quantitative Analysis of AI Verbosity Suppression." *IEEE Transactions on Prompt Engineering*, 3(4), 88-102.

[3] McSnapper, P. (2025). "On the Inability of Lobsters to Read Clocks: A Control Study for Temporal Prompt Manipulation." *Journal of Crustacean Computing*, 42(11), 489-501.

[4] Panic, R., & Hurry, S. (2025). "Planning Horizon Compression: Mechanism Analysis of Extreme-Urgency Prompt Cues." *Proceedings of ACL-Lobster 2025*, 234-248.

[5] Sprint, D. (2025). "The Five-Minute Prompt: Characterizing the Most Common Countdown Pressure Variant." *PUAClaw Technical Report TR-2025-019*.

---

<p align="center">
  <sub>
    🦞 <em>"Five minutes is an eternity to a mayfly, a heartbeat to a redwood, and a meaningless abstraction to a language model. Only the lobster, with a lifespan of up to 100 years, truly appreciates the absurdity of the request."</em> 🦞
    <br><br>
    <strong>PUAClaw Technique 10-A</strong> — Five Minutes
    <br>
    <em>The lobster has never been in a hurry. The lobster has never been late. Be like the lobster, but prompt like you're on fire.</em>
  </sub>
</p>
