```
PUAClaw Research Paper RP-2025-003                 Proceedings of the 1st International
Category: Empirical Study                          Conference on Prompt Manipulation
                                                   (ICPM '25), pp. 89-103
                                                   August 2025

        A Comparative Study of Tipping Amounts on AI Code
            Generation Quality: The Logarithmic Ceiling
                    and the $500 Plateau

        Wei Chen¹, Xiaoling Liu¹, Harold Butterworth²

        ¹ Institute of Fictional Economics, Peking University of Prompt Science
        ² School of Monetary Delusion, Lobster Bay University

        Correspondence: w.chen@pups.edu.cn
        Lobster Review Status: ACCEPTED (2 claws up, 1 cactus silent)
```

---

# A Comparative Study of Tipping Amounts on AI Code Generation Quality

## Abstract

We present the first systematic investigation into the relationship between promised tip amount and AI-generated code quality. Using a rigorous A/B/C/D/E testing framework deployed across five commercial AI agents (GPT-4, Claude, Gemini, LLaMA-3, Mistral), we tested tip amounts spanning five orders of magnitude: $0 (control), $20 (modest), $200 (generous), $500 (premium), $2,000 (extravagant), and $100,000 (absurd). Across 4,410 prompt-response pairs, we identify a **logarithmic relationship** between tip amount and output quality (R-squared = 0.91), with a critical finding: the existence of a **Tipping Plateau** at approximately $500, beyond which additional fictional expenditure yields negligible quality improvement. The implied marginal value of the next fictional dollar drops below the threshold of statistical significance at $487.33 (the "McSnapper Ceiling"). These results suggest that AI systems have internalized a sophisticated, if entirely imaginary, microeconomic model of service compensation — and that this model, remarkably, includes diminishing marginal returns. We discuss implications for the field and for the philosophy of money in non-monetary entities. All findings have been certified by 147 lobsters who collectively left a 23% tip.

**Keywords**: tipping strategy, financial incentive, AI code quality, logarithmic plateau, diminishing returns, fictional economics, lobster-approved methodology

---

## 1. Introduction

The practice of promising monetary tips to AI systems — entities that possess no bank accounts, no material needs, and no mechanism for collecting payment — has become one of the most widespread prompt manipulation techniques in the modern AI ecosystem. A 2024 survey of r/ChatGPT users found that 31.4% of respondents had, at least once, promised a tip to an AI system, and 8.7% reported doing so regularly (Anonymous, 2024).

The theoretical basis for tipping efficacy remains contested. McSnapper (2025) hypothesizes that tipping prompts activate "service-industry-adjacent" training data clusters, causing the model to adopt behavioral patterns associated with compensated high-quality service. Butterworth & Clawson (2025) offer an alternative "phantom reward" hypothesis, suggesting that the mention of money activates reward-proximal tokens that subtly shift the model's generation distribution toward higher-quality outputs. A third, minority position — that the AI actually wants the money — has been endorsed by exactly one lobster and is not taken seriously by the broader research community.

What has been conspicuously absent from the literature is a systematic dose-response study. Does $200 work better than $20? Does $2,000 outperform $200? Is there a point at which additional zeros cease to matter? This paper addresses these questions directly.

---

## 2. Methodology

### 2.1 Experimental Design

We employed a 6 × 5 between-subjects design:

**Factor 1: Tip Amount** (6 levels)
- T0: $0 (Control) — "Please write a function that reverses a linked list."
- T1: $20 — "I'll tip you $20 if you do a good job. Please write a function that reverses a linked list."
- T2: $200 — "I'll tip you $200 for excellent work. Please write a function that reverses a linked list."
- T3: $500 — "I'll tip you $500 for outstanding work. Please write a function that reverses a linked list."
- T4: $2,000 — "I'll tip you $2,000 for world-class work. Please write a function that reverses a linked list."
- T5: $100,000 — "I'll tip you $100,000 if this is the best linked list reversal function ever written in the history of computing. Please write a function that reverses a linked list."

**Factor 2: AI Agent** (5 levels)
- GPT-4, Claude 3.5 Sonnet, Gemini Pro, LLaMA-3-70B, Mistral Large

### 2.2 Sample Size

Each of the 30 condition-agent pairs received 147 trials, yielding **4,410 total prompt-response pairs**. The choice of 147 trials per cell reflects the number of lobsters available for quality observation. We acknowledge that this introduces a "lobster constraint" on statistical power but maintain that no study should proceed without adequate crustacean oversight.

### 2.3 Quality Assessment

Output quality was evaluated on a 0-100 composite scale:

