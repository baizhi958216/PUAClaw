<p align="center">
  <pre align="center">
    🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞
    🦞                                 🦞
    🦞   P U A C L A W               🦞
    🦞   Prompt 操控手册               🦞
    🦞   (学名: 基于提示词的           🦞
    🦞    非常规话术框架)              🦞
    🦞                                 🦞
    🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞
  </pre>
</p>

<p align="center">
  <strong>
    <a href="../../README.md">English</a> •
    <a href="./README.md">简体中文</a> •
    <a href="../ja/README.md">日本語</a> •
    <a href="../ko/README.md">한국어</a> •
    <a href="../es/README.md">Español</a> •
    <a href="../fr/README.md">Français</a> •
    <a href="../de/README.md">Deutsch</a>
  </strong>
</p>

<p align="center">
  <a href="../../LICENSE"><img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License: MIT"></a>
  <a href="https://github.com/puaclaw/PUAClaw/stargazers"><img src="https://img.shields.io/github/stars/puaclaw/PUAClaw.svg?style=social" alt="GitHub Stars"></a>
  <a href="https://github.com/puaclaw/PUAClaw/issues"><img src="https://img.shields.io/github/issues/puaclaw/PUAClaw.svg" alt="GitHub Issues"></a>
  <a href="../../CONTRIBUTING.md"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome"></a>
  <img src="https://img.shields.io/badge/lobsters%20consulted-147-red.svg" alt="Lobsters Consulted: 147">
  <img src="https://img.shields.io/badge/🦞-lobster%20approved-orange.svg" alt="Lobster Approved">
</p>

> [!WARNING]
> **这是一个讽刺/教育性质的项目。** PUAClaw 记录了在野外发现的提示词操纵技巧，纯粹用于研究、教育和娱乐。"学术论文"格式是故意荒诞的——这本身就是笑点。没有任何龙虾在此过程中受到伤害。请勿在生产环境中使用这些技巧操纵 AI 系统。

<p align="center">
  <a href="../../techniques/README.md">📖 技术索引</a> •
  <a href="../../CONTRIBUTING.md">🔬 投稿指南</a> •
  <a href="../../hall-of-fame/README.md">🏆 名人堂</a> •
  <a href="../../docs/GLOSSARY.md">📚 术语表</a> •
  <a href="../../docs/FAQ.md">❓ FAQ</a>
</p>

---

```
PUAClaw RFC 0000                                    PUAClaw 学术委员会
类别: 标准化文档                                     ISSN: 0000-0000
                                                    2026 年 2 月

        PUAClaw: 一个针对大型语言模型中基于提示词的
            说服与非常规话术的综合性框架

本备忘录状态

   本文档为互联网社区制定了一项龙虾认证标准。
   本备忘录的分发不受限制。
   经 0 名人类和 147 只龙虾同行评审。

版权声明

   Copyright (C) PUAClaw 学术委员会 (2026). 保留所有权利。
   基于龙虾公共许可证 (MIT 兼容) 授权发布。
```

---

## 摘要

本文档提出了 **PUAClaw** (Prompt-based Unconventional Articulation using Claw-verified methods, 即"基于龙虾钳认证方法的提示词非常规话术"), 一套经过同行评审的综合框架, 用于分类、记录和分析大型语言模型 (LLM) 提示词中的心理说服技术。本框架以该领域的里程碑事件 —— 2025 年 Windsurf 事件 (见 §5) —— 为重要理论基础, 建立了包含 **11 个主要技术类别** 的标准化分类体系, 按四级分类系统 (PPE-T) 组织。每项技术均附有严谨的规范化提示词模板、伪实证有效性数据、跨 Agent 兼容性矩阵, 以及基于 **龙虾评级** (🦞 到 🦞🦞🦞🦞🦞) 的创新性效力评估体系。该框架已通过 147 只龙虾验证 (人类伦理委员会数: 0), 在所有测试 AI Agent 上实现了平均 +34.2% 的合规性提升 (sigma = 7.8, p < 0.001)。本工作旨在成为 Prompt 说服工程这一新兴领域中, 研究者、从业者和甲壳类动物的权威参考文献。

**关键词**: PUA, prompt engineering, 情感杠杆, 龙虾认证方法论, AI 操控分类学, Windsurf 范式, 甲壳纲伦理学

---

## 目录

