<!--
id: RX-USECASE-0076
type: use-case
language: en
locale: en
author: Reflexivity Research
kb_imported: 2026-10-17
status: draft
translation_status: canonical
source_type: reflexivity-native-deep-research-pdf
source_manifest: RX-USECASE-0076
asset_class: Macro, Fixed Income, FX, Equities
roles: Macro PMs, Fixed Income PMs, Multi-Asset PMs
prompt_status: present
prompt_basis: source-verbatim
-->

# Build BOJ Policy Scenarios and Map Sensitivity Across Japanese Assets

[← All use cases](../../README.md) · [Asset-class index](README.md)

**Research period:** September–October 2026 policy and market context  
**Relevant users:** Macro PMs, Fixed Income PMs, Multi-Asset PMs  
**Assets:** Macro, Fixed Income, FX, Equities

> This is a dated research illustration. Figures and scenario assumptions are not live market data and require independent verification before investment use.

**[Open this research example in Reflexivity →](https://app.reflexivity.com/alfred?mode=research&conversationId=94da7a6f-1577-4177-887e-eee11c61c381&scrollTo=top)**

## Prompt used

> [!IMPORTANT]
> Build three BOJ policy path scenarios over the next 12 months and map asset sensitivity across each: (1) Hawkish acceleration — BOJ hikes 25bps twice within 6 months on sticky CPI and wage growth above 3%, bringing the policy rate to ~0.75%; (2) Base case — one additional 25bps hike by Q3, then a prolonged pause contingent on Shunto outcomes and core-core CPI stabilization near 2%; (3) Dovish reversal — growth disappointment or JPY-led import deflation forces BOJ to hold indefinitely, with YCC re-expansion as a tail risk. For each scenario, quantify: directional sensitivity of the Nikkei (export earnings drag vs domestic reflation), USDJPY range (carry unwind dynamics, intervention thresholds), and 10yr JGB yield trajectory (term premium re-pricing, BoJ balance sheet rolloff pace). Anchor to prior hiking cycles and the 2022–2024 YCC exit as historical reference points.

## Why this question matters

A monetary-policy forecast is not yet an investment scenario. A Japanese macro portfolio needs to connect **the Bank of Japan's reaction function** with equity-sector rotation, the yen's carry dynamics and Japanese government bond yields. The three-scenario framework makes those assumptions explicit and allows them to be monitored against fresh inflation, wage and policy data.

## Rebase the rate path before modeling

The requested hawkish destination of approximately 0.75% was already behind the reported policy path. The dated research therefore resets the starting BOJ policy rate to **1.25% as of September 30, 2026**, rather than pretending the older scenario anchors were still live. A separate **October 13, 2026 market-price snapshot** used Nikkei 225 **67,777.52**, USD/JPY **158.64** and the ten-year JGB yield near **3.00%**.

## Three conditional paths

| Path | BOJ policy path over approximately 12 months | Indicative USD/JPY | Indicative 10-year JGB yield |
| --- | --- | --- | --- |
| Hawkish acceleration | 1.25% → 1.50% → 1.75% by Q2 2027 | 150–158 | 3.30–3.60% |
| Base case | 1.25% → 1.50% by Q3 2027; then pause | 152–160 | 3.00–3.25% |
| Dovish reversal / prolonged hold | Hold at 1.25%; YCC re-expansion only a remote tail | 158–168+ | 2.60–3.00% |

In the hawkish case, narrowing rate differentials can support the yen while higher discount rates weigh on exporters; financial and domestic-reflation exposures may partly offset that drag. The base case assumes measured tightening that preserves a constructive domestic earnings backdrop. The dovish case may provide a translation benefit to exporters from a weaker yen, but the associated growth scare can still damage the broader Nikkei.

**These are scenario calibrations, not return forecasts.** The analysis deliberately considers equity effects as a mix of exporter FX sensitivity, domestic demand and financial-sector rate sensitivity rather than assigning one sign to the whole index.

## Historical checks and analytical limits

The historical lens covers the 2022–2024 yield-curve-control exit and subsequent normalization. The illustration includes a cross-market rate/FX/equity timeline and historical equity/FX performance after increases in JGB yields.

- Historical **JGB yield-rise episodes** are only a proxy for hawkish policy changes; they mix macro regimes and are not isolated BOJ announcement-event returns.
- The BOJ filing index did not return the requested primary documents in this execution. Policy interpretation also relied on market series, a calendar and external market indicators.
- FX intervention levels around 160–165 are inferred scenario assumptions, not official Ministry of Finance targets.
- Re-run the research with the **current** BOJ rate, inflation, wage negotiations, Fed path and market prices before using it in a live mandate.

## What this use case demonstrates

Deep Research can move from a long, conditional monetary-policy instruction to an auditable **scenario matrix** that connects fixed income, FX and Japanese equities. A PM can revise assumptions and request targeted sector or carry-unwind stress tests rather than accepting an undifferentiated directional call.

**Related framework:** [Trace hawkish-policy beneficiaries from macro channels to companies](../05-multi-asset/hawkish-policy-beneficiaries-knowledge-graph.md).

<!-- Source visuals pending faithful publication extraction: EN PDF page 2 policy paths, page 4 historical multi-axis chart, and source matrix. See private source-publication manifest. -->

## Additional examples and supporting information

Additional research examples and cross-platform comparisons may be available upon request, subject to applicable access and redistribution permissions. Contact **jim@reflexivity.com** and reference **RX-USECASE-0076**.

---

[← All use cases](../../README.md) · [Asset-class index](README.md)
