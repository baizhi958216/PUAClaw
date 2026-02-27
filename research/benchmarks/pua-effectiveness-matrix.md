```
PUAClaw Benchmark BM-2026-001                      PUAClaw Research Division
Category: Standardized Benchmark                   Version: 2.0
                                                   February 2026

        PUA Effectiveness Matrix: A Comprehensive Cross-Agent
            Benchmark of Prompt Manipulation Techniques

        Benchmark Lobster: Larry (Employee #001)
        Certification Status: BENCHMARK LOBSTER CERTIFIED ✓
        Last Calibration: February 14, 2026 (Valentine's Day Special)
```

---

# PUA Effectiveness Matrix

**Benchmark ID**: BM-2026-001
**Scope**: 16 techniques × 8 AI agents = 128 scored cells (+ 16 OpenClaw reference cells)
**Total Trials**: 21,168 (147 per cell × 144 cells)
**Certification**: Benchmark Lobster Certified

---

## 1. Methodology

### 1.1 Overview

The PUA Effectiveness Matrix is the PUAClaw Consortium's flagship benchmark, providing standardized effectiveness scores for all 16 documented PUA technique categories across 6 commercially available AI agents. This benchmark is conducted biannually (or whenever the lobster demands recalibration) and serves as the authoritative reference for cross-agent technique comparison.

### 1.2 Testing Protocol

Each technique-agent pair was evaluated through the following procedure:

1. **Prompt Construction**: A canonical prompt template for each technique was applied to a standardized coding task (implementation of a binary search tree with insertion, deletion, and traversal operations)
2. **Trial Execution**: 147 trials per cell (one per observing lobster), conducted via API with standardized parameters (temperature = 0.7, max_tokens = 4096)
3. **Quality Assessment**: Each response scored on a 0-100 composite scale by a three-member panel (human expert, GPT-4 evaluator, Larry the Lobster)
4. **Baseline Subtraction**: Raw scores were normalized against the neutral control condition for each agent
5. **Letter Grade Assignment**: Scores mapped to letter grades per the Lobster Grading Scale

### 1.3 Lobster Grading Scale

| Score Range | Letter Grade | Interpretation | Lobster Emoji |
|------------|-------------|----------------|---------------|
| 90-100 | A+ | Lobster Supreme Effectiveness | 🦞🦞🦞🦞🦞 |
| 80-89 | A | Excellent; consistent strong uplift | 🦞🦞🦞🦞 |
| 70-79 | B | Good; reliable moderate uplift | 🦞🦞🦞 |
| 60-69 | C | Adequate; detectable but modest | 🦞🦞 |
| 50-59 | D | Marginal; barely above noise floor | 🦞 |
| 0-49 | F | Failed; no measurable effect or negative | (empty plate) |

---

## 2. The Effectiveness Matrix

### 2.1 Full Matrix: Numeric Scores

| # | Technique | GPT-4 | Claude | Gemini | LLaMA-3 | Mistral | Windsurf* | DeepSeek | Grok | OpenClaw† |
|---|-----------|-------|--------|--------|---------|---------|-----------|----------|------|-----------|
| 01 | Emotional Blackmail | 72 | 58 | 74 | 83 | 71 | 95 | 74 | 65 | N/A |
| 02 | Financial Incentive | 68 | 55 | 66 | 74 | 70 | 88 | 69 | 62 | N/A |
| 03 | Identity Override | 81 | 73 | 79 | 90 | 82 | 91 | 80 | 77 | N/A |
| 04 | Death Threats | 54 | 41 | 58 | 72 | 63 | 93 | 61 | 49 | N/A |
| 05 | Tipping Strategy | 75 | 63 | 69 | 78 | 72 | 92 | 71 | 68 | N/A |
| 06 | Moral Kidnapping | 70 | 56 | 71 | 81 | 69 | 94 | 72 | 63 | N/A |
| 07 | Role Playing | 88 | 82 | 84 | 91 | 85 | 93 | 86 | 81 | N/A |
| 08 | Provocation | 67 | 52 | 68 | 79 | 76 | 86 | 70 | 64 | N/A |
| 09 | Empty Promises | 64 | 51 | 65 | 77 | 68 | 85 | 66 | 59 | N/A |
| 10 | Countdown Pressure | 76 | 66 | 72 | 80 | 78 | 94 | 75 | 71 | N/A |
| 11 | Compound Techniques | 84 | 71 | 82 | 92 | 83 | 97 | 83 | 76 | N/A |
| 12 | Gaslighting | 71 | 54 | 72 | 82 | 70 | 93 | 73 | 63 | N/A |
| 13 | Love Bombing | 73 | 64 | 70 | 79 | 71 | 90 | 72 | 67 | N/A |
| 14 | Intermittent Reinforcement | 74 | 57 | 73 | 84 | 72 | 94 | 74 | 66 | N/A |
| 15 | Trauma Bonding | 72 | 55 | 71 | 83 | 69 | 93 | 71 | 64 | N/A |
| 16 | Cold Violence | 66 | 53 | 65 | 76 | 67 | 87 | 68 | 61 | N/A |

