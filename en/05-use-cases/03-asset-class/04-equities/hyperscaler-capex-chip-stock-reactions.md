<!--
id: RX-USECASE-0077
type: use-case
language: en
locale: en
author: Reflexivity Research
kb_imported: 2026-10-17
status: draft
translation_status: canonical
source_type: reflexivity-native-deep-research-pdf
source_manifest: RX-USECASE-0077
asset_class: Equities, Technology
roles: Technology Equity PMs, Thematic PMs, Hedge Funds
prompt_status: present
prompt_basis: source-verbatim
-->

# Test Hyperscaler Capital Spending Against AI Chip-Stock Reactions

[← All use cases](../../README.md) · [Asset-class index](README.md)

**Research period:** Eight reported quarters ending in 2026  
**Relevant users:** Technology Equity PMs, Thematic PMs, Hedge Funds  
**Assets:** Equities, Technology

> This is a dated research illustration. Figures and scenario assumptions are not live market data and require independent verification before investment use.

**[Open this research example in Reflexivity →](https://app.reflexivity.com/alfred?mode=research&conversationId=181a2fc1-8aed-4178-b95f-7f315ba6166d&scrollTo=top)**

## Prompt used

> [!IMPORTANT]
> Over the last eight quarters, how has capex guidance from Microsoft, Alphabet, Amazon and Meta changed on each earnings call? How did Nvidia, Broadcom and TSMC shares perform in the five trading days after each hyperscaler raised guidance, compared with the S&P 500?

## Investment question

Large increases in capital expenditure by Microsoft, Alphabet, Amazon and Meta can signal demand for compute and data-center equipment. An equity investor still needs to distinguish the spending announcement from **actual subsequent performance** in NVIDIA, Broadcom and TSMC, and then compare the outcome with the S&P 500.

## Measure spending first

The research followed eight reported quarters of capital expenditure using cash-flow-statement data. Across the selected first-to-last observations, reported quarterly capex increased by approximately **126.6% at Microsoft**, **214.6% at Alphabet**, **94.8% at Amazon** and **108.7% at Meta**. Amazon's most recent reported quarterly figure reached approximately **$54.21 billion**.

That is a useful spending trajectory, but it is not identical to management's **forward capex guidance**.

## Compare the five-trading-day market reaction

A "raise" event was defined as **quarter-on-quarter growth in reported capex** at an earnings call, yielding 21 observations. The example calculated five-trading-day price performance following those calls.

| Security | Mean five-day return after selected capex-rise events | Excess over S&P 500 |
| --- | ---: | ---: |
| Broadcom (AVGO) | +1.88% | +1.03 percentage points |
| TSMC (TSM) | +1.70% | +0.85 percentage points |
| NVIDIA (NVDA) | +1.19% | +0.34 percentage points |
| S&P 500 | +0.85% | Benchmark |

The resulting averages show modest positive excess performance for the semiconductor names, with Broadcom strongest in this sample. **They do not establish that capex drove the returns.** For example, the same chip-price window can appear multiple times when hyperscalers report on the same day.

## Research workflow

1. Build a dated capital-expenditure series for each company and normalize reporting periods.
2. Classify the event using a documented rule: reported capex growth or independently checked forward **guidance**—do not conflate them.
3. Align earnings timestamps with the next five trading sessions for the chip stocks and the benchmark.
4. De-duplicate overlapping event windows or explicitly flag the shared market exposure.
5. Compare absolute and excess returns with both hit rate and event-by-event outcomes.

## Limitations

- The measured event is **reported capex growth**, a proxy for guidance; this execution could not reliably extract every verbatim forward-dollar guidance announcement.
- Multiple earnings announcements share return windows. The 21 observations therefore do not represent 21 independent trading signals.
- Returns are price-only, and market conditions, concurrent chip earnings and other news can dominate the observed five-day performance.
- The data are a historical illustration, not an assessment of current capex guidance.

## What this use case demonstrates

Reflexivity can join financial-statement observations, earnings dates and market-price windows into a comparative event study while keeping the event definition explicit. The next research pass should rebuild events from verified management guidance and remove overlapping price windows.

**Related example:** [Analyze hyperscaler off-balance-sheet obligations](../05-multi-asset/hyperscaler-off-balance-sheet-debt.md), which addresses financing risk rather than chip-stock event returns.

<!-- Source visuals pending: EN PDF p2 hyperscaler capex lines, p4 five-day bar chart, p5–6 event table. -->

## Additional examples and supporting information

Additional research examples and cross-platform comparisons may be available upon request, subject to applicable access and redistribution permissions. Contact **jim@reflexivity.com** and reference **RX-USECASE-0077**.

---

[← All use cases](../../README.md) · [Asset-class index](README.md)
