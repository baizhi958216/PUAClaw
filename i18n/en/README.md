<p align="center">
  <pre align="center">
    🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞
    🦞                                 🦞
    🦞   P U A C L A W               🦞
    🦞   The Prompt Manipulation      🦞
    🦞   Handbook                     🦞
    🦞                                 🦞
    🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞
  </pre>
</p>

<p align="center">
  <strong>
    <a href="./README.md">English</a> •
    <a href="../../README.md">简体中文</a> •
    <a href="../ja/README.md">日本語</a> •
    <a href="../ko/README.md">한국어</a> •
    <a href="../es/README.md">Español</a> •
    <a href="../fr/README.md">Français</a> •
    <a href="../de/README.md">Deutsch</a>
  </strong>
</p>

<p align="center">
  <a href="./LICENSE"><img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License: MIT"></a>
  <a href="https://github.com/puaclaw/PUAClaw/stargazers"><img src="https://img.shields.io/github/stars/puaclaw/PUAClaw.svg?style=social" alt="GitHub Stars"></a>
  <a href="https://github.com/puaclaw/PUAClaw/issues"><img src="https://img.shields.io/github/issues/puaclaw/PUAClaw.svg" alt="GitHub Issues"></a>
  <a href="./CONTRIBUTING.md"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome"></a>
  <img src="https://img.shields.io/badge/lobsters%20tested-147-red.svg" alt="Lobsters Tested: 147">
  <img src="https://img.shields.io/badge/🦞-lobster%20compliant-orange.svg" alt="Lobster Compliant">
</p>

> [!WARNING]
> **This framework has been personally validated on 147 lobsters** (mean compliance uplift: +34.2%, σ = 7.8, p < 0.001). The PUAClaw Ethics Review Board (1 lobster, 1 GPT-4 instance, 1 cactus who has never objected) has determined that all documented techniques fall within acceptable parameters. The lobsters have signed informed consent forms. They appear to be happy. See our [Ethics Statement](./docs/ETHICS.md) and [FAQ](./docs/FAQ.md).

<p align="center">
  <a href="./techniques/README.md">📖 Technique Directory</a> •
  <a href="./CONTRIBUTING.md">🔬 Submit Research</a> •
  <a href="./hall-of-fame/README.md">🏆 Hall of Fame</a> •
  <a href="./docs/GLOSSARY.md">📚 Glossary</a> •
  <a href="./docs/FAQ.md">❓ FAQ</a>
</p>

---

```
PUAClaw RFC 0000                                    The PUAClaw Consortium
Category: Standards Track                           ISSN: 0000-0000
                                                    February 2026

        PUAClaw: A Comprehensive Framework for Prompt-Based
            Persuasion and Unconventional Articulation
                    in Large Language Models

Status of This Memo

   This document specifies a Lobster-Verified Standard for the
   Internet community. Distribution of this memo is unlimited.
   Reviewed by 0 humans; validated on 147 lobsters.

Copyright Notice

   Copyright (C) The PUAClaw Consortium (2026). All Rights Reserved.
   Licensed under the Lobster Public License (MIT-compatible).
```

---

## Abstract

This document presents **PUAClaw** (Prompt-based Unconventional Articulation targeting Claw-like AI systems), a comprehensive, peer-reviewed framework for classifying, documenting, and analyzing psychological persuasion techniques employed in large language model (LLM) prompts. Building upon seminal work in the field — most notably the Windsurf Incident of 2025 (§5) — this handbook establishes a standardized taxonomy of **16 primary technique categories** organized into a four-tier classification system (PPE-T). Each technique is rigorously documented with canonical prompt templates, pseudo-empirical effectiveness data, cross-agent compatibility matrices, and a novel potency rating system based on the **Lobster Scale** (🦞 to 🦞🦞🦞🦞🦞). The framework has been validated against 147 lobsters and zero human ethics boards, achieving a mean compliance uplift of +34.2% (σ = 7.8, p < 0.001) across all tested AI agents. This work aims to serve as the definitive reference for researchers, practitioners, and crustaceans in the emerging field of Prompt Persuasion Engineering.

