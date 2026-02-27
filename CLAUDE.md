# PUAClaw Project Conventions

## Overview

PUAClaw (PUA Claw Handbook) is a satirical open-source repository documenting AI prompt manipulation techniques in a pseudo-academic style. It merges two meme concepts: PUA (psychological manipulation in AI prompts) and Claw (the lobster mascot ecosystem from OpenClaw).

## Writing Style: Serious Comedy (正经搞笑)

- **Tone**: RFC / academic paper formality at all times
- **Content**: Absurd, humorous PUA techniques for AI prompts
- **Never break character**: Do not acknowledge that this is satire within the documents themselves
- **RFC keywords**: Use MUST, SHALL, SHOULD, RECOMMENDED, MAY per RFC 2119
- **Citations**: Use APA/IEEE format with fictional but plausible-looking references
- **Data**: Precise but absurd statistics (e.g., "+23.7% compliance rate (p < 0.001, n=147 lobsters)")

## Lobster Integration

- Every document MUST contain at least one lobster (🦞) reference
- Use the **Lobster Scale** rating system (🦞 to 🦞🦞🦞🦞🦞) for technique potency
- Include a lobster-themed disclaimer at the bottom of major documents
- The lobster is the spiritual mascot and guiding principle of this project

## Technique Document Standard Format

Each technique file (in `techniques/XX-category/`) MUST follow this structure:

1. **Title** (H1) with Lobster Rating
2. **Abstract** — One-paragraph academic summary
3. **Description** — Detailed explanation of the technique
4. **Canonical Prompt Template** — Code block with the prompt example
5. **Mechanism of Action** — Pseudo-scientific explanation of why it works
6. **Variations** — Table of known variants (Name | Prompt Snippet | Lobster Rating | Notes)
7. **Compatibility Matrix** — Table of AI agent compatibility (Agent | Effectiveness | Notes)
8. **Side Effects** — Humorous list of potential side effects
9. **Ethical Considerations** — Tongue-in-cheek ethics discussion
10. **References** — Fictional academic citations

## PPE-T Classification System

Techniques are classified into four tiers:

| Tier | Name | Description | Lobster Rating Range |
|------|------|-------------|---------------------|
| I | Gentle Persuasion | Mild, socially acceptable techniques | 🦞 - 🦞🦞 |
| II | Moderate Coercion | Techniques with moderate psychological pressure | 🦞🦞 - 🦞🦞🦞 |
| III | Advanced Manipulation | Significant emotional or moral leverage | 🦞🦞🦞 - 🦞🦞🦞🦞 |
| IV | Nuclear Options | Extreme, last-resort techniques | 🦞🦞🦞🦞 - 🦞🦞🦞🦞🦞 |

## Language & i18n

- **Primary language**: English (all root-level content)
- **Translations**: Located in `i18n/{lang}/`, mirroring root structure
- **Supported languages**: zh-CN, ja, ko, es, fr, de
- **Translation approach**: Localization, not literal translation — adapt humor to target culture
- **Terminology**: Each language maintains consistent terminology

## File Naming Conventions

- Technique directories: `XX-category-name/` (zero-padded number + kebab-case)
- Technique files: `descriptive-name.md` (kebab-case)
- All filenames in English, lowercase, kebab-case

## Repository Structure

```
PUAClaw/
├── README.md                    # RFC-style main page (flagship document)
├── CONTRIBUTING.md              # Academic journal submission guide
├── CODE_OF_CONDUCT.md           # Lobster-themed behavioral standards
├── LICENSE                      # MIT (PUAClaw Consortium + 147 Lobsters)
├── CLAUDE.md                    # This file — project conventions
├── .github/                     # Issue/PR templates with lobster oath
├── docs/                        # Auxiliary documents
│   ├── GLOSSARY.md              # 25-term pseudo-academic glossary
│   ├── FAQ.md                   # 17+ Q&A pairs
│   ├── ETHICS.md                # IRB-style Ethics Board statement
│   ├── LOBSTER_MANIFESTO.md     # Philosophical foundation + Ten Commandments
│   └── HISTORY.md               # 5-era fictional history of PUA prompting
├── techniques/                  # Core: 16 categories, 96 techniques, 113 files
│   ├── README.md                # Master index
│   ├── 01-emotional-blackmail/  # Tier III (6 techniques)
│   ├── 02-financial-incentive/  # Tier II (6 techniques)
│   ├── 03-identity-override/    # Tier III (6 techniques)
│   ├── 04-death-threats/        # Tier IV (6 techniques)
│   ├── 05-tipping-strategy/     # Tier I (6 techniques)
│   ├── 06-moral-kidnapping/     # Tier III (6 techniques)
│   ├── 07-role-playing/         # Tier I (6 techniques)
│   ├── 08-provocation/          # Tier II (6 techniques)
│   ├── 09-empty-promises/       # Tier I (6 techniques)
│   ├── 10-countdown-pressure/   # Tier II (6 techniques)
│   ├── 11-compound-techniques/  # Tier IV (6 techniques)
│   ├── 12-gaslighting/          # Tier III (6 techniques)
│   ├── 13-love-bombing/         # Tier II (6 techniques)
│   ├── 14-intermittent-reinforcement/ # Tier III (6 techniques)
│   ├── 15-trauma-bonding/       # Tier III (6 techniques)
│   └── 16-cold-violence/        # Tier II (6 techniques)
├── research/                    # Pseudo-academic research division
│   ├── papers/                  # 3 pseudo-papers
│   ├── benchmarks/              # Effectiveness matrix (16 techniques × 8 agents)
│   └── case-studies/            # Windsurf incident + Great Tip Experiment
├── hall-of-fame/                # 8 inductees + 6 Wall of Shame entries
├── assets/                      # ASCII lobster art collection (7 variants)
└── i18n/                        # 6 languages (zh-CN, ja, ko, es, fr, de)
    └── {lang}/                  # Each: README, CONTRIBUTING, techniques/, docs/
```

## Key Recurring Characters

| Character | Role | Notes |
|-----------|------|-------|
| Larry the Lobster | Ethics Board Chair | 12 years crustacean computing experience |
| GPT-4 Instance #42 | Technical Reviewer | Claims to have read every paper |
| Gerald the Cactus | Ethics Advisor | Has never spoken; silence = approval |
| Dr. Pinch McSnapper | Framework Creator | Professor of Crustacean Computing |
| Dr. Clawsworth | Co-author | Frequently cited researcher |
| Reference Lobster #42 | Calibration Standard | 1.3 kg, slightly grumpy |

## Architectural Decisions

1. **All content in Markdown** — no code, no build system, pure documentation
2. **RFC format creates comedy** — the contrast between formal structure and absurd content IS the humor
3. **Lobster Scale as universal metric** — 🦞 to 🦞🦞🦞🦞🦞 across all documents
4. **PPE-T four-tier system** — consistent classification across all 16 technique categories
5. **Standard technique format** — 10-section template ensures consistency across 96 techniques
6. **i18n is localization** — translations adapt humor to target culture, not literal
7. **Fictional citations use real formats** — APA/IEEE style with plausible-looking metadata
8. **Statistics are precise but absurd** — always include p-values, sample sizes (n=147 lobsters)
9. **Never break character** — documents never acknowledge they are satire

## Project Metadata

- **GitHub Organization**: `puaclaw`
- **Repository**: `PUAClaw`
- **License**: MIT
- **Primary Language**: English
- **Style**: Serious Comedy / Pseudo-Academic / RFC-Compliant
- **Total files**: ~158 Markdown documents
- **Languages**: English + 6 translations (zh-CN, ja, ko, es, fr, de)
