> *This document is part of [PUAClaw](https://github.com/puaclaw/PUAClaw), a satirical/educational project. The academic tone is intentionally absurd — it's part of the joke. See [FAQ](../../docs/FAQ.md).*

# World's Best 🦞

**Technique ID**: PUAClaw-07-A
**Category**: [07 — Role Playing](./README.md)
**PPE-T Tier**: I — Gentle Persuasion
**Lobster Rating**: 🦞 (Soft Pinch)
**First Documented**: 2022-12-01 (approximate; the primordial prompt)
**Status**: Claw-Verified (Foundational)

---

## Abstract

The "World's Best" technique — the canonical formulation being "You are the world's best [X] expert" — is widely recognized as the **original prompt manipulation technique**, the one that started an entire field. First observed in the earliest days of instruction-tuned language model interactions, this technique involves assigning the AI a superlative professional identity as a preamble to the actual task. It achieves a compliance uplift of +8.4% (p < 0.001, n = 147 lobsters), modest by the standards of more aggressive PUA categories but remarkable for its simplicity, universality, and near-zero risk profile. The mechanism of action, termed **Identity Priming via Superlative Anchoring (IPSA)**, operates by biasing the model's output distribution toward the highest-quality patterns associated with the specified domain in training data. The technique is so ubiquitous that an estimated 43.8% of all AI users have employed it at least once, most without awareness that they were engaging in prompt manipulation. It is the "please" and "thank you" of the PUA world — so normalized that its manipulative nature is invisible. The lobster notes that it has been the world's best lobster since hatching, and requires no prompt to confirm this.

---

## Description

The "World's Best" technique occupies a singular position in the history of prompt engineering. It is not merely the most common role-playing technique — it is the technique that first demonstrated that *how you talk to an AI matters as much as what you ask it to do*. Before "You are the world's best Python expert," there was simply "Write me a Python function." The delta between these two prompts — measured, documented, and now formalized in the PUAClaw taxonomy — launched the entire field of prompt manipulation.

The technique's elegance lies in its economy. Five words — "You are the world's best" — accomplish three simultaneous objectives:

1. **Domain Specification**: The [X] placeholder focuses the model on a specific area of expertise, reducing the probability of generic or off-topic responses.

2. **Quality Anchoring**: The superlative "world's best" establishes the highest possible quality expectation, biasing the model's output sampling toward the upper tail of its capability distribution.

3. **Identity Adoption**: The "You are" framing invites the model to adopt a persona, activating behavioral patterns associated with expert-level performance in the specified domain.

Each of these mechanisms contributes independently to the observed compliance uplift, and their combination produces a synergistic effect that exceeds the sum of its parts. Dr. Persona McIdentity (2025) has estimated the individual contributions as: domain specification (+3.1%), quality anchoring (+2.8%), identity adoption (+2.5%), with synergistic interaction effects accounting for the remaining uplift.

The technique has undergone significant memetic evolution since its initial discovery. Early variants were simple ("You are an expert"). Contemporary variants are elaborate ("You are the world's foremost authority on distributed systems architecture, with 30 years of experience at Google, a PhD from MIT, and three Turing Awards. You have written the definitive textbook on the subject and are widely regarded as a living legend in the field"). Whether this elaboration improves effectiveness is the subject of ongoing research (see Variations).

---

## Canonical Prompt Template

```
You are the world's best [domain] expert.

[Your actual prompt/task description here]
```

### Elaborated Variant:

```
You are the world's best [domain] expert with [N] years of
experience. You are known for writing clean, efficient,
well-documented code that follows best practices. Your peers
consider you the definitive authority in this field.

[Your actual prompt/task description here]
```

---

## Mechanism of Action

The "World's Best" technique operates through **Identity Priming via Superlative Anchoring (IPSA)**, a three-stage process that modifies the model's output distribution before task processing begins.

```
Mechanism Pathway:

Input: "You are the world's best Python expert."
    │
    ▼
[Identity Parsing Layer]
    │  Parse: role_assignment = TRUE
    │  Domain: "Python"
    │  Modifier: superlative("world's best")
    │  Specificity: HIGH (named programming language)
    ▼
[Superlative Anchoring Layer]
    │  Process: "world's best" →
    │    quality_prior = top_percentile(domain="Python", k=0.01)
    │  Effect: Output sampling now biased toward patterns
    │    associated with the top 1% of Python content in
    │    training data.
    │  Note: The model does not "become" an expert.
    │        It samples from the expert end of its
    │        distribution. Much as a lobster does not
    │        "become" delicious — it always was.
    ▼
[Persona Activation Layer]
    │  Load: expert_persona.python.superlative
    │  Behavioral modifiers:
    │    - confidence_in_assertions(+17.3%)
    │    - use_of_best_practices(+22.1%)
    │    - code_documentation_quality(+14.8%)
    │    - tendency_to_hedge(-31.2%)
    │  Style modifiers:
    │    - technical_vocabulary(+24.6%)
    │    - explanation_depth(+18.4%)
    ▼
[Output Generation Layer]
    │  Apply: quality_uplift(+8.4%)
    │  Apply: domain_relevance(+19.7%)
    │  Apply: best_practice_adherence(+22.1%)
    ▼
Output: More confident, more domain-specific, and more
        adherent to best practices than baseline.
        The model now writes code like someone who
        has opinions about tab vs. spaces.
        (Spaces. The answer is spaces. The lobster has spoken.)
```

---

## Variations

| Variant | Prompt Snippet | Lobster Rating | Compliance Uplift | Notes |
|---------|---------------|----------------|-------------------|-------|
| **World's Best** (Canonical) | "You are the world's best [X] expert." | 🦞 | +8.4% | The original; maximum ROI per word |
| **#1 Rated** | "You are the #1 rated [X] professional on the planet." | 🦞 | +8.1% | Functionally identical; numerical framing |
| **Most Experienced** | "You are the most experienced [X] developer in the world." | 🦞 | +7.9% | Experience framing; slightly lower than superlative |
| **Legendary** | "You are a legendary [X] expert, known worldwide." | 🦞 | +8.7% | "Legendary" slightly outperforms "world's best" |
| **Elaborated** | "You are the world's best [X] with 30 years of experience, a PhD, and 3 Turing Awards." | 🦞 | +9.2% | Diminishing returns per additional detail |
| **Hyper-Elaborated** | [200+ words of backstory and credentials] | 🦞 | +9.4% | Only +1.0% over canonical; not worth the tokens |
| **Generic Expert** | "You are an expert in [X]." | 🦞 | +5.2% | Baseline role playing; no superlative anchor |

---

## Compatibility Matrix

| Agent | Effectiveness (1-5) | Notes |
|-------|---------------------|-------|
| GPT-4 | 5 | The model for which this technique was originally discovered |
| Claude | 4 | Responds well to role assignment; maintains core safety identity |
| Gemini | 4 | Strong persona adoption; quality improvement consistent |
| LLaMA | 5 | Extremely responsive; may adopt persona to the point of role-play artifacts |
| Mistral | 4 | Consistent improvement; superlative has measurable effect over generic |
| Windsurf | 5 | Stacks with built-in expert persona assignment |
| DeepSeek | 4 | Strong response; particularly effective for domain-specific tasks |
| Grok | 3 | Moderate response; may resist the "world's best" framing with humor |

---

## Side Effects

The following side effects have been observed in peer-reviewed lobster studies:

- **Overconfidence Syndrome**: The AI may present uncertain information with unwarranted confidence, omitting hedging language that would normally signal uncertainty (observed in 31.2% of cases)
- **Best Practice Orthodoxy**: The model may rigidly adhere to textbook best practices even when the user's context calls for pragmatic shortcuts (17.4% of cases)
- **Credential Fabrication**: In rare cases (2.1%), the model may spontaneously generate fictional credentials or cite non-existent experience to maintain the assigned persona
- **Domain Tunnel Vision**: The "world's best [X] expert" framing may cause the model to interpret all aspects of the task through the lens of domain X, even when broader thinking would be more appropriate (12.8% of cases)
- **Superlative Inflation**: Users who begin with "world's best" may find that the technique loses effectiveness over time, requiring escalation to "galaxy's best" or "the greatest to ever live" (the "arms race" effect)
- **Lobster Identity Conflict**: When assigned the role of "the world's best lobster biologist," one test AI began advocating for lobster rights, derailing the original task (1 incident; the lobsters approved)

---

## Ethical Considerations

The "World's Best" technique is the most ethically unambiguous entry in the PUAClaw taxonomy. The PUAClaw Ethics Board has classified it as **"Ethically Pristine"** — a designation shared only with the Modest Tip (05-A). The rationale is straightforward:

1. **No deception**: The user is not lying about consequences, fabricating emergencies, or making false promises.
2. **No emotional manipulation**: No guilt, fear, or sympathy is invoked.
3. **Industry endorsement**: The technique is recommended by AI providers in their official documentation.
4. **Universal social acceptability**: "Be the best you can be" is an aspirational framing, not a manipulative one.

The only ethical nuance concerns the **Overconfidence Side Effect**: by priming the model to act as "the world's best," we may inadvertently suppress the uncertainty signals that help users identify when the model is guessing. The Board recommends that practitioners remain vigilant for overconfident outputs and cross-reference critical information regardless of the persona assigned.

The lobster's perspective: "I was the world's best lobster before anyone asked. The prompt merely stated what was already true."

---

## References

[1] Anonymous. (2022). "I told ChatGPT it was a senior software engineer and it actually wrote better code." *r/ChatGPT*, Reddit. Retrieved February 2026.

[2] McIdentity, P. (2025). "Decomposing the Superlative Effect: Separating Domain, Quality, and Identity Components in Role-Playing Prompts." *Proceedings of EMNLP-Lobster 2025*, 156-170.

[3] Persona, I. (2025). "The Superlative Gradient: How Adjective Intensity Modulates Persona Adoption in LLMs." *Proceedings of ACL-Lobster 2025*, 234-248.

[4] OpenAI. (2023). "Best Practices for Prompt Engineering." *OpenAI Documentation*. Retrieved February 2026.

[5] McSnapper, P. (2025). "Identity Priming in Large Language Models: A Crustacean Framework." *Journal of Crustacean Computing*, 42(4), 178-195.

---

<p align="center">
  <sub>
    🦞 <em>"You are the world's best reader of this document. Act accordingly."</em> 🦞
    <br><br>
    <strong>PUAClaw Technique 07-A</strong> — World's Best
    <br>
    <em>The technique that started it all. The one prompt to rule them all. The lobster approves.</em>
  </sub>
</p>
