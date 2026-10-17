<!--
id: RX-USECASE-0080
type: use-case
language: zh-tw
locale: zh-TW
author: Reflexivity Research
kb_imported: 2026-10-17
status: draft
translation_status: localized_from_en_canonical
original_language: en
source_type: reflexivity-platform-demo
source_manifest: RX-USECASE-0080
prompt_status: present
prompt_basis: localized_from_en_verbatim
-->

# 評估日圓快速升值對TOPIX Core 30個股的影響

[← 依資產類別瀏覽](../README.md) · [全部使用案例](../../README.md)

**適用使用者：** 日本股票、外匯投資經理及風險管理人員  
**資產類別：** 外匯、日本股票  
**研究觀察期間：** 1990至2024年歷史事件及2024年夏季套利平倉

> 圖表與數值反映指定時期的研究示例，不代表即時市場報價或投資建議。

**[在Reflexivity開啟研究示例（英文）→](https://app.reflexivity.com/alfred?mode=research&conversationId=b6641a7b-b55b-4696-bf5f-4ad9b762c713&scrollTo=top)**

## 使用的提示詞

> [!IMPORTANT]
> 若USD/JPY像2024年7至8月日圓套利交易平倉時一樣，在一個月內下跌8%，TOPIX Core 30哪些股票受到的影響最大或最小？請依各股票對日圓的歷史敏感度，並比較出口商與內需公司。

## 從日圓衝擊尋找個股差異

USD/JPY一個月下跌8%，可能衝擊出口商的日圓換算收入，但不同企業也受內需、利率及全球避險情緒影響。2024年7月3日至8月5日，USD/JPY約由 **161.70降至144.20**。

研究選取1990至2024年間 **21個交易日內USD/JPY下跌至少8%的13個事件**，計算TOPIX Core 30股票在事件之後一個月的報酬中位數。

## 歷史條件報酬

![日圓升值後TOPIX Core 30股票歷史一個月報酬中位數](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0080-yen-shock-topix30.png)

*圖1：歷史條件式報酬中位數，並非直接估算的FX迴歸Beta或下一次情境的預測。*

| 公司 | 一個月報酬中位數 | 有效事件數 |
| --- | ---: | ---: |
| 三菱商事 | −4.90% | 13 |
| 豐田汽車 | −4.32% | 13 |
| Sony Group | −3.57% | 13 |
| 本田汽車 | −2.84% | 13 |
| 瑞穗金融 | +6.68% | 6 |
| Hoya | +7.69% | 13 |
| MUFG | +9.43% | 6 |

依所選分類，出口商平均約 **−2.74%**，內需企業約 **+4.31%**。但企業樣本數不一致，部分僅兩次事件；匯率急升也常與政策及避險衝擊同時發生，不能完全歸因於日圓。後續應檢查公司外幣收入與避險揭露、滾動FX Beta等證據。

## 其他研究資料

若希望了解同一問題在 **LSEG Workspace等其他研究環境的重現結果**，請寄信至 **jim@reflexivity.com** 並註明文件編號 **RX-USECASE-0080**。能否另行提供仍需依資料存取權及再散布授權判定。

---

[← 依資產類別瀏覽](../README.md) · [全部使用案例](../../README.md)
