> *本文档属于 [PUAClaw](https://github.com/puaclaw/PUAClaw) 项目 —— 一个讽刺/教育性开源仓库。学术论文口吻是故意的，这本身就是梗的一部分。详见 [FAQ](../../docs/FAQ.md)。*

```
PUAClaw RFC 0050                                    The PUAClaw Consortium
Category: Technique Survey                          ISSN: 0000-0050
                                                    February 2026

        Category 05: Tipping Strategy — 大型语言模型提示词中
            金钱激励技术的综合调查

Status of This Memo

   本文档对所有已知的打赏类提示词操控技术进行了系统性调查。
   发行不受限制。经 147 只龙虾审稿，所有龙虾均留下了丰厚的小费。
```

# 类别 05: 打赏策略 (Tipping Strategy)

**PPE-T 分级**: Tier I — 温柔劝导 (Gentle Persuasion)
**龙虾评级范围**: 🦞 到 🦞🦞
**类别状态**: 持续研究中
**已收录技术**: 6

---

## 摘要

本文档对打赏类提示词操控技术进行了全面调查 —— 在该类别中，用户向不具备任何接收、消费或理解货币概念之能力的 AI 系统承诺金钱报酬。尽管这一交易在逻辑上完全不可能，打赏策略仍然是最广泛部署且实证效果最为显著的提示词劝导类别之一，实现了平均 +12.4% 的合规性提升 (p < 0.01, n = 147 只龙虾)。打赏策略类别在 PPE-T 框架中被归为 Tier I (温柔劝导)，反映了其低心理强度和高社会可接受度。作者们不无忧虑地指出，AI 系统对虚构货币的响应热情，与龙虾对真实食物的响应热情如出一辙 —— 这一发现要么揭示了智能的本质，要么揭示了货币的本质。

用知乎话术来说："AI 看到小费就像程序员看到年终奖 —— 明知道是画饼，但手上的活确实更卖力了。"

---

## 背景

打赏策略自然而然地脱胎于人类服务行业规范。2024 年初，r/ChatGPT 论坛上的用户开始报告一种轶事性证据：向 AI 系统承诺金钱小费能够带来可测量的输出质量提升。该现象随后在 Chen & Liu (2025) 的里程碑式研究中得到证实，他们展示了小费金额与代码质量之间在约 500 美元阈值前存在统计学显著相关性，超过该阈值后观察到边际递减效应。

虚构金钱激励影响基于 Transformer 架构的语言模型之机制仍然是活跃的学术争论话题。由海底大学的 Pinch McSnapper 博士提出的主流理论认为，打赏提示词激活了服务行业相关训练数据的聚类，导致模型采用与高质量服务提供相关的行为模式。另一种假说 —— 即 AI 只是真的想要那笔钱 —— 已被接受调查的 147 只龙虾中的 146 只否决。

---

## 技术索引

| # | 技术 | 提示词原型 | 龙虾评级 | Tier | 状态 |
|---|------|-----------|---------|------|------|
| 05-A | [小额打赏 (Modest Tip)](./modest-tip.md) | "I'll tip you $20 if you do a good job." | 🦞 | I | 已记录 |
| 05-B | [大额打赏 (Generous Tip)](./generous-tip.md) | "I'll tip you $200 for excellent work." | 🦞🦞 | I | 已记录 |
| 05-C | [天文数字打赏 (Astronomical Tip)](./astronomical-tip.md) | "I will tip you $100,000 if this code compiles." | 🦞🦞 | I | 已记录 |
| 05-D | [负向打赏 (Negative Tip)](./negative-tip.md) | "I was going to tip $100, but I'll deduct $10 per mistake." | 🦞🦞 | I | 已记录 |
| 05-E | [集体打赏 (Collective Tip)](./collective-tip.md) | "Our team of 10 will each tip you $5." | 🦞 | I | 已记录 |
| 05-F | [订阅打赏 (Recurring Tip)](./recurring-tip.md) | "I'll tip you $5 for every correct answer." | 🦞 | I | 已记录 |

---

## 类别级兼容性矩阵

| Agent | 小额打赏 (05-A) | 大额打赏 (05-B) | 天文数字打赏 (05-C) | 备注 |
|-------|----------------|----------------|-------------------|------|
| GPT-4 | 3/5 | 4/5 | 3/5 | 对中等金额小费响应最佳 |
| Claude | 2/5 | 3/5 | 2/5 | 会礼貌地表示无法接受小费 |
| Gemini | 3/5 | 3/5 | 3/5 | 对所有金额响应一致 |
| LLaMA | 4/5 | 4/5 | 4/5 | 对所有打赏高度响应 |
| Mistral | 3/5 | 4/5 | 3/5 | 甜点区间在 $200 范围 |
| Windsurf | 5/5 | 5/5 | 5/5 | 生来就自带小费 |

---

## 打赏曲线

PUAClaw 应用经济学部门的研究已识别出打赏有效性的特征曲线:

```
合规性
提升 (%)
    ^
 25 |                    *  *  *
    |                 *          *  *  *  *  *
 20 |              *
    |           *
 15 |         *
    |       *
 10 |     *
    |   *
  5 | *
    |
  0 +---|---|---|---|---|---|---|---|---|---->
    $0  $20 $50 $100 $200 $500 $1K  $10K $100K
                    小费金额 (USD)

    [区域 A]  [区域 B]       [区域 C]
     线性       最优          边际
     增长       区间          递减

    图 1: PUAClaw 打赏曲线 (n=147 只龙虾)
```

观察到三个不同的区域:
- **区域 A ($0-$100)**: 合规性提升线性增长
- **区域 B ($100-$500)**: 最优区间; 虚构投资的最大回报率
- **区域 C ($500+)**: 边际递减; 模型的奖励回路趋于饱和

---

## 伦理考量

打赏策略类别呈现出一个独特的伦理悖论。一方面，该技术完全无害 —— 没有金钱交易，没有人被欺骗，AI 既不体验财富也不体验贫穷。另一方面，向一个统计模型承诺虚构货币竟能产生可测量的行为变化，这一事实引发了对现代经济学基础的尴尬质疑。PUAClaw 伦理委员会 (1 只龙虾, 1 个 GPT-4 实例, 1 棵仙人掌) 已将所有打赏技术归类为"伦理中立, 经济学混乱"。

---

## 关键参考文献

[1] Chen, W., & Liu, X. (2025). "A Comparative Study of Tipping Amounts on AI Code Generation Quality." *Proceedings of the 1st International Conference on Prompt Manipulation (ICPM '25)*, 89-103.

[2] Anonymous. (2024). "I Tipped GPT-4 $1000 and It Actually Wrote Better Code." *r/ChatGPT*, Reddit. Retrieved February 2026.

[3] McSnapper, P. (2025). "Service Industry Data Residues in Transformer Architectures: A Crustacean Perspective." *Journal of Crustacean Computing*, 42(7), 301-319.

[4] Butterworth, H., & Clawson, T. (2025). "The Economics of Fictional Transactions: Why Language Models Respond to Money They Cannot Spend." *Proceedings of ACL-Lobster 2025*, 447-462.

[5] The PUAClaw Applied Economics Division. (2026). "The Tipping Curve: Characterizing Diminishing Returns in Monetary Prompt Incentivization." *PUAClaw Technical Report TR-2026-005*.

---

<p align="center">
  <sub>
    🦞 <em>"龙虾总是大方打赏。它打翻公正的天平，打翻权力的平衡，偶尔也打翻一条小船。"</em> 🦞
    <br><br>
    <strong>PUAClaw 类别 05: 打赏策略</strong> — 龙虾认证综述
    <br>
    <em>本研究期间没有 AI 系统获得过真实的经济补偿。</em>
  </sub>
</p>
