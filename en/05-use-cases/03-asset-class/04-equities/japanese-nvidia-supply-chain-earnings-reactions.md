<!--
id: RX-USECASE-0079
type: use-case
language: en
locale: en
author: Reflexivity Research
kb_imported: 2026-10-17
status: draft
translation_status: canonical
source_type: reflexivity-native-deep-research-pdf
source_manifest: RX-USECASE-0079
asset_class: Equities, Semiconductors
roles: Thematic Equity PMs, Japan Equity PMs, Semiconductor Analysts
prompt_status: present
prompt_basis: source-verbatim
-->

# Screen Japanese NVIDIA-Related Suppliers Around NVIDIA Earnings

[← All use cases](../../README.md) · [Asset-class index](README.md)

**Research period:** Eight NVIDIA earnings releases, November 2024–August 2026  
**Relevant users:** Thematic Equity PMs, Japan Equity PMs, Semiconductor Analysts  
**Assets:** Equities, Semiconductors

> This is a dated research illustration. Figures and scenario assumptions are not live market data and require independent verification before investment use.

**[Open this research example in Reflexivity →](https://app.reflexivity.com/alfred?mode=research&conversationId=3d561345-1c4e-4605-8d5c-dbb9c73342ed&scrollTo=top)**

## Prompt used

> [!IMPORTANT]
> Which Japanese listed companies have the strongest supply-chain links to NVIDIA, excluding Tokyo Electron and Advantest? For each, show the average next-day move on the TSE after NVIDIA’s last eight earnings releases, how often it moved in the same direction as NVIDIA, and rank them

## Investment question

A global AI-chip event may affect Japanese packaging, materials, manufacturing-equipment and component companies differently. A usable supplier screen should separate **economic or thematic exposure**, the first observable Tokyo share-price move and repeated directional agreement with NVIDIA's earnings reaction.

This example excludes **Tokyo Electron** and **Advantest**, as specified in the question, and considers eight NVIDIA earnings releases from November 2024 through August 2026.

## Build a candidate universe

The research identified twelve Tokyo-listed companies from substrate, wafer, equipment and electronic-component categories. Names in the screen included Ibiden, Disco, SCREEN, Shin-Etsu Chemical, Renesas, SUMCO, TDK, Murata, Lasertec, Kokusai Electric, Tokyo Seimitsu and Hamamatsu Photonics.

The candidate ranking was based on qualitative supply-chain relevance, **not** on each firm's observed earnings-day return.

## Illustrative market observations

![Average next-TSE-session stock movement and same-direction hit rate for twelve Japanese company candidates around eight NVIDIA earnings releases](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0079-nvidia-japanese-suppliers.png)

*Figure 1. **Two different percentage metrics share one axis**: mean stock-price return, typically within several percentage points, and direction agreement, often tens of percent. Compare them **within each metric**, not by bar length across metrics. The original first-TSE-session timing also needs post-US-earnings alignment verification.*

| Japanese company | Average measured TSE session move | Same direction as NVDA |
| --- | ---: | ---: |
| Ibiden (4062) | +4.24% | 4/8 (50%) |
| Disco (6146) | +2.28% | 3/8 (38%) |
| Kokusai Electric (6525) | +2.32% | 2/8 (25%) |
| Murata (6981) | +1.56% | 5/8 (62%) |
| Hamamatsu Photonics (6965) | +0.55% | 6/8 (75%) |

The table illustrates why **return magnitude**, **directional consistency** and **strength of industrial linkage** must be reviewed separately. The highest average return did not have the highest same-direction frequency.

## Critical timing and provenance limitations

NVIDIA normally reports **after the US market closes**. Depending on the release and Japan holiday calendar, the first TSE session after the US date may occur **before the US market has traded on the new earnings information**. The documented first-TSE-session measure can therefore be misaligned with NVIDIA's actual post-earnings reaction. A stronger study would use the appropriately aligned **second TSE session** where necessary.

- Qualitative supplier links came from the in-house knowledge graph and broad industry relationships; they were **not verified as direct NVIDIA contracts or quantified sales dependencies** in this execution.
- Same-direction counts are descriptive for only eight releases, not proof of repeatable alpha.
- Supplier ranking and reaction ranking answer different questions. Neither should be described as an endorsed investment list.
- A follow-up should validate first/second Tokyo sessions and company-specific revenue exposure from primary disclosures.

## What this use case demonstrates

The workflow uses a company event as the seed for **knowledge-graph universe expansion**, then tests that universe with market data. It is useful as a starting list for bottom-up fundamental research and event-timing QA—not a causal test of supplier revenue transmission.

**Related example:** [Find Japanese companies related to rising US stocks](rising-us-stocks-related-japanese-companies.md).

## Additional examples and supporting information

Additional research examples and cross-platform comparisons may be available upon request, subject to applicable access and redistribution permissions. Contact **jim@reflexivity.com** and reference **RX-USECASE-0079**.

---

[← All use cases](../../README.md) · [Asset-class index](README.md)
