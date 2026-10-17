<!--
id: RX-USECASE-0083
type: use-case
language: en
locale: en
author: Reflexivity Research
provided: 2026-10-17
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

| Bank | Quarterly observations | Mean release-day price reaction | Median |
| --- | ---: | ---: | ---: |
| JPM | 21 | −0.27% | −0.74% |
| BAC | 20 | +1.59% | +1.85% |
| GS | 21 | +0.82% | +0.90% |

These statistics summarize **overall earnings reactions**, not a clean NII guidance cut-versus-hold comparison. The bank-level averages differed, but the variation reflects all earnings information and market conditions.

## Where the requested classification remains incomplete

The research could not verify a reliable, complete quarter-by-quarter **NII guidance direction** dataset for all three firms. Goldman Sachs does not consistently publish NII guidance as a comparable core indicator. The analysis therefore did **not** calculate a valid three-bank cut-versus-raised-or-flat panel.

For BAC, documented later-period constructive NII guidance was available; the report calculated an approximately **+0.58%** average earnings-day reaction for selected raised/flat guidance quarters from Q3 2024 through Q4 2025. This is a narrow, observed subset and should **not** be presented as the three-bank causal effect of NII guidance.

## How to improve the study

1. Identify each earnings event and exact release time from primary investor-relations material.
2. Extract explicit NII guidance with its basis: net interest income level, growth rate, ex-trading NII or other bank-specific definitions.
3. Mark `cut`, `flat`, `raise`, `not guided` and `unverified` separately; do not infer guidance direction from interest-rate regimes.
4. Align price reaction to the first liquid trading session after each release; compare bank- and index-relative returns.
5. Present the classified event counts before computing mean or median bucket returns.

## What this use case demonstrates

Deep Research can assemble a five-year market-reaction panel and identify a meaningful **source coverage gap** instead of fabricating classifications. Before making a trading or marketing claim about NII guidance, the missing primary-guidance observations must be recovered.

<!-- Source visuals pending: EN PDF p2 quarterly earnings reactions and p4 bank mean/median comparison; p5–9 event-level price table. -->

## Additional examples and supporting information

Additional research examples and cross-platform comparisons may be available upon request, subject to applicable access and redistribution permissions. Contact **jim@reflexivity.com** and reference **RX-USECASE-0083**.

---

[← All use cases](../../README.md) · [Asset-class index](README.md)
