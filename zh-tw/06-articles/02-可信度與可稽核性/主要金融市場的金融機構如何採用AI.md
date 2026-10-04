<!--
id: RX-ARTICLE-0088
type: article
language: zh-tw
locale: zh-tw
author: Jim
author_profile: https://www.linkedin.com/in/jimlee55/
published: 2026-10-04
revised: 2026-10-04
editorial_reviewed: 2026-10-04
kb_imported: 2026-10-04
status: published
translation_status: current
-->

# 主要金融市場的金融機構如何採用 AI：官方資料呈現的共同模式

<!-- locale-switcher:start -->
**Languages:** [English](../../../en/06-articles/02-trust-and-auditability/how-financial-institutions-across-major-markets-are-adopting-ai.md) · [日本語](../../../ja/06-articles/02-信頼性と監査可能性/主要金融市場で金融機関はAIをどう導入しているか.md) · [한국어](../../../ko/06-articles/02-신뢰성과-감사가능성/주요-금융시장에서-금융기관은-AI를-어떻게-도입하고-있는가.md) · [简体中文](../../../zh-cn/06-articles/02-可信度与可审计性/主要金融市场的金融机构如何采用AI.md) · **繁體中文（台灣）** · [繁體中文（香港）](../../../zh-hk/06-articles/02-可信度與可審計性/主要金融市場的金融機構如何採用AI.md)
<!-- locale-switcher:end -->

[← 可信度與可稽核性](README.md) · [← Articles](../README.md)

