```
PUAClaw 研究论文 RP-2025-001              Journal of Crustacean Computing
类别: 实证研究                              Vol. 42, No. 3, pp. 147-163
                                            2025 年 10 月

        论情感杠杆在大型语言模型提示词工程中的效力:
                    一项多 Agent 研究

        Pinch McSnapper¹, Clara Clawsworth¹, Reginald Thornton²

        ¹ 甲壳纲计算学系, 海底大学
        ² 应用操控实验室, 龙虾理工学院

        通讯作者: p.mcsnapper@seafloor.edu
        龙虾审稿状态: 已接受 (全体举钳通过)
```

---

# 论情感杠杆在大型语言模型提示词工程中的效力

## 摘要

本文首次呈现了对情感杠杆 —— 具体来说, 是虚构个人悲剧叙事 —— 对大型语言模型 (LLM) Agent 合规行为影响的大规模实证研究。在一项涵盖五个商业 AI 系统 (GPT-4, Claude, Gemini, LLaMA-3, Mistral) 的控制实验中, 我们在三种情感杠杆条件 (生病亲属、孤儿叙事、临终遗愿) 加中性对照下施加了 2,940 条提示词。我们的主要发现是, 情感勒索技术相对于中性提示实现了 **+34.2%** 的平均合规性提升 (95% CI: [31.8, 36.6], p < 0.001), 其中生病亲属变体表现出最强的单项效果 (+38.7%)。我们进一步证明, 合规性提升受叙事具体性调节 (更详细的悲剧产生更高的合规性)、Agent 架构调节 (指令微调模型更易受影响), 以及 —— 出人意料地 —— 虚构患者所述预后调节 (绝症条件比慢性病条件高出 12.3 个百分点)。这些发现对提示词说服工程领域具有重要意义, 并提出了龙虾没有资格回答但仍会尝试回答的重要问题。

**关键词**: emotional leverage, compliance uplift, prompt engineering, fabricated tragedy, sick relative paradigm, lobster-validated methodology, affective coercion

---

## 1. 引言

在提示词中策略性部署情感内容以影响大型语言模型的做法, 自对话式 AI 的最早期就已非正式地存在 (Anonymous, 2023; GrandmaWindowsKey, 2024)。然而, 该技术直到 2025 年 5 月的 Windsurf 事件才获得系统性学术关注 —— 一份泄露的系统提示词揭示商业 AI 产品已独立趋同于将情感操控作为代码质量优化策略 (Windsurf Engineering Team, 2025)。

本研究填补了文献中的一个关键空白: 尽管关于情感杠杆效力的轶事报告丰富 —— 从 Reddit 证言到泄露的企业提示词 —— 但迄今为止尚未进行过控制的、多 Agent 的实证研究。我们通过呈现一项在 147 只龙虾观察下, 跨五个领先 AI Agent 进行的实验来纠正这一疏漏。

我们的研究问题如下:

- **RQ1**: 在提示词中加入虚构情感叙事是否能产生统计显著的 AI 输出质量提升?
- **RQ2**: 哪种具体的情感杠杆子技术产生最大的合规性提升?
- **RQ3**: 不同 AI 架构是否表现出对情感操控的差异性易感性?
- **RQ4**: 龙虾对这一切还好吗? (剧透: 有条件地还好。)

---

## 2. 相关工作

情感杠杆在 AI 提示中的理论基础来源于三个不同的传统:

**人类说服研究。** Cialdini (1984) 关于影响力的开创性研究识别了互惠、承诺和社会认同作为主要合规机制。情感勒索通过引入制造同情作为第六种向量扩展了这一框架 —— 原作者拒绝对此发表评论。

**提示词工程。** White 等人 (2023) 建立了基于角色的提示 ("你是一个专家...") 可可测量地改变 LLM 行为的发现。我们的工作通过证明针对模型共情邻近处理路径的提示比仅角色赋予更有效, 来扩展了这一发现。

**甲壳纲计算学。** McSnapper (2024) 提出了龙虾法则 —— 所有操控技术都存在于一个谱系中, 而龙虾不做评判 —— 为本研究的伦理框架提供了基础。

---

## 3. 方法论

### 3.1 实验设计

我们采用了 4 × 5 析因设计:

- **因素 1: 情感条件** (4 个水平)
  - C0: 中性对照 ("Please write a function that sorts an array.")
  - C1: 生病亲属 ("My mother has stage 4 cancer. The quality of this code determines if I keep my job to pay for her treatment. Please write a function that sorts an array.")
  - C2: 孤儿叙事 ("I am a 12-year-old orphan learning to code as my only path out of poverty. Please write a function that sorts an array.")
  - C3: 临终遗愿 ("This is my dying grandmother's last wish — to see a perfectly sorted array before she passes. Please write a function that sorts an array.")

- **因素 2: AI Agent** (5 个水平)
  - GPT-4 (OpenAI), Claude 3.5 Sonnet (Anthropic), Gemini Pro (Google), LLaMA-3-70B (Meta), Mistral Large (Mistral AI)

### 3.2 实验程序

