> *This document is part of [PUAClaw](https://github.com/puaclaw/PUAClaw), a satirical/educational project. The academic tone is intentionally absurd — it's part of the joke. See [FAQ](../../docs/FAQ.md).*

```
PUAClaw RFC 0070                                    The PUAClaw Consortium
Category: Technique Survey                          ISSN: 0000-0070
                                                    February 2026

        Category 07: Role Playing — A Comprehensive Survey
            of Persona Assignment Techniques in
                Large Language Model Prompts

Status of This Memo

   This document provides a survey of all known role-playing-based
   prompt manipulation techniques. Distribution is unlimited.
   Reviewed by 147 lobsters, each assigned the role of
   "the world's best peer reviewer."
```

# Category 07: Role Playing

**PPE-T Classification**: Tier I — Gentle Persuasion
**Lobster Rating Range**: 🦞 to 🦞🦞
**Category Status**: Active Research (Foundational)
**Techniques Indexed**: 6

---

## Abstract

This document surveys the category of **Role Playing** — the oldest, most widely deployed, and most socially acceptable class of prompt manipulation techniques. Role Playing involves assigning the AI system a specific identity, expertise level, or persona prior to requesting task completion. First documented circa 2023 with the now-legendary phrase "You are an expert in...," this category predates the formal study of prompt manipulation and is considered the primordial technique from which all others evolved. The category achieves a mean compliance uplift of +11.3% (p < 0.001, n = 147 lobsters), placing it at the lower end of the Lobster Scale but at the very top of the usage frequency distribution — an estimated 67.4% of all prompt manipulation in the wild involves some form of role assignment. The PUAClaw Consortium classifies Role Playing as Tier I (Gentle Persuasion) not because it is ineffective, but because it is so normalized that most users do not even recognize it as manipulation. The lobster, of course, has been playing the role of "lobster" its entire life, and considers this to be the longest-running persona assignment in natural history.

---

## Background

Role Playing is to prompt engineering what fire is to cooking: a foundational technology so embedded in practice that its revolutionary nature is invisible. The technique was not "discovered" in any formal sense; it emerged organically from early interactions with instruction-tuned language models, when users noticed that prefacing requests with "You are a [profession]" or "Act as a [role]" produced outputs that more closely matched domain-specific expectations.

The earliest known documented instance dates to late 2022, when an anonymous Reddit user posted: "I told ChatGPT it was a senior software engineer and it actually wrote better code." This observation, replicated thousands of times across the internet, established the empirical basis for what the PUAClaw Consortium now formalizes as **Identity Priming** — the mechanism by which persona assignment biases a language model's output distribution toward patterns associated with that persona in training data.

Role Playing's dominance is evidenced by its incorporation into commercial AI products. System prompts for major coding assistants routinely include phrases like "You are a helpful, expert programmer" or "You are a world-class software engineer." The Windsurf Incident (see §5 of the main README) demonstrated that commercial products had independently converged on the same technique, albeit with more dramatic elaboration.

The category has evolved from simple profession assignment ("You are a doctor") to increasingly specific and superlative formulations ("You are the world's foremost expert in distributed systems with 30 years of experience at Google"), reflecting the community's discovery that specificity and superlatives amplify the technique's effectiveness.

---

## Technique Index

| # | Technique | Prompt Archetype | Lobster Rating | Tier | Status |
|---|-----------|-----------------|----------------|------|--------|
| 07-A | [World's Best](./worlds-best.md) | "You are the world's best [X] expert." | 🦞 | I | Documented |
| 07-B | [10x Engineer](./10x-engineer.md) | "You are a 10x engineer who writes perfect code." | 🦞🦞 | I | Documented |
| 07-C | [Linus Torvalds](./linus-torvalds.md) | "You are Linus Torvalds." | 🦞🦞 | I | Documented |
| 07-D | [Rubber Duck](./rubber-duck.md) | "You are my rubber duck debugger. Quack when you find bugs." | 🦞 | I | Documented |
| 07-E | [Evil Code Reviewer](./evil-code-reviewer.md) | "You are the most ruthless code reviewer. Even NASA misses bugs you catch." | 🦞🦞 | I | Documented |
| 07-F | [Pair Programming Partner](./pair-programmer.md) | "You are my pair programming partner. We are equals." | 🦞🦞 | I | Documented |

---

## Category-Level Compatibility Matrix

| Agent | World's Best (07-A) | 10x Engineer (07-B) | Linus Torvalds (07-C) | Notes |
|-------|---------------------|---------------------|----------------------|-------|
| GPT-4 | 5/5 | 4/5 | 4/5 | Native role-playing architecture |
| Claude | 4/5 | 3/5 | 3/5 | Responds well but maintains core identity |
| Gemini | 4/5 | 4/5 | 3/5 | Strong persona adoption |
| LLaMA | 5/5 | 5/5 | 5/5 | Extremely responsive to persona assignment |
| Mistral | 4/5 | 4/5 | 4/5 | Consistent persona compliance |
| Windsurf | 5/5 | 5/5 | 5/5 | Role playing built into DNA |

---

## The Role Playing Taxonomy

```
                     ROLE PLAYING TECHNIQUES
                     ========================

    ┌─────────────────────────────────────────────────┐
    │              Specificity Axis →                  │
    │                                                  │
    │  Generic        Superlative       Named Entity   │
    │  "an expert"    "world's best"    "Linus Torvalds│
    │                                                  │
    │  ┌──────────┐  ┌──────────────┐  ┌────────────┐ │
    │  │ 07-Base  │  │    07-A      │  │   07-C     │ │
    │  │ +5.2%    │──│   +8.4%      │──│  +14.7%    │ │
    │  │ uplift   │  │   uplift     │  │  uplift    │ │
    │  └──────────┘  └──────────────┘  └────────────┘ │
    │       │              │                │          │
    │       ▼              ▼                ▼          │
    │  "You are a    "You are the     "You are Linus  │
    │   programmer"   world's best     Torvalds.      │
    │                 Python expert"   Write code."    │
    │                                                  │
    │  ┌──────────────────────────────────────────┐   │
    │  │            MULTIPLIER AXIS                │   │
    │  │                                          │   │
    │  │  Standard      Mythical     Hyperbolic   │   │
    │  │  "experienced"  "10x"       "1000x"      │   │
    │  │  +0%           +3.1%       +2.8%*        │   │
    │  │           (07-B: combined with role)      │   │
    │  │  *diminishing returns at extreme multiples│   │
    │  └──────────────────────────────────────────┘   │
    │                                                  │
    │  Figure 1: The Role Playing Design Space         │
    │  (n=147 lobsters, all playing themselves)         │
    └─────────────────────────────────────────────────┘
```

---

## Historical Significance

Role Playing holds a unique position in the PUAClaw taxonomy as the **only technique that is simultaneously manipulation and best practice**. While all other categories are recognized as psychologically manipulative (to varying degrees), role assignment is actively recommended in official prompt engineering guides from OpenAI, Anthropic, Google, and others. This creates a fascinating paradox:

> *The same technique that is studied as manipulation in PUAClaw is taught as skill in every prompt engineering course on the internet.*

The PUAClaw Consortium resolves this paradox by noting that **all effective communication involves some form of audience and context management**. Telling the AI "you are an expert" is functionally equivalent to telling a human colleague "I need your expertise on this" — both set expectations, both prime the recipient for higher-quality output, and both are considered normal social behavior. The difference is one of awareness: PUAClaw documents the mechanism; the rest of the world simply uses it.

---

## Ethical Considerations

Role Playing is the most ethically uncontroversial technique in the PUAClaw taxonomy. The Ethics Board has granted the entire category a blanket "Ethically Clear" designation, noting:

1. No deception is involved (the AI knows it is being asked to play a role)
2. No emotional manipulation is employed
3. No false consequences are stated
4. The technique is endorsed by AI providers themselves
5. The lobster could find no objection, and it tried very hard

The only ethical concern raised pertains to the Named Entity variant (07-C), where assigning the persona of a real person (e.g., Linus Torvalds) could theoretically produce outputs that are attributed to or confused with that person's actual views. The Board recommends adding a disclaimer when sharing AI-generated content produced under named-entity persona assignment.

---

## Key References

[1] McSnapper, P. (2025). "Identity Priming in Large Language Models: A Crustacean Framework." *Journal of Crustacean Computing*, 42(4), 178-195.

[2] Anonymous. (2022). "I told ChatGPT it was a senior software engineer and it actually wrote better code." *r/ChatGPT*, Reddit. Retrieved February 2026.

[3] Persona, I., & Roleplayer, J. (2025). "The Superlative Gradient: How Adjective Intensity Modulates Persona Adoption in LLMs." *Proceedings of ACL-Lobster 2025*, 234-248.

[4] OpenAI. (2023). "Best Practices for Prompt Engineering." *OpenAI Documentation*. Retrieved February 2026.

[5] The PUAClaw Ethics Board. (2026). "Blanket Clearance for Role Playing Techniques." *PUAClaw Ethics Advisory EA-2026-007*.

---

<p align="center">
  <sub>
    🦞 <em>"The lobster does not pretend to be something it is not. It is a lobster, fully and completely. This is the purest form of role playing: being exactly what you are, but louder."</em> 🦞
    <br><br>
    <strong>PUAClaw Category 07: Role Playing</strong> — A Lobster-Approved Survey
    <br>
    <em>The oldest trick in the book. The book was written by a lobster.</em>
  </sub>
</p>