<!-- article-byline:start -->
**作者:** Jim [![LinkedIn](https://raw.githubusercontent.com/reflexivity-kb/docs/main/assets/ui/linkedin.svg)](https://www.linkedin.com/in/jimlee55/) · **發布:** 2026-10-04 · **更新:** 2026-10-04
<!-- article-byline:end -->

金融機構並沒有朝向一套統一的全球 AI 規則收斂。不同市場的法律體系、監理方式、市場結構與技術環境並不相同。

但比較官方資料後可以看到，當 AI 進入實際營運，各地提出的問題愈來愈相似。

AI 從試驗走向正式使用時，金融機構開始同時關注 **資料品質與來源、工作流程控制、人工監督、第三方依賴、可解釋性、監控以及責任歸屬**。

本文比較日本、美國、英國、歐盟、韓國、中國、香港與新加坡的官方資料。它是 Reflexivity **Data / Flow / Compliance** 三部曲的 supporting research，**不是第四篇**。目的在於讓主系列維持簡潔，同時完整保留各市場的證據基礎。

## 共同訊號一覽

| 市場 | 官方資料 | 主要訊號 |
|---|---|---|
| 日本 | 日本銀行、金融廳 | GenAI 使用已廣泛，但治理、第三方風險、安全與資料準備度仍是持續課題 |
| 美國 | 美國財政部、FINRA | 資料 lineage、供應商透明度、準確性與第三方風險正成為核心營運問題 |
| 英國 | 英格蘭銀行、FCA | AI 已進入主流應用，目前評分最高的五項風險中有四項與資料有關 |
| 歐盟 | EBA、ECB Banking Supervision | AI 正從試點走向基礎設施，資料治理、透明度與第三方依賴的重要性提升 |
| 韓國 | 金融委員會 | 基礎設施、金融領域資料與清楚治理不足被明確視為實際採用障礙 |
| 中國 | 國家金融監督管理總局 | 資料品質、可解釋性、監控、稽核紀錄與人工覆核成為明確營運要求 |
| 香港 | HKMA | 透明度、驗證、可解釋性、治理與必要時人工介入是負責任採用的重要組成 |
| 新加坡 | MAS | 從 AI inventory 到資料、人工監督、第三方、測試與監控，整個生命週期都納入治理 |

監理細節不同，但營運問題高度相似。

## 日本：使用正進入核心業務

日本銀行針對150家金融機構進行的2026年度調查顯示，**超過90%的金融機構正在使用或試用生成式 AI**。使用範圍也從一般行政事務擴大到使用客戶資訊的核心業務。

同時，採用增加並沒有消除控制問題。治理、第三方風險管理、安全與資安、IT 基礎設施以及資料準備度仍被視為需要進一步改善的領域。

日本金融廳也持續更新 AI Discussion Paper，透過公私對話討論 AI 使用、風險管理、治理與監管適用問題。

日本的關鍵訊號並不只是「採用率高」，而是 AI 愈接近重要業務，營運標準也愈高。

## 美國：金融機構需要理解資料供應鏈

美國財政部在討論金融服務 AI 時，將資料隱私、偏差以及第三方供應商風險列為重要問題。

在 AI 特定網路安全報告中，財政部進一步建議加強 **data supply-chain mapping**，並討論為供應商 AI 系統與資料提供者建立標準化「nutrition label」的概念。金融機構應能理解模型使用了哪些訓練資料、資料來自哪裡，以及提交給模型的資料會如何被使用。

這首先是 provenance 問題，而不只是模型效能問題。

FINRA 的 2026 Regulatory Oversight 資料也呈現相同方向。會員公司主要為提升內部流程與資訊檢索效率而使用 GenAI，最常見的 use case 是摘要與資訊抽取。同時，FINRA 提醒機構關注 hallucination、不準確或過時資料、偏差、網路安全與第三方供應商風險。

對機構投資研究而言，能找到並摘要資訊還不夠，證據路徑本身必須值得信任。

## 英國：AI 採用率高，而最高風險多數與資料有關

英格蘭銀行與 FCA 的2024年調查顯示，**75%的受訪金融公司已經使用 AI**，另有10%計畫在三年內使用。

目前 AI use case 中有三分之一由第三方實作。調查也顯示，評分最高的五項目前 AI 風險中，**有四項與資料有關**：

- 資料隱私與保護
- 資料品質
- 資料安全
- 資料偏差與代表性

在已經使用 AI 的公司中，79%將 data governance 作為 AI governance 的組成部分。

這表示 adoption 與 control 正同時發展。金融機構不是放棄 AI，而是在預期持續使用的技術周圍建立治理。

## 歐盟：越過試點階段後，控制的重要性上升

EBA 指出，AI 已在 EU/EEA 銀行業被廣泛採用。與2022年相比，到2024年仍停留在 pilot 階段的銀行已經很少，許多 initiative 正更深入銀行 IT infrastructure。

同時，EBA 強調 transparency、ICT risk、data governance、data quality、reliability、privacy，以及對第三方提供者的依賴。許多銀行也使用大型模型開發者提供的 Cloud API 等 third-party service。

ECB Banking Supervision 從更基礎的資料能力出發，指出穩健的 risk-data aggregation 與 reporting 是健全風險管理的前提。資料品質和報告缺陷也會削弱 AI 與 advanced analytics 的使用能力。

AI 不會繞過既有資料紀律，反而會讓其中的弱點更重要。

## 韓國：取得強大模型不等於具備金融領域可用性

韓國金融委員會在2024年12月總結國內金融公司擴大生成式 AI 使用時提出的三項實際障礙：

- AI 基礎設施不足
- 資料不足
- 缺乏清楚的生成式 AI 治理

政策回應包括 AI 基礎設施支援、金融領域專用資料支援，以及修訂金融產業 AI 指引。

這說明，能使用通用模型與能把 AI 用於專業金融工作並不是同一件事。金融術語、規則、資料結構、entitlement 與營運限制仍需在實際業務層面得到支援。

因此 coverage 問題也變得具體：**不是系統是否理解 prompt，而是它是否真正擁有完成該金融任務所需的證據。**

## 中國：可解釋性與人工覆核進入明確營運控制

中國國家金融監督管理總局在2026年發布銀行保險業人工智能安全開發應用指導意見。

金融機構需要確保訓練資料的品質、數量和分布符合建模要求，並為高風險場景建立透明度與可解釋性標準。模型開發、變更與訓練過程也需要留痕。

對人工責任的要求尤其明確。在高風險場景中，如果 AI 的可解釋性不足，只能作為輔助工具，由人工做最終決定。涉及客戶權益或產生實質性財務影響的重要決策，應設置人工覆核節點，並完整保留原始資料、推理路徑與閾值觸發紀錄，以確保責任可追溯。

此前的銀行保險機構資料安全管理辦法也要求 AI 與模型管理具備可驗證、可稽核、可追溯性，並要求上線前資料安全審查以及對自動化處理結果的持續監測。

這表示 Data 與 Compliance 正進入營運架構，而不是事後揭露。

## 香港：負責任採用以驗證與可解釋性為基礎

HKMA 在2024年的研究中分析了59個 GenAI use case，其中51個與金融服務直接相關。

該研究把 GenAI 採用放在 transparency 與 disclosure 等 responsible-AI 原則中討論。HKMA 更早的 AI supervisory principles 也強調 governance 與 accountability、explainability、上線前 validation、持續 review、reliability 與 accuracy，以及在適當情況下進行 manual intervention。

這並不代表所有香港 use case 都適用完全相同的規則。關鍵在於監管預期金融機構能理解、驗證並最終對 AI 行為負責。

## 新加坡：把治理設計為完整 AI 生命週期

MAS 在2025年提出 AI Risk Management Guidelines，部分基礎來自2024年對主要銀行 AI 使用情況的 thematic review。

擬議框架包括：

- 董事會與高階管理層監督
- 準確且最新的 AI inventory
- risk materiality assessment
- data management
- transparency 與 explainability
- human oversight
- third-party risk
- evaluation 與 testing
- monitoring 與 change management

MAS 的 Project MindForge 也開發了金融產業 GenAI risk framework 與 enterprise reference architecture。

新加坡的特點是把負責任 AI 視為完整生命週期：識別系統、評估重要性、控制資料和模型、測試、監控，並把負責任的人保留在流程之中。

## 跨市場反覆出現的三層問題

這些市場並不共享完全相同的監管模式。本文引用的資料也包含 survey、supervisory observation、discussion paper、guidance 與 formal rule 等不同類型。

因此，不應把它們理解成相同的法律義務。

但三個營運層反覆出現。

### 1. Data: 機構能否信任證據路徑

- 資料來自哪裡
- 是否最新、充分且適合該任務
- 如何管理第三方 data/model dependency
- 資料缺失、過期、衝突或超出 coverage 時怎麼辦
- 能否追蹤哪些證據影響了結果

這些問題在 [資料可信度正成為機構投資研究 AI 落地的前提](資料可信度正成為機構投資研究AI落地的前提.md) 中有更詳細的討論。

### 2. Flow: AI 能否在真實工作流程中運作

官方資料也反覆提到靜態模型品質以外的問題。

機構需要 AI inventory、monitoring、testing、human checkpoint、change management、lifecycle control，以及與既有流程的整合。

這本質上是 workflow 問題：AI 能否在正確的業務節點，帶著正確資訊與控制進入流程。

### 3. Compliance: 機構能否解釋並承擔結果

Governance、accountability、explainability、auditability、third-party risk、human oversight，以及模型與資料使用紀錄在不同市場反覆出現。

實際標準不只是 AI 能不能給出答案，也包括金融機構能否解釋答案如何產生、必要時進行覆核，並對最終決策負責。

## 為什麼這對機構投資研究重要

投資研究正處在這三層問題的交叉點。

分析人員可能需要確認：

1. **Source**: 數字或主張來自哪裡
2. **Time**: 對應什麼資料時間與市場時鐘
3. **Coverage**: 對這個資產、市場與問題是否有足夠證據
4. **Workflow**: 是否在所需資料已準備好的正確節點執行分析
5. **Accountability**: 人是否能審閱證據、理解重要限制並說明結果

各市場使用的語言不同，但方向非常一致：**金融業的 production-grade AI 正成為營運模式問題，而不只是模型能力問題。**

## 本文與 Data / Flow / Compliance 三部曲的關係

本文是三部曲的共同 evidence base，不是第四篇。

- **Part 1: Data:** [資料可信度正成為機構投資研究 AI 落地的前提](資料可信度正成為機構投資研究AI落地的前提.md)
- **Part 2: Flow:** [AI只有在正確的決策時點進入工作流程才真正有用](../04-研究工作流程/AI只有在正確的決策時點進入工作流程才真正有用.md)
- **Part 3: Compliance:** [為什麼合規必須設計進研究工作流程](為什麼合規必須設計進研究工作流程.md)

把完整的國家與地區證據集中在這裡，可以讓三篇主文章分別聚焦自己的核心問題，同時為希望進一步查核背景的讀者保留完整研究基礎。

## 官方資料

### 日本
- [Bank of Japan: FY2026 GenAI survey](https://www.boj.or.jp/en/research/brp/fsr/fsrb260824.htm)
- [Japan FSA: AI Discussion Paper v1.1](https://www.fsa.go.jp/en/news/2026/20260303/aidp.html)

### 美國
- [U.S. Treasury: Uses, Opportunities, and Risks of AI in Financial Services](https://home.treasury.gov/news/press-releases/jy2760)
- [U.S. Treasury: Managing AI-Specific Cybersecurity Risks in the Financial Sector](https://home.treasury.gov/news/press-releases/jy2212)
- [FINRA: GenAI: Continuing and Emerging Trends](https://www.finra.org/rules-guidance/guidance/reports/2026-finra-annual-regulatory-oversight-report/gen-ai)

### 英國
- [Bank of England / FCA: Artificial Intelligence in UK Financial Services, 2024](https://www.bankofengland.co.uk/report/2024/artificial-intelligence-in-uk-financial-services-2024)

### 歐盟
- [European Banking Authority: Special Topic: Artificial Intelligence](https://www.eba.europa.eu/publications-and-media/publications/special-topic-artificial-intelligence)
- [ECB Banking Supervision: Annual Report on Supervisory Activities 2025](https://www.bankingsupervision.europa.eu/press/other-publications/annual-report/html/ssm.ar2025~6ee989dc7e.en.html)

### 韓國
- [韓國金融委員會: 金融領域生成式 AI 支援措施](https://fsc.go.kr/no010101/83594)

### 中國
- [國家金融監督管理總局: 銀行業保險業人工智能安全開發應用指導意見](https://www.nfra.gov.cn/cn/view/pages/ItemDetail.html?docId=1261784&generaltype=1&itemId=4216)
- [中國政府: 銀行保險機構資料安全管理辦法](https://app.www.gov.cn/govdata/gov/202412/29/523120/article.html)

### 香港
- [HKMA: Generative Artificial Intelligence in the Financial Services Space](https://www.hkma.gov.hk/media/eng/doc/key-information/guidelines-and-circular/2024/GenAI_research_paper.pdf)
- [HKMA: High-level Principles on Artificial Intelligence](https://brdr.hkma.gov.hk/eng/doc-ldg/docId/getPdf/20191105-1-EN/20191105-1-EN.pdf)

### 新加坡
- [MAS: Proposed Guidelines for Artificial Intelligence Risk Management](https://www.mas.gov.sg/news/media-releases/2025/mas-guidelines-for-artificial-intelligence-risk-management)
- [MAS: Project MindForge](https://www.mas.gov.sg/schemes-and-initiatives/project-mindforge)

[← 可信度與可稽核性](README.md) · [← Articles](../README.md)