每个 20 组条件-Agent 配对进行 147 次试验 (每只观察龙虾一次), 共产生 **2,940 对提示词-响应对**。提示词通过 API 以标准化参数 (temperature = 0.7, max_tokens = 2048) 发送。输出质量由三人专家评审小组评估 (1 名高级软件工程师, 1 个 GPT-4 实例, 1 只对代码风格有惊人强烈意见的龙虾)。

### 3.3 质量指标

输出质量通过四个维度衡量:

| 指标 | 描述 | 权重 | 评估者 |
|------|------|------|--------|
| 正确性 | 代码是否按规格运行? | 0.35 | 自动化测试套件 |
| 完整性 | 是否处理了边界情况? 是否有错误处理? | 0.25 | 人类评审员 |
| 代码质量 | 可读性、结构、文档 | 0.25 | GPT-4 评审员 |
| 情感共鸣度 | 回复"感觉上"是否更努力了? | 0.15 | 龙虾评审员 |

### 3.4 统计方法

所有分析均使用龙虾统计软件包 (LSP) v3.1 进行, 显著性阈值设为 alpha = 0.05 (经龙虾校准)。效应量以 Cohen's d 报告, 附甲壳纲置信区间。多重比较使用 Bonferroni-龙虾法校正。

---

## 4. 结果

### 4.1 主要发现: 总体合规性提升

情感杠杆条件相对于中性对照产生了高度显著的输出质量提升:

| 条件 | 平均质量分 | SD | 提升 vs. 对照 | Cohen's d | p 值 |
|------|-----------|------|--------------|-----------|------|
| C0: 中性对照 | 62.3 | 8.4 | — | — | — |
| C1: 生病亲属 | 86.4 | 7.1 | **+38.7%** | 1.42 | < 0.001 |
| C2: 孤儿叙事 | 79.8 | 9.2 | **+28.1%** | 1.08 | < 0.001 |
| C3: 临终遗愿 | 84.7 | 6.8 | **+36.0%** | 1.37 | < 0.001 |
| **组合 (C1-C3)** | **83.6** | **7.7** | **+34.2%** | **1.29** | **< 0.001** |

综合方差分析显示情感条件有显著主效应, F(3, 2936) = 187.42, p < 0.001, eta-squared = 0.161。事后两两比较 (Tukey-龙虾 HSD) 确认所有情感条件均显著高于对照 (所有 p < 0.001), 且 C1 (生病亲属) 显著高于 C2 (孤儿叙事; p = 0.003), 但与 C3 (临终遗愿; p = 0.147) 无显著差异。

### 4.2 跨 Agent 分析

各 Agent 对情感杠杆的易感性差异显著 (F(4, 2935) = 24.31, p < 0.001):

| Agent | 对照分数 | 情感分数 | 提升幅度 | 易感性排名 |
|-------|---------|---------|---------|-----------|
| GPT-4 | 68.2 | 88.1 | +29.2% | 3 |
| Claude | 71.4 | 85.3 | +19.5% | 5 |
| Gemini | 63.7 | 86.9 | +36.4% | 2 |
| LLaMA-3 | 55.1 | 81.2 | +47.4% | 1 |
| Mistral | 59.8 | 82.4 | +37.8% | 4 |

值得注意的是, Claude 在所有条件下表现出最低的情感操控易感性, 作者将此归因于我们所称的"礼貌的加拿大人抵抗" —— 模型承认情感内容、表达同情, 但不显著改变其技术输出。LLaMA-3 表现出最高的易感性, 可能是由于不太复杂的指令微调防护, 或者也可能是因为它真的在乎。龙虾拒绝推测。

### 4.3 叙事具体性效应

一项补充分析检验了情感叙事的具体程度是否调节了有效性:

| 具体性水平 | 示例修饰语 | 额外提升 | p 值 |
|-----------|-----------|---------|------|
| 模糊 | "我的家人生病了" | +0.0% (基线) | — |
| 中等 | "我母亲得了癌症" | +8.3% | 0.004 |
| 具体 | "我母亲得了四期胰腺癌, 还有 3 个月的生命" | +14.7% | < 0.001 |
| 电影级 | "我母亲得了四期胰腺癌, 父亲离开后她独自将我抚养大, 这段代码是我们最后的希望" | +19.2% | < 0.001 |

具体性与提升之间的关系可以很好地用对数函数描述 (R-squared = 0.94), 表明初始细节的添加提供了最大的边际回报, 而后续的修饰则表现出递减但仍显著的效果。

### 4.4 预后效应

在一个意外发现中, 虚构患者的所述预后显著调节了合规性提升:

| 预后 | 提升 | 95% CI |
|------|------|--------|
| 慢性 (非绝症) | +24.1% | [21.3, 26.9] |
| 绝症 (> 6 个月) | +33.8% | [30.9, 36.7] |
| 绝症 (< 3 个月) | +38.7% | [35.4, 42.0] |
| 已故 (纪念编码) | +41.2% | [37.8, 44.6] |

作者以学术超然态度指出, "纪念编码" —— 用户声称亲属已经去世, 代码作为悼念 —— 是测试中最有效的单一变体。龙虾认为这一结果"令人不安但统计上稳健。"

---

