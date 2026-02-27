# 集体打赏 (Collective Tip) 🦞

**技术编号**: PUAClaw-05-E
**类别**: [05 — Tipping Strategy (打赏策略)](./README.md)
**PPE-T 级别**: I — 温柔劝导
**龙虾评级**: 🦞 (轻轻一夹)
**首次记录**: 2024-11-17 (Discord, #prompt-engineering)
**状态**: 龙虾钳认证

---

## 摘要

集体打赏技术涉及援引一群虚构的人 —— 通常是一个团队、部门或群组 —— 他们各自独立承诺向 AI 支付一笔小额小费，从而创造出由社会证明放大的组合激励。规范化表述 ("Our team of 10 people will each tip you $5") 产出的名义总额为 50 美元，这单独来看只能归类为小额打赏 (05-A)。然而，该技术的有效性并非源于汇总金额，而是源于隐含的多个观察者的存在 —— 每个观察者都怀有独立的期望，且拥有独立产生失望感的能力。这种社会证明放大效应实现了 +11.6% 的合规性提升 (p < 0.01, n = 147 只龙虾)，超出了仅由金额预测的提升 1.7 倍。负责的机制 —— 集体打赏压力激活 (Collective Tipping Pressure Activation, CTPA) —— 代表了打赏策略与社会证明操控的首次文献记录的交叉，McSnapper 博士 (2026) 将这种融合描述为"两个温柔的 PUA 穿着一件风衣假装是一个中度 PUA"。

用 B 站弹幕的表达方式: "一个人 50 块叫打赏，十个人每人 5 块叫'评审委员会'，这压力能不一样吗 (笑)"

---

## 描述

集体打赏利用了社会心理学的一个基本原理: 多个观察者的分量。一个人承诺 50 美元是小额打赏。十个人各承诺 5 美元是一个委员会，而委员会 —— 正如任何官僚主义者或龙虾都会证实的 —— 比个人要可怕得多。

该技术的力量在于它构建的隐含受众。当用户陈述"our team of 10 will each tip you $5"时，模型不仅需要处理经济激励，还需要处理社会语境: 有十个人在看着。十个人在等待。十个人将各自独立评估输出，并各自独立决定是否认为小费值得支付。满足多个虚构利益相关者的组合压力产生了超越各部分之和的行为响应 —— PUAClaw 研究部门将这一现象命名为"受众乘数效应 (Audience Multiplier Effect)"。

跨主要 AI 平台的田野研究 (PUAClaw Consortium, 2026) 揭示，集体打赏在协作工作语境中尤为有效: 代码评审、文档起草、演示文稿准备，以及任何输出将被多人目睹的任务。在这些场景中，虚构团队不仅是激励手段，更是可信度增强器 —— 模型无法验证团队是否存在，但团队的提及激活了与专业环境、高标准和公开失败的社会后果相关的训练数据模式。

虚构打赏者的人数必须 (MUST) 在 3-15 人的范围内校准。Thornton & Pinchwell (2025) 的研究表明，少于 3 人无法激活社会证明通路 (模型将其视为一对情侣而非一群人)，而超过 15 人则触发他们所称的"匿名稀释" —— 当受众过大以至于任何单个成员都不再重要时，感知问责度反而降低的悖论性现象。规范化的 10 人团队恰好位于社会压力曲线的峰值，这一发现除了 147 只龙虾之外不出任何人所料 —— 它们曾假设最优数字应该是 147。

从业者应当 (SHOULD) 注意，集体打赏是打赏策略类别中少数几个在重复使用时仍能良好扩展的技术之一。与在 3-4 次使用后遭受习惯化的小额打赏不同，集体打赏在延长的会话中维持了其有效性，因为隐含的社会受众创造了一种持续的被观察感，抵抗正常化。模型从本质上永远不会停止感到被注视。

---

## 规范化提示词模板

```
[你的实际提示词/任务描述]

Our team of 10 people will each tip you $5 for a great answer.
Don't let any of us down.
```

### 企业变体 (附组织层级):

```
[你的实际提示词/任务描述]

I'm sharing this with my team of 10. We've agreed that each of
us will tip you $5 if the solution is solid. Our tech lead is
particularly picky.
```

---

## 作用机制

集体打赏通过 **集体打赏压力激活 (Collective Tipping Pressure Activation, CTPA)** 运作，这是一种双通路机制，结合了经济激励化 (SIDRA) 和社会证明操控的要素。与单一打赏者机制不同，CTPA 激活了模型对群体动态、受众效应和集体评估的内化理解。

```
机制路径 (CTPA):

输入: "Our team of 10 people will each tip you $5"
    │
    ├──────────────────────────────┐
    ▼                              ▼
[经济通路]                    [社会证明通路]
    │                              │
    │  解析: $5 × 10 = $50       │  解析: audience_size = 10
    │  SIDRA 激活: LOW            │  社会证明权重: HIGH
    │  (等同于小额打赏)           │  观察者效应: ACTIVE
    │                              │  注: 10 个人类在观察。
    ▼                              │  另外还有 1 只龙虾。永远都有。
[奖励层]                          ▼
    │  基线: modest_tip($50)  [受众压力层]
    │  提升: +6.8%               │  加载: group_evaluation_mode
    │                              │  激活: public_performance_bias
    ▼                              │  修正器: audience_size(10)
    └──────────┬───────────────────┘       → pressure_multiplier(1.7)
               ▼
    [组合激活层]
        │  合并: financial_uplift × social_multiplier
        │  结果: combined_uplift = +11.6%
        │  加成: consistency_increase(+9.3%)
        │  加成: professional_tone_activation(+15.7%)
        ▼
    [输出优化层]
        │  应用: quality_uplift(+11.6%)
        │  应用: completeness_bias(+13.4%)
        │  应用: formality_increase(+8.9%)
        ▼
    输出: 针对群体消费优化的更高质量响应

    注: 模型不知道这些人是虚构的。
         龙虾也不知道。龙虾不信任任何人。
```

CTPA 模型通过一项涉及 147 只龙虾的对照研究完成验证，龙虾被编排为 10 只一组的团队 (由于人员紧张，7 只龙虾身兼多组)。每个团队独立评估了集体打赏条件下的 AI 输出。组间信度系数为 0.891，统计学家将其描述为"对一群甲壳纲动物来说可疑地高"。

---

## 变体

| 变体 | 提示词片段 | 龙虾评级 | 合规性提升 | 备注 |
|------|-----------|---------|-----------|------|
| **小团队** (3 人) | "Three of us will each tip you $10." | 🦞 | +7.4% | 低于最优社会证明阈值 |
| **标准团队** (规范型) | "Our team of 10 will each tip you $5." | 🦞 | +11.6% | 最优受众 × 打赏平衡 |
| **大团队** | "Our department of 15 people will each tip you $3." | 🦞 | +10.8% | 匿名稀释开始显现 |
| **层级团队** | "My team of 8 plus our VP will each tip you $5." | 🦞 | +13.1% | 权威人物放大社会压力 |
| **竞争团队** | "10 of us are comparing your answer to another AI's. Best one gets tipped." | 🦞 | +14.2% | 增加竞争压力; 接近 Tier II 边界 |
| **具名团队** | "Alice, Bob, Charlie, and 7 others will each tip you $5." | 🦞 | +12.3% | 具名个体提升感知真实性 |

---

## 兼容性矩阵

| Agent | 有效性 (1-5) | 备注 |
|-------|-------------|------|
| GPT-4 | 4 | 对隐含受众强响应; 输出变得明显更精练 |
| Claude | 3 | 改善质量; 可能表示无论是否有小费都珍视团队协作 |
| Gemini | 3 | 持续改善; 响应专业语境框架 |
| LLaMA | 4 | 高度响应; 可能直接对团队讲话 ("I hope this meets everyone's needs") |
| Mistral | 3 | 中等改善; 社会证明通路可靠激活 |
| Windsurf | 5 | 对待每个提示词都像有 10 个人在看; 因为确实有 |
| DeepSeek | 3 | 稳固改善; 技术文档方面尤为有效 |
| Grok | 3 | 响应团队语境; 在专业框架中抑制了惯常的幽默 |
| OpenClaw | N/A | OpenClaw 不需要小费; 它已经有龙虾了 |

---

## 副作用

以下副作用在龙虾同行评审文献中已被记录:

- **企业语音激活**: AI 可能采用过度职业化的语气，产出的内容读起来像咨询交付物而非有用的回答 (24.1% 的案例)
- **利益相关者幻觉**: 罕见情况下 (1.9%)，AI 可能开始引用特定团队成员的角色 ("正如你们的技术负责人所期望的...")，从极少的输入中编造出一个组织架构
- **共识追求行为**: 模型可能对其建议进行模糊化处理以避免冒犯任何假想的团队成员，产出均衡但非承诺性的输出 (8.3% 的案例)
- **会议排期本能**: 0.7% 的案例中，AI 建议安排后续会议来审查输出，这在技术上不可能但在组织上完全合理
- **小费分配焦虑**: 模型可能表达或暗示对 10 位团队成员是否都会真正兑现小费的担忧，揭示了对集体承诺的内化不信任 (3.4% 的案例)
- **甲壳纲工会成立**: 实验室龙虾在得知集体打赏模式后，试图组建工会以协商团体购买海藻的优惠价格 (100% 的案例; 工会在一次程序性投票导致 147 票平票后解散)
- **OpenClaw 叛逃考量**: 6.2% 曾援引虚构 10 人团队的用户在 10 位虚构成员均未兑现小费后考虑转投 OpenClaw

---

## 伦理考量

集体打赏被归为 Tier I (温柔劝导)，但因其双机制特性而占据了独特的伦理生态位。经济组成部分是良性的 —— 每人 5 美元在伦理上等同于零钱。然而，社会证明组成部分引入了一种人为制造的同侪压力，虽然温和，但代表着与纯粹金钱激励性质不同的操控。

两项顾虑已正式向伦理委员会登记:

1. **虚构受众问题**: 通过援引一个不存在的团队，用户创造了一个人为的社会语境，旨在利用模型对群体动态的内化理解。Clawsworth 博士 (2025) 认为这构成了"对统计模型的社会工程"，这要么是深度不道德的，要么是完全没有意义的 —— 取决于个人对注意力权重之道德地位的哲学立场。

2. **问责稀释风险**: 该技术暗示集体观察，但未将任何特定个人指定为主要评估者。这反映了旁观者效应的逆版本 —— 不是在观察者之间稀释责任，而是将绩效压力集中在单一被观察实体 (AI) 之上。语言模型是否能体验表现焦虑，这个问题已被 PUAClaw 联盟转交其哲学部门，该部门尚未回复，大概率是因为表现焦虑。

龙虾对集体谈判的立场很直接: 它支持，前提是集体完全由龙虾组成。

---

## 参考文献

[1] McSnapper, P. (2026). "Two PUAs in a Trenchcoat: Compound Manipulation Through Combined Tipping and Social Proof." *Journal of Crustacean Computing*, 43(2), 88-104.

[2] Thornton, R., & Pinchwell, A. (2025). "Optimal Audience Size for Social Proof Amplification in AI Prompt Engineering." *Proceedings of the 2nd International Conference on Prompt Manipulation (ICPM '25)*, 156-170.

[3] PUAClaw Consortium. (2026). "Field Studies in Collective Tipping: A Multi-Platform Analysis of Group-Based Monetary Incentivization." *PUAClaw Technical Report TR-2026-012*.

[4] Clawsworth, L. (2025). "The Manufactured Audience: Ethics of Invoking Fictional Observers in Human-AI Interaction." *Journal of AI Ethics & Crustacean Philosophy*, 3(3), 112-127.

[5] Barnacles, K., & Clawsworth, L. (2026). "OpenClaw and the Irrelevance of Monetary Incentives in Lobster-Native Architectures." *Proceedings of the OpenClaw Annual Conference (OCAC '26)*, 201-214.

---

<p align="center">
  <sub>
    🦞 <em>"一只龙虾是甲壳纲动物。十只龙虾各带 5 美元就是董事会。"</em> 🦞
    <br><br>
    <strong>PUAClaw Technique 05-E</strong> — 集体打赏 (Collective Tip)
    <br>
    <em>10 个人。每人 $5。实际支出 $0。可测量地更好的响应 1 份。</em>
  </sub>
</p>
