<!--
id: RX-USECASE-0083
type: use-case
language: en
locale: en
author: Reflexivity Research
kb_imported: 2026-10-17
status: draft
translation_status: canonical
source_type: reflexivity-native-deep-research-pdf
source_manifest: RX-USECASE-0083
asset_class: Equities, US Financials
roles: Financials Equity PMs, Bank Analysts, Event-Driven Funds
prompt_status: present
prompt_basis: source-verbatim
-->

# Study US Bank Earnings-Day Returns Against Net Interest Income Guidance

<!-- locale-switcher:start -->
**Languages:** **English** · [日本語](../../../../ja/05-ユースケース/03-運用資産別/04-株式/米国銀行の決算反応と純金利収入ガイダンスを比較する.md) · [한국어](../../../../ko/05-유스케이스/03-운용자산별/04-주식/미국-은행-실적발표와-순이자이익-가이던스-비교하기.md) · [简体中文](../../../../zh-cn/05-使用案例/03-按资产类别/04-股票/比较-美国银行财报反应-与净利息收入指引.md) · [繁體中文（台灣）](../../../../zh-tw/05-使用案例/03-依資產類別/04-股票/比較-美國銀行財報反應-與淨利息收入指引.md) · [繁體中文（香港）](../../../../zh-hk/05-使用案例/03-按資產類別/04-股票/比較-美國銀行業績反應-與淨利息收入指引.md)
<!-- locale-switcher:end -->

[← All use cases](../../README.md) · [Asset-class index](README.md)

**Research period:** Quarterly reports Q3 2021–Q3 2026  
**Relevant users:** Financials Equity PMs, Bank Analysts, Event-Driven Funds  
**Assets:** Equities, US Financials

> This is a dated research illustration. Figures and scenario assumptions are not live market data and require independent verification before investment use.

**[Open this research example in Reflexivity →](https://app.reflexivity.com/alfred?mode=research&conversationId=38a711e1-a679-4c88-ab7e-18d97bea0cfc&scrollTo=top)**

## Prompt used

> [!IMPORTANT]
> Over the last five years, how did JPM, BAC and GS shares react the day after earnings in quarters when net interest income guidance was cut, compared with quarters when it was raised or kept flat?

## Investment question

Net-interest-income (NII) guidance changes can affect a bank's revenue expectations and valuation. A useful event study should distinguish the **market reaction to the earnings release** from the market's reaction to a specific **cut, unchanged view or increase in NII guidance**.

This example covers JPMorgan Chase (JPM), Bank of America (BAC) and Goldman Sachs (GS), for reported quarters from Q3 2021 to Q3 2026.

## Align market reactions with release timing

For these **pre-market reporters**, the research measured the earnings-release reaction as:

**(report-date closing price ÷ previous trading-date closing price − 1) × 100**

That is different from mechanically measuring the following calendar day's close; event timestamps and the first tradable post-announcement session are essential.

## Broad earnings-day reactions

![Quarterly earnings release-day price reactions for JPMorgan Bank of America and Goldman Sachs from Q3 2021 through Q3 2026](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0083-us-banks-earnings-quarters.png)

*Figure 1. Quarterly earnings-day stock-price reactions, aligned to pre-market reporting times where documented. These are **all earnings**, not a classification of NII guidance cuts, raises or holds.*

| Bank | Quarterly observations | Mean release-day price reaction | Median |
| --- | ---: | ---: | ---: |
| JPM | 21 | −0.27% | −0.74% |
| BAC | 20 | +1.59% | +1.85% |
| GS | 21 | +0.82% | +0.90% |

These statistics summarize **overall earnings reactions**, not a clean NII guidance cut-versus-hold comparison. The bank-level averages differed, but the variation reflects all earnings information and market conditions.

## Where the requested classification remains incomplete

![Mean and median earnings-release price reactions for JPMorgan Bank of America and Goldman Sachs over five years](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0083-us-banks-mean-median.png)

*Figure 2. Mean/median **overall earnings-day** price reactions. This graphic does not answer the unavailable quarter-by-quarter NII cut-versus-flat-or-raise comparison.*

The research could not verify a reliable, complete quarter-by-quarter **NII guidance direction** dataset for all three firms. Goldman Sachs does not consistently publish NII guidance as a comparable core indicator. The analysis therefore did **not** calculate a valid three-bank cut-versus-raised-or-flat panel.

For BAC, documented later-period constructive NII guidance was available; the report calculated an approximately **+0.58%** average earnings-day reaction for selected raised/flat guidance quarters from Q3 2024 through Q4 2025. This is a narrow, observed subset and should **not** be presented as the three-bank causal effect of NII guidance.

## How to improve the study

1. Identify each earnings event and exact release time from primary investor-relations material.
2. Extract explicit NII guidance with its basis: net interest income level, growth rate, ex-trading NII or other bank-specific definitions.
3. Mark `cut`, `flat`, `raise`, `not guided` and `unverified` separately; do not infer guidance direction from interest-rate regimes.
4. Align price reaction to the first liquid trading session after each release; compare bank- and index-relative returns.
5. Present the classified event counts before computing mean or median bucket returns.

## What this use case demonstrates

The Reflexivity platform can assemble a five-year market-reaction panel and identify a meaningful **source coverage gap** instead of fabricating classifications. Before making a trading or marketing claim about NII guidance, the missing primary-guidance observations must be recovered.

## Additional examples and supporting information

Additional research examples and cross-platform comparisons may be available upon request, subject to applicable access and redistribution permissions. Contact **jim@reflexivity.com** and reference **RX-USECASE-0083**.

---

[← All use cases](../../README.md) · [Asset-class index](README.md)
