<!--
id: RX-USECASE-0078
type: use-case
language: zh-tw
locale: zh-TW
author: Reflexivity Research
kb_imported: 2026-10-17
status: draft
translation_status: localized_from_en_canonical
original_language: en
source_type: reflexivity-platform-demo
source_manifest: RX-USECASE-0078
prompt_status: present
prompt_basis: localized_from_en_verbatim
-->

# 比較日本銀行股在BOJ利率調整後的超額報酬與EPS修正

<!-- locale-switcher:start -->
**Languages:** [English](../../../../en/05-use-cases/03-asset-class/04-equities/japanese-bank-returns-vs-topix-after-boj-hikes.md) · [日本語](../../../../ja/05-ユースケース/03-運用資産別/04-株式/BOJの利上げ後に主要銀行株とEPS予想がどう動いたか比較する.md) · [한국어](../../../../ko/05-유스케이스/03-운용자산별/04-주식/BOJ-금리변경-후-일본-은행주와-EPS-변화-분석하기.md) · [简体中文](../../../../zh-cn/05-使用案例/03-按资产类别/04-股票/比较-日本银行股-在央行调息后的相对收益和EPS调整.md) · **繁體中文（台灣）** · [繁體中文（香港）](../../../../zh-hk/05-使用案例/03-按資產類別/04-股票/比較-日本銀行股-在BOJ調息後的超額回報與EPS預期調整.md)
<!-- locale-switcher:end -->

[← 依資產類別瀏覽](../README.md) · [全部使用案例](../../README.md)

**適用使用者：** 日本股票、銀行業及多資產投資經理  
**資產類別：** 日本股票、金融  
**研究觀察期間：** 2024年3月至2026年10月14日

> 圖表與數值反映指定時期的研究示例，不代表即時市場報價或投資建議。

**[在Reflexivity開啟研究示例（英文）→](https://app.reflexivity.com/alfred?mode=research&conversationId=cfe0f411-8375-4f25-bfee-d5436222ec8c&scrollTo=top)**

## 使用的提示詞

> [!IMPORTANT]
> 自2024年以來，每次日本銀行調整政策利率後20個交易日，MUFG、SMFG與瑞穗相對TOPIX的股價表現如何？請一併比較各銀行在相同期間的未來12個月EPS一致預期修正幅度。

## 升息不代表銀行股一定領漲

銀行利差可能因升息改善，但日圓套利部位平倉及整體風險偏好同樣會改變價格。本案例比較調息後 **20個交易日的TOPIX超額報酬**與**同期間12個月遠期EPS預期修正**。

截至2026年10月14日，完整觀察期涵蓋五次BOJ利率調整；2026年9月18日的事件因20個交易日尚未結束而排除。

## 相對TOPIX的報酬

![MUFG SMFG瑞穗在BOJ調息後20個交易日超額報酬](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0078-bank-excess-returns.png)

*圖1：單位為百分點，而非股票絕對報酬。*

| 事件 | MUFG | SMFG | 瑞穗 |
| --- | ---: | ---: | ---: |
| 2024年7月 | −9.95點 | −8.69點 | −9.46點 |
| 2025年1月 | +3.76點 | +4.13點 | +8.21點 |
| 2025年12月 | +8.15點 | +0.85點 | +10.59點 |
| 2026年6月 | +10.33點 | +7.51點 | +8.12點 |

2024年7月發生套利交易平倉，三家銀行明顯落後TOPIX；後續事件則呈現不同反應。

## 盈餘預期修正

![日本三大銀行BOJ事件後未來12個月EPS預期調整](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0078-bank-eps-revisions.png)

*圖2：相同20個交易日期間的遠期12個月EPS一致預期變動。*

2026年6月期間的EPS修正為MUFG **+7.47%**、SMFG **+7.95%**、瑞穗 **+3.65%**。

MUFG、SMFG的部分預期來自**美元計價ADR資料**，瑞穗則以日圓計價。轉為百分比也無法完全排除預估基礎與匯率差異。此事件研究也不是剔除其他總體因素的純粹政策因果估計。

## 其他研究資料

若希望了解同一問題在 **LSEG Workspace等其他研究環境的重現結果**，請寄信至 **jim@reflexivity.com** 並註明文件編號 **RX-USECASE-0078**。能否另行提供仍需依資料存取權及再散布授權判定。

---

[← 依資產類別瀏覽](../README.md) · [全部使用案例](../../README.md)
