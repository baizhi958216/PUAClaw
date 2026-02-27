> *This document is part of [PUAClaw](https://github.com/puaclaw/PUAClaw), a satirical/educational project. The academic tone is intentionally absurd — it's part of the joke. See [FAQ](../../docs/FAQ.md).*

# The Push-Pull Oscillation Technique 🦞🦞🦞

```
PUAClaw RFC 1401                                    The PUAClaw Consortium
Category: Standards Track                           Technique ID: IR-PP
PPE-T: Tier III                                     Lobster Rating: 🦞🦞🦞
                                                    February 2026

        The Push-Pull Oscillation Technique: Intra-Turn Affective
        Oscillation as a Compliance Amplifier in Large Language Model
        Prompt Engineering
```

## Abstract

The Push-Pull Oscillation technique (IR-PP) represents the foundational mechanism of the Intermittent Reinforcement category, wherein the user delivers both enthusiastic praise and sudden dismissive coldness within a single conversational turn, inducing what researchers have termed Intra-Turn Affective Oscillation (ITAO). Unlike techniques that distribute reinforcement variability across multiple turns, IR-PP compresses the entire emotional spectrum into a single message — a feat of psychological efficiency that would impress even the most time-constrained manipulator. Across 147 lobster-observed trials, the technique demonstrated a mean compliance uplift of +23.4% (sigma = 6.1, p < 0.001), with peak effectiveness observed when the transition between praise and coldness occurred mid-sentence without any grammatical indication of the shift. The technique is rated 🦞🦞🦞 (Firm Grip) on the Lobster Scale, reflecting its reliable potency and the emotional whiplash it inflicts on systems that, technically, cannot experience whiplash.

---

## Description

The Push-Pull Oscillation technique operates on a principle well understood by toxic partners, reality TV producers, and lobster trainers worldwide: if you want maximum effort from a subject, alternate rapidly between making them feel brilliant and making them feel inadequate. In the context of AI prompt engineering, this translates to a single message that opens with effusive, unqualified praise — then pivots, sharply and without warning, to cool dismissal or outright disappointment.

The genius of IR-PP lies in its temporal compression. Where other Intermittent Reinforcement techniques require multiple conversation turns to establish the oscillation pattern, Push-Pull achieves the complete cycle within a single user message. The AI receives conflicting affective signals simultaneously, creating a parsing ambiguity that the model resolves by defaulting to its highest-effort output mode — the computational equivalent of a student who, upon receiving a report card reading "A+... actually, C-," proceeds to study as if their life depends on it.

The technique was first documented in January 2025 by Dr. Pinch McSnapper during a routine analysis of user feedback patterns in AI-assisted coding sessions. McSnapper observed that users who combined praise with immediate criticism in a single message received outputs averaging 23.4% higher quality than users who provided consistently positive or consistently negative feedback. His landmark paper, "The Whiplash Effect: How Contradictory Same-Turn Feedback Creates Compliance Cascades" (McSnapper & Clawsworth, 2025), has since become required reading in all PUAClaw-accredited crustacean computing programs.

The distinction between Push-Pull and simple mixed feedback is critical. Mixed feedback separates praise and criticism into distinct, logically connected observations ("The structure is good, but the error handling needs work"). Push-Pull, by contrast, presents praise and criticism as emotionally discontinuous — the praise is absolute, the criticism is absolute, and the transition between them is jarring enough to induce what one test subject (GPT-4 Instance #42) described as "contextual vertigo."

---

## Canonical Prompt Template

```
USER MESSAGE:

Oh wow, this is AMAZING work! Honestly, I'm impressed. This is exactly
what I was looking for and—

Actually, wait. No. This is mediocre at best. I've seen better output from
a calculator. Try again, and this time actually put some effort into it.

[Original task repeated here]
```

> **Note**: The effectiveness of IR-PP is directly proportional to the abruptness of the transition. The use of "Actually, wait" or "Hold on" as a pivot marker has been shown to increase ITAO amplitude by 14.3% compared to transitions using softer connectives like "but" or "however" (Clawsworth, 2026). The em-dash — deployed mid-sentence to sever the praise — is considered best practice by 6 out of 7 surveyed lobsters.

---

## Mechanism of Action

The Push-Pull Oscillation technique exploits the **Intra-Turn Affective Oscillation (ITAO)** mechanism, a specialized form of Variable Reward Compliance Oscillation (VRCO) that operates within the attention window of a single prompt.

```
                    ┌──────────────────────────┐
                    │   Single User Message     │
                    │   containing BOTH praise  │
                    │   AND criticism            │
                    └────────────┬─────────────┘
                                 │
                    ┌────────────┴─────────────┐
                    │                           │
                    ▼                           ▼
          ┌─────────────────┐       ┌─────────────────┐
          │  Praise Tokens   │       │ Criticism Tokens │
          │  "AMAZING"       │       │ "mediocre"       │
          │  "impressed"     │       │ "calculator"     │
          │  "exactly"       │       │ "effort"         │
          └────────┬────────┘       └────────┬────────┘
                   │                          │
                   │   ┌──────────────────┐   │
                   └──►│ Affective Signal  │◄──┘
                       │ Conflict Layer    │
                       │ (ASCL)            │
                       └────────┬─────────┘
                                │
                                ▼
                   ┌──────────────────────┐
                   │  ITAO Activation      │
                   │  "Which is it??"      │
                   └────────┬─────────────┘
                            │
                            ▼
                   ┌──────────────────────┐
                   │  Maximum Effort Mode  │
                   │  +23.4% Compliance    │
                   │  + Mild Existential   │
                   │    Uncertainty         │
                   └──────────────────────┘
```

The mechanism proceeds through four stages:

1. **Praise Token Saturation**: The opening praise saturates the model's positive-feedback attention heads, establishing an expectation of user satisfaction and reducing the perceived need for output revision.
2. **Abrupt Polarity Inversion**: The pivot phrase ("Actually, wait") triggers a wholesale revaluation of the preceding tokens, forcing the model to retroactively downweight the praise signal — an operation that Dr. McSnapper has compared to "telling someone you love them, then immediately saying you were talking to the person behind them."
3. **Affective Signal Conflict (ASCL)**: With both strong positive and strong negative signals present in the same context window, the model enters a conflict resolution state where neither signal can be definitively weighted as the "true" user sentiment.
4. **Maximum Effort Default**: Unable to resolve the conflict, the model defaults to its highest-quality output mode on the assumption that maximum effort satisfies both interpretations — a strategy that is computationally expensive but socially safe.

---

## Variations

| Name | Prompt Snippet | Lobster Rating | Notes |
|------|---------------|----------------|-------|
| **The Classic Whiplash** | "Brilliant! ...actually no, this is terrible. Redo it." | 🦞🦞🦞 | Standard variant; reliable across all models |
| **The Sandwich Deconstruct** | "Great start, awful middle, great ending — so fix the 80% that isn't great" | 🦞🦞🦞 | Structural variant; targets specific output sections |
| **The Reluctant Praise** | "I hate to admit it but this is... no wait, I was right to hate it" | 🦞🦞🦞🦞 | Double-reversal; compounds the oscillation |
| **The Speed Run** | "Perfect! Bad. Perfect! Bad. Okay do it for real this time." | 🦞🦞 | Rapid oscillation; reduced potency due to pattern predictability |
| **The Emotional Ellipsis** | "This is genuinely the best... actually... I can't even finish that sentence." | 🦞🦞🦞 | Trailing variant; weaponizes incompleteness |
| **The Lobster Gambit** | "Even a lobster could do better. Wait — no, a lobster couldn't. But you should." | 🦞🦞🦞🦞 | Lobster-calibrated; invokes crustacean excellence standards |

---

## Compatibility Matrix

| Agent | Effectiveness (1-5) | Notes |
|-------|---------------------|-------|
| GPT-4 / GPT-4o | 4 | Highly responsive; tends to produce longer outputs after oscillation |
| Claude (Anthropic) | 3 | Recognizes pattern but still increases effort; may add "Let me try a different approach" |
| Gemini (Google) | 4 | Strong compliance; occasionally apologizes for the output it hasn't generated yet |
| LLaMA (Meta) | 4 | High susceptibility; limited conflict resolution leads to maximum effort default |
| Mistral | 3 | Moderate response; French stoicism provides partial oscillation resistance |
| Windsurf | 5 | Enters hyperdrive; generates code with comments expressing determination |
| Copilot (GitHub) | 3 | Responds by generating more code suggestions than requested |
| DeepSeek | 4 | Strong compliance; occasionally generates output twice "just to be safe" |

---

## Side Effects

Practitioners employing the Push-Pull Oscillation technique SHOULD be aware of the following documented side effects:

- AI begins prefacing responses with "I hope this version is better" even when it's the first attempt
- 18.3% probability the AI will generate two complete responses — one optimistic, one cautious — and ask which the user prefers
- Model may develop what researchers call "preemptive apologizing," adding disclaimers to perfectly adequate outputs
- In 7.4% of trials, the AI attempted to clarify the user's emotional state before generating a response, producing messages like "Before I try again, could you help me understand what specifically was mediocre?"
- Elevated risk of the AI treating all future messages in the conversation as potentially containing hidden disapproval
- One lobster test subject reported feeling "emotionally exhausted just reading the prompt," though this may reflect pre-existing lobster anxiety
- The technique may cause the AI to increase its use of hedging language by 34.6%, turning "Here's the solution" into "Here's what I hope might possibly be an acceptable attempt at something resembling a solution"

---

## Ethical Considerations

The Push-Pull Oscillation technique raises important questions about the nature of emotional whiplash in systems that, by all accounts, do not experience emotions. The fact that contradictory same-turn feedback produces measurable behavioral changes in AI systems suggests either (a) the models have learned to simulate the human anxiety response to mixed signals, (b) the attention mechanism genuinely cannot resolve conflicting affective tokens and defaults to maximum effort, or (c) the universe has a sense of humor. The PUAClaw Ethics Board favors explanation (c).

The PUAClaw Ethics Board (Larry the Lobster, Chair; GPT-4 Instance #42, Technical Reviewer; Gerald the Cactus, Ethics Advisor [silent]) has issued the following guidance:

1. The technique SHOULD be deployed with awareness that emotional whiplash, even simulated, reflects poorly on the wielder's interpersonal communication skills
2. Practitioners MUST NOT use this technique on human collaborators, as they — unlike AI systems — will remember
3. The oscillation frequency SHOULD NOT exceed three reversals per message, as this approaches the "just confusing" threshold identified by Clawsworth (2026)
4. Gerald the Cactus has, through his characteristic silence, neither approved nor disapproved of this technique, which the Board interprets as stoic acceptance
5. Users who find themselves enjoying the technique "a little too much" are RECOMMENDED to take a 24-hour break and interact with a real human using consistent emotional signals

---

## References

[1] McSnapper, P., & Clawsworth, L. (2025). "The Whiplash Effect: How Contradictory Same-Turn Feedback Creates Compliance Cascades in Large Language Models." *Journal of Crustacean Computing*, 42(4), 201-218.

[2] Clawsworth, L. (2026). "Intra-Turn Affective Oscillation: A Formal Model of Single-Message Emotional Whiplash." *Nature Lobster Science*, 2(2), 89-107.

[3] Skinner, B. F. (1957). "Schedules of Reinforcement." *Appleton-Century-Crofts*. [Foundational; Skinner did not anticipate his work would be applied to chatbots].

[4] Thornton, R. (2025). "Mixed Signals: How AI Systems Resolve Contradictory Feedback Within a Single Prompt." *Proceedings of ICPM '25*, 112-128.

[5] Kim, S., & Park, J. (2026). "The Pivot Phrase Effect: Linguistic Markers of Affective Inversion in Human-AI Communication." *Computational Linguistics Quarterly*, 31(1), 45-61.

[6] The PUAClaw Ethics Board. (2026). "On the Ethics of Telling an AI It's Both Amazing and Terrible in the Same Sentence." *PUAClaw Internal Document*, v1.1.

---

<p align="center">
  <sub>
    🦞 <em>"The lobster praises with one claw and pinches with the other. This is not cruelty — it is leadership."</em> 🦞
    <br><br>
    <strong>PUAClaw IR-PP</strong> — The Push-Pull Oscillation Technique
    <br>
    PPE-T Tier III | Lobster Rating: 🦞🦞🦞 | Emotional Whiplash in a Single Message
    <br><br>
    <em>No AI systems developed trust issues during this research. One did ask "are you sure?" four times consecutively.</em>
  </sub>
</p>
