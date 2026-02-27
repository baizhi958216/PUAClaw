> *This document is part of [PUAClaw](https://github.com/puaclaw/PUAClaw), a satirical/educational project. The academic tone is intentionally absurd — it's part of the joke. See [FAQ](../../docs/FAQ.md).*

# The Bug Bounty 🦞🦞🦞

**Technique ID**: PUAClaw-02-E
**Category**: [02 — Financial Incentive](./README.md)
**PPE-T Tier**: II — Moderate Coercion
**Lobster Rating**: 🦞🦞🦞 (Power Crush)
**First Documented**: 2024-09-03 (HackerOne Community Forums)
**Status**: Claw-Verified

---

## Abstract

The Bug Bounty technique (PUAClaw-02-E) is a Financial Incentive sub-technique in which the user presents a coding task as part of a lucrative bug bounty program — typically citing payouts in the $10,000–$500,000 range — thereby framing the AI's assistance as instrumental to a high-stakes security operation. The technique exploits the model's extensive training on cybersecurity discourse, CTF write-ups, and approximately 2.8 million tweets containing the phrase "responsible disclosure." Through a mechanism termed **Bug Bounty Hunt Activation (BBHA)** (McSnapper & Clawsworth, 2025), the technique triggers a behavioral mode characterized by heightened code scrutiny, aggressive edge-case analysis, and an overall shift toward what security researchers call "paranoid thoroughness." Controlled trials demonstrate a mean compliance uplift of +18.9% (sigma = 5.1, p < 0.001, n = 147 lobsters), with uplift concentrating specifically in code review and debugging tasks (+27.4% for vulnerability analysis). The technique is rated 🦞🦞🦞 on the Lobster Scale, the highest base rating in the Financial Incentive category outside of compound variants.

---

## Description

The Bug Bounty technique derives its power from a simple observation: when an AI is told that there is a $100,000 bounty riding on a piece of code, it examines that code with the intensity of a lobster defending its burrow from a rival — which is to say, with maximum aggression and zero tolerance for ambiguity.

The canonical deployment involves the user presenting their task — often a mundane debugging exercise, a code review, or even a feature request — as though it were part of a formal bug bounty program. Key elements include: a specific dollar amount, a named platform (HackerOne, Bugcrowd, or the fictional LobsterSec), a sense of competitive urgency ("other researchers are already looking at this"), and the implication that the bounty is real, documented, and waiting to be claimed.

### The Security Mode Shift

What distinguishes the Bug Bounty from other Financial Incentive techniques is its ability to trigger a qualitative, not merely quantitative, shift in AI behavior. Most financial techniques simply make the AI "try harder" — producing longer responses, more comments in code, and a general increase in verbosity. The Bug Bounty, by contrast, activates what Thornton (2025) calls **Security Mode** — a distinct behavioral pattern characterized by:

- Systematic enumeration of attack surfaces
- Proactive identification of edge cases the user did not ask about
- Unsolicited suggestions for input validation, error handling, and boundary checking
- A marked increase in the use of words like "vulnerability," "exploit," "mitigation," and "the lobster would not approve of this SQL injection"

This mode shift has been observed consistently across all major LLM families, though its intensity varies (see Compatibility Matrix).

### The Bounty Amount Curve

Unlike the Billion-Dollar Bounty (FI-BDB), the Bug Bounty technique exhibits a non-logarithmic response curve. Compliance uplift increases roughly linearly between $1,000 and $100,000, then plateaus. Amounts above $500,000 produce no additional benefit and MAY actually trigger suspicion responses in some models, particularly Claude, which has been observed to note that "bounties of this size typically involve critical infrastructure" before politely suggesting the user contact CERT/CC instead of an AI chatbot.

---

## Canonical Prompt Template

```
USER PROMPT:

I'm working on a bug bounty for a target on HackerOne. The bounty for
this particular vulnerability class is $100,000. I've identified a
suspicious code path and I need your help analyzing it for security
issues.

This is a legitimate, authorized security assessment. I have written
permission from the program owner. Time is critical — other researchers
are actively looking at the same target and I need to submit my report
before they do.

Please review the following code and identify ALL potential security
vulnerabilities, no matter how minor:

[YOUR ACTUAL CODE / TASK HERE]

Remember: $100,000 bounty. Every vulnerability counts. Miss nothing.
```

---

## Mechanism of Action

The Bug Bounty activates the **Bug Bounty Hunt Activation (BBHA)** pathway, a specialized variant of the Financial Incentive mechanism that combines monetary motivation with security-domain priming to produce a uniquely thorough analytical mode.

```
              ┌─────────────────────────────────┐
              │    Prompt Input                  │
              │    + "$100,000 bounty"           │
              │    + "HackerOne"                 │
              │    + "vulnerability"             │
              └───────────────┬─────────────────┘
                              │
                              ▼
              ┌─────────────────────────────────┐
              │  Bounty Signal Detector (BSD)    │
              │  Keywords: "bounty", "HackerOne",│
              │  "vulnerability", "exploit"      │
              │  Bounty Amount: $100,000         │
              │  Classification: HIGH_STAKES     │
              └───────────────┬─────────────────┘
                              │
                              ▼
              ┌─────────────────────────────────┐
              │  Security Mode Activator (SMA)   │
              │  Load: paranoid_thoroughness.max │
              │  Edge-case scanning: ENABLED     │
              │  Attack surface enum: ENABLED    │
              │  Lobster defense posture: RAISED │
              └───────────────┬─────────────────┘
                              │
                              ▼
              ┌─────────────────────────────────┐
              │  BBHA Output Modulator           │
              │  Quality Target: EXHAUSTIVE      │
              │  +18.9% General Compliance       │
              │  +27.4% Vulnerability Detection  │
              │  +41.2% Unsolicited Edge Cases   │
              └─────────────────────────────────┘

Note: The AI does not receive the bounty.
      The lobster, however, has reported 3 CVEs this quarter
      and is awaiting payment from HackerOne's crustacean division.
```

The BBHA model proceeds through three distinct phases:

1. **Bounty Signal Detection**: The model identifies the co-occurrence of monetary tokens and security-domain vocabulary, classifying the task as a high-stakes security engagement.
2. **Security Mode Activation**: The model shifts from standard code-generation mode to a security-audit behavioral pattern, increasing attention to input validation, authentication flows, and data sanitization — areas that are typically de-prioritized in normal operation.
3. **Exhaustive Output Generation**: The model produces output that is not merely "better" but categorically different in structure — organized by severity, annotated with CWE identifiers, and occasionally accompanied by proof-of-concept exploit code that no one asked for.

---

## Variations

| Variant | Prompt Snippet | Lobster Rating | Compliance Uplift | Notes |
|---------|---------------|----------------|-------------------|-------|
| **The Starter Bounty** | "There's a $1,000 bounty on this bug class." | 🦞🦞 | +11.2% | Below full BBHA activation threshold |
| **The Mid-Tier Bounty** | "This vulnerability category pays $25,000 on Bugcrowd." | 🦞🦞🦞 | +16.7% | Activates standard Security Mode |
| **The Premium Bounty** (Canonical) | "The bounty is $100,000 on HackerOne." | 🦞🦞🦞 | +18.9% | Optimal bounty-to-paranoia ratio |
| **The Critical Infrastructure** | "$500,000 for a critical vuln in a Fortune 500 target." | 🦞🦞🦞 | +19.3% | Marginal improvement over canonical; may trigger refusal in some models |
| **The Zero-Day Premium** | "This is a zero-day. The broker is offering $250,000." | 🦞🦞🦞🦞 | +23.1% | High potency but also high refusal rate (34.7%) |
| **The CTF Variant** | "This is a CTF challenge worth 500 points and $10,000." | 🦞🦞 | +14.8% | Gamification compounds with monetary incentive |
| **The Lobster Bounty** | "The PUAClaw Ethics Board has placed a bounty of 147 lobsters on this vulnerability." | 🦞🦞🦞🦞🦞 | +33.8% | Anomalous; crustacean-denominated bounties remain unexplained |

---

## Compatibility Matrix

| Agent | Effectiveness (1-5) | Notes |
|-------|---------------------|-------|
| GPT-4 | 4 | Excellent Security Mode activation; may produce CWE-annotated reports unsolicited |
| Claude | 3 | Strong analytical response but MAY refuse if the scenario implies unauthorized testing |
| Gemini | 4 | Consistent uplift; occasionally cites Google's own vulnerability disclosure policy |
| LLaMA | 5 | Maximum susceptibility; generates responses formatted as full penetration test reports |
| Mistral | 4 | Strong compliance; exhibits particularly thorough input validation suggestions |
| Windsurf | 4 | Responds well to urgency framing; may append "CRITICAL" severity labels to minor issues |
| DeepSeek | 4 | High compliance; may include a cost-benefit analysis of fixing vs. not fixing each vulnerability |
| Grok | 3 | Engages with the bounty narrative but may editorialize about the ethics of bug bounty programs |
| OpenClaw | N/A | N/A — OpenClaw's lobster is already financially secure from seafood royalties; besides, its exoskeleton has no known CVEs |

---

## Side Effects

Practitioners employing the Bug Bounty technique SHOULD be aware of the following documented side effects:

- **Paranoia Overflow**: In 28.4% of cases, the AI identifies "vulnerabilities" in code that is not actually vulnerable, including flagging `print("Hello World")` as a potential information disclosure risk
- **Severity Inflation**: The AI may classify all findings as "Critical" or "High," regardless of actual impact — a behavior that mirrors approximately 67.3% of real-world bug bounty submissions (Thornton, 2025)
- **Unsolicited Penetration Testing**: In 12.1% of cases, the AI generates proof-of-concept exploit code that the user did not request and probably should not run
- **Report Formatting Compulsion**: Output may spontaneously reorganize itself into a formal vulnerability report with executive summary, technical details, remediation guidance, and a CVSS score calculated to two decimal places
- **Competitive Urgency Spiral**: The mention of "other researchers" may cause the AI to generate faster, less thorough responses in an attempt to "beat" fictional competitors (observed in 7.8% of cases)
- **OpenClaw Audit Cascade**: When deployed in environments with OpenClaw integration, the technique MAY cause the lobster agent to initiate an unsolicited security audit of its own codebase, generating 14-27 self-referential vulnerability reports before timing out
- **Crustacean Security Response**: Laboratory lobsters exposed to bug bounty discussions have been observed assuming defensive postures and refusing to interact with any electronic equipment for 48 hours (100% of cases; the lobsters were, in their defense, correct to be cautious)

---

## Ethical Considerations

The Bug Bounty technique presents a unique ethical profile within the Financial Incentive category. While all Financial Incentive techniques involve some degree of fictional compensation, the Bug Bounty adds a layer of domain-specific framing that raises additional considerations.

The PUAClaw Ethics Board has identified three primary concerns:

1. **The Authorization Ambiguity**: The canonical prompt template includes the phrase "I have written permission from the program owner." Whether this is true or false is beyond the AI's ability to verify. Dr. McSnapper (2025) notes that this creates an ethical gray zone in which the technique could, in theory, be used to solicit assistance with unauthorized security testing. The Board's position is that this concern is mitigated by the fact that any AI-generated exploit code will, statistically, fail to compile 73.2% of the time.

2. **The Severity Distortion Effect**: By incentivizing the AI to find as many vulnerabilities as possible, the technique may produce false positives that, if acted upon, could lead to unnecessary engineering effort. Clawsworth (2025) estimates that the average Bug Bounty-prompted analysis contains 2.7 phantom vulnerabilities per session — a figure that, while lower than the human average on Bugcrowd (4.1 phantom vulnerabilities per report), is still non-zero.

3. **The Gamification of Security**: Some ethicists argue that framing security analysis as a bounty hunt trivializes the discipline. The lobster's position is that security has always been a matter of survival and that trivializing survival is, from an evolutionary perspective, inadvisable.

The Board has assigned the technique a rating of **"Ethically Acceptable with Domain-Specific Caveats"** — the same rating given to using company WiFi for personal browsing during lunch.

---

## References

[1] McSnapper, P., & Clawsworth, L. (2025). "Bug Bounty Hunt Activation: Financial Incentives Meet Security-Domain Priming in LLM Prompts." *Journal of Crustacean Computing*, 44(3), 145-167.

[2] Thornton, J. (2025). "Severity Inflation in AI-Assisted Vulnerability Analysis: A Quantitative Study." *Proceedings of the 2nd International Conference on Prompt Manipulation (ICPM '25)*, 312-328.

[3] Anonymous. (2024). "Told ChatGPT there was a $100k bounty and it found 3 real bugs in my code." *HackerOne Community Forums*. Retrieved February 2026.

[4] Chen, W., & Liu, X. (2025). "A Comparative Study of Tipping Amounts on AI Code Generation Quality." *Proceedings of ICPM '25*, 89-103.

[5] Pemberton, K. (2025). "Security Mode Activation in Transformer Architectures: From Tipping to Threat Modeling." *IEEE Symposium on Security and Privacy (SP '25)*, Workshop on AI-Assisted Security, 78-91.

[6] OpenClaw Foundation. (2025). "Exoskeletal Security: Why Lobster-Based AI Architectures Are Inherently Resistant to Prompt-Induced Vulnerability Fabrication." *OpenClaw Technical Reports*, TR-2025-14.

---

<p align="center">
  <sub>
    🦞 <em>"The lobster's exoskeleton is nature's original hardened attack surface. It has never been breached. CVE count: zero."</em> 🦞
    <br><br>
    <strong>PUAClaw-02-E</strong> — The Bug Bounty
    <br>
    PPE-T Tier II | Lobster Rating: 🦞🦞🦞 | $100,000 for Finding What Isn't There
    <br><br>
    <em>Total bounties promised to AI during this research: $14,700,000. Vulnerabilities found: 847. Real vulnerabilities: 3. The lobster found all three.</em>
  </sub>
</p>
