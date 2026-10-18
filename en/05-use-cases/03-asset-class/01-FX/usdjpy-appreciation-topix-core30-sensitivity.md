<!--
id: RX-USECASE-0080
type: use-case
language: en
locale: en
author: Reflexivity Research
kb_imported: 2026-10-17
status: draft
translation_status: canonical
source_type: reflexivity-native-deep-research-pdf
source_manifest: RX-USECASE-0080
asset_class: FX, Japanese Equities
roles: Japan Equity PMs, FX PMs, Risk Managers
prompt_status: present
prompt_basis: source-verbatim
-->

# Assess TOPIX Core 30 Sensitivity to a Sharp Yen Appreciation

<!-- locale-switcher:start -->
**Languages:** **English** · [日本語](../../../../ja/05-ユースケース/03-運用資産別/01-FX/急激な円高でTOPIX-Core-30銘柄の影響を比較する.md) · [한국어](../../../../ko/05-유스케이스/03-운용자산별/01-FX/엔화-급등-시-TOPIX-Core-30-종목별-민감도-비교하기.md) · [简体中文](../../../../zh-cn/05-使用案例/03-按资产类别/01-FX/评估-日元快速升值-对TOPIX-Core-30股票的影响.md) · [繁體中文（台灣）](../../../../zh-tw/05-使用案例/03-依資產類別/01-FX/評估-日圓快速升值-對TOPIX-Core-30個股的影響.md) · [繁體中文（香港）](../../../../zh-hk/05-使用案例/03-按資產類別/01-FX/評估-日圓急升-對TOPIX-Core-30股票的影響.md)
<!-- locale-switcher:end -->

[← All use cases](../../README.md) · [Asset-class index](README.md)

**Research period:** Historical events from 1990–2024; July–August 2024 illustration  
**Relevant users:** Japan Equity PMs, FX PMs, Risk Managers  
**Assets:** FX, Japanese Equities

> This is a dated research illustration. Figures and scenario assumptions are not live market data and require independent verification before investment use.

**[Open this research example in Reflexivity →](https://app.reflexivity.com/alfred?mode=research&conversationId=b6641a7b-b55b-4696-bf5f-4ad9b762c713&scrollTo=top)**

## Prompt used

> [!IMPORTANT]
> If USD/JPY falls 8% over one month, as it did during the July–August 2024 carry-trade unwind, which TOPIX Core 30 stocks would be most and least affected? Base it on each stock’s historical sensitivity to the yen, and compare exporters with domestic-demand names.

## Investment question

An eight-percent monthly fall in USD/JPY is not equally favorable or unfavorable for every Japanese equity. Exporters, domestic banks, insurers and consumer businesses have different earnings currencies and different exposure to the risk-off conditions that may accompany an abrupt yen rally.

The question asks for a **TOPIX Core 30 cross-section** rather than a general forecast of USD/JPY.

## Design the historical test

The reference episode was the July–August 2024 carry-trade unwind, when USD/JPY fell from about **161.70 to 144.20** from July 3 to August 5 (approximately **−10.82%** peak to trough).

The example identified **13 historical episodes** between 1990 and 2024 in which USD/JPY declined at least eight percent over 21 trading days. For each Japanese stock, it compared the **median forward one-month price return** across matching episodes. This is a conditional event-study median, **not** a fitted FX beta or a direct estimate of profit sensitivity.

## Illustrative results

![Historical conditional median one-month returns across TOPIX Core 30 constituents following sharp USDJPY declines](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0080-yen-shock-topix30.png)

*Figure 1. Conditional historical **median forward one-month stock returns** after a qualifying 8% monthly USD/JPY fall; not regression betas or mechanically predicted future returns. Selected company labels are shown in the plot; full source observations differ in sample count.*

| Company | Median one-month return following qualifying yen rallies | Category in the screen | Available historical episodes |
| --- | ---: | --- | ---: |
| Mitsubishi Corp | −4.90% | Exporter/global cyclical | 13 |
| Toyota Motor | −4.32% | Exporter/global cyclical | 13 |
| Sony Group | −3.57% | Exporter/global cyclical | 13 |
| Honda Motor | −2.84% | Exporter/global cyclical | 13 |
| Mizuho Financial | +6.68% | Domestic demand / financials | 6 |
| Hoya | +7.69% | Mixed/other | 13 |
| Mitsubishi UFJ Financial | +9.43% | Domestic demand / financials | 6 |

In the selected grouping, exporters averaged **−2.74%** versus **+4.31%** for domestic-demand companies. Those conditional historical returns provide a useful way to challenge a blanket view of the yen's effect on the Nikkei.

## Interpretation and limitations

- **Event-regime confounding:** yen rallies often coexist with changes in US rates, global risk appetite and Japanese policy expectations. The stock results cannot be attributed solely to FX translation.
- **Uneven samples:** MUFG and Mizuho have only six observations in this screen, versus thirteen for some other names; Recruit and SoftBank Corp have only two.
- **Classification:** trading houses and global platform businesses may span multiple economic categories. Category averages are descriptive, not sector-neutral factor estimates.
- **No mechanical prediction:** historical medians over very different macro regimes should not be presented as precise responses to the next eight-percent shock.

## What this use case demonstrates

Reflexivity can turn a macro shock into a **named-equity sensitivity screen** with defined event thresholds, observation windows and group comparisons. The next step is to complement the historical conditioning with rolling FX regressions and company-level foreign revenue/hedge disclosure analysis.

**Related example:** [Analyze the drivers of a rapid yen rally](yen-strength-background-outlook.md) asks why the currency moved and whether its move may persist; this example focuses on equities.

## Additional examples and supporting information

Additional research examples and cross-platform comparisons may be available upon request, subject to applicable access and redistribution permissions. Contact **jim@reflexivity.com** and reference **RX-USECASE-0080**.

---

[← All use cases](../../README.md) · [Asset-class index](README.md)
