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

| BOJ change | MUFG excess | SMFG excess | Mizuho excess |
| --- | ---: | ---: | ---: |
| July 2024 | −9.95 pp | −8.69 pp | −9.46 pp |
| January 2025 | +3.76 pp | +4.13 pp | +8.21 pp |
| December 2025 | +8.15 pp | +0.85 pp | +10.59 pp |
| June 2026 | +10.33 pp | +7.51 pp | +8.12 pp |

The **July 2024** BOJ hike coincided with a major yen carry-trade unwind; all three bank shares fell sharply and underperformed TOPIX. The later windows were generally more favorable, but bank-level returns diverged even when the policy direction was the same.

The corresponding forward EPS observations also varied. In the June 2026 window, the reported revisions were **MUFG +7.47%, SMFG +7.95% and Mizuho +3.65%**. In December 2025, SMFG showed a **−4.41%** revision despite positive relative share performance.

## Why the earnings measure needs care

The dataset compares Tokyo-listed share returns in yen with forward EPS consensus sourced partly from **NYSE ADR coverage for MUFG/SMFG in USD**, and from a yen-denominated series for Mizuho. Percent changes reduce unit differences but do not automatically remove estimate-basis, reporting and ADR comparability issues.

The July 2024 period contains broader market stress; these results are **associations over event windows**, not clean causal estimates of an isolated BOJ decision. Date alignment, market closures and estimate-series continuity should be rechecked before investment use.

## What this use case demonstrates

Deep Research combines event calendars, price history, benchmark-relative returns and analyst estimates in one question. The resulting comparison can be expanded into a multi-bank earnings-sensitivity or net-interest-margin follow-up, with clear distinctions between policy events and concurrent market shocks.

<!-- Source visuals pending: EN PDF p2 excess returns by event, p4 forward EPS revision chart, p5–6 bank-level table. -->

## Additional examples and supporting information

Additional research examples and cross-platform comparisons may be available upon request, subject to applicable access and redistribution permissions. Contact **jim@reflexivity.com** and reference **RX-USECASE-0078**.

---

[← All use cases](../../README.md) · [Asset-class index](README.md)