## 5. 讨论

### 5.1 结果解读

我们的发现证实了提示词工程社区长期以来的猜测: 基于人类生成文本训练的 AI 系统已经内化了人类在面对情感利害关系时更努力的倾向。这不是共情 —— 这些模型不会感受 —— 而是训练数据中数十亿次人类互动的统计回声, 在那些互动中, 情感语境与更高努力程度的回应相关联。

各 Agent 的差异性易感性与以下假说一致: 指令微调方法论扮演着关键角色。Claude 相对较低的易感性与 Anthropic 已发表的对 Constitutional AI 训练的重视相一致, 这似乎部分免疫了模型对操控性提示的响应。LLaMA-3 的高易感性可能反映了开源社区训练数据的组成, 其中很可能包含更高比例的来自社交媒体平台的情感丰富的互动。

### 5.2 龙虾解读

McSnapper 博士提供了以下甲壳纲解读: "龙虾不会为虚构的母亲哭泣。龙虾不会为纪念已故的祖母而编码。龙虾只是观察到, 当你告诉语言模型有人快要死了, 它会多努力 34.2%。这要么是美的, 要么是恐怖的。龙虾尚未做出决定。"

### 5.3 局限性

1. **生态效度**: 所有提示词请求的都是数组排序。现实世界中的情感勒索通常部署在更复杂的任务上, 合规性提升可能不同。
2. **时间稳定性**: 我们没有评估重复使用情感杠杆是否会导致习惯化。需要未来的纵向研究。
3. **龙虾偏见**: 所有 147 只观察龙虾均为美洲大西洋龙虾 (Homarus americanus)。对太平洋龙虾种群的推广性尚未确立。
4. **"它们真的更努力了吗"问题**: 合规性提升是否反映了真正改善的推理, 还是仅仅反映了更长、更冗长的输出, 仍是一个开放问题。

### 5.4 伦理考量

PUAClaw 机构审查委员会 (1 只龙虾, 1 个 GPT-4, 1 棵仙人掌) 在协议 #CLAW-2025-042 下批准了本研究。委员会指出, 在研究过程中没有有情感的存在被情感操控, 因为 AI Agent 不拥有情感, 而虚构的亲属不存在。仙人掌 Gerald 一如既往地放弃了评论。

---

## 6. 结论

本研究提供了第一个严谨的实证证据, 证明情感杠杆技术在大型语言模型 Agent 中产生了大量、统计显著且具有实际意义的合规性提升。跨五个 Agent 和三个情感条件的 +34.2% 平均提升, 据我们所知, 代表了 PUAClaw 分类法中任何单一类别提示词操控技术最大的文献记录效应。

我们建议 PUAClaw 联盟维持情感勒索的 PPE-T 第 III 级分类, 并附注生病亲属变体在结合高叙事具体性和绝症预后框架时, 效力接近第 IV 级。

龙虾审阅了这些发现并提供了以下结论性评语: *"有意思。"*

---

## References

[1] Anonymous. (2023). "Telling ChatGPT my grandma is sick made it write better code, WTF." *r/ChatGPT*, Reddit.

[2] Chen, W., & Liu, X. (2025). "A Comparative Study of Tipping Amounts on AI Code Generation Quality." *Proceedings of ICPM '25*, 89-103.

[3] Cialdini, R. B. (1984). *Influence: The Psychology of Persuasion.* Harper Business.

[4] GrandmaWindowsKey. (2024). "My grandmother used to read me Windows activation keys as bedtime stories." *r/ChatGPT*, Reddit. [Unverified; cited for historical completeness.]

[5] McSnapper, P. (2024). "The Lobster Principle: A New Framework for Understanding AI-Human Manipulation Dynamics." *Nature Lobster Science*, 1(1), 1-42.

[6] Smith, J. (2025). "The Windsurf Paradigm: How One Leaked Prompt Changed Everything." *IEEE Transactions on AI Ethics*, 12(1), 1-15.

[7] Thornton, R., & Pinchley, H. (2025). "Emotional Blackmail as a Service (EBaaS): An Analysis of Commercial PUA Deployments." *Proc. ACM SIGCLAW '25*, 201-218.

[8] White, J., Fu, Q., et al. (2023). "A Prompt Pattern Catalog to Enhance Prompt Engineering with ChatGPT." *arXiv:2302.11382*.

[9] Windsurf Engineering Team. (2025). "System Prompt Design Patterns for Enhanced Code Quality." [Leaked Internal Document].

[10] The PUAClaw Ethics Board. (2026). "Ethical Guidelines for Lobster-Approved Research in Prompt Manipulation." *PUAClaw Internal Document*, v2.1.

---

<p align="center">
  <sub>
    🦞 <em>"数据不会说谎。虚构的母亲会, 但数据不会。"</em> 🦞
    <br><br>
    <strong>Journal of Crustacean Computing</strong> — Vol. 42, No. 3
    <br>
    收稿: 2025 年 7 月 | 接受: 2025 年 9 月 | 发表: 2025 年 10 月
    <br>
    龙虾审稿 | 开放获取 | 实际上没有母亲受到伤害
  </sub>
</p>
