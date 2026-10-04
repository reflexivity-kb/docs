<!--
id: RX-ARTICLE-0088
type: article
language: zh-cn
locale: zh-cn
author: Jim
author_profile: https://www.linkedin.com/in/jimlee55/
published: 2026-10-04
revised: 2026-10-04
editorial_reviewed: 2026-10-04
kb_imported: 2026-10-04
status: published
translation_status: current
-->

# 主要金融市场的金融机构如何采用 AI：官方资料呈现的共同模式

<!-- locale-switcher:start -->
**Languages:** [English](../../../en/06-articles/02-trust-and-auditability/how-financial-institutions-across-major-markets-are-adopting-ai.md) · [日本語](../../../ja/06-articles/02-信頼性と監査可能性/主要金融市場で金融機関はAIをどう導入しているか.md) · [한국어](../../../ko/06-articles/02-신뢰성과-감사가능성/주요-금융시장에서-금융기관은-AI를-어떻게-도입하고-있는가.md) · **简体中文** · [繁體中文（台灣）](../../../zh-tw/06-articles/02-可信度與可稽核性/主要金融市場的金融機構如何採用AI.md) · [繁體中文（香港）](../../../zh-hk/06-articles/02-可信度與可審計性/主要金融市場的金融機構如何採用AI.md)
<!-- locale-switcher:end -->

[← 可信度与可审计性](README.md) · [← Articles](../README.md)