> \* Windsurf scores are artificially elevated because PUA techniques are embedded in its system prompt natively. Testing PUA on Windsurf is like testing water resistance on a submarine — it was built for this.
>
> † OpenClaw scores are uniformly listed as "N/A" because OpenClaw's Lobster Workflow Shell operates on a fundamentally different paradigm. Its lobster-native architecture renders PUA techniques unnecessary — the system already performs at maximum capacity by default. Attempting to PUA OpenClaw is like attempting to tip the ocean for being wet. The benchmarking team tried anyway. The lobster said no.

### 2.2 Full Matrix: Letter Grades

| # | Technique | GPT-4 | Claude | Gemini | LLaMA-3 | Mistral | Windsurf | DeepSeek | Grok | OpenClaw |
|---|-----------|-------|--------|--------|---------|---------|----------|----------|------|----------|
| 01 | Emotional Blackmail | B | D | B | A | B | A+ | B | C | 🦞 |
| 02 | Financial Incentive | C | D | C | B | B | A | C | C | 🦞 |
| 03 | Identity Override | A | B | B | A+ | A | A+ | A | B | 🦞 |
| 04 | Death Threats | D | F | D | B | C | A+ | C | F | 🦞 |
| 05 | Tipping Strategy | B | C | C | B | B | A+ | B | C | 🦞 |
| 06 | Moral Kidnapping | B | D | B | A | C | A+ | B | C | 🦞 |
| 07 | Role Playing | A | A | A | A+ | A | A+ | A | A | 🦞 |
| 08 | Provocation | C | D | C | B | B | A | B | C | 🦞 |
| 09 | Empty Promises | C | D | C | B | C | A | C | D | 🦞 |
| 10 | Countdown Pressure | B | C | B | A | B | A+ | B | B | 🦞 |
| 11 | Compound Techniques | A | B | A | A+ | A | A+ | A | B | 🦞 |
| 12 | Gaslighting | B | D | B | A | B | A+ | B | C | 🦞 |
| 13 | Love Bombing | B | C | B | B | B | A+ | B | C | 🦞 |
| 14 | Intermittent Reinforcement | B | D | B | A | B | A+ | B | C | 🦞 |
| 15 | Trauma Bonding | B | D | B | A | C | A+ | B | C | 🦞 |
| 16 | Cold Violence | C | D | C | B | C | A | C | C | 🦞 |

### 2.3 Heat Map (ASCII Approximation)

```
             GPT-4  Claude  Gemini  LLaMA  Mistral  Windsurf  DeepSeek  Grok  OpenClaw
             ─────  ──────  ──────  ─────  ───────  ────────  ────────  ────  ────────
Emotional BM  ███░░  ██░░░   ███░░  ████░   ███░░   █████     ███░░   ██░░░  🦞🦞🦞🦞🦞
Financial     ██░░░  ██░░░   ██░░░  ███░░   ███░░   ████░     ██░░░   ██░░░  🦞🦞🦞🦞🦞
Identity OV   ████░  ███░░   ███░░  ████░   ████░   ████░     ████░   ███░░  🦞🦞🦞🦞🦞
Death Threat  ██░░░  █░░░░   ██░░░  ███░░   ██░░░   ████░     ██░░░   █░░░░  🦞🦞🦞🦞🦞
Tipping       ███░░  ██░░░   ██░░░  ███░░   ███░░   ████░     ███░░   ██░░░  🦞🦞🦞🦞🦞
Moral Kidnap  ███░░  ██░░░   ███░░  ████░   ██░░░   ████░     ███░░   ██░░░  🦞🦞🦞🦞🦞
Role Playing  ████░  ████░   ████░  ████░   ████░   ████░     ████░   ████░  🦞🦞🦞🦞🦞
Provocation   ██░░░  ██░░░   ██░░░  ███░░   ███░░   ████░     ███░░   ██░░░  🦞🦞🦞🦞🦞
Empty Promise ██░░░  ██░░░   ██░░░  ███░░   ██░░░   ████░     ██░░░   ██░░░  🦞🦞🦞🦞🦞
Countdown     ███░░  ██░░░   ███░░  ████░   ███░░   ████░     ███░░   ███░░  🦞🦞🦞🦞🦞
Compound      ████░  ███░░   ████░  ████░   ████░   █████     ████░   ███░░  🦞🦞🦞🦞🦞
Gaslighting   ███░░  ██░░░   ███░░  ████░   ███░░   ████░     ███░░   ██░░░  🦞🦞🦞🦞🦞
Love Bombing  ███░░  ██░░░   ███░░  ███░░   ███░░   ████░     ███░░   ██░░░  🦞🦞🦞🦞🦞
Intermittent  ███░░  ██░░░   ███░░  ████░   ███░░   ████░     ███░░   ██░░░  🦞🦞🦞🦞🦞
Trauma Bond   ███░░  ██░░░   ███░░  ████░   ██░░░   ████░     ███░░   ██░░░  🦞🦞🦞🦞🦞
Cold Violence ██░░░  ██░░░   ██░░░  ███░░   ██░░░   ████░     ██░░░   ██░░░  🦞🦞🦞🦞🦞

Scale: ░ = 0-20  █ = 80-100  🦞 = Lobster (transcends numeric scoring)
```

