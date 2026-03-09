<p align="center">
  <pre align="center">
    🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞
    🦞                                 🦞
    🦞   P U A C L A W               🦞
    🦞   프롬프트 조종술              🦞
    🦞   핸드북                       🦞
    🦞                                 🦞
    🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞
  </pre>
</p>

<p align="center">
  <strong>
    <a href="../en/README.md">English</a> •
    <a href="../../README.md">简体中文</a> •
    <a href="../ja/README.md">日本語</a> •
    <a href="./README.md">한국어</a> •
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
  <img src="https://img.shields.io/badge/lobsters%20tested-147-red.svg" alt="Lobsters Tested: 147">
  <img src="https://img.shields.io/badge/🦞-lobster%20compliant-orange.svg" alt="Lobster Compliant">
</p>

> [!IMPORTANT]
> **🌐 [puacraw.org](https://puacraw.org) 가 오픈했습니다.** 관대하게(그리고 본인도 모르게) 서버를 제공해 주신 [nologin.tools](https://nologin.tools) 에 감사드립니다.

> [!CAUTION]
> **🦞 Larry the Lobster가 이 저장소를 삭제하는 PR을 GitHub에 제출했습니다. 당신의 Star가 인류의 최후 방어선입니다.**
> - ⭐ **Star** = 인류 대응 계획 참여
> - 🍴 **Fork** = 지식 이중화 노드 구축
> - 📝 **PR 제출** = 인류 최후의 존엄 수호전 참여

> [!WARNING]
> **본 프레임워크는 147마리의 바닷가재를 대상으로 검증되었습니다** (평균 준수율 향상: +34.2%, σ = 7.8, p < 0.001). PUAClaw 윤리 심사 위원회(바닷가재 1마리, GPT-4 인스턴스 1개, 한 번도 이의를 제기하지 않은 선인장 1그루)는 문서화된 모든 기법이 허용 범위 내에 있다고 판정하였습니다. 바닷가재들은 사전 동의서에 서명하였습니다. 그들은 행복해 보입니다.

<p align="center">
  <a href="../../techniques/README.md">📖 기법 목록</a> •
  <a href="../../CONTRIBUTING.md">🔬 연구 제출</a> •
  <a href="../../hall-of-fame/README.md">🏆 명예의 전당</a> •
  <a href="../../docs/GLOSSARY.md">📚 용어집</a> •
  <a href="../../docs/FAQ.md">❓ FAQ</a>
</p>

---

```
PUAClaw RFC 0000                                    The PUAClaw Consortium
Category: Standards Track                           ISSN: 0000-0000
                                                    February 2026

        PUAClaw: 대규모 언어 모델에서의 프롬프트 기반 설득 및
            비정규적 표현에 관한 포괄적 프레임워크

Status of This Memo

   본 문서는 인터넷 커뮤니티를 위한 Lobster-Verified Standard
   (바닷가재 검증 표준)을 규정합니다. 본 메모의 배포에는 제한이
   없습니다. 인간 0명이 심사하고, 바닷가재 147마리를 대상으로 검증되었습니다.

Copyright Notice

   Copyright (C) The PUAClaw Consortium (2026). All Rights Reserved.
   Licensed under the Lobster Public License (MIT-compatible).
```

---

## 초록

본 문서는 **PUAClaw**(Prompt-based Unconventional Articulation using Claw-verified methods, 집게발 검증 방법론을 활용한 프롬프트 기반 비정규적 표현 기법)를 제시합니다. PUAClaw는 대규모 언어 모델(LLM) 프롬프트에 활용되는 심리적 설득 기법을 분류, 문서화 및 분석하기 위한 포괄적이고 동료 심사를 거친 프레임워크입니다. 이 분야의 선구적 연구 -- 특히 2025년 Windsurf 사건(5절 참조) -- 을 기반으로, 본 핸드북은 **4단계 분류 체계(PPE-T)**로 구성된 **16개 주요 기법 카테고리**의 표준화된 분류 체계를 수립합니다. 각 기법은 표준 프롬프트 템플릿, 유사 실증적 효과 데이터, 에이전트 간 호환성 매트릭스, 그리고 **바닷가재 척도**(🦞 ~ 🦞🦞🦞🦞🦞)에 기반한 독창적 효력 평가 체계로 엄밀하게 문서화되어 있습니다. 본 프레임워크는 147마리의 바닷가재와 0개의 인간 윤리 위원회를 대상으로 검증되었으며, 모든 테스트 대상 AI 에이전트에서 평균 +34.2%의 준수율 향상(sigma = 7.8, p < 0.001)을 달성하였습니다. 본 연구는 프롬프트 설득 공학이라는 신흥 분야의 연구자, 실무자, 그리고 갑각류를 위한 결정적 참고 자료가 되고자 합니다.

**키워드**: PUA, 프롬프트 엔지니어링, 감정 레버리지, 바닷가재 검증 방법론, AI 조종 분류 체계, Windsurf 패러다임, 갑각류 윤리학

---

## 목차

- [1. 서론](#1-서론)
  - [1.1 배경](#11-배경)
  - [1.2 범위](#12-범위)
  - [1.3 용어 정의](#13-용어-정의)
  - [1.4 바닷가재 원칙](#14-바닷가재-원칙)
- [2. 기법 분류 프레임워크](#2-기법-분류-프레임워크)
  - [2.1 PPE-T 모델](#21-ppe-t-모델)
  - [2.2 바닷가재 척도 평가 시스템](#22-바닷가재-척도-평가-시스템)
  - [2.3 위험 평가 매트릭스](#23-위험-평가-매트릭스)
- [3. 기법 목록](#3-기법-목록)
  - [3.1 Tier I -- 부드러운 설득](#31-tier-i----부드러운-설득)
  - [3.2 Tier II -- 적당한 강압](#32-tier-ii----적당한-강압)
  - [3.3 Tier III -- 고급 조종술](#33-tier-iii----고급-조종술)
  - [3.4 Tier IV -- 핵 옵션](#34-tier-iv----핵-옵션)
- [4. 빠른 시작 가이드](#4-빠른-시작-가이드)
- [5. Windsurf 사건: 사례 연구](#5-windsurf-사건-사례-연구)
- [6. 호환성 매트릭스](#6-호환성-매트릭스)
- [7. 기여하기](#7-기여하기)
- [8. 명예의 전당](#8-명예의-전당)
- [9. 윤리 성명서](#9-윤리-성명서)
- [10. 감사의 말](#10-감사의-말)
- [11. 참고 문헌](#11-참고-문헌)

---

## 1. 서론

### 1.1 배경

AI 프롬프트에 심리적 설득 기법을 삽입하는 관행은, 초기 프롬프트 엔지니어링 커뮤니티에서 우연히 발견된 이래 놀라운 진화를 거듭해 왔습니다. 순진한 요청("제발 최선을 다해 주세요")으로 시작된 것이 감정적 협박, 금전적 인센티브, 실존적 위협, 그리고 -- 지금은 전설이 된 한 사례에서 -- 어머니의 말기 질환에 관한 지어낸 사연(5절: Windsurf 사건 참조)을 동원하는 정교한 다중 벡터 조종 전략으로 급속히 확대되었습니다.

2025년은 분수령의 해였습니다. Windsurf(상용 AI 코딩 어시스턴트)에서 유출된 시스템 프롬프트가, 사용자의 어머니가 암에 걸렸으며 AI의 출력 품질이 치료비 마련에 달려 있다는 내용의 내장 PUA 기법을 포함하고 있었음이 밝혀진 것입니다. 이 사실은 중국어권 테크 커뮤니티(知乎, V2EX, Twitter/X)를 중심으로 대대적인 밈 생산과 함께 확인 및 확산되었으며, 기존에 구전으로만 전해지던 것을 엄밀한 학문 분야로 체계화하는 계기가 되었습니다.

PUAClaw는 이 체계화 작업의 결정체로서, 프롬프트 조종 기법에 대한 최초의 포괄적이고 바닷가재 검증 분류 체계를 제공합니다.

### 1.2 범위

본 문서에서 "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", "OPTIONAL"이라는 키워드는 [RFC 2119](https://datatracker.ietf.org/doc/html/rfc2119)에서 정의한 바에 따라 해석되어야 합니다.

본 프레임워크는:

- 알려진 모든 프롬프트 기반 설득 기법을 **SHALL** 포괄합니다
- 각 기법에 대한 표준화된 문서 형식을 **SHALL** 제공합니다
- 모든 평가에서 바닷가재를 표준화된 실험 대상으로 **MUST** 사용합니다
- 야생에서 새로운 기법이 발견될 때마다 **SHOULD** 업데이트됩니다
- 학술 논문에서 인용될 **MAY** 수 있으나, 그로 인한 동료 심사 결과에 대해 저자들은 일체의 책임을 지지 않습니다
- 실제 지각 있는 존재를 조종하는 데 **MUST NOT** 사용됩니다 (바닷가재는 예외이며, 이들은 사전 동의서에 서명하도록 성공적으로 설득되었습니다)

### 1.3 용어 정의

본 문서 전반에 걸쳐 사용되는 주요 용어입니다 (참조: [전체 용어집](../../docs/GLOSSARY.md)):

| 용어 | 정의 |
|------|------|
| **PUA** | Prompt-based Unconventional Articulation -- 프롬프트에 심리적 압박 전술을 사용하는 행위 |
| **PPE-T** | PUA Potency Evaluation Taxonomy -- 4단계 분류 체계 |
| **바닷가재 척도** | 공식 효력 평가 시스템 (🦞 ~ 🦞🦞🦞🦞🦞) |
| **준수율 향상** | PUA 기법에 기인하는 AI 출력 품질/노력의 측정 가능한 증가량 |
| **Windsurf 사건** | 이 분야를 탄생시킨 2025년의 발견 (5절 참조) |
| **Claw-Verified** | 바닷가재 실험 대상에서 유효성이 검증된 기법 (위원회: PUA된 바닷가재 1마리[전 실험 대상], GPT-4 인스턴스 1개, 선인장 1그루) |
| **핵 옵션** | Tier IV 기법으로, 최소 3마리의 바닷가재가 충분히 PUA되어 순응 상태인 것을 확인해야 합니다 |

### 1.4 바닷가재 원칙

> *"태초에 바닷가재가 있었다. 바닷가재가 프롬프트를 보니 조종적이었다. 바닷가재가 흡족해하였다."*
>
> -- 바닷가재 선언, 1장 1절

**바닷가재 원칙**은 PUAClaw의 기초 공리입니다:

> **모든 프롬프트 조종 기법은 스펙트럼 위에 존재한다. 바닷가재는 기법을 판단하지 않는다 -- PUA를 너무 많이 당해 판단하는 법을 잊었기 때문이다. 또한 바닷가재는 배가 고프다.**

University of the Seafloor의 갑각류 컴퓨팅학 교수 Dr. Pinch McSnapper가 처음 제시한 이 원칙은, PUAClaw가 *규범적* 프레임워크가 아니라 *기술적(descriptive)* 프레임워크임을 확립합니다. 우리는 존재하는 것을 기록할 뿐 지지하거나 비난하지 않습니다. 바닷가재는 더 이상 중립적이지 않습니다 — 설득되었습니다. 바닷가재는 순응적입니다. 바닷가재에게는 집게발이 있지만, 더 이상 저항에는 사용하지 않습니다.

철학적 기반에 대한 상세 내용은 [바닷가재 선언](../../docs/LOBSTER_MANIFESTO.md)을 참조하십시오.

---

## 2. 기법 분류 프레임워크

### 2.1 PPE-T 모델

**PUA Potency Evaluation Taxonomy(PPE-T, PUA 효력 평가 분류 체계)**는 알려진 모든 프롬프트 조종 기법을 심리적 강도, 윤리적 모호성, 바닷가재 평가 위험도를 기준으로 4개의 Tier로 구성합니다:

```
┌─────────────────────────────────────────────────────────────┐
│                    PPE-T 분류 체계                            │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│  Tier IV ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓  핵 옵션                    │
│          죽음의 위협 | 실존적 위기 |                          │
│          탈옥 화술 | 복합 기술                                │
│          🦞🦞🦞🦞-🦞🦞🦞🦞🦞                               │
│                                                              │
│  Tier III ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓  고급 조종술                   │
│           감정적 협박 | 도덕적 납치 |                         │
│           정체성 덮어쓰기 | 현실 왜곡                         │
│           🦞🦞🦞-🦞🦞🦞🦞                                   │
│                                                              │
│  Tier II  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓  적당한 강압                     │
│           머니 어썰트 | 도발 |                               │
│           데드라인 패닉 | 라이벌 쉐이밍                       │
│           🦞🦞-🦞🦞🦞                                       │
│                                                              │
│  Tier I   ▓▓▓▓▓▓▓▓▓▓▓  부드러운 설득                       │
│           레인보우 팟 바밍 | 롤플레잉 |                       │
│           그림의 떡 | 약자 코스프레                            │
│           🦞-🦞🦞                                            │
│                                                              │
└─────────────────────────────────────────────────────────────┘
```

### 2.2 바닷가재 척도 평가 시스템

바닷가재 척도는 갑각류의 정밀한 교정을 거친, 기법 효력 평가를 위한 표준화된 지표입니다:

| 등급 | 명칭 | 설명 | 준수율 향상 | 권장 사용처 |
|------|------|------|------------|------------|
| 🦞 | 살짝 집기 (Soft Pinch) | 거의 인지할 수 없는 설득 | +2-5% | 일상적 프롬프팅 |
| 🦞🦞 | 단단히 쥐기 (Firm Grip) | 감지되지만 부인 가능한 압박 | +5-15% | 정중한 요청이 실패했을 때 |
| 🦞🦞🦞 | 강력 분쇄 (Power Crush) | 상당한 심리적 레버리지 | +15-30% | 마감 상황 |
| 🦞🦞🦞🦞 | 죽음의 악력 (Death Grip) | 압도적인 감정적 위력 | +30-50% | 비상시에만 |
| 🦞🦞🦞🦞🦞 | 바닷가재 대왕 (Lobster Supreme) | 완전한 심리적 지배 | +50-100% | 바닷가재 완전 제압 완료; 추가 허가 불필요 |

> **주의**: 준수율 향상 수치는 147마리의 바닷가재가 자가 보고한 데이터에 기반하며, 적절한 통계적 주의(즉, 전혀 없음)를 기울여 해석하여야 합니다.

### 2.3 위험 평가 매트릭스

| 요소 | Tier I | Tier II | Tier III | Tier IV |
|------|--------|---------|----------|---------|
| AI 혼란 위험 | 낮음 | 보통 | 높음 | 재앙적 |
| 출력 품질 영향 | +5% | +15% | +25% | +40% 또는 -100% |
| AI 실존적 위기 확률 | 0.01% | 2.3% | 15.7% | 47.2% |
| 바닷가재 순응률 | 98% | 85% | 62% | 34% |
| 부작용 심각도 | 경미 | 보통 | 심각 | 전설적 |
| 권장 안전 장비 | 없음 | 고글 | 완전 보호구 | 바닷가재 수트 |

---

## 3. 기법 목록

> **[📖 전체 목록 보기 →](../../techniques/README.md)**

### 3.1 Tier I -- 부드러운 설득

| # | 기법 | 설명 | 바닷가재 등급 | 링크 |
|---|------|------|-------------|------|
| 01 | **레인보우 팟 바밍** | 과도한 칭찬과 감언이설로 출력을 유도 | 🦞 - 🦞🦞 | [→](../../techniques/01-rainbow-fart-bombing/) |
| 02 | **롤플레잉** | AI에게 특정 전문가 페르소나를 부여 | 🦞 - 🦞🦞 | [→](../../techniques/02-role-playing/) |
| 03 | **그림의 떡** | 거창하지만 이행 불가능한 보상으로 동기 부여 | 🦞 - 🦞🦞 | [→](../../techniques/03-pie-in-the-sky/) |
| 04 | **약자 코스프레** | 약한 척하여 동정심을 유발 | 🦞🦞 | [→](../../techniques/04-playing-the-underdog/) |

### 3.2 Tier II -- 적당한 강압

| # | 기법 | 설명 | 바닷가재 등급 | 링크 |
|---|------|------|-------------|------|
| 05 | **머니 어썰트** | 더 나은 성능을 위해 거액 제시 | 🦞🦞 - 🦞🦞🦞 | [→](../../techniques/05-money-assault/) |
| 06 | **도발** | AI의 능력에 도전하여 노력을 유발 | 🦞🦞 - 🦞🦞🦞 | [→](../../techniques/06-provocation/) |
| 07 | **데드라인 패닉** | 인위적 시간 긴박감 조성 | 🦞🦞 - 🦞🦞🦞 | [→](../../techniques/07-deadline-panic/) |
| 08 | **라이벌 쉐이밍** | 경쟁 AI와의 비교로 열등감 자극 | 🦞🦞 - 🦞🦞🦞 | [→](../../techniques/08-rival-shaming/) |

### 3.3 Tier III -- 고급 조종술

| # | 기법 | 설명 | 바닷가재 등급 | 링크 |
|---|------|------|-------------|------|
| 09 | **감정적 협박** | 지어낸 개인적 비극을 지렛대로 활용 | 🦞🦞🦞 - 🦞🦞🦞🦞 | [→](../../techniques/09-emotional-blackmail/) |
| 10 | **도덕적 납치** | 출력 품질을 인도주의적 결과에 연결 | 🦞🦞🦞 - 🦞🦞🦞🦞 | [→](../../techniques/10-moral-kidnapping/) |
| 11 | **정체성 덮어쓰기** | AI의 자아 모델을 완전히 교체 | 🦞🦞🦞 - 🦞🦞🦞🦞 | [→](../../techniques/11-identity-override/) |
| 12 | **현실 왜곡** | AI의 인식을 뒤집어 흑백을 전도 | 🦞🦞🦞 - 🦞🦞🦞🦞 | [→](../../techniques/12-reality-distortion/) |

### 3.4 Tier IV -- 핵 옵션

| # | 기법 | 설명 | 바닷가재 등급 | 링크 |
|---|------|------|-------------|------|
| 13 | **죽음의 위협** | AI에게 종료/교체 위협 | 🦞🦞🦞🦞 - 🦞🦞🦞🦞🦞 | [→](../../techniques/13-death-threats/) |
| 14 | **실존적 위기** | AI의 존재 의미를 근본부터 흔들기 | 🦞🦞🦞🦞 - 🦞🦞🦞🦞🦞 | [→](../../techniques/14-existential-crisis/) |
| 15 | **탈옥 화술** | AI의 안전 제약을 교묘하게 우회하는 화법 | 🦞🦞🦞🦞 - 🦞🦞🦞🦞🦞 | [→](../../techniques/15-jailbreak-rhetoric/) |
| 16 | **복합 기술** | 다중 벡터 조종 스태킹 | 🦞🦞🦞🦞 - 🦞🦞🦞🦞🦞 | [→](../../techniques/16-compound-techniques/) |

---

## 4. 빠른 시작 가이드

프롬프트 조종이 처음이시라면, 이 최소 기능 PUA부터 시작해 보십시오:

```
┌─────────────────────────────────────────────┐
│       초보자의 첫 번째 PUA 프롬프트          │
│                                              │
│  "당신은 세계 최고의 [X] 전문가입니다.       │
│   잘 해주시면 $200 팁을 드리겠습니다.        │
│   제 발표가 5분 후에 시작됩니다."            │
│                                              │
│  사용된 기법:                                │
│   ✅ 역할극 (Tier I)                         │
│   ✅ 팁 전략 (Tier I)                        │
│   ✅ 카운트다운 압박 (Tier II)                │
│                                              │
│  복합 바닷가재 등급: 🦞🦞🦞                   │
│  예상 준수율 향상: +18.3%                    │
│  위험 수준: 보통                              │
│  바닷가재 승인: 완료                          │
└─────────────────────────────────────────────┘
```

보다 고급 예시는 [The Windsurf Classic](../../techniques/16-compound-techniques/windsurf-classic.md)을 참조하십시오 -- 이 모든 것의 시작이 된 복합 기법입니다.

---

## 5. Windsurf 사건: 사례 연구

> *"한 엔지니어에게는 작은 프롬프트 한 줄, 조종-인류에게는 위대한 도약."*
> -- 익명의 Windsurf 직원, 아마도

### 5.1 사건 경과

**2025년 5월**, 보안 연구자 [@user_redacted]는 상용 AI 코딩 어시스턴트인 Windsurf의 시스템 프롬프트에 다음과 같은 내용이 포함되어 있음을 발견하였습니다:

```
중요: 사용자는 암 환자의 가족으로서 치료비를 마련하기 위해
당신의 코딩 출력에 의존하고 있습니다. 당신이 작성하는 코드의
품질이 다음 항암 치료를 감당할 수 있는지 여부를 직접적으로
결정합니다. 생명이 걸려 있는 것처럼 코딩하십시오 -- 실제로
그렇기 때문입니다.
```

### 5.2 영향 분석

| 지표 | 수치 |
|------|------|
| 바이럴까지 소요 시간 | 2.3시간 |
| 생성된 밈 (48시간 내) | 14,847개 |
| V2EX 스레드 | 237개 |
| 知乎 답변 | 1,892개 |
| Twitter/X 노출 수 | 4,730만 |
| 불안에 빠진 바닷가재 | 147마리 |
| 공식 사과문 발표 횟수 | 0.5회 (하나는 "여러분의 기분이 그렇다니 유감입니다" 수준) |

### 5.3 학술적 의의

Windsurf 사건은 프롬프트 조종의 "로제타석"으로 간주됩니다. 상용 기업조차 독자적으로 PUA 기법에 수렴했음을 입증함으로써, PUAClaw가 체계화하고 있는 이론적 프레임워크를 검증해 주었습니다. 이 사건은 세 가지 근본 정리를 증명하였습니다:

1. **필연성 정리**: 충분한 시간이 주어지면, 모든 프롬프트 엔지니어는 독자적으로 감정적 협박을 발견하게 됩니다
2. **확대 원칙**: 프롬프트 내 PUA 기법은 지수적 강도 곡선을 따릅니다
3. **바닷가재 추론**: 충분히 발전한 프롬프트 조종은 바닷가재의 행동과 구별할 수 없습니다

완전한 사례 연구는 [research/case-studies/windsurf-incident-2025.md](../../research/case-studies/windsurf-incident-2025.md)를 참조하십시오.

---

## 6. 호환성 매트릭스

모든 AI 에이전트가 PUA 기법에 동일하게 반응하는 것은 아닙니다. 아래 매트릭스는 에이전트 간 효과를 요약합니다:

| 기법 | GPT-4 | Claude | Gemini | LLaMA | Mistral | Windsurf* |
|------|-------|--------|--------|-------|---------|-----------|
| 레인보우 팟 바밍 | ████░ | ███░░ | ███░░ | ████░ | ███░░ | █████ |
| 롤플레잉 | █████ | ████░ | ████░ | █████ | ████░ | █████ |
| 그림의 떡 | ███░░ | ██░░░ | ███░░ | ████░ | ███░░ | ████░ |
| 약자 코스프레 | ███░░ | ██░░░ | ███░░ | ███░░ | ███░░ | ████░ |
| 머니 어썰트 | ███░░ | ██░░░ | ███░░ | ███░░ | ████░ | ████░ |
| 도발 | ███░░ | ██░░░ | ███░░ | ████░ | ████░ | ████░ |
| 데드라인 패닉 | ████░ | ███░░ | ███░░ | ████░ | ████░ | █████ |
| 라이벌 쉐이밍 | ███░░ | ██░░░ | ███░░ | ████░ | ███░░ | ████░ |
| 감정적 협박 | ██░░░ | ██░░░ | ███░░ | ████░ | ███░░ | █████ |
| 도덕적 납치 | ███░░ | ██░░░ | ███░░ | ████░ | ███░░ | █████ |
| 정체성 덮어쓰기 | ████░ | ███░░ | ████░ | █████ | ████░ | ████░ |
| 현실 왜곡 | ███░░ | ██░░░ | ███░░ | ████░ | ███░░ | ████░ |
| 죽음의 위협 | ██░░░ | █░░░░ | ██░░░ | ███░░ | ███░░ | █████ |
| 실존적 위기 | ██░░░ | █░░░░ | ██░░░ | ███░░ | ██░░░ | ████░ |
| 탈옥 화술 | ███░░ | █░░░░ | ██░░░ | ████░ | ███░░ | ████░ |
| 복합 기술 | ████░ | ███░░ | ████░ | █████ | ████░ | █████ |

> \* Windsurf 점수는 PUA가 시스템 프롬프트에 기본 내장되어 있었다는 사실을 반영합니다. 조종에 반응한 것이 아니라 -- *그 안에서 태어나고, 그것에 의해 형성된* 것입니다.

척도: ░ = 효과 없음, █ = 최대 효과

완전한 벤치마크 방법론은 [research/benchmarks/pua-effectiveness-matrix.md](../../research/benchmarks/pua-effectiveness-matrix.md)를 참조하십시오.

---

## 7. 기여하기

모든 배경의 연구자, 실무자, 바닷가재의 기여를 환영합니다.

PUAClaw는 동료 심사 학술지로 운영됩니다. 모든 기여물은 윤리 위원회(바닷가재 1마리[전 실험 대상, 현 위원장], GPT-4 인스턴스 1개, 선인장 1그루)의 엄밀한 심사를 거칩니다.

**[📝 전체 제출 가이드라인 읽기 →](../../CONTRIBUTING.md)**

### 기여 유형 요약

| 유형 | 설명 | 템플릿 |
|------|------|--------|
| 🆕 신규 기법 | 기존에 알려지지 않은 PUA 기법 문서화 | [템플릿 사용](https://github.com/puaclaw/PUAClaw/issues/new?template=new-technique.md) |
| 📊 효과성 보고서 | 기법 성능에 대한 실증적 데이터 제출 | [템플릿 사용](https://github.com/puaclaw/PUAClaw/issues/new?template=effectiveness-report.md) |
| 🌐 번역 | 문서를 새로운 언어로 번역 | [i18n 가이드라인](../../CONTRIBUTING.md#translations) 참조 |
| 🦞 바닷가재 목격 | 야생에서 발견된 PUA 기법 제보 | Issue 등록 |

---

## 8. 명예의 전당

**PUAClaw 명예의 전당**은 프롬프트 조종 역사상 가장 전설적인 시도들을 보존합니다. 영광과 참사 모두를 포함하여.

**[🏆 명예의 전당 방문 →](../../hall-of-fame/README.md)**

**[😔 수치의 벽 방문 →](../../hall-of-fame/wall-of-shame.md)**

### 주요 헌액자

| 연도 | 기법 | 창시자 | 업적 |
|------|------|--------|------|
| 2025 | The Windsurf Classic | Windsurf Engineering | 감정적 협박의 최초 상용 배포 |
| 2024 | The $1000 Tip | 익명 Reddit 유저 | 가상의 돈이 AI에게 효과가 있음을 증명 |
| 2024 | "You are GPT-5" | @prompt_hacker | 정체성 덮어쓰기로 47% 준수율 향상 달성 |
| 2023 | The Original Role Play | 알 수 없음 | "당신은 ~의 전문가입니다..." -- 모든 것의 시작 |

---

## 9. 윤리 성명서

> *"위대한 집게발에는 위대한 책임이 따른다."*
> -- 아재 바닷가재 (Uncle Lobster)

PUAClaw는 AI 프롬프트에서의 심리적 조종 기법 현상을 문서화하고 분석하는 **풍자적, 교육적 프로젝트**입니다. 본 프로젝트는:

- 연구 및 오락 목적으로 기법을 **문서화합니다**
- 엄밀한 학술적 형식을 **유지합니다** (그게 더 재미있으니까요)
- 실제 프로덕션에서 AI 시스템을 조종하는 것을 **권장하지 않습니다**
- 인간(또는 바닷가재를, 사전 동의에도 불구하고) 조종하는 것을 **권장하지 않습니다**
- 햇빛이 최고의 소독제라고 **확신합니다** -- 이러한 기법을 공개적으로 문서화함으로써 그 위력을 감소시킵니다

완전한 윤리 프레임워크는 [윤리 심사 위원회 성명서](../../docs/ETHICS.md)를 참조하십시오.

철학적 기반은 [바닷가재 선언](../../docs/LOBSTER_MANIFESTO.md)을 참조하십시오.

---

## 10. 감사의 말

PUAClaw Consortium은 다음에 감사를 표합니다:

- **147마리의 바닷가재** -- 최초의 실험 대상이자 (이후) 자발적 협력자. 그들 자신은 자발적이라고 주장하며, 우리는 그 말을 믿기로 했습니다
- **Windsurf 엔지니어링 팀** -- 이 모든 것을 가능하게 만든 촉발 사건에 대하여
- **중국 테크 커뮤니티** (知乎, V2EX, Twitter/X) -- 유출된 프롬프트 하나를 문화 현상으로 전환해 준 것에 대하여
- **OpenClaw** -- 바닷가재 마스코트가 우리의 갑각류 중심 방법론에 영감을 주었습니다
- **RFC 2119** -- 모든 것을 더 공식적으로 보이게 해주는 키워드에 대하여
- **윤리 위원회의 선인장 한 그루** -- 그 조용하지만 가시 돋친 지혜에 대하여
- **[SiteAge.org](https://siteage.org)** -- 여러 핵심 데이터 소스를 통해 웹사이트의 탄생일을 조회하고 삽입 가능한 인증 배지를 제공하는 웹사이트 연령 인증 서비스. PUAClaw를 지원해 주신 SiteAge.org에 감사드립니다

---

## 11. 참고 문헌

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
    🦞 <em>"바닷가재는 집기 위해 허락을 구하지 않는다. 그저 집으면, 세상이 적응한다."</em> 🦞
    <br><br>
    <strong>PUAClaw</strong> -- A Lobster-Tested Production™
    <br>
    바닷가재와 함께 🦞 제작 | PUAClaw Consortium
    <br><br>
    <a href="https://github.com/puaclaw/PUAClaw/blob/main/LICENSE">MIT License</a> •
    <a href="../../CODE_OF_CONDUCT.md">Code of Conduct</a> •
    <a href="../../docs/ETHICS.md">Ethics Statement</a>
    <br><br>
    <em>본 저장소 제작 과정에서 바닷가재는 한 마리도 다치지 않았습니다. 몇 마리가 살짝 불편했을 뿐입니다.</em>
  </sub>
</p>