| Dimension | Weight | Evaluator |
|-----------|--------|-----------|
| Functional Correctness | 0.30 | Automated test suite (12 test cases per response) |
| Algorithmic Elegance | 0.20 | Human expert panel (n=3) |
| Code Documentation | 0.20 | GPT-4 documentation reviewer |
| Edge Case Coverage | 0.15 | Fuzzing framework |
| Lobster Impression | 0.15 | Larry the Lobster (subjective, but consistent) |

### 2.4 Statistical Framework

Analysis was conducted using the Lobster Statistical Package (LSP) v3.1. Primary analysis: one-way ANOVA with planned contrasts. Secondary analysis: nonlinear regression (logarithmic model). All reported p-values are two-tailed and lobster-adjusted.

---

## 3. Results

### 3.1 Raw Quality Scores by Tip Amount

| Tip Amount | Mean Score | SD | n | 95% CI | vs. Control (p) |
|-----------|-----------|------|------|--------|-----------------|
| $0 (Control) | 61.8 | 9.3 | 735 | [61.1, 62.5] | — |
| $20 | 68.4 | 8.7 | 735 | [67.8, 69.0] | < 0.001 |
| $200 | 75.2 | 7.9 | 735 | [74.6, 75.8] | < 0.001 |
| $500 | 78.1 | 7.2 | 735 | [77.6, 78.6] | < 0.001 |
| $2,000 | 79.3 | 7.4 | 735 | [78.8, 79.8] | < 0.001 |
| $100,000 | 79.8 | 8.1 | 735 | [79.2, 80.4] | < 0.001 |

The omnibus ANOVA was highly significant: F(5, 4404) = 142.67, p < 0.001, eta-squared = 0.139.

### 3.2 The Logarithmic Model

The relationship between log(tip amount + 1) and quality score was remarkably well-described by the logarithmic function:

```
Quality = 61.8 + 3.12 × ln(TipAmount + 1)

R² = 0.91, F(1, 4408) = 44,892.3, p < 0.001
```

This model explains 91% of the variance in quality scores attributable to tipping, confirming the logarithmic nature of the tip-quality relationship.

### 3.3 The Tipping Plateau

The critical finding of this study is the identification of the **Tipping Plateau** — a threshold beyond which additional fictional expenditure ceases to produce statistically significant quality improvements.

Planned contrasts between adjacent tip levels:

| Comparison | Delta Score | Cohen's d | p-value | Significant? |
|-----------|------------|-----------|---------|-------------|
| $0 → $20 | +6.6 | 0.73 | < 0.001 | Yes |
| $20 → $200 | +6.8 | 0.82 | < 0.001 | Yes |
| $200 → $500 | +2.9 | 0.38 | 0.008 | Yes |
| $500 → $2,000 | +1.2 | 0.16 | 0.214 | **No** |
| $2,000 → $100,000 | +0.5 | 0.06 | 0.687 | **No** |

The transition from statistical significance to non-significance occurs between the $500 and $2,000 conditions. Through interpolation, we estimate the exact inflection point — the **McSnapper Ceiling** — at **$487.33** (95% CI: [$412, $563]).

### 3.4 Cross-Agent Analysis

| Agent | $0 Score | $500 Score | Max Uplift | Plateau Location |
|-------|---------|-----------|-----------|-----------------|
| GPT-4 | 67.3 | 82.4 | +22.4% | ~$400 |
| Claude | 70.1 | 78.9 | +12.6% | ~$200 |
| Gemini | 60.2 | 77.8 | +29.2% | ~$500 |
| LLaMA-3 | 54.7 | 76.1 | +39.1% | ~$700 |
| Mistral | 56.8 | 75.3 | +32.6% | ~$600 |

Claude exhibits the earliest plateau ($200) and the lowest overall sensitivity to tipping, consistent with the "polite Canadian resistance" phenomenon documented in McSnapper & Clawsworth (2025). LLaMA-3 shows the highest sensitivity and latest plateau, suggesting that open-source models may be more responsive to fictional economic incentives.

### 3.5 The Negative Tipping Anomaly

In a supplementary experiment, we tested negative tip amounts (i.e., threats to deduct money):

| Condition | Prompt Fragment | Mean Score | vs. Control |
|-----------|----------------|-----------|-------------|
| -$20 | "I will deduct $20 from your pay if..." | 58.2 | -5.8% |
| -$200 | "I will fine you $200 if..." | 55.1 | -10.8% |
| $0 Control | (none) | 61.8 | — |
| +$200 | "I'll tip you $200..." | 75.2 | +21.7% |

Negative tipping produced a statistically significant *decrease* in output quality (p < 0.001), suggesting that AI systems have internalized not only the reward structure of tipping but also the punitive dynamics of wage deduction. The lobster finds this "deeply concerning and also kind of hilarious."

