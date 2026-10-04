<!--
id: RX-ARTICLE-0091
type: article
language: en
locale: en
author: Jim
author_profile: https://www.linkedin.com/in/jimlee55/
published: 2026-10-04
revised: 2026-10-04
editorial_reviewed: 2026-10-04
kb_imported: 2026-10-04
status: published
translation_status: canonical
-->

# Compliance Has to Be Designed Into the Research Workflow

<!-- locale-switcher:start -->
**Languages:** **English** · [日本語](../../../ja/06-articles/02-信頼性と監査可能性/コンプライアンスはリサーチワークフローに組み込んで設計する.md) · [한국어](../../../ko/06-articles/02-신뢰성과-감사가능성/리서치-워크플로에-컴플라이언스를-설계해야-하는-이유.md) · [简体中文](../../../zh-cn/06-articles/02-可信度与可审计性/为什么合规必须设计进研究工作流.md) · [繁體中文（台灣）](../../../zh-tw/06-articles/02-可信度與可稽核性/為什麼合規必須設計進研究工作流程.md) · [繁體中文（香港）](../../../zh-hk/06-articles/02-可信度與可審計性/為甚麼合規必須設計進研究工作流程.md)
<!-- locale-switcher:end -->

[← Trust & Auditability](README.md) · [← Articles](../README.md)

