<!--
id: RX-USECASE-0078
type: use-case
language: en
locale: en
author: Reflexivity Research
kb_imported: 2026-10-17
status: draft
translation_status: canonical
source_type: reflexivity-native-deep-research-pdf
source_manifest: RX-USECASE-0078
asset_class: Equities, Japanese Financials
roles: Japanese Equity PMs, Bank Analysts, Multi-Asset PMs
prompt_status: present
prompt_basis: source-verbatim
-->

# Compare Japanese Bank Returns and EPS Revisions After BOJ Rate Changes

<!-- locale-switcher:start -->
**Languages:** **English** · [日本語](../../../../ja/05-ユースケース/03-運用資産別/04-株式/BOJの利上げ後に主要銀行株とEPS予想がどう動いたか比較する.md) · [한국어](../../../../ko/05-유스케이스/03-운용자산별/04-주식/BOJ-금리변경-후-일본-은행주와-EPS-변화-분석하기.md) · [简体中文](../../../../zh-cn/05-使用案例/03-按资产类别/04-股票/比较-日本银行股-在央行调息后的相对收益和EPS调整.md) · [繁體中文（台灣）](../../../../zh-tw/05-使用案例/03-依資產類別/04-股票/比較-日本銀行股-在BOJ利率調整後的超額報酬與EPS修正.md) · [繁體中文（香港）](../../../../zh-hk/05-使用案例/03-按資產類別/04-股票/比較-日本銀行股-在BOJ調息後的超額回報與EPS預期調整.md)
<!-- locale-switcher:end -->

[← All use cases](../../README.md) · [Asset-class index](README.md)

**Research period:** March 2024 through October 14, 2026  
**Relevant users:** Japanese Equity PMs, Bank Analysts, Multi-Asset PMs  
**Assets:** Equities, Japanese Financials

> This is a dated research illustration. Figures and scenario assumptions are not live market data and require independent verification before investment use.

**[Open this research example in Reflexivity →](https://app.reflexivity.com/alfred?mode=research&conversationId=cfe0f411-8375-4f25-bfee-d5436222ec8c&scrollTo=top)**

## Prompt used

> [!IMPORTANT]
> How have MUFG, SMFG and Mizuho shares performed versus TOPIX in the 20 trading days after each BOJ policy rate change since 2024, and how did consensus EPS estimates for each bank change over the same windows?

## Investment question

Higher Japanese rates can support bank net-interest-margin expectations, but the **share-price response** can be overwhelmed by carry unwinds, market-wide risk and differences among banks. Testing MUFG, SMFG and Mizuho against TOPIX and analyst EPS revisions makes those channels visible rather than assuming every BOJ hike benefits every bank.

## Set event windows and benchmarks

The dated analysis tracked BOJ rate-change events since March 2024. Five events had a complete **20-trading-day** follow-up as of October 14, 2026. The September 18, 2026 move was identified but **excluded** because its full window was not yet available.

Bank and TOPIX cumulative price returns were measured over each post-announcement window. Excess return is **bank return minus TOPIX return** in percentage points. Forward 12-month consensus EPS change was computed over the same window.

## Compare contrasting events

![Twenty-trading-day TOPIX-relative returns for MUFG SMFG and Mizuho following five historical BOJ rate-change events](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0078-bank-excess-returns.png)

*Figure 1. Bank excess price returns versus TOPIX (percentage points) over matched 20-trading-day windows following the identified BOJ events.*

| BOJ change | MUFG excess | SMFG excess | Mizuho excess |
| --- | ---: | ---: | ---: |
| July 2024 | −9.95 pp | −8.69 pp | −9.46 pp |
| January 2025 | +3.76 pp | +4.13 pp | +8.21 pp |
| December 2025 | +8.15 pp | +0.85 pp | +10.59 pp |
| June 2026 | +10.33 pp | +7.51 pp | +8.12 pp |

The **July 2024** BOJ hike coincided with a major yen carry-trade unwind; all three bank shares fell sharply and underperformed TOPIX. The later windows were generally more favorable, but bank-level returns diverged even when the policy direction was the same.

The corresponding forward EPS observations also varied. In the June 2026 window, the reported revisions were **MUFG +7.47%, SMFG +7.95% and Mizuho +3.65%**. In December 2025, SMFG showed a **−4.41%** revision despite positive relative share performance.

## Why the earnings measure needs care

![Forward twelve-month consensus EPS change for three major Japanese banks over BOJ event study windows](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0078-bank-eps-revisions.png)

*Figure 2. Change in forward twelve-month consensus EPS over corresponding 20-trading-day windows (%). The estimate series may differ in currency, ADR basis and coverage across banks.*

The dataset compares Tokyo-listed share returns in yen with forward EPS consensus sourced partly from **NYSE ADR coverage for MUFG/SMFG in USD**, and from a yen-denominated series for Mizuho. Percent changes reduce unit differences but do not automatically remove estimate-basis, reporting and ADR comparability issues.

The July 2024 period contains broader market stress; these results are **associations over event windows**, not clean causal estimates of an isolated BOJ decision. Date alignment, market closures and estimate-series continuity should be rechecked before investment use.

## What this use case demonstrates

Deep Research combines event calendars, price history, benchmark-relative returns and analyst estimates in one question. The resulting comparison can be expanded into a multi-bank earnings-sensitivity or net-interest-margin follow-up, with clear distinctions between policy events and concurrent market shocks.

## Additional examples and supporting information

Additional research examples and cross-platform comparisons may be available upon request, subject to applicable access and redistribution permissions. Contact **jim@reflexivity.com** and reference **RX-USECASE-0078**.

---

[← All use cases](../../README.md) · [Asset-class index](README.md)
