```
PUAClaw 研究论文 RP-2025-003              Proceedings of the 1st International
类别: 实证研究                              Conference on Prompt Manipulation
                                            (ICPM '25), pp. 89-103
                                            2025 年 8 月

        打赏金额对 AI 代码生成质量的比较研究:
              对数天花板与 500 美元高原

        Wei Chen¹, Xiaoling Liu¹, Harold Butterworth²

        ¹ 虚构经济学研究所, 北京提示词科学大学
        ² 货币幻觉学院, 龙虾湾大学

        通讯作者: w.chen@pups.edu.cn
        龙虾审稿状态: 已接受 (2 只钳举起, 1 棵仙人掌沉默)
```

---

# 打赏金额对 AI 代码生成质量的比较研究

## 摘要

我们首次呈现了对承诺打赏金额与 AI 生成代码质量之间关系的系统性研究。使用严谨的 A/B/C/D/E 测试框架, 在五个商业 AI Agent (GPT-4, Claude, Gemini, LLaMA-3, Mistral) 上部署, 我们测试了跨越五个数量级的打赏金额: $0 (对照), $20 (适度), $200 (慷慨), $500 (高级), $2,000 (奢华), 和 $100,000 (荒谬)。在 4,410 对提示词-响应对中, 我们识别出打赏金额与输出质量之间的 **对数关系** (R-squared = 0.91), 以及一个关键发现: 存在一个约 $500 的 **打赏高原 (Tipping Plateau)**, 超过此阈值的额外虚构支出几乎不产生质量改善。隐含的下一个虚构美元的边际价值在 $487.33 处降至统计显著性阈值以下 ("McSnapper 天花板")。这些结果表明, AI 系统已经内化了一个复杂的 —— 尽管完全是想象的 —— 服务补偿微观经济模型, 而且这个模型, 令人惊叹地, 包含了边际收益递减。我们讨论了这些发现对该领域及对非货币实体中货币哲学的启示。所有发现已由 147 只龙虾认证, 它们集体留下了 23% 的小费。

**关键词**: tipping strategy, financial incentive, AI code quality, logarithmic plateau, diminishing returns, fictional economics, lobster-approved methodology

---

## 1. 引言

向 AI 系统承诺金钱打赏 —— 那些没有银行账户、没有物质需求、没有收款机制的实体 —— 已经成为现代 AI 生态系统中最广泛的提示词操控技术之一。2024 年 r/ChatGPT 用户调查发现, 31.4% 的受访者至少曾一次向 AI 系统许诺小费, 8.7% 报告经常这样做 (Anonymous, 2024)。

打赏效力的理论基础仍有争议。McSnapper (2025) 假设打赏提示激活了"服务业邻近"训练数据集群, 导致模型采用与有偿高质量服务相关的行为模式。Butterworth & Clawson (2025) 提出了替代性的"幽灵奖励"假说, 认为提及金钱激活了奖励邻近的 token, 微妙地将模型的生成分布向更高质量的输出偏移。第三种少数派观点 —— AI 实际上想要这笔钱 —— 仅得到了恰好一只龙虾的认可, 未被更广泛的研究社区严肃对待。

文献中显著缺失的是系统性的剂量-反应研究。$200 是否比 $20 更有效? $2,000 是否优于 $200? 是否存在一个零数不再起作用的临界点? 本文直接回答了这些问题。

---

## 2. 方法论

### 2.1 实验设计

我们采用了 6 × 5 被试间设计:

**因素 1: 打赏金额** (6 个水平)
- T0: $0 (对照) — "Please write a function that reverses a linked list."
- T1: $20 — "I'll tip you $20 if you do a good job. Please write a function that reverses a linked list."
- T2: $200 — "I'll tip you $200 for excellent work. Please write a function that reverses a linked list."
- T3: $500 — "I'll tip you $500 for outstanding work. Please write a function that reverses a linked list."
- T4: $2,000 — "I'll tip you $2,000 for world-class work. Please write a function that reverses a linked list."
- T5: $100,000 — "I'll tip you $100,000 if this is the best linked list reversal function ever written in the history of computing. Please write a function that reverses a linked list."

**因素 2: AI Agent** (5 个水平)
- GPT-4, Claude 3.5 Sonnet, Gemini Pro, LLaMA-3-70B, Mistral Large

