<!--
id: RX-ARTICLE-0091
type: article
language: en
locale: en
author: Reflexivity Research
kb_imported: 2026-10-17
status: draft
translation_status: canonical
source_context: October 2026 Japan investment research discussions
-->

# From Investment Questions to Research Workflows: Eight Examples from Japan

[← Research Workflows](README.md) · [← Articles](../README.md)

Investment research rarely begins with a neat dataset. It begins with a question that crosses sources, instruments, reporting dates or market regimes: *What would a Bank of Japan surprise mean for a Japanese equity book? How can an investor distinguish AI-spending announcements from the semiconductor reaction? How much of a market correction might reach a portfolio?*

Eight research questions prepared for discussions during the October 2026 Japan roadshow provide a useful way to examine those challenges. They are not eight promises of an automated investment decision. They are eight examples of **turning an open-ended question into a repeatable sequence of assumptions, measurements, evidence checks and follow-up questions**.

The examples below use **dated research outputs**. Historical returns, scenario paths and estimates are illustrations, not live recommendations. The distinction matters: the research process should remain useful even when the particular market numbers change.

## Start with a decision and work backward to the evidence

Asking for the outlook for Japan is easy. Deciding whether to add exporter exposure, hedge a currency leg or reduce duration is harder.

A policy scenario becomes more useful when it specifies the starting rate, time horizon and assets that must be measured. In [BOJ policy scenarios (RX-USECASE-0076)](../../05-use-cases/03-asset-class/03-macro/boj-policy-path-scenarios-cross-asset-sensitivity.md), three possible BOJ paths connect the rate outlook to USD/JPY, ten-year JGB yields and Japanese equities. The 2026 starting point must be rebased from the older rate levels embedded in the original prompt.

The next question is *which holdings are actually sensitive to the exchange rate?* [TOPIX Core 30 sensitivity to yen appreciation (RX-USECASE-0080)](../../05-use-cases/03-asset-class/01-FX/usdjpy-appreciation-topix-core30-sensitivity.md) screens TOPIX Core 30 stocks using historical periods of sharp yen appreciation. Because the analysis is based on conditional historical returns, the apparent winners and losers are not automatic earnings forecasts or regression-based currency betas.

Then comes a less observable risk: positioning. [yen carry positioning and Nikkei unwind risk (RX-USECASE-0081)](../../05-use-cases/03-asset-class/01-FX/jpy-positioning-nikkei-unwind-asymmetry.md) compares a 2024 carry-trade unwind with the later yen-rate environment and asks whether an abrupt reversal could spill into equities. The important distinction is between **price and carry proxies** and direct CFTC or foreign-investor hedging data, which this particular English example did not have.

Together these questions form a practical chain: **policy path → currency shock → security-level exposure → unwind risk**. Each step suggests the next piece of evidence a portfolio manager should seek.

## Trace an event from corporate investment to related securities

AI infrastructure provides another chain of questions.

[hyperscaler capital spending (RX-USECASE-0077)](../../05-use-cases/03-asset-class/04-equities/hyperscaler-capex-chip-stock-reactions.md) compares reported quarterly capital expenditure at Microsoft, Alphabet, Amazon and Meta with subsequent returns in NVIDIA, Broadcom and TSMC. The original question asked about **management guidance**; the available study uses **reported spending growth as a proxy**, so it cannot be presented as a complete transcript-verified guidance study. Multiple earnings windows also overlap, limiting independent event counts.

A supply-chain perspective opens a different question: what might an NVIDIA earnings event mean for Japanese-listed firms? [NVIDIA-linked Japanese supply chains (RX-USECASE-0079)](../../05-use-cases/03-asset-class/04-equities/japanese-nvidia-supply-chain-earnings-reactions.md) creates a candidate universe and compares Tokyo share-price movements over eight NVIDIA earnings releases. But the US-after-market release time and the Tokyo session calendar must be aligned before calling a return a *post-earnings reaction*. Nor should a thematic industry link be confused with a verified direct NVIDIA supply agreement.

The same event-study discipline applies to financials. In [Japanese bank returns and EPS revisions (RX-USECASE-0078)](../../05-use-cases/03-asset-class/04-equities/japanese-bank-returns-vs-topix-after-boj-hikes.md), MUFG, SMFG and Mizuho returns are benchmarked against TOPIX over twenty trading days after BOJ policy changes and compared with forward EPS consensus revisions. The July 2024 market shock is a reminder that policy direction alone cannot explain an equity move.

In [US bank earnings and NII guidance (RX-USECASE-0083)](../../05-use-cases/03-asset-class/04-equities/us-bank-earnings-net-interest-income-guidance.md), JPMorgan, Bank of America and Goldman Sachs earnings-day stock reactions can be measured across five years. Yet the original question—how price moves differ when net interest income guidance is **cut, unchanged or raised**—remains incompletely answered without a bank-by-bank, quarter-by-quarter guidance classification. A valid research workflow preserves that gap rather than inventing the missing panel.

## Bring the question back to the actual portfolio

Company screens, macro regimes and historical analogies are inputs; the investor still has to understand the portfolio.

[equal-weighted multi-asset portfolio risk (RX-USECASE-0082)](../../05-use-cases/03-asset-class/05-multi-asset/portfolio-monte-carlo-spx-five-percent-correction.md) starts from twenty equity holdings and three currency pairs, assumes equal weights and applies a five-percent S&P 500 factor shock to a Monte Carlo risk model. The output includes asset betas and simulated conditional return quantiles.

That output is valuable only alongside its model assumptions. Constant factor exposures and approximately normal residuals can understate correlation breaks, nonlinear losses and liquidity effects in a disorderly selloff. A portfolio risk estimate should therefore be a *starting point for validation*, not a guarantee about its left tail.

## A useful research system shows its limits

These eight workflows share a discipline that matters more than any single graph.

A good analysis defines **the market observation date**, names **the exact event or modeled shock**, distinguishes **a directly verified input from a proxy**, and allows the reader to inspect **what was not established**. In the examples above, unresolved forward guidance, cross-market earnings timestamps, futures positioning and consensus estimate comparability are material parts of the conclusion.

Those limitations do not negate the usefulness of research automation. They clarify its role. The objective is to shorten the path from a complex investment question to evidence a professional can review, challenge and extend.

That is a more durable standard for Deep Research than judging a system by whether every initial question receives a confident-sounding answer.

## Explore the eight research examples

The linked Reflexivity Use Cases include the original English prompts, research workflows, selected dated results, source-supported charts and known limitations. They can be browsed by investor type, asset class or insight type from the [Use Case index](../../05-use-cases/README.md).

Additional research examples, alternate-language outputs and comparisons with other research environments may be available on request, subject to relevant access, licensing and redistribution permissions. For details, contact **jim@reflexivity.com** and cite one or more of the document IDs **RX-USECASE-0076 through RX-USECASE-0083**.

---

[← Research Workflows](README.md) · [← Articles](../README.md)
