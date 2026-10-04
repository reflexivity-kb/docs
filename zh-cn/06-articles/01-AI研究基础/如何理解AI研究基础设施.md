<!--
id: RX-ARTICLE-0046
type: article
language: zh-cn
locale: zh-cn
author: Reflexivity GTM Team
author_profile: https://www.linkedin.com/company/reflexivityai
published: 2026-10-03
revised: 2026-10-03
editorial_reviewed: 2026-10-03
kb_imported: 2026-10-03
status: published
translation_status: translated
-->

# 如何理解 AI 研究基础设施

<!-- locale-switcher:start -->
**Languages:** [English](../../../en/06-articles/01-ai-research-foundations/how-to-think-about-ai-research-infrastructure.md) · [日本語](../../../ja/06-articles/01-AIリサーチの基礎/AIリサーチ基盤をどう考えるべきか.md) · [한국어](../../../ko/06-articles/01-AI-리서치-기초/AI-리서치-인프라를-어떻게-볼-것인가.md) · **简体中文** · [繁體中文（台灣）](../../../zh-tw/06-articles/01-AI研究基礎/如何理解AI研究基礎設施.md) · [繁體中文（香港）](../../../zh-hk/06-articles/01-AI研究基礎/如何理解AI研究基礎設施.md)
<!-- locale-switcher:end -->

[← AI 研究基础](README.md) · [← Articles](../README.md)

<!-- article-byline:start -->
**作者:** Reflexivity GTM Team [![LinkedIn](https://raw.githubusercontent.com/reflexivity-kb/docs/main/assets/ui/linkedin.svg)](https://www.linkedin.com/company/reflexivityai) · **发布:** 2026-10-03 · **更新:** 2026-10-03
<!-- article-byline:end -->

讨论 AI 研究基础设施时，人们很容易先看模型、context window 和界面。但机构研究真正依赖的是更完整的架构：投资语境、金融数据、多步骤工作流、监控、可审计性和状态保存。

按层拆开来看，就能区分哪些能力会随着新模型一起增强，哪些能力仍然必须在模型周围独立建设。

## 先从研究工作负载出发，而不是从模型参数出发

机构研究会在多种模式之间切换：快速市场核查、深度多步骤分析、历史比较、场景研究，以及对覆盖范围的持续监控。

不同工作流对基础设施有不同要求。有些任务以检索为主，有些需要计算和结构化数据，还有一些必须在用户不主动提问时持续运行。

因此，研究架构需要同时支持按需研究和持续研究。

## 问题与数据之间还需要语境层

把模型接入更多数据，并不会自动告诉系统哪些数据最重要。

投资研究依赖实体识别和关系判断：哪些公司相关、哪些产品重要、哪些主题或宏观因素应纳入分析、哪些地方可能出现二阶影响。

Knowledge Graph 提供这层关系和语境，帮助在深度分析之前定义研究范围。

## 数据与推理需要协同工作

Reflexivity 将 relationship intelligence 与金融时间序列、新闻、事件、公司文件和可信外部信息结合起来。Alfred 在同一个研究工作流中使用这些信息，而不是把它们当成彼此孤立的搜索结果。

## 监控会改变系统架构

传统聊天系统是 pull 模式：用户提问时系统运行。

持续投资监控增加了 push 模式要求：发现事件、判断相关性、连接到敞口，并决定是否值得打断用户。

这与等待问题输入是不同类型的工作负载。

## 可审计性和持续性也是基础设施

来源追溯、缺失数据说明、保存研究、定期运行、跨时期比较和历史复盘，不只是 UI 功能，而是把 AI 用于长期研究流程所需的基础。

## 把系统理解为多层结构

AI 研究基础设施可以拆成以下几层：

- **界面层：**用户与系统交互的位置
- **模型层：**通用推理引擎
- **投资语境层：**实体、关系、敞口和研究范围
- **数据层：**市场数据、文件、新闻、事件等
- **工作流层：**多步骤分析、场景、历史比较和重复任务
- **监控层：**持续发现与相关性筛选
- **审计层：**引用、可追溯计算、证据边界与缺失数据处理
- **持续性层：**保存、重复任务、跨时期比较和状态

这样拆分后可以看到，新模型或新界面的出现不会让其他层自动消失。某一层进步会让整个系统更强，但其他层仍然需要独立存在。

[← AI 研究基础](README.md) · [← Articles](../README.md)
