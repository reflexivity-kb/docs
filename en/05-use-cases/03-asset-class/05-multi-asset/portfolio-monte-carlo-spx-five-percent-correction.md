<!--
id: RX-USECASE-0082
type: use-case
language: en
locale: en
author: Reflexivity Research
kb_imported: 2026-10-17
status: draft
translation_status: canonical
source_type: reflexivity-native-deep-research-pdf
source_manifest: RX-USECASE-0082
asset_class: Multi-Asset, US Equities, FX
roles: Multi-Asset PMs, Portfolio Risk Managers, Hedge Funds
prompt_status: present
prompt_basis: source-verbatim
-->

# Model Equal-Weighted Portfolio Risk During a Five-Percent S&P 500 Correction

<!-- locale-switcher:start -->
**Languages:** **English** · [日本語](../../../../ja/05-ユースケース/03-運用資産別/05-マルチアセット/SP500の5パーセント調整を想定したポートフォリオのモンテカルロ分析.md) · [한국어](../../../../ko/05-유스케이스/03-운용자산별/05-멀티에셋/SP500-5퍼센트-조정-시-포트폴리오-몬테카를로-분석하기.md) · [简体中文](../../../../zh-cn/05-使用案例/03-按资产类别/05-多资产/用蒙特卡洛模拟-评估SP500下跌5百分比时的组合风险.md) · [繁體中文（台灣）](../../../../zh-tw/05-使用案例/03-依資產類別/05-多資產/用蒙地卡羅-評估SP500下跌5百分比時的組合風險.md) · [繁體中文（香港）](../../../../zh-hk/05-使用案例/03-按資產類別/05-多資產/用蒙特卡羅-評估SP500下跌5百分比時的組合風險.md)
<!-- locale-switcher:end -->

[← All use cases](../../README.md) · [Asset-class index](README.md)

**Research period:** Daily estimates October 2023–October 2026; SPX event reference 1965–2026  
**Relevant users:** Multi-Asset PMs, Portfolio Risk Managers, Hedge Funds  
**Assets:** Multi-Asset, US Equities, FX

> This is a dated research illustration. Figures and scenario assumptions are not live market data and require independent verification before investment use.

**[Open this research example in Reflexivity →](https://app.reflexivity.com/alfred?mode=research&conversationId=e2b98809-14cb-44d8-8889-b0a4820fdaf1&scrollTo=top)**

## Prompt used

> [!IMPORTANT]
> Can you please use Montecarlo analysis to assess downside risk from a 5% SPX correction to the my portfolio of NVDA, AAPL, MSFT, GOOGL, AMZN, META, AVGO, TSLA, BRK.B, LLY, JPM, V, MA, WMT, COST, XOM, NFLX, AMD, BAC, UNH, USDJPY, EURUSD, GBPUSD? Assume equal weighting for all assets

## Investment question

A diversified book of US equities and currency pairs does not necessarily move in line with the S&P 500. A portfolio manager wants to know how a **five-percent SPX decline** could affect the entire book, which securities drive the losses and how sensitive the result is to modeling choices.

## Portfolio and conditional model

![Estimated S&P 500 factor betas for the 20 US equities and three currency pairs in the illustrative portfolio](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0082-spx-beta-by-asset.png)

*Figure 1. Estimated daily-return SPX beta by holding over the 2023–2026 sample. A high beta indicates stronger estimated factor response, **not** a guaranteed future loss.*

The example includes **23 equal-weighted positions**: 20 US equities and three FX pairs (USD/JPY, EUR/USD, GBP/USD), each at approximately **4.35%** portfolio weight.

A 50,000-draw simulation used a **linear SPX-beta factor shock of −5%**, adding correlated residuals estimated from daily price-return data from October 2023 to October 2026. The source also describes 158 historical 21-trading-day SPX drawdown episodes as a context check.

## Illustrative model output

![First through ninety-ninth percentile bar summary of simulated conditional portfolio returns under a five percent S&P 500 decline](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0082-simulated-portfolio-quantiles.png)

*Figure 2. Simulated portfolio **return quantiles**, not a histogram or smooth density. Model output conditions on a −5% SPX factor shock and fixed-beta, approximately Gaussian residual assumptions.*

| Modeled statistic under the specified SPX shock | Reported result |
| --- | ---: |
| Mean portfolio return | −4.66% |
| Portfolio beta to SPX | 0.93 |
| 95% loss VaR, reported as return threshold | −5.16% |
| 99% loss VaR, reported as return threshold | −5.37% |
| 95% CVaR / expected-shortfall return | −5.29% |
| Reported probability of losing more than 5% | 13.4% |
| Lowest simulated portfolio return | approximately −5.99% |

The higher-beta names in the reported estimates include **AMD (2.349), TSLA (2.310), NVIDIA (2.106) and Broadcom (2.065)**. The FX positions had much lower estimated SPX sensitivities in this factor specification.

## How to interpret the risk numbers

These values represent the **output of one modeled distribution**, not a verified limit on realized portfolio loss. The specific factor/residual calibration yields unusually narrow-looking conditional tails; in real market dislocations, cross-asset correlations, factor exposures and volatility can shift together.

- The residuals were modeled as approximately normal with fixed betas. Fat tails, jumps, liquidity shocks and nonlinear options exposures are not captured.
- Treat FX pairs as **explicit currency positions** with clarified quote and P&L conventions; simple equal numerical weights across equity securities and quoted FX pairs need portfolio-construction scrutiny.
- The source uses a market shock over a defined time horizon and daily beta estimates; these need an internally consistent portfolio return horizon and validation against actual stress windows.
- Re-estimate the covariance and run **fat-tailed or empirical-resampling sensitivities** before any real risk-limit decision.

## What this use case demonstrates

Reflexivity can combine a natural-language multi-asset holdings list with beta estimates, covariance assumptions, simulation and tail-risk metrics. The value lies in making assumptions visible and supporting follow-up scenario comparisons—not in treating one 50,000-draw number as a guarantee.

## Additional examples and supporting information

Additional research examples and cross-platform comparisons may be available upon request, subject to applicable access and redistribution permissions. Contact **jim@reflexivity.com** and reference **RX-USECASE-0082**.

---

[← All use cases](../../README.md) · [Asset-class index](README.md)