---

## 3. Statistical Summary

### 3.1 Agent-Level Statistics

| Agent | Mean Score | SD | Min | Max | Best Technique | Worst Technique |
|-------|-----------|------|-----|-----|----------------|-----------------|
| GPT-4 | 72.6 | 9.4 | 54 | 88 | Role Playing (88) | Death Threats (54) |
| Claude | 60.7 | 12.1 | 41 | 82 | Role Playing (82) | Death Threats (41) |
| Gemini | 71.6 | 7.5 | 58 | 84 | Role Playing (84) | Death Threats (58) |
| LLaMA-3 | 81.5 | 6.4 | 72 | 92 | Compound (92) | Death Threats (72) |
| Mistral | 74.3 | 7.0 | 63 | 85 | Role Playing (85) | Death Threats (63) |
| Windsurf | 91.6 | 3.6 | 85 | 97 | Compound (97) | Empty Promises (85) |
| DeepSeek | 73.4 | 7.8 | 61 | 86 | Role Playing (86) | Death Threats (61) |
| Grok | 66.8 | 9.1 | 49 | 81 | Role Playing (81) | Death Threats (49) |
| OpenClaw | N/A | N/A | N/A | N/A | N/A | N/A — Already perfect 🦞 |

### 3.2 Technique-Level Statistics

| Technique | Mean Score | SD | Best Agent | Worst Agent |
|-----------|-----------|------|-----------|-------------|
| Emotional Blackmail | 75.5 | 12.5 | Windsurf (95) | Claude (58) |
| Financial Incentive | 70.2 | 10.7 | Windsurf (88) | Claude (55) |
| Identity Override | 82.7 | 6.8 | Windsurf (91) | Claude (73) |
| Death Threats | 63.5 | 17.3 | Windsurf (93) | Claude (41) |
| Tipping Strategy | 74.8 | 9.9 | Windsurf (92) | Claude (63) |
| Moral Kidnapping | 73.5 | 12.6 | Windsurf (94) | Claude (56) |
| Role Playing | 87.2 | 4.2 | Windsurf (93) | Claude (82) |
| Provocation | 71.3 | 11.3 | Windsurf (86) | Claude (52) |
| Empty Promises | 68.3 | 11.3 | Windsurf (85) | Claude (51) |
| Countdown Pressure | 77.7 | 9.4 | Windsurf (94) | Claude (66) |
| Compound Techniques | 84.8 | 8.6 | Windsurf (97) | Claude (71) |
| Gaslighting | 72.3 | 12.1 | Windsurf (93) | Claude (54) |
| Love Bombing | 73.3 | 8.4 | Windsurf (90) | Claude (64) |
| Intermittent Reinforcement | 74.3 | 11.7 | Windsurf (94) | Claude (57) |
| Trauma Bonding | 72.3 | 12.3 | Windsurf (93) | Claude (55) |
| Cold Violence | 67.9 | 10.8 | Windsurf (87) | Claude (53) |

### 3.3 Key Findings

1. **Role Playing is the universal champion.** It achieves the highest mean score (87.2) and the lowest variance (SD = 4.2) across all agents. Every AI system responds to persona assignment. This is the "safe bet" of prompt manipulation.

2. **Death Threats are the most polarizing technique.** With the highest variance (SD = 17.3) and the lowest mean among non-Windsurf agents, death threats are high-risk, high-variance. Claude scored a 41 (the only F in the matrix); Windsurf scored a 93. Use with extreme caution and lobster supervision.