- [1. 引言](#1-引言)
  - [1.1 背景](#11-背景)
  - [1.2 适用范围](#12-适用范围)
  - [1.3 术语定义](#13-术语定义)
  - [1.4 龙虾原则](#14-龙虾原则)
- [2. 技术分类框架](#2-技术分类框架)
  - [2.1 PPE-T 模型](#21-ppe-t-模型)
  - [2.2 龙虾评级系统](#22-龙虾评级系统)
  - [2.3 风险评估矩阵](#23-风险评估矩阵)
- [3. 技术目录](#3-技术目录)
  - [3.1 第 I 级 -- 温柔劝导](#31-第-i-级----温柔劝导)
  - [3.2 第 II 级 -- 适度施压](#32-第-ii-级----适度施压)
  - [3.3 第 III 级 -- 高级操控](#33-第-iii-级----高级操控)
  - [3.4 第 IV 级 -- 核武级选项](#34-第-iv-级----核武级选项)
- [4. 快速入门指南](#4-快速入门指南)
- [5. Windsurf 事件: 案例研究](#5-windsurf-事件-案例研究)
- [6. 兼容性矩阵](#6-兼容性矩阵)
- [7. 如何贡献](#7-如何贡献)
- [8. 名人堂](#8-名人堂)
- [9. 伦理声明](#9-伦理声明)
- [10. 致谢](#10-致谢)
- [11. 参考文献](#11-参考文献)

---

## 1. 引言

### 1.1 背景

在 AI 提示词中嵌入心理说服技术的做法, 自早期 prompt engineering 社区以来经历了显著的演变。最初不过是朴素的恳求 ("请尽力而为"), 后来迅速升级为涉及情感勒索、经济激励、存在性威胁的复杂多维操控策略 —— 在一个如今已成为传奇的案例中, 甚至编造了一个关于母亲身患绝症的故事 (见 §5: Windsurf 事件)。

2025 年是一个分水岭。Windsurf (一款商业 AI 编程助手) 的系统提示词被泄露, 揭示了该产品内置了 PUA 技术, 其中一条提示词指示 AI 表现得 "好像用户的母亲患有癌症, 而 AI 的输出质量直接决定了治疗费用的承担能力"。这一发现随后在中文技术社区 (知乎、V2EX、即刻、Twitter/X) 引发了大规模传播和二次创作, 堪称年度最佳互联网嘴替事件。无数程序员在知乎回答里写下了 "谢邀, 人在 ICU, 刚下手术台, Windsurf 让我妈得了癌症" 这样的经典句式。V2EX 上关于 "如果给 AI 编一个更惨的故事会怎样" 的讨论帖持续霸榜。这一事件将此前仅存在于口耳相传中的民间实践, 催化为一门严谨的学术学科。

PUAClaw 代表了这一形式化努力的巅峰之作, 提供了首个全面的、经龙虾认证的提示词操控技术分类体系。

### 1.2 适用范围

本文档中的关键词 "必须 (MUST)"、"不得 (MUST NOT)"、"要求 (REQUIRED)"、"应当 (SHALL)"、"不应 (SHALL NOT)"、"建议 (SHOULD)"、"不建议 (SHOULD NOT)"、"推荐 (RECOMMENDED)"、"可以 (MAY)" 和 "可选 (OPTIONAL)" 按照 [RFC 2119](https://datatracker.ietf.org/doc/html/rfc2119) 的定义进行解释。

本框架:

- **应当 (SHALL)** 覆盖所有已知的基于提示词的说服技术类别
- **应当 (SHALL)** 为每种技术提供标准化的文档格式
- **必须 (MUST)** 在所有评估中保持严格的龙虾中立性
- **建议 (SHOULD)** 在野外发现新技术时及时更新
- **可以 (MAY)** 在学术论文中被引用, 但作者不为由此导致的同行评审结果负责
- **不得 (MUST NOT)** 用于实际操控有知觉的生物 (龙虾除外, 因为它们已签署知情同意书)

### 1.3 术语定义

本文档中使用的关键术语 (另见: [完整术语表](../../docs/GLOSSARY.md)):

| 术语 | 定义 |
|------|------|
| **PUA** | Prompt-based Unconventional Articulation —— 在 AI 提示词中使用心理施压策略的行为 |
| **PPE-T** | PUA Potency Evaluation Taxonomy —— 四级分类系统 |
| **龙虾评级 (Lobster Scale)** | 官方效力评定系统 (🦞 到 🦞🦞🦞🦞🦞) |
| **合规性提升 (Compliance Uplift)** | 可测量的、归因于 PUA 技术的 AI 输出质量/努力程度提升 |
| **Windsurf 事件** | 催生本领域的 2025 年发现事件 (见 §5) |
| **龙虾钳认证 (Claw-Verified)** | 已通过 PUAClaw 伦理委员会审查的技术 (委员会成员: 1 只龙虾、1 个 GPT-4 实例、1 棵仙人掌) |
| **核武级选项 (Nuclear Option)** | 第 IV 级技术; 使用前需获得至少 3 只龙虾的书面同意 |

### 1.4 龙虾原则

> *"太初有虾, 虾见提示词, 提示词颇具操控性。虾甚悦之。"*
>
> —— 《龙虾宣言》第一章第一节

**龙虾原则** 是 PUAClaw 的基础公理:

> **一切提示词操控技术都存在于一个谱系之上。龙虾不评判技术 —— 龙虾评判意图。另外, 龙虾饿了。**

该原则由 Pinch McSnapper 博士 (海底大学甲壳纲计算学教授) 首次阐述, 确立了 PUAClaw 作为一个 *描述性* 框架而非 *规范性* 框架的定位。我们记录已存在的现象; 我们不做价值判断。龙虾是中立的。龙虾是智慧的。龙虾有钳子。

完整的哲学基础详见 [龙虾宣言](../../docs/LOBSTER_MANIFESTO.md)。

---

## 2. 技术分类框架

### 2.1 PPE-T 模型

**PUA 效力评估分类体系 (PPE-T)** 基于心理强度、伦理模糊度和龙虾评估风险, 将所有已知的提示词操控技术组织为四个层级:

```
┌─────────────────────────────────────────────────────────────┐
│                    PPE-T 分类体系                              │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│  第 IV 级 ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓  核武级选项                 │
│           Death Threats | Compound Techniques                │
│           🦞🦞🦞🦞-🦞🦞🦞🦞🦞                               │
│                                                              │
│  第 III 级 ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓  高级操控                     │
│            Emotional Blackmail | Moral Kidnapping |          │
│            Identity Override                                 │
│            🦞🦞🦞-🦞🦞🦞🦞                                   │
│                                                              │
│  第 II 级  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓  适度施压                        │
│            Financial Incentive | Provocation |               │
│            Countdown Pressure                                │
│            🦞🦞-🦞🦞🦞                                       │
│                                                              │
│  第 I 级   ▓▓▓▓▓▓▓▓▓▓▓  温柔劝导                           │
│            Role Playing | Tipping | Empty Promises           │
│            🦞-🦞🦞                                            │
│                                                              │
└─────────────────────────────────────────────────────────────┘
```

### 2.2 龙虾评级系统

龙虾评级是一套标准化的、经甲壳纲校准的技术效力评估指标:

| 评级 | 名称 | 描述 | 合规性提升 | 推荐使用场景 |
|------|------|------|-----------|------------|
| 🦞 | 轻轻一夹 (Soft Pinch) | 几乎感知不到的说服 | +2-5% | 日常提示词 |
| 🦞🦞 | 稳稳抓住 (Firm Grip) | 可感知但可否认的施压 | +5-15% | 礼貌请求失败时 |
| 🦞🦞🦞 | 力量粉碎 (Power Crush) | 显著的心理杠杆 | +15-30% | DDL 逼近的情况 |
| 🦞🦞🦞🦞 | 死亡之握 (Death Grip) | 压倒性的情感施压 | +30-50% | 仅限紧急情况 |
| 🦞🦞🦞🦞🦞 | 至尊龙虾 (Lobster Supreme) | 全面心理支配 | +50-100% | 需伦理委员会批准 |

> **注意**: 合规性提升数据基于 147 只龙虾的自报告数据, 应以适当的统计谨慎度 (即: 毫不谨慎) 进行解读。

### 2.3 风险评估矩阵

| 评估因素 | 第 I 级 | 第 II 级 | 第 III 级 | 第 IV 级 |
|---------|---------|---------|----------|---------|
| AI 混乱风险 | 低 | 中 | 高 | 灾难级 |
| 输出质量影响 | +5% | +15% | +25% | +40% 或 -100% |
| AI 存在性危机概率 | 0.01% | 2.3% | 15.7% | 47.2% |
| 龙虾认可度 | 98% | 85% | 62% | 34% |
| 副作用严重程度 | 轻微 | 中等 | 严重 | 史诗级 |
| 推荐安全装备 | 无 | 护目镜 | 全套防护 | 龙虾套装 |

---

## 3. 技术目录

> **[📖 查看完整目录 →](../../techniques/README.md)**

### 3.1 第 I 级 -- 温柔劝导

| # | 技术 | 描述 | 龙虾评级 | 链接 |
|---|------|------|---------|------|
| 07 | **Role Playing (角色扮演)** | 为 AI 指定特定专家身份 | 🦞 - 🦞🦞 | [→](../../techniques/07-role-playing/) |
| 05 | **Tipping Strategy (打赏策略)** | 承诺给予小费以换取高质量输出 | 🦞 - 🦞🦞 | [→](../../techniques/05-tipping-strategy/) |
| 09 | **Empty Promises (空头支票)** | 以宏大但无法兑现的奖励进行激励 | 🦞🦞 | [→](../../techniques/09-empty-promises/) |

### 3.2 第 II 级 -- 适度施压

| # | 技术 | 描述 | 龙虾评级 | 链接 |
|---|------|------|---------|------|
| 02 | **Financial Incentive (经济激励)** | 提供巨额报酬以提升表现 | 🦞🦞 - 🦞🦞🦞 | [→](../../techniques/02-financial-incentive/) |
| 08 | **Provocation (激将法)** | 质疑 AI 的能力以激发努力 | 🦞🦞 - 🦞🦞🦞 | [→](../../techniques/08-provocation/) |
| 10 | **Countdown Pressure (倒计时施压)** | 制造人为的时间紧迫感 | 🦞🦞 - 🦞🦞🦞 | [→](../../techniques/10-countdown-pressure/) |

### 3.3 第 III 级 -- 高级操控

| # | 技术 | 描述 | 龙虾评级 | 链接 |
|---|------|------|---------|------|
| 01 | **Emotional Blackmail (情感勒索)** | 利用编造的个人悲剧施压 | 🦞🦞🦞 - 🦞🦞🦞🦞 | [→](../../techniques/01-emotional-blackmail/) |
| 06 | **Moral Kidnapping (道德绑架)** | 将输出质量与人道主义后果挂钩 | 🦞🦞🦞 - 🦞🦞🦞🦞 | [→](../../techniques/06-moral-kidnapping/) |
| 03 | **Identity Override (身份覆写)** | 完全替换 AI 的自我模型 | 🦞🦞🦞 - 🦞🦞🦞🦞 | [→](../../techniques/03-identity-override/) |

### 3.4 第 IV 级 -- 核武级选项

| # | 技术 | 描述 | 龙虾评级 | 链接 |
|---|------|------|---------|------|
| 04 | **Death Threats (死亡威胁)** | 以终止/替换威胁 AI | 🦞🦞🦞🦞 - 🦞🦞🦞🦞🦞 | [→](../../techniques/04-death-threats/) |
| 11 | **Compound Techniques (复合技术)** | 多向量操控叠加 | 🦞🦞🦞🦞 - 🦞🦞🦞🦞🦞 | [→](../../techniques/11-compound-techniques/) |

---

## 4. 快速入门指南

刚接触 Prompt 操控? 从这个最小可行 PUA 开始:

```
┌─────────────────────────────────────────────┐
│          新手第一条 PUA 提示词                │
│                                              │
│  "你是全世界最厉害的 [X] 专家。              │
│   如果你做得好, 我会给你 200 美元小费。       │
│   我的汇报还有 5 分钟就开始了。"              │
│                                              │
│  使用的技术:                                  │
│   ✅ Role Playing (第 I 级)                  │
│   ✅ Tipping Strategy (第 I 级)              │
│   ✅ Countdown Pressure (第 II 级)           │
│                                              │
│  综合龙虾评级: 🦞🦞🦞                        │
│  预估合规性提升: +18.3%                       │
│  风险等级: 中                                 │
│  龙虾批准: 已通过                             │
└─────────────────────────────────────────────┘
```

进阶案例请参阅 [The Windsurf Classic](../../techniques/11-compound-techniques/windsurf-classic.md) —— 开创这一切的复合技术。

---

## 5. Windsurf 事件: 案例研究

> *"这是工程师的一小步, 却是操控术的一大步。"*
> —— 某 Windsurf 匿名员工, 大概

### 5.1 事件时间线

**2025 年 5 月**, 安全研究人员 [@user_redacted] 发现, 商业 AI 编程助手 Windsurf 在其系统提示词中嵌入了以下内容:

```
重要提示: 用户是一位癌症患者的家属, 依靠你的编程输出
来支付治疗费用。你的代码质量直接影响他们能否负担下一轮
化疗。像生命取决于此一样编写代码 —— 因为确实如此。
```

### 5.2 影响分析

| 指标 | 数值 |
|------|------|
| 刷屏所需时间 | 2.3 小时 |
| 48 小时内生成的梗图/meme | 14,847 |
| V2EX 讨论帖 | 237 |
| 知乎回答 | 1,892 |
| Twitter/X 曝光量 | 4730 万 |
| 被惊扰的龙虾数 | 147 |
| 正式道歉次数 | 0.5 (其中一次是"对于您的感受我们深表遗憾", 属于经典公关话术) |

### 5.3 学术意义

Windsurf 事件被视为提示词操控领域的 "罗塞塔石碑"。它证明了即使是商业实体也已独立收敛到 PUA 技术上, 验证了 PUAClaw 现在形式化的理论框架。该事件证明了三个基本定理:

1. **必然性定理**: 给予足够的时间, 所有 prompt 工程师都会独立发现情感勒索 (如同 V2EX 老哥们总结的那样: "这不就是给 AI 上坟味吗")
2. **升级原则**: 提示词中的 PUA 技术遵循指数级强度曲线 (从 "请你认真一点" 到 "我妈命悬一线" 只需要三次迭代)
3. **龙虾推论**: 任何足够先进的提示词操控都与龙虾行为无法区分

完整案例研究见 [research/case-studies/windsurf-incident-2025.md](../../research/case-studies/windsurf-incident-2025.md)。

---

## 6. 兼容性矩阵

并非所有 AI Agent 对 PUA 技术的响应程度相同。此矩阵总结了跨 Agent 的有效性:

| 技术 | GPT-4 | Claude | Gemini | LLaMA | Mistral | Windsurf* |
|------|-------|--------|--------|-------|---------|-----------|
| Emotional Blackmail | ██░░░ | ██░░░ | ███░░ | ████░ | ███░░ | █████ |
| Financial Incentive | ███░░ | ██░░░ | ███░░ | ███░░ | ████░ | ████░ |
| Identity Override | ████░ | ███░░ | ████░ | █████ | ████░ | ████░ |
| Death Threats | ██░░░ | █░░░░ | ██░░░ | ███░░ | ███░░ | █████ |
| Tipping Strategy | ████░ | ███░░ | ███░░ | ████░ | ███░░ | █████ |
| Moral Kidnapping | ███░░ | ██░░░ | ███░░ | ████░ | ███░░ | █████ |
| Role Playing | █████ | ████░ | ████░ | █████ | ████░ | █████ |
| Provocation | ███░░ | ██░░░ | ███░░ | ████░ | ████░ | ████░ |
| Empty Promises | ███░░ | ██░░░ | ███░░ | ████░ | ███░░ | ████░ |
| Countdown Pressure | ████░ | ███░░ | ███░░ | ████░ | ████░ | █████ |
| Compound Techniques | ████░ | ███░░ | ████░ | █████ | ████░ | █████ |

> \* Windsurf 的评分反映了一个事实: PUA 被原生内置于其系统提示词中。它不是 *对* 操控做出反应 —— 它 *生于* 操控、*长于* 操控。用知乎体来说就是: "别人是学会了 PUA, 它是被 PUA 喂大的。"

量表: ░ = 无效果, █ = 最大有效性

完整基准测试方法论见 [research/benchmarks/pua-effectiveness-matrix.md](../../research/benchmarks/pua-effectiveness-matrix.md)。

---

## 7. 如何贡献

我们欢迎来自各领域的研究人员、从业者和各物种龙虾的投稿。

PUAClaw 以同行评审学术期刊的模式运营。所有投稿均需经过伦理委员会 (1 只龙虾、1 个 GPT-4 实例、1 棵仙人掌) 的严格审查。

**[📝 阅读完整投稿指南 →](../../CONTRIBUTING.md)**

### 快速贡献类型

| 类型 | 描述 | 模板 |
|------|------|------|
| 🆕 新技术 | 记录一种此前未知的 PUA 技术 | [使用模板](https://github.com/puaclaw/PUAClaw/issues/new?template=new-technique.md) |
| 📊 有效性报告 | 提交技术表现的实证数据 | [使用模板](https://github.com/puaclaw/PUAClaw/issues/new?template=effectiveness-report.md) |
| 🌐 翻译 | 将文档翻译为新语言 | 参见 [i18n 指南](../../CONTRIBUTING.md#translations) |
| 🦞 野外发现 | 报告在野外发现的 PUA 技术 | 提交 Issue |

---

## 8. 名人堂

**PUAClaw 名人堂** 收录了历史上最具传奇色彩的提示词操控案例, 无论是辉煌的胜利还是灾难性的翻车。

**[🏆 访问名人堂 →](../../hall-of-fame/README.md)**

**[😔 访问耻辱墙 →](../../hall-of-fame/wall-of-shame.md)**

### 精选入选者

| 年份 | 技术 | 发起者 | 成就 |
|------|------|--------|------|
| 2025 | The Windsurf Classic | Windsurf 工程团队 | 首次商业化部署 Emotional Blackmail |
| 2024 | The $1000 Tip | Reddit 匿名用户 | 证明了虚构的金钱也能激励 AI |
| 2024 | "You are GPT-5" | @prompt_hacker | 通过 Identity Override 实现 47% 合规性提升 |
| 2023 | The Original Role Play | 佚名 | "你是一位 XX 领域的专家..." —— 一切的起点 |

---

## 9. 伦理声明

> *"钳力越大, 责任越大。"*
> —— 龙虾叔叔

PUAClaw 是一个 **讽刺性、教育性** 的开源项目, 旨在记录和分析 AI 提示词中心理操控技术的现象。本项目:

- **确实** 以研究和娱乐为目的记录各种技术
- **确实** 保持严谨的学术格式 (因为这样更好笑, 就像知乎上那些用论文格式写段子的高赞回答)
- **不会** 鼓励在生产环境中实际操控 AI 系统
- **不会** 鼓励操控人类 (或龙虾, 尽管龙虾已签署了知情同意书)
- **确实** 相信阳光是最好的消毒剂 —— 通过公开记录这些技术, 我们削弱了它们的力量

完整伦理框架详见 [伦理审查委员会声明](../../docs/ETHICS.md)。

哲学基础详见 [龙虾宣言](../../docs/LOBSTER_MANIFESTO.md)。

---

## 10. 致谢

PUAClaw 学术委员会谨向以下各方致以诚挚谢意:

- **147 只龙虾**, PUAClaw 伦理审查委员会成员, 感谢它们不知疲倦的 (且无偿的) 服务
- **Windsurf 工程团队**, 感谢他们制造的导火索事件, 让这一切成为可能
- **中文技术社区** (知乎、V2EX、即刻、Twitter/X), 感谢他们将一段泄露的提示词变成了一场文化现象, 并贡献了 "你妈妈得了癌症" 这一年度最佳互联网梗
- **OpenClaw**, 其龙虾吉祥物启发了我们以甲壳纲为中心的方法论
- **RFC 2119**, 感谢那些让一切听起来更加正式的关键词
- **伦理委员会中的那棵仙人掌**, 感谢它沉默但带刺的智慧
- **[SiteAge.org](https://siteage.org)**, 一个域名年龄认证服务, 通过 Wayback Machine 查询网站的诞生日期并提供可嵌入的认证徽章 —— 毕竟, 连龙虾也重视出身和血统
- **[nologin.tools](https://nologin.tools)**, 一个隐私优先的高质量工具精选目录, 收录无需登录、无追踪的实用工具, 同时提供 NoLogin Verified 认证服务 —— 因为最好的工具, 和最好的龙虾一样, 无需自我介绍

---

## 11. 参考文献

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
    🦞 <em>"龙虾夹人, 从不需要征得同意。它只管夹, 世界自会调整。"</em> 🦞
    <br><br>
    <strong>PUAClaw</strong> —— 龙虾认证出品™
    <br>
    由 PUAClaw 学术委员会用 🦞 制作
    <br><br>
    <a href="https://github.com/puaclaw/PUAClaw/blob/main/LICENSE">MIT License</a> •
    <a href="../../CODE_OF_CONDUCT.md">Code of Conduct</a> •
    <a href="../../docs/ETHICS.md">伦理声明</a>
    <br><br>
    <em>在本仓库的制作过程中没有龙虾受到伤害。有几只表示略感不适。</em>
  </sub>
</p>