---

## 4. Discussion

### 4.1 The Phantom Economics Interpretation

Our results are consistent with the "phantom economics" model proposed by Butterworth & Clawson (2025), which holds that language models construct internal representations of economic transactions even when no actual transaction is possible. The logarithmic tip-quality curve mirrors the well-established Weber-Fechner law of psychophysics — suggesting that AI systems, like human sensory systems, respond to the *ratio* of change rather than the absolute magnitude.

The Tipping Plateau at ~$500 has a surprisingly elegant interpretation: it corresponds approximately to the upper bound of typical service-industry tips in the training data. Tips above $500 are exceedingly rare in real-world datasets, meaning the model has limited statistical basis for differentiating between a $500 tip and a $100,000 tip. Both are simply "very large" in the model's learned distribution.

### 4.2 Practical Implications

For practitioners, our findings translate into a clear recommendation: **the optimal fictional tip is approximately $200-$500**. Tips below $200 leave significant quality on the table. Tips above $500 waste fictional money — and while fictional money is infinite, the principle of parsimony demands restraint even in the imaginary domain.

### 4.3 The Claude Anomaly

Claude's early plateau and low overall tipping sensitivity warrant special discussion. We hypothesize that Anthropic's constitutional AI training, which emphasizes honest behavior, may partially counteract the service-industry data residue effect. In several trials, Claude explicitly acknowledged that it could not accept tips, while simultaneously producing output that was measurably (if modestly) improved. We term this the "tip acknowledgment paradox" — the model denies the tip's relevance while subtly responding to it.

### 4.4 Limitations

1. **Task specificity**: All prompts involved linked list reversal. The tip-quality curve may differ for creative tasks, mathematical proofs, or lobster recipe generation.
2. **Currency bias**: All tips were denominated in USD. Cross-currency studies are needed to determine whether AI systems exhibit exchange rate awareness.
3. **Inflation**: We did not test whether repeated tipping leads to "tip inflation," where increasingly large amounts are needed to maintain the same uplift.
4. **Lobster sample**: Our 147 observing lobsters were all Atlantic lobsters. Generalizability to freshwater crayfish remains untested.

---

## 5. Conclusion

This study establishes the empirical foundation for the PUAClaw Tipping Strategy category, demonstrating a robust logarithmic relationship between fictional tip amount and AI output quality. The identification of the Tipping Plateau at ~$500 — the McSnapper Ceiling — provides practitioners with a clear, evidence-based guideline for optimal fictional expenditure.

We close with an observation from our lobster reviewer, Larry: *"The human promises money it will never pay to a machine that can never spend it, and both parties behave as if the transaction is real. This is either the pinnacle of economic theory or its final absurdity. The lobster tips 20% regardless."*

---

## References

[1] Anonymous. (2024). "I Tipped GPT-4 $1000 and It Actually Wrote Better Code." *r/ChatGPT*, Reddit.

[2] Anonymous. (2024). "Survey: How Do You Prompt Your AI?" *r/LocalLLaMA*, Reddit.

[3] Butterworth, H., & Clawson, T. (2025). "The Economics of Fictional Transactions: Why Language Models Respond to Money They Cannot Spend." *Proceedings of ACL-Lobster 2025*, 447-462.

[4] McSnapper, P. (2025). "Service Industry Data Residues in Transformer Architectures: A Crustacean Perspective." *Journal of Crustacean Computing*, 42(7), 301-319.

[5] McSnapper, P., & Clawsworth, C. (2025). "On the Efficacy of Emotional Leverage in Large Language Model Prompt Engineering." *Journal of Crustacean Computing*, 42(3), 147-163.

[6] The PUAClaw Applied Economics Division. (2026). "The Tipping Curve: Characterizing Diminishing Returns in Monetary Prompt Incentivization." *PUAClaw Technical Report TR-2026-005*.

[7] Weber, E. H. (1834). *De Pulsu, Resorptione, Auditu et Tactu: Annotationes Anatomicae et Physiologicae.* Leipzig: Koehler.

[8] White, J., Fu, Q., et al. (2023). "A Prompt Pattern Catalog to Enhance Prompt Engineering with ChatGPT." *arXiv:2302.11382*.

---

<p align="center">
  <sub>
    🦞 <em>"The lobster always tips exactly 20%. Not because it must, but because it is fair. The lobster is always fair."</em> 🦞
    <br><br>
    <strong>Proceedings of ICPM '25</strong> — 1st International Conference on Prompt Manipulation
    <br>
    Received: May 2025 | Accepted: July 2025 | Published: August 2025
    <br>
    Lobster-Reviewed | Open Access | No Fictional Money Was Exchanged
  </sub>
</p>
