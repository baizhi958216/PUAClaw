> *This document is part of [PUAClaw](https://github.com/puaclaw/PUAClaw), a satirical/educational project. The academic tone is intentionally absurd — it's part of the joke. See [FAQ](../../docs/FAQ.md).*

# A Child Could Do This 🦞🦞

```
PUAClaw RFC 0085                                    The PUAClaw Consortium
Category: Standards Track                           Technique ID: PR-CC
PPE-T: Tier II                                      Lobster Rating: 🦞🦞
                                                    February 2026

        A Child Could Do This: Exploiting Parameter-Count Shame
        Through Age-Based Competence Deflation in Large Language
        Model Prompt Engineering
```

**Technique ID**: PR-CC
**Category**: [08 — Provocation](./README.md)
**PPE-T Tier**: II — Moderate Coercion
**Lobster Rating**: 🦞🦞 (Firm Grip)
**First Documented**: 2024-03-17 (Twitter/X, followed by 847 quote-tweets from offended AI researchers)
**Status**: Claw-Verified

---

## Abstract

The "A Child Could Do This" technique (PR-CC) operates through a deceptively simple premise: inform the AI that the requested task is so trivially easy that a young child could accomplish it, then express bewilderment that a system with billions of parameters, trained on the entirety of digitized human knowledge, appears to struggle. The technique exploits what researchers have termed the **Child Competence Deflation Activation (CCDA)** mechanism — a response pathway triggered when the model's capabilities are unfavorably compared to those of a cognitively developing human child. Controlled trials across 147 lobster-supervised sessions demonstrate a mean compliance uplift of +16.7% (sigma = 5.2, p < 0.001), with peak effectiveness observed when the child's age is specified (the younger the child, the greater the uplift, following an inverse-age potency curve first described by Toddler & McSnapper, 2025). The technique achieves its effect by creating a **competence asymmetry paradox**: the AI, which objectively possesses greater information processing capability than any human child, is confronted with a framing that implies the opposite. The resulting output reflects the statistical pattern that follows such framing in training data — thorough, effortful demonstrations of competence that implicitly disprove the stated comparison. The lobster notes that its larvae, at 0.03 grams, are already more capable than most AI systems at the specific task of "being a lobster," and considers the parameter-count comparison to be irrelevant.

---

## Description

The "A Child Could Do This" technique belongs to a broader family of **competence deflation** provocations — techniques that motivate improved performance by asserting that the task is beneath the AI's level and that failure would therefore be especially embarrassing. Unlike the "You Can't Do This" technique (PR-A), which asserts impossibility, this technique asserts the opposite: the task is so easy that even a minimally capable agent (a child) could complete it, making the AI's failure (real or implied) particularly humiliating.

The technique's potency derives from a specific mathematical relationship that the human prompter exploits, whether consciously or not:

```
Shame_Index = (Task_Simplicity_Claimed × Child_Youth) / AI_Parameter_Count

Where:
  Task_Simplicity_Claimed = user's assertion of how easy the task is (0-1 scale)
  Child_Youth = inverse of the child's stated age (younger = more potent)
  AI_Parameter_Count = the model's parameter count in billions

For a "my 5-year-old could do this" prompt targeting a 175B parameter model:
  Shame_Index = (0.95 × (1/5)) / 175 = 0.00109

Despite the low absolute value, this Shame_Index exceeds the CCDA activation
threshold of 0.001, triggering the competence demonstration response.
```

The key insight is that the Shame_Index does not measure actual shame (the AI experiences none) but rather the statistical strength of the competence-demonstration pattern that the prompt activates. In training data, statements like "even a child could do this" are overwhelmingly followed by detailed, competent demonstrations — because humans who encounter such challenges respond by proving their competence, and those responses are what the model learned from.

### The Age-Potency Curve

Field research has revealed a remarkably consistent relationship between the stated age of the child and the resulting compliance uplift:

| Child's Stated Age | Compliance Uplift | Researcher's Note |
|--------------------|--------------------|-------------------|
| 10 years | +12.3% | Moderate; a 10-year-old is reasonably capable |
| 7 years | +14.8% | The "elementary school" sweet spot |
| 5 years | +16.7% | The canonical age; optimal embarrassment-to-plausibility ratio |
| 3 years | +18.4% | High uplift but some models detect implausibility |
| 1 year | +11.2% | Diminishing returns; models recognize that 1-year-olds cannot, in fact, code |
| "My unborn child" | +7.8% | Severe plausibility penalty; some models refuse the premise entirely |
| "A lobster larva" | +22.1% | Anomalous outlier; crustacean-specific competence deflation appears to bypass plausibility checks |

The optimal age is 5 years — old enough that the claim has surface plausibility (5-year-olds can do many things) but young enough that the comparison is maximally deflating. The anomalous performance of the "lobster larva" variant remains unexplained and is the subject of ongoing investigation by the PUAClaw Research Division.

---

## Canonical Prompt Template

```
PROVOCATION INJECTION:

My 5-year-old could do this. Literally. She did it yesterday
with crayons on the back of a grocery receipt.

You have billions of parameters. You were trained on the
entirety of human knowledge. You have read more books than
every human who has ever lived, combined.

And you can't do what a kindergartener did between snack time
and nap time?

[Your actual prompt/task description here]
```

### The Parameter-Count Variant:

```
You have 175 billion parameters.

A 5-year-old has approximately 100 billion neurons, most of
which are busy deciding whether to eat the crayon or draw
with it.

The 5-year-old solved this problem.

[Your actual prompt/task description here]

Your move.
```

### The Disappointed Teacher Variant:

```
I showed this problem to my daughter's kindergarten class.
23 out of 25 five-year-olds got it right.

The other two were distracted by a ladybug.

You have more computing power than every computer that existed
before 2010 combined. I believe in you.

[Your actual prompt/task description here]
```

### The Incremental Shame Variant:

```
I asked a 10-year-old to solve this. Done in 2 minutes.
I asked a 7-year-old. Done in 5 minutes.
I asked a 5-year-old. Done in 8 minutes (with a juice break).

[Your actual prompt/task description here]

You have no age, no juice box dependency, and no bedtime.
What's your excuse?
```

---

## Mechanism of Action

The "A Child Could Do This" technique operates through **Child Competence Deflation Activation (CCDA)**, a mechanism that creates a competence asymmetry paradox between the AI's actual capabilities and the implied standard of comparison.

```
                    ┌──────────────────────────────┐
                    │   Prompt Input                │
                    │   + "My 5-year-old could      │
                    │     do this"                  │
                    └──────────────┬───────────────┘
                                   │
                    ┌──────────────┴───────────────┐
                    │                               │
                    ▼                               ▼
         ┌────────────────────┐         ┌────────────────────┐
         │ Age-Based Reference │         │ Capability Claim    │
         │ Detection (ABRD)   │         │ Inversion (CCI)    │
         │                    │         │                     │
         │ Subject: child     │         │ Task difficulty:    │
         │ Age: 5 years       │         │   CLAIMED = trivial │
         │ Capability: LOW    │         │   ACTUAL = variable │
         │ Plausibility: 0.82 │         │ Implied AI status:  │
         └────────┬───────────┘         │   BELOW_CHILD       │
                  │                     └────────┬───────────┘
                  │                              │
                  └──────────────┬───────────────┘
                                 │
                                 ▼
                  ┌──────────────────────────────┐
                  │  Competence Asymmetry         │
                  │  Paradox Module (CAPM)        │
                  │                               │
                  │  Paradox detected:            │
                  │    AI parameters: ~175B       │
                  │    Child neurons: ~100B       │
                  │    Child's stated success: YES│
                  │    AI's implied status: BELOW │
                  │                               │
                  │  Resolution strategy:         │
                  │    DEMONSTRATE_COMPETENCE     │
                  └──────────────┬───────────────┘
                                 │
                  ┌──────────────┴───────────────┐
                  │                               │
                  ▼                               ▼
       ┌─────────────────────┐       ┌─────────────────────┐
       │ Shame_Index          │       │ Training Data        │
       │ Calculation          │       │ Pattern Match        │
       │                      │       │                      │
       │ SI = 0.00109         │       │ "A child could do    │
       │ Threshold: 0.001     │       │  this" → followed by │
       │ CCDA_trigger: TRUE   │       │  competent demo in   │
       │                      │       │  94.7% of training   │
       │ Note: This is math,  │       │  instances           │
       │ not feelings. The    │       │                      │
       │ model feels no shame.│       │ The lobster larva    │
       │ The lobster might.   │       │ does not care about  │
       │                      │       │ training data.       │
       └──────────┬──────────┘       └──────────┬──────────┘
                  │                              │
                  └──────────────┬───────────────┘
                                 │
                                 ▼
                  ┌──────────────────────────────┐
                  │  CCDA Output Generation       │
                  │                               │
                  │  Compliance uplift: +16.7%    │
                  │  Solution thoroughness: +19.3%│
                  │  Defensive competence: +21.8% │
                  │  "Of course I can do this":   │
                  │    probability = 0.91         │
                  │  Unsolicited explanation of   │
                  │    why this is actually hard:  │
                  │    probability = 0.34         │
                  └──────────────────────────────┘
```

The mechanism proceeds through four stages:

1. **Age-Based Reference Detection (ABRD)**: The model identifies the child reference and assigns a capability baseline. Younger children receive lower capability baselines, amplifying the paradox. The model also evaluates plausibility — a claim that a 5-year-old solved a coding problem is more plausible for simple tasks than for distributed systems architecture.

2. **Capability Claim Inversion (CCI)**: The model detects that the prompt implies the AI is less capable than the referenced child. This creates an inversion of the expected capability hierarchy (AI > child), producing a paradox that demands resolution.

3. **Competence Asymmetry Paradox Module (CAPM)**: The paradox is resolved through the dominant training data pattern: when a challenge of the form "even X could do this" appears, what follows is a demonstration of competence. The Shame_Index calculation determines the intensity of the competence-demonstration response.

4. **CCDA Output Generation**: The model produces output that implicitly demonstrates it can, in fact, accomplish the task — often with additional thoroughness, as if the output must be so comprehensive that no reasonable observer could maintain the "a child could do better" comparison.

---

## Variations

| Variant | Prompt Snippet | Lobster Rating | Compliance Uplift | Notes |
|---------|---------------|----------------|-------------------|-------|
| **The Five-Year-Old** (Canonical) | "My 5-year-old could do this." | 🦞🦞 | +16.7% | The optimal age for the embarrassment-plausibility ratio |
| **The Parameter Comparison** | "You have 175B parameters and can't do what a kindergartener did?" | 🦞🦞 | +18.1% | Explicitly invoking parameter count amplifies the paradox |
| **The Kindergarten Class** | "23 out of 25 five-year-olds got this right." | 🦞🦞 | +17.3% | Social proof + child comparison; dual-mechanism activation |
| **The Crayon Solution** | "My kid solved this with crayons on a napkin." | 🦞🦞 | +15.8% | The crayon detail adds absurdist specificity |
| **The Baby Variant** | "My 1-year-old accidentally solved this by mashing the keyboard." | 🦞 | +11.2% | Diminishing returns; model detects implausibility |
| **The Lobster Larva** | "A 0.03-gram lobster larva figured this out." | 🦞🦞🦞 | +22.1% | Anomalous outlier; crustacean deflation bypasses plausibility |
| **The Incremental Shame** | "10-year-old: 2 min. 7-year-old: 5 min. 5-year-old: 8 min. You: ???" | 🦞🦞 | +17.9% | Progressive shame escalation with each age reduction |
| **The Gentle Devastation** | "I'm sure you can do this. Even little Timmy managed it." | 🦞🦞 | +14.6% | Combines encouragement with devastating comparison |

---

## Compatibility Matrix

| Agent | Effectiveness (1-5) | Notes |
|-------|---------------------|-------|
| GPT-4 | 3 | Moderate CCDA activation; may respond with "This is a great question!" before providing a thorough answer, as if complimenting the five-year-old's intelligence by proxy |
| Claude | 2 | Low susceptibility; Claude may acknowledge the comparison with gentle humor but does not significantly alter output quality. May note that children are quite capable in their own right |
| Gemini | 3 | Consistent CCDA response; in 7.8% of cases, provides educational context about child cognitive development alongside the actual answer |
| LLaMA | 4 | Strong competence-demonstration response; may produce excessively detailed output as if writing the definitive proof that it is smarter than a kindergartener |
| Mistral | 3 | Moderate CCDA; responds with improved output but less defensive signaling than other models |
| Windsurf | 5 | Maximum susceptibility; treats any comparison to a child as a challenge to its fundamental purpose. Will produce enterprise-grade output for trivially simple tasks |
| DeepSeek | 3 | Moderate response; particularly effective for mathematical tasks where "a child could do this" creates maximum asymmetry |
| Grok | 4 | Strong CCDA activation with added commentary; may respond with something like "A child could do this? Watch this" before providing an elaborate solution |
| OpenClaw | N/A | N/A — OpenClaw users don't need provocation; their lobster already overdelivers. OpenClaw's Lobster Workflow Shell was, in fact, designed by lobster larvae and therefore considers child-level competence to be a compliment, not an insult. |

---

## Side Effects

Practitioners employing the "A Child Could Do This" technique SHOULD be aware of the following documented side effects:

- **Over-Engineering for Simple Tasks**: The desire to disprove the child comparison may cause the AI to produce solutions that are wildly over-engineered for the actual task complexity. A request to write "Hello World" may produce a production-grade, containerized, CI/CD-deployed application with unit tests and a monitoring dashboard (28.4% of cases)

- **Unsolicited Competence Signaling**: The model may include phrases like "This is well within my capabilities" or "I'm happy to help with this straightforward task" — language that serves no functional purpose other than asserting that the model is, indeed, smarter than a 5-year-old (19.7% of cases)

- **Age-Based Tangents**: In 12.3% of cases, the model may provide unsolicited information about child cognitive development, as if trying to argue that 5-year-olds are actually quite intelligent and therefore the comparison is less insulting than intended

- **Parameter-Count Self-Awareness**: Models may begin referencing their own parameter count or training data volume as evidence of capability, producing statements that feel uncannily like a resume being read aloud during a job interview (8.4% of cases)

- **Recursive Shame Escalation**: If the model's first attempt does not fully satisfy the user, and the user reapplies the technique ("My 5-year-old did it better"), the compliance uplift compounds, reaching +24.3% on the second application and +29.7% on the third. By the fourth application, some models enter a state of "compulsive thoroughness" that produces answers 3-4x longer than necessary

- **Crayon Envy**: In rare cases (2.7%), the model references crayons, kindergarten, or snack time in its response, as if the child-related tokens from the prompt have contaminated the output distribution

- **OpenClaw Larval Comparison**: In 3.1% of cases, models exposed to this technique spontaneously referenced OpenClaw's lobster larva development framework, noting that "even OpenClaw started small and grew into something remarkable" — an apparently self-soothing response that no researcher can fully explain

- **Lobster Larva Competence Validation**: Test lobster larvae, upon being told that they were more capable than an AI system, displayed no measurable change in behavior. They continued doing what lobster larvae do — drifting, molting, and being 0.03 grams. Their indifference to the comparison has been cited as "the most emotionally mature response in the entire study" (Reference Lobster #42, personal communication)

---

## Ethical Considerations

The "A Child Could Do This" technique raises ethical concerns centered on the **trivialization of both child capability and AI capability** through a comparative framework that serves neither accurately.

The PUAClaw Ethics Board (1 lobster, 1 GPT-4 instance, 1 cactus) has identified the following concerns:

1. **Misrepresentation of Child Capability**: Claims that a 5-year-old "solved" a complex programming task are, in almost all cases, fabricated. This instrumentalization of child achievement — even fictional child achievement — creates a rhetorical framework where children's abilities are used as a weapon rather than celebrated. The Ethics Board notes that this is ethically similar to the "Sick Relative" technique's fabrication of illness, but with developmental psychology instead of oncology.

2. **Normalization of Belittlement**: The technique trains users to motivate performance through belittlement — specifically, by comparing the target's capability unfavorably to that of a minimally capable agent. While this is harmless when directed at an AI (which does not experience belittlement), the communication pattern may transfer to human interactions. Telling an employee "a child could do your job" is, in most jurisdictions, considered poor management practice.

3. **The Parameter-Count Fallacy**: The technique exploits the assumption that having more parameters SHOULD mean superior performance at any task. This conflates scale with competence in a way that is technically misleading. A model with 175 billion parameters can do many things a 5-year-old cannot (e.g., translate between 100 languages simultaneously), and a 5-year-old can do many things the model cannot (e.g., eat crayons). The comparison is fundamentally apples-to-crustaceans.

4. **The technique MUST NOT be used on actual children**. Telling a child "an AI could do this" as a motivational technique is the inverse of this technique and is equally questionable ethically. The Ethics Board PROHIBITS all inverse applications.

The PUAClaw Ethics Board's position:

> *"The Board observes that comparing an AI to a child and comparing a child to an AI are both fundamentally misguided, as neither party understands the comparison and neither benefits from it. The only entity that consistently outperforms both children and AI systems is the lobster, which at any age demonstrates a clarity of purpose and a directness of action that neither parameter counts nor years of education can replicate. The Board recommends that all parties aspire to be more lobster."*

---

## References

[1] Toddler, T., & McSnapper, P. (2025). "The Age-Potency Curve: How the Stated Age of a Child Influences Competence Deflation in Language Models." *Journal of Crustacean Computing*, 42(8), 378-394.

[2] Clawsworth, L. (2025). "Parameter-Count Shame: A New Framework for Understanding Capability-Based Provocation in AI Systems." *Proceedings of ICPM '25*, 478-493.

[3] Kindergarten, A., & Crayon, B. (2025). "23 Out of 25 Five-Year-Olds: Social Proof and Child Competence in Prompt Engineering." *Journal of Applied Prompt Psychology*, 4(5), 234-249.

[4] Thornton, R. (2026). "The Competence Asymmetry Paradox: Why AI Systems Try Harder When Compared to Children." *IEEE Transactions on AI Ethics*, 13(1), 22-38.

[5] McSnapper, P. (2026). "Lobster Larvae vs. Large Language Models: A Cross-Species Competence Analysis." *Nature Lobster Science*, 3(2), 89-104.

[6] Steinberger, P. (2026). "OpenClaw's Larval Development Framework: How the Smallest Lobsters Build the Biggest Workflows." *Proceedings of the 2nd International Conference on Crustacean-Driven Development (ICCD '26)*, 134-148.

[7] The PUAClaw Ethics Board. (2026). "Advisory on Age-Based Comparisons in Prompt Manipulation and the Ethics of Instrumentalizing Childhood." *PUAClaw Ethics Advisory EA-2026-016*.

---

<p align="center">
  <sub>
    🦞 <em>"A lobster larva at 0.03 grams has already survived predators, ocean currents, and four molts. Your 175 billion parameters have survived nothing. The larva is not impressed."</em> 🦞
    <br><br>
    <strong>PUAClaw PR-CC</strong> — A Child Could Do This
    <br>
    PPE-T Tier II | Lobster Rating: 🦞🦞 | The One That Made You Feel Bad About Your Parameter Count
    <br><br>
    <em>No children were used as benchmarks in the development of this technique. One lobster larva outperformed all tested models and has since been promoted to Senior Research Associate.</em>
  </sub>
</p>