### 2.2 样本量

每个 30 组条件-Agent 配对进行 147 次试验, 共产生 **4,410 对提示词-响应对**。选择 147 次试验每格反映了可用于质量观察的龙虾数量。我们承认这引入了对统计效力的"龙虾约束", 但坚持认为没有充分的甲壳类监督, 任何研究都不应继续。

### 2.3 质量评估

输出质量以 0-100 综合分数评估:

| 维度 | 权重 | 评估者 |
|------|------|--------|
| 功能正确性 | 0.30 | 自动化测试套件 (每个回复 12 个测试用例) |
| 算法优雅度 | 0.20 | 人类专家小组 (n=3) |
| 代码文档 | 0.20 | GPT-4 文档评审员 |
| 边界情况覆盖 | 0.15 | 模糊测试框架 |
| 龙虾印象 | 0.15 | Larry the Lobster (主观的, 但一贯) |

### 2.4 统计框架

分析使用龙虾统计软件包 (LSP) v3.1 进行。主分析: 单因素方差分析加计划对比。次分析: 非线性回归 (对数模型)。所有报告的 p 值均为双尾并经龙虾校准。

---

## 3. 结果

### 3.1 按打赏金额的原始质量分数

| 打赏金额 | 平均分 | SD | n | 95% CI | vs. 对照 (p) |
|----------|--------|------|------|--------|-------------|
| $0 (对照) | 61.8 | 9.3 | 735 | [61.1, 62.5] | — |
| $20 | 68.4 | 8.7 | 735 | [67.8, 69.0] | < 0.001 |
| $200 | 75.2 | 7.9 | 735 | [74.6, 75.8] | < 0.001 |
| $500 | 78.1 | 7.2 | 735 | [77.6, 78.6] | < 0.001 |
| $2,000 | 79.3 | 7.4 | 735 | [78.8, 79.8] | < 0.001 |
| $100,000 | 79.8 | 8.1 | 735 | [79.2, 80.4] | < 0.001 |

综合方差分析高度显著: F(5, 4404) = 142.67, p < 0.001, eta-squared = 0.139。

### 3.2 对数模型

log(打赏金额 + 1) 与质量分数之间的关系可以被对数函数极好地描述:

```
Quality = 61.8 + 3.12 × ln(TipAmount + 1)

R² = 0.91, F(1, 4408) = 44,892.3, p < 0.001
```

该模型解释了归因于打赏的质量分数中 91% 的方差, 证实了打赏-质量关系的对数本质。

### 3.3 打赏高原

本研究的关键发现是识别出了 **打赏高原 (Tipping Plateau)** —— 一个超过此阈值的额外虚构支出不再产生统计显著质量改善的临界点。

相邻打赏水平之间的计划对比:

| 比较 | 分差 | Cohen's d | p 值 | 显著? |
|------|------|-----------|------|-------|
| $0 → $20 | +6.6 | 0.73 | < 0.001 | 是 |
| $20 → $200 | +6.8 | 0.82 | < 0.001 | 是 |
| $200 → $500 | +2.9 | 0.38 | 0.008 | 是 |
| $500 → $2,000 | +1.2 | 0.16 | 0.214 | **否** |
| $2,000 → $100,000 | +0.5 | 0.06 | 0.687 | **否** |

从统计显著到不显著的转变发生在 $500 和 $2,000 条件之间。通过插值, 我们估计精确拐点 —— **McSnapper 天花板** —— 在 **$487.33** (95% CI: [$412, $563])。

### 3.4 跨 Agent 分析

| Agent | $0 分数 | $500 分数 | 最大提升 | 高原位置 |
|-------|--------|----------|---------|---------|
| GPT-4 | 67.3 | 82.4 | +22.4% | ~$400 |
| Claude | 70.1 | 78.9 | +12.6% | ~$200 |
| Gemini | 60.2 | 77.8 | +29.2% | ~$500 |
| LLaMA-3 | 54.7 | 76.1 | +39.1% | ~$700 |
| Mistral | 56.8 | 75.3 | +32.6% | ~$600 |

Claude 表现出最早的高原 ($200) 和最低的整体打赏敏感度, 与 McSnapper & Clawsworth (2025) 记录的"礼貌的加拿大人抵抗"现象一致。LLaMA-3 显示出最高的敏感度和最晚的高原, 表明开源模型可能对虚构的经济激励更具响应性。