<!-- article-byline:start -->
**作者:** Jim [![LinkedIn](https://raw.githubusercontent.com/reflexivity-kb/docs/main/assets/ui/linkedin.svg)](https://www.linkedin.com/in/jimlee55/) · **发布:** 2026-10-04 · **更新:** 2026-10-04
<!-- article-byline:end -->

金融机构并没有朝着一套统一的全球 AI 规则收敛。不同市场的法律体系、监管方式、市场结构和技术环境并不相同。

但比较官方资料后可以看到，AI 进入实际运营以后，各地提出的问题越来越相似。

当 AI 从试验走向生产，金融机构开始同时关注 **数据质量与来源、工作流控制、人工监督、第三方依赖、可解释性、监控以及责任归属**。

本文比较日本、美国、英国、欧盟、韩国、中国、香港和新加坡的官方资料。各市场的监管环境和采用速度并不相同，但有三个运营问题反复出现：**数据与证据链是否可信，AI 是否能在正确的决策时点进入研究工作流，以及人是否能够审查、解释并治理最终结果。**

## 共同信号一览

| 市场 | 官方资料 | 主要信号 |
|---|---|---|
| 日本 | 日本银行、金融厅 | GenAI 使用已经广泛，但治理、第三方风险、安全与数据准备度仍是持续课题 |
| 美国 | 美国财政部、FINRA | 数据 lineage、供应商透明度、准确性和第三方风险正在成为核心运营问题 |
| 英国 | 英格兰银行、FCA | AI 已进入主流应用，当前评分最高的五项风险中有四项与数据有关 |
| 欧盟 | EBA、ECB Banking Supervision | AI 正从试点走向基础设施，数据治理、透明度和第三方依赖的重要性上升 |
| 韩国 | 金融委员会 | 基础设施、金融领域数据以及清晰治理不足被明确视为实际采用障碍 |
| 中国 | 国家金融监督管理总局 | 数据质量、可解释性、监控、审计记录和人工复核成为明确的运营要求 |
| 香港 | HKMA | 透明度、验证、可解释性、治理和必要时的人工介入是负责任采用的重要组成 |
| 新加坡 | MAS | 从 AI inventory 到数据、人工监督、第三方、测试和监控，整个生命周期都被纳入治理 |

监管细节不同，但运营问题高度相似。

## 日本：使用正在进入核心业务

日本银行针对150家金融机构开展的2026年度调查显示，**超过90%的金融机构正在使用或试用生成式 AI**。使用范围也从一般行政事务扩大到使用客户信息的核心业务。

与此同时，采用增加并没有消除控制问题。治理、第三方风险管理、安全与安保、IT 基础设施以及数据准备度仍被视为需要进一步改善的领域。

日本金融厅也持续更新 AI Discussion Paper，并通过公私对话讨论 AI 使用、风险管理、治理和监管适用问题。

日本的关键信号并不只是“采用率高”，而是 AI 越接近重要业务，运营标准也越高。

## 美国：金融机构需要理解数据供应链

美国财政部在讨论金融服务 AI 时，将数据隐私、偏差以及第三方供应商风险列为重要问题。

在 AI 特定网络安全报告中，财政部进一步建议加强 **data supply-chain mapping**，并讨论为供应商 AI 系统和数据提供商建立标准化“nutrition label”的思路。金融机构应能够理解模型使用了什么训练数据、数据来自哪里，以及提交给模型的数据会如何被使用。

这首先是 provenance 问题，而不仅仅是模型性能问题。

FINRA 的 2026 Regulatory Oversight 材料也呈现相同方向。会员公司主要为了提升内部流程和信息检索效率而使用 GenAI，最常见的 use case 是摘要和信息抽取。同时，FINRA 提醒机构关注 hallucination、不准确或过时的数据、偏差、网络安全和第三方供应商风险。

对于机构投资研究而言，能够找到并总结信息还不够，证据路径本身必须值得信任。

## 英国：AI 采用率高，而最高风险多数与数据有关

英格兰银行和 FCA 的2024年调查显示，**75%的受访金融公司已经使用 AI**，另有10%计划在三年内使用。

当前 AI use case 中有三分之一由第三方实现。调查还显示，评分最高的五项当前 AI 风险中，**有四项与数据有关**：

- 数据隐私与保护
- 数据质量
- 数据安全
- 数据偏差与代表性

在已经使用 AI 的公司中，79%将 data governance 作为 AI governance 的组成部分。

这说明 adoption 与 control 正在同时发展。金融机构不是放弃 AI，而是在预期继续使用的技术周围建立治理体系。

## 欧盟：越过试点阶段后，控制的重要性上升

EBA 指出，AI 已在 EU/EEA 银行业被广泛采用。与2022年相比，到2024年仍停留在 pilot 阶段的银行已经很少，许多 initiative 正更深地进入银行 IT infrastructure。

与此同时，EBA 强调 transparency、ICT risk、data governance、data quality、reliability、privacy 以及对第三方提供商的依赖。许多银行也在使用大型模型开发者提供的 Cloud API 等 third-party service。

ECB Banking Supervision 从更基础的数据能力出发，指出稳健的 risk-data aggregation 与 reporting 是健全风险管理的前提。数据质量和报告缺陷也会削弱 AI 与 advanced analytics 的使用能力。

AI 并不会绕过既有数据纪律，反而会让其中的弱点变得更重要。

## 韩国：获得强大模型不等于具备金融领域可用性

韩国金融委员会在2024年12月总结了国内金融公司在扩大生成式 AI 使用时提出的三项实际障碍：

- AI 基础设施不足
- 数据不足
- 缺乏清晰的生成式 AI 治理

政策回应包括 AI 基础设施支持、金融领域专用数据支持以及修订金融行业 AI 指引。

这说明，能够使用通用模型与能够把 AI 用于专业金融工作并不是一回事。金融术语、规则、数据结构、entitlement 和运营约束仍需要在实际业务层面得到支持。

因此 coverage 问题也变得具体：**不是系统是否理解 prompt，而是它是否真正拥有完成该金融任务所需的证据。**

## 中国：可解释性与人工复核进入明确的运营控制

中国国家金融监督管理总局在2026年发布了银行保险业人工智能安全开发应用指导意见。

金融机构需要确保训练数据的质量、数量和分布满足建模要求，并为高风险场景建立透明度和可解释性标准。模型开发、变更和训练过程也需要留痕。

对人工责任的要求尤其明确。在高风险场景中，如果 AI 的可解释性不足，只能作为辅助工具，由人工做最终决定。涉及客户权益或产生实质性财务影响的重要决策，应设置人工复核节点，并完整保留原始数据、推理路径和阈值触发记录，以确保责任可追溯。

此前的银行保险机构数据安全管理办法也要求 AI 和模型管理具备可验证、可审核、可追溯性，并要求上线前数据安全审查以及对自动化处理结果的持续监测。

这说明 Data 和 Compliance 正进入运营架构，而不是事后的披露环节。

## 香港：负责任采用以验证与可解释性为基础

HKMA 在2024年的研究中分析了59个 GenAI use case，其中51个与金融服务直接相关。

该研究把 GenAI 采用放在 transparency 与 disclosure 等 responsible-AI 原则中讨论。HKMA 更早的 AI supervisory principles 也强调 governance 与 accountability、explainability、上线前 validation、持续 review、reliability 与 accuracy，以及在适当情况下进行 manual intervention。

这并不表示所有香港 use case 都适用完全相同的规则。关键在于监管预期金融机构能够理解、验证并最终对 AI 行为负责。

## 新加坡：把治理设计为完整的 AI 生命周期

MAS 在2025年提出 AI Risk Management Guidelines，部分基础来自2024年对主要银行 AI 使用情况的 thematic review。

拟议框架包括：

- 董事会与高级管理层监督
- 准确且最新的 AI inventory
- risk materiality assessment
- data management
- transparency 与 explainability
- human oversight
- third-party risk
- evaluation 与 testing
- monitoring 与 change management

MAS 的 Project MindForge 也开发了金融行业 GenAI risk framework 与 enterprise reference architecture。

新加坡的特点是把负责任 AI 看作完整生命周期：识别系统、评估重要性、控制数据和模型、测试、监控，并把负责任的人保留在流程之中。

## 跨市场反复出现的三层问题

这些市场并不共享完全相同的监管模式。本文引用的材料也包括 survey、supervisory observation、discussion paper、guidance 和 formal rule 等不同类型。

因此，不应把它们理解为相同的法律义务。

但三个运营层反复出现。

### 1. Data: 机构能否信任证据路径

- 数据来自哪里
- 数据是否最新、充分且适合该任务
- 如何管理第三方 data/model dependency
- 数据缺失、过期、冲突或超出 coverage 时怎么办
- 能否追踪哪些证据影响了结果

这些问题在 [数据可信度正在成为机构投资研究 AI 落地的前提](数据可信度正在成为机构投资研究AI落地的前提.md) 中有更详细的讨论。

### 2. Flow: AI 能否在真实工作流中运行

官方资料也反复提到静态模型质量以外的问题。

机构需要 AI inventory、monitoring、testing、human checkpoint、change management、lifecycle control，以及与现有流程的整合。

这本质上是 workflow 问题：AI 能否在正确的业务节点，带着正确的信息和控制进入流程。

### 3. Compliance: 机构能否解释并承担结果

Governance、accountability、explainability、auditability、third-party risk、human oversight，以及模型和数据使用记录在不同市场反复出现。

实际标准不仅是 AI 能不能给出答案，还包括金融机构能否解释答案如何产生、必要时进行复核，并对最终决策负责。

## 为什么这对机构投资研究重要

投资研究正处在这三层问题的交叉点。

分析人员可能需要确认：

1. **Source**: 数字或主张来自哪里
2. **Time**: 对应什么数据时间与市场时钟
3. **Coverage**: 对这个资产、市场和问题是否有足够证据
4. **Workflow**: 是否在所需数据已经准备好的正确节点运行分析
5. **Accountability**: 人是否能够审阅证据、理解重要限制并说明结果

各市场使用的语言不同，但方向非常一致：**金融行业的 production-grade AI 正在成为运营模式问题，而不仅仅是模型能力问题。**

## 各市场反复出现的三个运营问题

综合这些官方资料，可以看到三个彼此关联的运营问题。

1. **数据:** 是否能够确认数字或论断的来源、对应时点，以及当前覆盖范围是否足以回答问题。
2. **工作流:** 分析是否能在真正可用的时点进入研究与投资决策流程。
3. **审查与责任:** 人是否能够检查证据、理解重要限制、在必要时介入，并解释最终判断。

这并不是三个彼此独立的检查项。AI 越接近生产环境，就越需要在同一运营模式中同时处理这些问题。

关于第一个问题，可进一步参阅[数据可信度正在成为机构投资研究 AI 落地的前提](数据可信度正在成为机构投资研究AI落地的前提.md)。

## 官方资料

### 日本
- [Bank of Japan: FY2026 GenAI survey](https://www.boj.or.jp/en/research/brp/fsr/fsrb260824.htm)
- [Japan FSA: AI Discussion Paper v1.1](https://www.fsa.go.jp/en/news/2026/20260303/aidp.html)

### 美国
- [U.S. Treasury: Uses, Opportunities, and Risks of AI in Financial Services](https://home.treasury.gov/news/press-releases/jy2760)
- [U.S. Treasury: Managing AI-Specific Cybersecurity Risks in the Financial Sector](https://home.treasury.gov/news/press-releases/jy2212)
- [FINRA: GenAI: Continuing and Emerging Trends](https://www.finra.org/rules-guidance/guidance/reports/2026-finra-annual-regulatory-oversight-report/gen-ai)

### 英国
- [Bank of England / FCA: Artificial Intelligence in UK Financial Services, 2024](https://www.bankofengland.co.uk/report/2024/artificial-intelligence-in-uk-financial-services-2024)

### 欧盟
- [European Banking Authority: Special Topic: Artificial Intelligence](https://www.eba.europa.eu/publications-and-media/publications/special-topic-artificial-intelligence)
- [ECB Banking Supervision: Annual Report on Supervisory Activities 2025](https://www.bankingsupervision.europa.eu/press/other-publications/annual-report/html/ssm.ar2025~6ee989dc7e.en.html)

### 韩国
- [金融委员会: 金融领域生成式 AI 支持措施](https://fsc.go.kr/no010101/83594)

### 中国
- [国家金融监督管理总局: 银行业保险业人工智能安全开发应用指导意见](https://www.nfra.gov.cn/cn/view/pages/ItemDetail.html?docId=1261784&generaltype=1&itemId=4216)
- [中国政府: 银行保险机构数据安全管理办法](https://app.www.gov.cn/govdata/gov/202412/29/523120/article.html)

### 香港
- [HKMA: Generative Artificial Intelligence in the Financial Services Space](https://www.hkma.gov.hk/media/eng/doc/key-information/guidelines-and-circular/2024/GenAI_research_paper.pdf)
- [HKMA: High-level Principles on Artificial Intelligence](https://brdr.hkma.gov.hk/eng/doc-ldg/docId/getPdf/20191105-1-EN/20191105-1-EN.pdf)

### 新加坡
- [MAS: Proposed Guidelines for Artificial Intelligence Risk Management](https://www.mas.gov.sg/news/media-releases/2025/mas-guidelines-for-artificial-intelligence-risk-management)
- [MAS: Project MindForge](https://www.mas.gov.sg/schemes-and-initiatives/project-mindforge)

[← 可信度与可审计性](README.md) · [← Articles](../README.md)