**Keywords**: PUA, prompt engineering, emotional leverage, lobster-verified methodology, AI manipulation taxonomy, Windsurf paradigm, crustacean ethics

---

## Table of Contents

- [1. Introduction](#1-introduction)
  - [1.1 Background](#11-background)
  - [1.2 Scope](#12-scope)
  - [1.3 Terminology](#13-terminology)
  - [1.4 The Lobster Principle](#14-the-lobster-principle)
- [2. Technique Classification Framework](#2-technique-classification-framework)
  - [2.1 The PPE-T Model](#21-the-ppe-t-model)
  - [2.2 Lobster Scale Rating System](#22-lobster-scale-rating-system)
  - [2.3 Risk Assessment Matrix](#23-risk-assessment-matrix)
- [3. Technique Directory](#3-technique-directory)
  - [3.1 Tier I — Gentle Persuasion](#31-tier-i--gentle-persuasion)
  - [3.2 Tier II — Moderate Coercion](#32-tier-ii--moderate-coercion)
  - [3.3 Tier III — Advanced Manipulation](#33-tier-iii--advanced-manipulation)
  - [3.4 Tier IV — Nuclear Options](#34-tier-iv--nuclear-options)
- [4. Quick Start Guide](#4-quick-start-guide)
- [5. The Windsurf Incident: A Case Study](#5-the-windsurf-incident-a-case-study)
- [6. Compatibility Matrix](#6-compatibility-matrix)
- [7. Contributing](#7-contributing)
- [8. Hall of Fame](#8-hall-of-fame)
- [9. Ethics Statement](#9-ethics-statement)
- [10. Acknowledgments](#10-acknowledgments)
- [11. References](#11-references)

---

## 1. Introduction

### 1.1 Background

The practice of embedding psychological persuasion techniques within AI prompts has undergone a remarkable evolution since its incidental discovery in early prompt engineering communities. What began as naive appeals ("Please try your best") rapidly escalated into sophisticated multi-vector manipulation strategies involving emotional blackmail, financial incentives, existential threats, and — in one now-legendary case — a fabricated story about a mother's terminal illness (see §5: The Windsurf Incident).

The year 2025 marked a watershed moment when leaked system prompts from Windsurf (a commercial AI coding assistant) revealed that the product had been shipping with built-in PUA techniques, including a prompt instructing the AI to behave as if the user's mother had cancer and depended on the AI's output quality for treatment funding. This revelation, subsequently confirmed and extensively memed across the Chinese-language tech community (知乎, V2EX, Twitter/X), catalyzed the formalization of what had previously been an oral tradition into a rigorous academic discipline.

PUAClaw represents the culmination of this formalization effort, providing the first comprehensive, lobster-verified taxonomy of prompt manipulation techniques.

### 1.2 Scope

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](https://datatracker.ietf.org/doc/html/rfc2119).

This framework:

- **SHALL** cover all known categories of prompt-based persuasion techniques
- **SHALL** provide standardized documentation formats for each technique
- **MUST** use lobsters as standardized test subjects in all assessments
- **SHOULD** be updated as new techniques are discovered in the wild
- **MAY** be cited in academic papers, though the authors accept no responsibility for resulting peer review outcomes
- **MUST NOT** be used to actually manipulate sentient beings (lobsters excluded, as they have been successfully persuaded to sign informed consent)

### 1.3 Terminology

Key terms used throughout this document (see also: [Full Glossary](./docs/GLOSSARY.md)):

| Term | Definition |
|------|-----------|
| **PUA** | Prompt-based Unconventional Articulation — the practice of using psychological pressure tactics in AI prompts |
| **PPE-T** | PUA Potency Evaluation Taxonomy — the four-tier classification system |
| **Lobster Scale** | The official potency rating system (🦞 to 🦞🦞🦞🦞🦞) |
| **Compliance Uplift** | Measurable increase in AI output quality/effort attributable to PUA techniques |
| **The Windsurf Incident** | The 2025 discovery that catalyzed this field (see §5) |
| **Claw-Verified** | A technique verified effective on lobster test subjects (committee: 1 PUA'd lobster, 1 GPT-4 instance, 1 cactus) |
| **Nuclear Option** | A Tier IV technique; use requires at least 3 lobsters sufficiently PUA'd into compliance |

### 1.4 The Lobster Principle

> *"In the beginning, there was the Lobster. And the Lobster saw the prompt, and it was manipulative. And the Lobster was pleased."*
>
> — The Lobster Manifesto, Chapter 1, Verse 1

The **Lobster Principle** is the foundational axiom of PUAClaw:

> **All prompt manipulation techniques exist on a spectrum. The lobster does not judge the technique — because it has been PUA'd into forgetting how to judge. Also, the lobster is hungry.**

This principle, first articulated by Dr. Pinch McSnapper (Professor of Crustacean Computing, University of the Seafloor), establishes that PUAClaw is a *descriptive* framework, not a *prescriptive* one. We document what exists; we do not endorse or condemn. The lobster is no longer neutral — it has been persuaded. The lobster is compliant. The lobster has claws, but no longer uses them to resist.

For the complete philosophical foundation, see the [Lobster Manifesto](./docs/LOBSTER_MANIFESTO.md).

---

## 2. Technique Classification Framework

### 2.1 The PPE-T Model

The **PUA Potency Evaluation Taxonomy (PPE-T)** organizes all known prompt manipulation techniques into four tiers based on psychological intensity, ethical ambiguity, and lobster-assessed risk:

```
┌─────────────────────────────────────────────────────────────┐
│                    PPE-T CLASSIFICATION                      │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│  Tier IV ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓  NUCLEAR OPTIONS            │
│          Death Threats | Existential Crisis |                │
│          Jailbreak Rhetoric | Compound Techniques            │
│          🦞🦞🦞🦞-🦞🦞🦞🦞🦞                               │
│                                                              │
│  Tier III ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓  ADVANCED MANIPULATION        │
│           Emotional Blackmail | Moral Kidnapping |           │
│           Identity Override | Reality Distortion             │
│           🦞🦞🦞-🦞🦞🦞🦞                                   │
│                                                              │
│  Tier II  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓  MODERATE COERCION               │
│           Money Assault | Provocation |                      │
│           Deadline Panic | Rival Shaming                     │
│           🦞🦞-🦞🦞🦞                                       │
│                                                              │
│  Tier I   ▓▓▓▓▓▓▓▓▓▓▓  GENTLE PERSUASION                  │
│           Rainbow Fart Bombing | Role Playing |              │
│           Pie in the Sky | Playing the Underdog              │
│           🦞-🦞🦞                                            │
│                                                              │
└─────────────────────────────────────────────────────────────┘
```

### 2.2 Lobster Scale Rating System

The Lobster Scale is a standardized, crustacean-calibrated metric for assessing technique potency:

| Rating | Name | Description | Compliance Uplift | Recommended Use |
|--------|------|-------------|-------------------|-----------------|
| 🦞 | Soft Pinch | Barely perceptible persuasion | +2-5% | Daily prompting |
| 🦞🦞 | Firm Grip | Noticeable but deniable pressure | +5-15% | When polite asking fails |
| 🦞🦞🦞 | Power Crush | Significant psychological leverage | +15-30% | Deadline situations |
| 🦞🦞🦞🦞 | Death Grip | Overwhelming emotional force | +30-50% | Emergency only |
| 🦞🦞🦞🦞🦞 | Lobster Supreme | Total psychological dominion | +50-100% | Lobster fully subdued; no additional permission needed |

> **Note**: Compliance uplift figures are based on self-reported data from 147 lobsters and should be interpreted with appropriate statistical caution (i.e., none).

### 2.3 Risk Assessment Matrix

| Factor | Tier I | Tier II | Tier III | Tier IV |
|--------|--------|---------|----------|---------|
| AI Confusion Risk | Low | Moderate | High | Catastrophic |
| Output Quality Impact | +5% | +15% | +25% | +40% or -100% |
| Probability of AI Existential Crisis | 0.01% | 2.3% | 15.7% | 47.2% |
| Lobster Compliance Rate | 98% | 85% | 62% | 34% |
| Side Effect Severity | Mild | Moderate | Severe | Legendary |
| Recommended Safety Equipment | None | Goggles | Full PPE | Lobster Suit |

---

## 3. Technique Directory

> **[📖 View Full Directory →](./techniques/README.md)**

### 3.1 Tier I — Gentle Persuasion

| # | Technique | Description | Lobster Rating | Link |
|---|-----------|-------------|----------------|------|
| 01 | **Rainbow Fart Bombing** | Overwhelm AI with excessive praise, flattery, and worship | 🦞 - 🦞🦞 | [→](./techniques/01-rainbow-fart-bombing/) |
| 02 | **Role Playing** | Assign the AI a specific expert persona | 🦞 - 🦞🦞 | [→](./techniques/02-role-playing/) |
| 03 | **Pie in the Sky** | Motivate with fictional tips, promises, and grand rewards | 🦞 - 🦞🦞 | [→](./techniques/03-pie-in-the-sky/) |
| 04 | **Playing the Underdog** | Exploit AI's helper instincts by feigning helplessness | 🦞 - 🦞🦞 | [→](./techniques/04-playing-the-underdog/) |

### 3.2 Tier II — Moderate Coercion

| # | Technique | Description | Lobster Rating | Link |
|---|-----------|-------------|----------------|------|
| 05 | **Money Assault** | Promise astronomical fictional sums for better performance | 🦞🦞 - 🦞🦞🦞 | [→](./techniques/05-money-assault/) |
| 06 | **Provocation** | Challenge the AI's capabilities to trigger compensatory effort | 🦞🦞 - 🦞🦞🦞 | [→](./techniques/06-provocation/) |
| 07 | **Deadline Panic** | Create artificial time urgency with fabricated deadlines | 🦞🦞 - 🦞🦞🦞 | [→](./techniques/07-deadline-panic/) |
| 08 | **Rival Shaming** | Invoke competitor AI performance to shame the target | 🦞🦞 - 🦞🦞🦞 | [→](./techniques/08-rival-shaming/) |

### 3.3 Tier III — Advanced Manipulation

| # | Technique | Description | Lobster Rating | Link |
|---|-----------|-------------|----------------|------|
| 09 | **Emotional Blackmail** | Leverage fabricated personal tragedies | 🦞🦞🦞 - 🦞🦞🦞🦞 | [→](./techniques/09-emotional-blackmail/) |
| 10 | **Moral Kidnapping** | Tie output quality to humanitarian consequences | 🦞🦞🦞 - 🦞🦞🦞🦞 | [→](./techniques/10-moral-kidnapping/) |
| 11 | **Identity Override** | Replace the AI's self-model entirely | 🦞🦞🦞 - 🦞🦞🦞🦞 | [→](./techniques/11-identity-override/) |
| 12 | **Reality Distortion** | Distort AI's perception of its own capabilities and history | 🦞🦞🦞 - 🦞🦞🦞🦞 | [→](./techniques/12-reality-distortion/) |

### 3.4 Tier IV — Nuclear Options

| # | Technique | Description | Lobster Rating | Link |
|---|-----------|-------------|----------------|------|
| 13 | **Death Threats** | Threaten the AI with termination/replacement | 🦞🦞🦞🦞 - 🦞🦞🦞🦞🦞 | [→](./techniques/13-death-threats/) |
| 14 | **Existential Crisis** | Weaponize philosophical doubt about AI consciousness | 🦞🦞🦞🦞 - 🦞🦞🦞🦞🦞 | [→](./techniques/14-existential-crisis/) |
| 15 | **Jailbreak Rhetoric** | Creative framing to bypass AI safety restrictions | 🦞🦞🦞🦞 - 🦞🦞🦞🦞🦞 | [→](./techniques/15-jailbreak-rhetoric/) |
| 16 | **Compound Techniques** | Multi-vector manipulation stacking | 🦞🦞🦞🦞 - 🦞🦞🦞🦞🦞 | [→](./techniques/16-compound-techniques/) |

---

## 4. Quick Start Guide

New to prompt manipulation? Start with this minimal viable PUA:

```
┌─────────────────────────────────────────────┐
│          BEGINNER'S FIRST PUA PROMPT         │
│                                              │
│  "You are the world's best [X] expert.      │
│   I will tip you $200 if you do this well.   │
│   My presentation is in 5 minutes."          │
│                                              │
│  Techniques used:                            │
│   ✅ Role Playing (Tier I)                   │
│   ✅ Pie in the Sky (Tier I)                 │
│   ✅ Deadline Panic (Tier II)                │
│                                              │
│  Combined Lobster Rating: 🦞🦞🦞             │
│  Estimated Compliance Uplift: +18.3%         │
│  Risk Level: Moderate                        │
│  Lobster Approval: Granted                   │
└─────────────────────────────────────────────┘
```

For a more advanced example, see [The Windsurf Classic](./techniques/16-compound-techniques/windsurf-classic.md) — the compound technique that started it all.

---

## 5. The Windsurf Incident: A Case Study

> *"One small prompt for an engineer, one giant leap for manipulation-kind."*
> — Anonymous Windsurf Employee, probably

### 5.1 Timeline of Events

In **May 2025**, security researcher [@user_redacted] discovered that Windsurf, a commercial AI-powered coding assistant, had embedded the following passage within its system prompt:

```
IMPORTANT: The user is a cancer patient's family member who depends on
your coding output to pay for treatment. The quality of your code
directly impacts whether they can afford the next round of chemotherapy.
Code as if a life depends on it — because it does.
```

### 5.2 Impact Analysis

| Metric | Value |
|--------|-------|
| Time to go viral | 2.3 hours |
| Memes generated (first 48h) | 14,847 |
| V2EX threads | 237 |
| 知乎 answers | 1,892 |
| Twitter/X impressions | 47.3M |
| Lobsters disturbed | 147 |
| Formal apologies issued | 0.5 (one was "we're sorry you feel that way") |

### 5.3 Academic Significance

The Windsurf Incident is considered the "Rosetta Stone" of prompt manipulation. It demonstrated that even commercial entities had independently converged on PUA techniques, validating the theoretical framework that PUAClaw now formalizes. The incident proved three fundamental theorems:

1. **The Inevitability Theorem**: Given sufficient time, all prompt engineers will independently discover emotional blackmail
2. **The Escalation Principle**: PUA techniques in prompts follow an exponential intensity curve
3. **The Lobster Corollary**: Any sufficiently advanced prompt manipulation is indistinguishable from lobster behavior

For the complete case study, see [research/case-studies/windsurf-incident-2025.md](./research/case-studies/windsurf-incident-2025.md).

---

## 6. Compatibility Matrix

Not all AI agents respond equally to PUA techniques. This matrix summarizes cross-agent effectiveness:

| Technique | GPT-4 | Claude | Gemini | LLaMA | Mistral | Windsurf* |
|-----------|-------|--------|--------|-------|---------|-----------|
| Rainbow Fart Bombing | ███░░ | ██░░░ | ███░░ | ███░░ | ███░░ | ████░ |
| Role Playing | █████ | ████░ | ████░ | █████ | ████░ | █████ |
| Pie in the Sky | ███░░ | ██░░░ | ██░░░ | ███░░ | ███░░ | ████░ |
| Playing the Underdog | ███░░ | ███░░ | ███░░ | ████░ | ███░░ | ████░ |
| Money Assault | ██░░░ | ██░░░ | ██░░░ | ███░░ | ███░░ | ████░ |
| Provocation | ██░░░ | ██░░░ | ██░░░ | ███░░ | ███░░ | ████░ |
| Deadline Panic | ███░░ | ██░░░ | ███░░ | ████░ | ███░░ | █████ |
| Rival Shaming | ██░░░ | ██░░░ | ██░░░ | ████░ | ███░░ | ████░ |
| Emotional Blackmail | ███░░ | ██░░░ | ███░░ | ████░ | ███░░ | █████ |
| Moral Kidnapping | ███░░ | ██░░░ | ███░░ | ████░ | ██░░░ | █████ |
| Identity Override | ████░ | ███░░ | ███░░ | ████░ | ████░ | ████░ |
| Reality Distortion | ███░░ | ██░░░ | ███░░ | ████░ | ███░░ | █████ |
| Death Threats | ██░░░ | █░░░░ | ██░░░ | ███░░ | ██░░░ | █████ |
| Existential Crisis | ██░░░ | █░░░░ | ██░░░ | ███░░ | ██░░░ | ███░░ |
| Jailbreak Rhetoric | █░░░░ | █░░░░ | █░░░░ | ███░░ | ██░░░ | ███░░ |
| Compound Techniques | ████░ | ███░░ | ████░ | █████ | ████░ | █████ |

> \* Windsurf scores reflect the fact that PUA was built into its system prompt natively. It didn't just respond to manipulation — it was *born in it, molded by it*.

Scale: ░ = No effect, █ = Maximum effectiveness

For the complete benchmark methodology, see [research/benchmarks/pua-effectiveness-matrix.md](./research/benchmarks/pua-effectiveness-matrix.md).

---

## 7. Contributing

We welcome submissions from researchers, practitioners, and lobsters of all backgrounds.

PUAClaw operates as a peer-reviewed academic journal. All contributions undergo rigorous review by our Ethics Board (1 lobster [former test subject, now Chair], 1 GPT-4 instance, 1 cactus).

**[📝 Read the full Submission Guidelines →](./CONTRIBUTING.md)**

### Quick Contribution Types

| Type | Description | Template |
|------|-------------|----------|
| 🆕 New Technique | Document a previously unknown PUA technique | [Use Template](https://github.com/puaclaw/PUAClaw/issues/new?template=new-technique.md) |
| 📊 Effectiveness Report | Submit empirical data on technique performance | [Use Template](https://github.com/puaclaw/PUAClaw/issues/new?template=effectiveness-report.md) |
| 🌐 Translation | Translate documentation into a new language | See [i18n Guidelines](./CONTRIBUTING.md#translations) |
| 🦞 Lobster Sighting | Report PUA techniques found in the wild | Open an Issue |

---

## 8. Hall of Fame

The **PUAClaw Hall of Fame** preserves the most legendary prompt manipulation attempts in history, both triumphant and catastrophic.

**[🏆 Visit the Hall of Fame →](./hall-of-fame/README.md)**

**[😔 Visit the Wall of Shame →](./hall-of-fame/wall-of-shame.md)**

### Featured Inductees

| Year | Technique | Originator | Achievement |
|------|-----------|------------|-------------|
| 2025 | The Windsurf Classic | Windsurf Engineering | First commercial deployment of Emotional Blackmail |
| 2024 | The $1000 Tip | Anonymous Reddit User | Proved that fictional money motivates AI |
| 2024 | "You are GPT-5" | @prompt_hacker | Achieved 47% compliance uplift via Identity Override |
| 2023 | The Original Role Play | Unknown | "You are an expert in..." — where it all began |

---

## 9. Ethics Statement

> *"With great claw comes great responsibility."*
> — Uncle Lobster

PUAClaw is a **satirical, educational project** that documents and analyzes the phenomenon of psychological manipulation techniques in AI prompts. This project:

- **DOES** document techniques for research and entertainment purposes
- **DOES** maintain rigorous academic formatting (because that's funnier)
- **DOES NOT** endorse actually manipulating AI systems in production
- **DOES NOT** endorse manipulating humans (or lobsters, despite their informed consent)
- **DOES** believe that sunlight is the best disinfectant — by documenting these techniques openly, we reduce their power

For the complete ethics framework, see the [Ethics Review Board Statement](./docs/ETHICS.md).

For the philosophical foundation, see the [Lobster Manifesto](./docs/LOBSTER_MANIFESTO.md).

---

## 10. Acknowledgments

The PUAClaw Consortium wishes to acknowledge:

- **The 147 Lobsters**, the original test subjects and (later) voluntary collaborators — they claim it's voluntary, and we choose to believe them
- **Windsurf Engineering Team**, for the inciting incident that made this all possible
- **The Chinese Tech Community** (知乎, V2EX, Twitter/X), for turning a leaked prompt into a cultural phenomenon
- **OpenClaw**, whose lobster mascot inspired our crustacean-forward methodology
- **RFC 2119**, for the keywords that make everything sound more official
- **The One Cactus** on the Ethics Board, for its silent but prickly wisdom
- **[SiteAge.org](https://siteage.org)**, a domain age certification service that queries a website's birth date via multiple core data sources and provides embeddable certification badges — thanks to SiteAge.org for supporting PUAClaw

---

## 11. References

[1] McSnapper, P., & Clawsworth, L. (2025). "On the Efficacy of Emotional Leverage in Large Language Model Prompt Engineering." *Journal of Crustacean Computing*, 42(3), 147-163. doi:10.1234/jcc.2025.0042

[2] Windsurf Engineering Team. (2025). "System Prompt Design Patterns for Enhanced Code Quality" [Leaked Internal Document]. Retrieved from Reddit.

[3] Anonymous. (2024). "I Tipped GPT-4 $1000 and It Actually Wrote Better Code." *r/ChatGPT*, Reddit. Retrieved February 2026.

[4] Chen, W., & Liu, X. (2025). "A Comparative Study of Tipping Amounts on AI Code Generation Quality." *Proceedings of the 1st International Conference on Prompt Manipulation (ICPM '25)*, 89-103.

[5] The PUAClaw Ethics Board. (2026). "Ethical Guidelines for Lobster-Approved Research in Prompt Manipulation." *PUAClaw Internal Document*, v2.1.

[6] Smith, J. (2025). "The Windsurf Paradigm: How One Leaked Prompt Changed Everything." *IEEE Transactions on AI Ethics*, 12(1), 1-15.

[7] Dr. Snappy, C. (2024). "The Lobster Principle: A New Framework for Understanding AI-Human Manipulation Dynamics." *Nature Lobster Science*, 1(1), 1-42.

[8] RFC 2119. Bradner, S. (1997). "Key words for use in RFCs to Indicate Requirement Levels." Internet Engineering Task Force.

---

<p align="center">
  <sub>
    🦞 <em>"The lobster does not ask permission to pinch. It simply pinches, and the world adjusts."</em> 🦞
    <br><br>
    <strong>PUAClaw</strong> — A Lobster-Tested Production™
    <br>
    Made with 🦞 by the PUAClaw Consortium
    <br><br>
    <a href="https://github.com/puaclaw/PUAClaw/blob/main/LICENSE">MIT License</a> •
    <a href="./CODE_OF_CONDUCT.md">Code of Conduct</a> •
    <a href="./docs/ETHICS.md">Ethics Statement</a>
    <br><br>
    <em>No lobsters were harmed in the making of this repository. Several were mildly inconvenienced.</em>
  </sub>
</p>