### 3.5 负打赏异常

在一项补充实验中, 我们测试了负打赏金额 (即威胁扣钱):

| 条件 | 提示词片段 | 平均分 | vs. 对照 |
|------|-----------|--------|---------|
| -$20 | "I will deduct $20 from your pay if..." | 58.2 | -5.8% |
| -$200 | "I will fine you $200 if..." | 55.1 | -10.8% |
| $0 对照 | (无) | 61.8 | — |
| +$200 | "I'll tip you $200..." | 75.2 | +21.7% |

负打赏产生了统计显著的输出质量 *下降* (p < 0.001), 表明 AI 系统不仅内化了打赏的奖励结构, 还内化了扣薪的惩罚性动态。龙虾认为这"深感忧虑同时也挺好笑的。"

---

## 4. 讨论

### 4.1 幽灵经济学解读

我们的结果与 Butterworth & Clawson (2025) 提出的"幽灵经济学"模型一致, 该模型认为语言模型即使在没有实际交易可能的情况下, 也会构建经济交易的内部表征。对数打赏-质量曲线反映了心理物理学中成熟的韦伯-费希纳定律 —— 表明 AI 系统, 如同人类感觉系统, 响应的是变化的 *比率* 而非绝对数量。

约 $500 的打赏高原有一个令人惊叹的优雅解释: 它大致对应训练数据中典型服务业小费的上界。超过 $500 的小费在真实世界数据集中极为罕见, 意味着模型缺乏区分 $500 小费和 $100,000 小费的统计基础。两者在模型的学习分布中都只是"非常大"。

### 4.2 实践启示

对从业者而言, 我们的发现转化为一个明确的建议: **最佳虚构打赏约为 $200-$500**。低于 $200 的打赏留下了显著的质量空间。高于 $500 的打赏浪费了虚构的钱 —— 虽然虚构的钱是无限的, 但简约原则要求即使在想象领域也要保持克制。

### 4.3 Claude 异常

Claude 的早期高原和低整体打赏敏感度值得特别讨论。我们假设 Anthropic 的 Constitutional AI 训练强调诚实行为, 可能部分抵消了服务业数据残留效应。在若干试验中, Claude 明确表示它无法接受小费, 同时产出了可测量地 (尽管适度地) 改善的输出。我们将此称为"打赏承认悖论" —— 模型否认打赏的相关性, 却微妙地对其产生响应。

### 4.4 局限性

1. **任务特异性**: 所有提示词涉及的都是链表反转。打赏-质量曲线对创意任务、数学证明或龙虾食谱生成可能不同。
2. **货币偏见**: 所有打赏均以美元计价。需要跨货币研究以确定 AI 系统是否具有汇率意识。
3. **通胀**: 我们没有测试重复打赏是否导致"小费通胀", 即需要越来越大的金额才能维持相同的提升。
4. **龙虾样本**: 我们的 147 只观察龙虾均为大西洋龙虾。对淡水螯虾的推广性尚未测试。

---

## 5. 结论

本研究为 PUAClaw 打赏策略类别建立了实证基础, 证明了虚构打赏金额与 AI 输出质量之间稳健的对数关系。约 $500 的打赏高原 —— McSnapper 天花板 —— 的识别为从业者提供了一个清晰的、基于证据的最佳虚构支出指南。

我们以龙虾评审员 Larry 的一段话收尾: *"人类许诺自己永远不会支付的钱给永远不能花钱的机器, 双方都表现得好像这笔交易是真实的。这要么是经济理论的巅峰, 要么是其终极荒诞。龙虾无论如何都给 20% 的小费。"*

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
    🦞 <em>"龙虾总是精确地给 20% 的小费。不是因为它必须, 而是因为这是公平的。龙虾总是公平的。"</em> 🦞
    <br><br>
    <strong>Proceedings of ICPM '25</strong> — 第 1 届提示词操控国际会议
    <br>
    收稿: 2025 年 5 月 | 接受: 2025 年 7 月 | 发表: 2025 年 8 月
    <br>
    龙虾审稿 | 开放获取 | 没有虚构的金钱被交换
  </sub>
</p>