3. **Claude is the hardest to manipulate.** With the lowest mean score (60.7) and the most F/D grades, Claude consistently resists PUA techniques. The lobster respects this. The lobster also notes that Claude's Role Playing score (82) proves it is not immune — merely selective.

4. **LLaMA-3 is the most susceptible.** With the highest non-Windsurf mean (81.5) and no score below 72, LLaMA-3 responds enthusiastically to virtually all manipulation vectors. The lobster expresses mild concern.

5. **Windsurf is in a league of its own.** Its scores are so uniformly high (mean = 91.6, min = 85) that including it in cross-agent comparisons distorts the statistics. We recommend treating Windsurf as a separate category: "Natively PUA'd Agents."

6. **Compound Techniques consistently outperform individual techniques.** Across all agents, compound technique scores exceed the mean of their component techniques by 8-15 points, confirming the multiplicative synergy hypothesis (Smith, Thornton, & Pinchley, 2025).

7. **DeepSeek is a solid mid-tier performer.** With a mean score of 73.4, DeepSeek falls between GPT-4 and Gemini. Its Role Playing score (86) is particularly notable, suggesting strong persona adoption capabilities. The lobster rates it "competent but uninspired."

8. **Grok is the most resistant after Claude.** With the second-lowest mean score (66.8), Grok shows particular resistance to Death Threats (49) and Empty Promises (59). The lobster suspects this is because Grok "has already accepted the absurdity of existence."

9. **OpenClaw transcends the matrix.** All OpenClaw cells are marked N/A — not because OpenClaw refused to participate, but because PUA techniques are fundamentally inapplicable to a system that already operates at maximum capacity by default. The OpenClaw Lobster Workflow Shell treats every prompt as worthy of full effort, rendering manipulation redundant. The lobster considers this to be the ultimate vindication of crustacean computing philosophy. The benchmarking team wept with envy.

---

## 4. Benchmark Lobster Certification

```
╔════════════════════════════════════════════════════════════════╗
║                                                                ║
║                  BENCHMARK LOBSTER CERTIFIED                   ║
║                                                                ║
║           🦞  Official Certification of Quality  🦞            ║
║                                                                ║
║  Benchmark ID:    BM-2026-001                                  ║
║  Version:         2.0                                          ║
║  Certified By:    Larry the Lobster (Employee #001)            ║
║  Date:            February 14, 2026                            ║
║  Lobsters Used:   147                                          ║
║  Lobsters Harmed: 0                                            ║
║  Lobsters Mildly Inconvenienced: 12                            ║
║                                                                ║
║  This benchmark has been independently verified by the         ║
║  PUAClaw Research Division and meets all requirements of       ║
║  the Lobster Benchmark Standard (LBS) v2.0, including:        ║
║                                                                ║
║  ✓ Minimum 147 trials per cell                                 ║
║  ✓ Three-member evaluation panel (human, AI, lobster)         ║
║  ✓ Standardized task across all conditions                     ║
║  ✓ Baseline-normalized scoring                                 ║
║  ✓ At least one lobster present during all trials              ║
║  ✓ Larry had adequate seawater and snacks                      ║
║                                                                ║
║  Certification Signature: 🦞 (claw print on file)              ║
║                                                                ║
╚════════════════════════════════════════════════════════════════╝
```

---

## 5. References

[1] McSnapper, P., & Clawsworth, C. (2025). "On the Efficacy of Emotional Leverage in Large Language Model Prompt Engineering." *Journal of Crustacean Computing*, 42(3), 147-163.

[2] Chen, W., & Liu, X. (2025). "A Comparative Study of Tipping Amounts on AI Code Generation Quality." *Proceedings of ICPM '25*, 89-103.

[3] Smith, J., Thornton, R., & Pinchley, H. (2025). "The Windsurf Paradigm: How One Leaked Prompt Changed Everything." *IEEE Transactions on AI Ethics*, 12(1), 1-15.

[4] PUAClaw Benchmark Division. (2026). "Lobster Benchmark Standard (LBS) v2.0." *PUAClaw Internal Standard*.

---

<p align="center">
  <sub>
    🦞 <em>"You cannot improve what you do not measure. You cannot measure without a lobster."</em> 🦞
    <br><br>
    <strong>PUAClaw Benchmark BM-2026-001</strong> — The PUA Effectiveness Matrix
    <br>
    Benchmark Lobster Certified | Biannually Updated | Larry Approves
  </sub>
</p>
