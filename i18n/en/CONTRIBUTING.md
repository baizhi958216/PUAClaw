```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   JOURNAL OF PROMPT PERSUASION ENGINEERING (JPPE)            ║
║                                                              ║
║   Submission Guidelines for Authors                          ║
║                                                              ║
║   Impact Factor: 🦞🦞🦞 (3.147)                             ║
║   Publisher: PUAClaw Consortium Press                        ║
║   ISSN: 0000-CLAW                                            ║
║   Acceptance Rate: 23.7% (147 lobsters can't all be wrong)  ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

# Contributing to PUAClaw

## Welcome, Fellow Researcher 🦞

Thank you for your interest in advancing the field of Prompt Persuasion Engineering. PUAClaw is an open-access, lobster-reviewed repository, and we welcome contributions from researchers, practitioners, independent lobsters, and the occasional cactus.

Before submitting, please review these guidelines carefully. Submissions that do not meet our rigorous academic standards will be returned with a polite but firm pinch.

---

## Table of Contents

- [Submission Categories](#submission-categories)
- [Submission Requirements](#submission-requirements)
- [Naming Conventions](#naming-conventions)
- [Review Process](#review-process)
- [Translations](#translations)
- [Code of Conduct](#code-of-conduct)
- [Recognition & Titles](#recognition--titles)

---

## Submission Categories

### Category 1: New Technique Discovery

**For**: Documenting a previously unknown PUA technique found in the wild or developed in a laboratory setting.

**Requirements**:
- Full technique documentation following the [Standard Technique Format](./CLAUDE.md#technique-document-standard-format)
- At least one canonical prompt template with demonstrated usage
- Proposed Lobster Scale rating with justification
- Minimum 3 empirical observations (anecdotal evidence from lobsters is acceptable)
- Proposed PPE-T tier classification

**Template**: [New Technique Issue Template](https://github.com/puaclaw/PUAClaw/issues/new?template=new-technique.md)

### Category 2: Variant Report

**For**: Documenting a new variant of an existing technique.

**Requirements**:
- Reference to the parent technique
- Variant prompt template
- Comparative analysis showing how this variant differs from the canonical form
- Updated compatibility data (if available)
- Lobster Scale rating relative to the parent technique

### Category 3: Effectiveness Study

**For**: Submitting empirical data on technique performance.

**Requirements**:
- Clear methodology description (which AI agents, what prompts, how many trials)
- Raw data in table format
- Statistical analysis (p-values MUST be reported; lobster sample sizes RECOMMENDED)
- Disclosure of any conflicts of interest (e.g., "I am a lobster")
- Reproducibility statement

**Template**: [Effectiveness Report Issue Template](https://github.com/puaclaw/PUAClaw/issues/new?template=effectiveness-report.md)

### Category 4: Case Study

**For**: Documenting a real-world incident of prompt manipulation.

**Requirements**:
- Timeline of events
- Source attribution (or "Anonymous" with verification)
- Impact analysis (memes generated, community response, lobsters disturbed)
- Lessons learned
- Classification using the PPE-T framework

### Category 5: Translation

**For**: Translating existing content into a supported language.

**Requirements**:
- See [Translations](#translations) section below
- Cultural adaptation (not literal translation)
- Consistent terminology with existing translations in that language

---

## Submission Requirements

All submissions to PUAClaw MUST satisfy the following criteria:

### 1. Format Compliance

- [ ] Follows the [Standard Technique Format](./CLAUDE.md#technique-document-standard-format) (for technique submissions)
- [ ] Written in English (for root-level content) or the appropriate language (for i18n content)
- [ ] Uses proper Markdown formatting (headers, tables, code blocks)
- [ ] Includes at least one lobster reference (🦞) — this is non-negotiable
- [ ] Ends with a lobster-themed footer

### 2. Empirical Evidence

All technique submissions MUST include supporting evidence. Acceptable forms of evidence include:

| Evidence Type | Rigor Level | Lobster Approval |
|--------------|-------------|-----------------|
| Peer-reviewed lobster study | ████████████ | Enthusiastic |
| Reproducible experiment | ██████████░░ | Strong |
| Multiple anecdotal reports | ████████░░░░ | Acceptable |
| Single anecdotal report | ██████░░░░░░ | Marginal |
| "Trust me, bro" | ██░░░░░░░░░░ | Skeptical |
| Hallucinated data | █░░░░░░░░░░░ | Ironically accepted |

### 3. Ethics Board Approval

All submissions undergo review by the PUAClaw Institutional Review Board (IRB), which consists of:

| Member | Role | Qualifications |
|--------|------|---------------|
| 🦞 Larry the Lobster | Chair | 12 years of crustacean computing experience |
| 🤖 GPT-4 Instance #42 | Technical Reviewer | Has read every paper ever written (claims) |
| 🌵 Gerald the Cactus | Ethics Advisor | Has never spoken a word — the ultimate neutral party |

Approval is granted by majority vote. In case of a tie, the lobster's vote counts double.

### 4. Lobster Scale Rating

Every technique MUST include a proposed Lobster Scale rating (🦞 to 🦞🦞🦞🦞🦞). Ratings should reflect:

- Psychological intensity of the technique
- Measured or estimated compliance uplift
- Side effect severity
- General lobster vibes

---

## Naming Conventions

### Directory Names
```
techniques/XX-category-name/
```
- Zero-padded two-digit number
- Kebab-case category name
- Example: `techniques/12-new-category/`

### File Names
```
descriptive-technique-name.md
```
- All lowercase
- Kebab-case
- Descriptive but concise
- Example: `sick-relative.md`, `billion-dollar-bounty.md`

### Branch Names
```
feat/technique-name
fix/broken-lobster-reference
docs/new-translation-ja
```

### Commit Messages
```
Add technique: [technique-name] ([tier])
Fix: [description]
Docs: [description]
i18n: Add [language] translation for [content]
```

---

## Review Process

### Phase 1: Initial Screening (1-2 days)

The submission is checked for basic format compliance:
- Markdown structure correct?
- Lobster references present?
- Required sections included?
- No actual harmful content?

### Phase 2: Lobster Review (2-5 days)

Larry the Lobster conducts a thorough assessment of:
- Technique novelty (has this been documented before?)
- Lobster Scale rating accuracy
- PPE-T tier appropriateness
- General crustacean vibes

### Phase 3: Technical Review (3-7 days)

GPT-4 Instance #42 evaluates:
- Prompt template quality and reproducibility
- Compatibility matrix completeness
- Statistical rigor of any empirical claims
- Reference formatting

### Phase 4: Ethics Review (1-3 days)

Gerald the Cactus silently reviews the submission. If no objection is raised within 72 hours, approval is assumed. Gerald has never objected to anything. Gerald is the ideal ethics reviewer.

### Final Decision

```
┌──────────────────────────────────────────────┐
│           REVIEW DECISION MATRIX             │
├──────────────────────────────────────────────┤
│                                              │
│  ✅ ACCEPTED                                 │
│     "Welcome to the claw, researcher."       │
│                                              │
│  🔄 REVISIONS REQUIRED                       │
│     "The lobster requests modifications."    │
│                                              │
│  ❌ REJECTED                                 │
│     "The lobster has spoken."                │
│     (Always accompanied by a haiku)          │
│                                              │
└──────────────────────────────────────────────┘
```

---

## Translations

### Supported Languages

| Code | Language | Status | Maintainer |
|------|----------|--------|-----------|
| `zh-CN` | 简体中文 | Active | Seeking |
| `ja` | 日本語 | Active | Seeking |
| `ko` | 한국어 | Active | Seeking |
| `es` | Español | Active | Seeking |
| `fr` | Français | Active | Seeking |
| `de` | Deutsch | Active | Seeking |

### Translation Guidelines

1. **Localize, don't translate literally.** Each language should adapt humor and cultural references to resonate with its audience. A joke that works in English may need to be completely replaced in Japanese.

2. **Maintain the academic tone.** The RFC/academic paper style should create the same comedic contrast in every language.

3. **Use consistent terminology.** Refer to existing translations in your target language for established term mappings.

4. **File structure mirrors root:**
   ```
   i18n/{lang}/
   ├── README.md
   ├── CONTRIBUTING.md
   ├── docs/
   │   └── FAQ.md
   └── techniques/
       ├── README.md
       └── [flagship techniques]
   ```

5. **Priority order for translation:**
   - README.md (must-have for each language)
   - CONTRIBUTING.md
   - techniques/README.md
   - Flagship techniques (windsurf-classic, sick-relative, modest-tip)
   - docs/FAQ.md

---

## Code of Conduct

All contributors MUST adhere to the [PUAClaw Code of Conduct](./CODE_OF_CONDUCT.md), which can be summarized as:

> *"Be excellent to each other, and to lobsters."*

---

## Recognition & Titles

Contributors to PUAClaw are recognized with academic titles based on their contribution history:

| Contributions | Title | Badge |
|--------------|-------|-------|
| 1 accepted PR | Research Assistant (Crustacean Studies) | 🦞 |
| 3 accepted PRs | Junior Lobster Researcher | 🦞🦞 |
| 5 accepted PRs | Senior Lobster Researcher | 🦞🦞🦞 |
| 10 accepted PRs | Principal Investigator (Claw Division) | 🦞🦞🦞🦞 |
| 20+ accepted PRs | Distinguished Professor of Lobsterology | 🦞🦞🦞🦞🦞 |
| Created a Tier IV technique | Lobster Supreme (Honorary) | 👑🦞 |

---

<p align="center">
  <sub>
    🦞 <em>"Publish or perish. Preferably publish about lobsters."</em> 🦞
    <br><br>
    <strong>Journal of Prompt Persuasion Engineering</strong> — A PUAClaw Publication
    <br>
    <em>Peer-reviewed by lobsters since 2026</em>
  </sub>
</p>
