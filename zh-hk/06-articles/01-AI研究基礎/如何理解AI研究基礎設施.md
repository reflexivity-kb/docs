<!--
id: RX-ARTICLE-0046
type: article
language: zh-hk
locale: zh-hk
author: Reflexivity GTM Team
author_profile: https://www.linkedin.com/company/reflexivityai
published: 2026-10-03
revised: 2026-10-03
editorial_reviewed: 2026-10-03
kb_imported: 2026-10-03
status: published
translation_status: translated
-->

# 如何理解 AI 研究基礎設施

<!-- locale-switcher:start -->
**Languages:** [English](../../../en/06-articles/01-ai-research-foundations/how-to-think-about-ai-research-infrastructure.md) · [日本語](../../../ja/06-articles/01-AIリサーチの基礎/AIリサーチ基盤をどう考えるべきか.md) · [한국어](../../../ko/06-articles/01-AI-리서치-기초/AI-리서치-인프라를-어떻게-볼-것인가.md) · [简体中文](../../../zh-cn/06-articles/01-AI研究基础/如何理解AI研究基础设施.md) · [繁體中文（台灣）](../../../zh-tw/06-articles/01-AI研究基礎/如何理解AI研究基礎設施.md) · **繁體中文（香港）**
<!-- locale-switcher:end -->

[← AI 研究基礎](README.md) · [← Articles](../README.md)

<!-- article-byline:start -->
**作者:** Reflexivity GTM Team [![LinkedIn](https://raw.githubusercontent.com/reflexivity-kb/docs/main/assets/ui/linkedin.svg)](https://www.linkedin.com/company/reflexivityai) · **發布:** 2026-10-03 · **更新:** 2026-10-03
<!-- article-byline:end -->

談到 AI 研究基礎設施，人們很容易先看模型、context window 及介面。但機構研究真正依賴的是更完整的架構：投資脈絡、金融數據、多步驟工作流程、監察、可審計性及狀態保存。

按層拆開來看，就能分清楚哪些能力會隨新模型一起增強，哪些能力仍必須在模型周圍獨立建立。

## 先由研究工作本身出發，而不是由模型規格出發

機構研究會在多種模式之間切換：快速市場核查、深度多步驟分析、歷史比較、情景研究，以及對覆蓋範圍的持續監察。

不同工作流程對基礎設施有不同要求。有些以檢索為主，有些需要計算及結構化數據，還有一些必須在使用者沒有主動提問時持續運作。

因此，研究架構需要同時支援按需研究及持續研究。

## 問題與數據之間還需要脈絡層

把模型接入更多數據，並不會自動告訴系統哪些數據最重要。

投資研究依賴實體識別及關係判斷：哪些公司相關、哪些產品重要、哪些主題或宏觀因素應納入分析、哪些地方可能出現二階影響。

Knowledge Graph 提供這層關係及脈絡，協助在深度分析之前定義研究範圍。

## 數據與推理需要協同運作

Reflexivity 將 relationship intelligence 與金融時間序列、新聞、事件、公司文件及可信外部資訊結合。Alfred 在同一個研究工作流程中使用這些資訊，而不是把它們當成彼此孤立的搜尋結果。

## 監察會改變系統架構

傳統聊天系統是 pull 模式：使用者提問時系統才執行。

持續投資監察增加了 push 模式要求：發現事件、判斷相關性、連接到曝險，並決定是否值得打斷使用者。

這與等待問題輸入是不同類型的工作負載。

## 可審計性及持續性也是基礎設施

來源追溯、缺失數據說明、保存研究、定期執行、跨期比較及歷史複查，不只是 UI 功能，而是把 AI 用於長期研究流程所需的基礎。

## 把系統理解成多層架構

AI 研究基礎設施可以拆成：

- **介面層：**使用者與系統互動的位置
- **模型層：**通用推理引擎
- **投資脈絡層：**實體、關係、曝險及研究範圍
- **數據層：**市場數據、文件、新聞、事件等
- **工作流程層：**多步驟分析、情景、歷史比較及重複任務
- **監察層：**持續發現及相關性篩選
- **審計層：**引用、可追溯計算、證據邊界及缺失數據處理
- **持續性層：**保存、重複任務、跨期比較及狀態

這樣拆分後可以看到，新模型或新介面的出現不會令其他層自動消失。某一層進步會令整體更強，但其他層仍然需要獨立存在。

[← AI 研究基礎](README.md) · [← Articles](../README.md)