<!-- article-byline:start -->
**By:** Jim [![LinkedIn](https://raw.githubusercontent.com/reflexivity-kb/docs/main/assets/ui/linkedin.svg)](https://www.linkedin.com/in/jimlee55/) · **Published:** 2026-10-04 · **Updated:** 2026-10-04
<!-- article-byline:end -->

In institutional AI, compliance cannot be treated as a final approval step applied after the model has already produced an answer.

The control architecture begins earlier: what evidence entered the workflow, what the system was allowed to access, who could review the result, where a human had to intervene, what third parties were involved, and who ultimately remained accountable for the decision.

## AI adoption creates an ownership question

The Bank of England and FCA's 2024 survey found that 84% of firms using AI had an accountable person for their AI framework. Among firms using or planning to use AI, 72% assigned accountability for AI use cases and outputs to executive leadership.

The same survey found that only 2% of reported use cases used fully autonomous decision-making.

Those figures do not create a universal rule for every institution or jurisdiction. They illustrate a broader operating principle: the more consequential the use case becomes, the more important it is to know who owns the system, who can challenge it, and who owns the final decision.

## Accountability cannot be outsourced with the model

A third of the AI use cases reported in the UK survey were third-party implementations.

U.S. Treasury work on AI in financial services has similarly highlighted third-party provider risk, data privacy, bias, and the need for firms to review AI use cases for compliance with existing laws and regulations before deployment and periodically thereafter.

Using an external model, cloud provider, data vendor, or application can reduce build cost and accelerate adoption. It does not transfer the institution's responsibility for understanding how the tool is used in its own process.

Third-party risk is therefore not a procurement footnote. It is part of the research architecture.

## Evidence has to remain reviewable

A compliance process is difficult to operate if the evidence path disappears inside a generated answer.

Institutional users may need to inspect:

- which source or dataset supported a claim;
- what calculation or transformation was performed;
- what evidence was missing;
- what assumptions affected the output;
- whether the output changed after new data arrived.

Reflexivity's current trust and auditability documentation is designed around traceable evidence, inspectable calculations, and explicit treatment of missing evidence rather than completing a result with unsupported assumptions.

That does not turn a research platform into a legal or regulatory control system. It does make human review more practical because the reviewer can inspect the basis of the analysis instead of reconstructing it from scratch.

## Human review should be part of the design

Regulatory and supervisory materials increasingly describe human oversight as part of the operating model.

China's National Financial Regulatory Administration stated in its 2026 guidance that, for high-risk scenarios where explainability is insufficient, AI should act as an auxiliary tool and a human should make the final decision. For important decisions affecting customer rights or material financial outcomes, the guidance calls for human review points and records that support traceability.

Hong Kong Monetary Authority materials similarly emphasize governance and accountability, explainability, validation before launch, ongoing review, and human-in-the-loop approaches for GenAI deployment.

These frameworks are not interchangeable legal requirements. The common principle is narrower: if a human is expected to own the outcome, the workflow has to give that human a meaningful point at which to review, challenge, or stop the process.

## Permission boundaries are part of the workflow

Compliance also begins with what the AI is allowed to access.

A concrete Reflexivity example is Microsoft 365 integration. Current documentation states that Microsoft 365 Copilot integration operates within existing Microsoft 365 Copilot security and permission boundaries. For documented Microsoft 365 source connections, users choose supported sources that Alfred can access and can disconnect them; organization-level administrator approval may also be required.

That is an integration-specific example, not a claim that every Reflexivity deployment uses the same permission model.

The broader design question is consistent across systems: access, entitlement, and data-sharing boundaries should be explicit enough that the institution can understand what entered the analysis and why the system was permitted to use it.

## Compliance is a lifecycle, not a checkbox

Singapore MAS's proposed AI Risk Management Guidelines frame AI risk management across the full lifecycle: governance and oversight, AI inventories, materiality assessment, data management, transparency and explainability, human oversight, third-party risk, evaluation and testing, monitoring, and change management.

That framing is useful because it moves compliance away from a final sign-off.

A production workflow has to keep asking:

- Who is accountable for this use case?
- What evidence and data entered the analysis?
- What permissions and entitlements applied?
- What third parties were involved?
- Where is human review required?
- Can the result and important limitations be explained?
- Is the system still behaving as expected after deployment or change?

## What Reflexivity can support today

Reflexivity's current customer documentation supports several parts of that operating model:

- traceable evidence and source-oriented review;
- inspectable quantitative inputs and calculations;
- explicit treatment of missing evidence;
- decision support that leaves the final judgment with the investor;
- persistent workflows that can be reviewed over time;
- integration-specific security and permission boundaries where those are documented.

These capabilities should not be read as a claim that Reflexivity automatically satisfies every law, policy, internal control framework, or regulatory requirement in every market.

The more defensible claim is simpler: institutional AI is easier to govern when evidence, limitations, human review, and access boundaries are designed into the workflow rather than reconstructed after the answer is generated.

For the broader cross-market evidence, see [How Financial Institutions Across Major Markets Are Adopting AI: What Official Evidence Shows](how-financial-institutions-across-major-markets-are-adopting-ai.md).

## Data / Flow / Compliance

This article is **Part 3: Compliance** in a three-part series.

- **Part 1: Data:** [Data Trust Is Becoming the Adoption Layer for AI in Institutional Research](data-trust-is-becoming-the-adoption-layer-for-ai-in-institutional-research.md)
- **Part 2: Flow:** [AI Is Only Useful When It Arrives at the Point of Decision](../04-research-workflows/ai-is-only-useful-when-it-arrives-at-the-point-of-decision.md)
- **Part 3: Compliance:** Compliance Has to Be Designed Into the Research Workflow

## Further reading

- [Bank of England / FCA: Artificial Intelligence in UK Financial Services, 2024](https://www.bankofengland.co.uk/report/2024/artificial-intelligence-in-uk-financial-services-2024)
- [U.S. Treasury: Uses, Opportunities, and Risks of AI in Financial Services](https://home.treasury.gov/news/press-releases/jy2760)
- [HKMA: Generative Artificial Intelligence in the Financial Services Space](https://www.hkma.gov.hk/media/eng/doc/key-information/guidelines-and-circular/2024/GenAI_research_paper.pdf)
- [HKMA: High-level Principles on Artificial Intelligence](https://brdr.hkma.gov.hk/eng/doc-ldg/docId/getPdf/20191101-1-EN/20191101-1-EN.pdf)
- [National Financial Regulatory Administration: Guidance on Safe Development and Application of AI in Banking and Insurance](https://www.nfra.gov.cn/cn/view/pages/ItemDetail.html?docId=1261784&generaltype=1&itemId=4216)
- [MAS: Proposed Guidelines for Artificial Intelligence Risk Management](https://www.mas.gov.sg/news/media-releases/2025/mas-guidelines-for-artificial-intelligence-risk-management)

[← Trust & Auditability](README.md) · [← Articles](../README.md)
