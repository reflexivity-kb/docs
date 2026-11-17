<!--
id: RX-USECASE-0100
type: use-case
language: ja
locale: ja
author: Reflexivity GTM Team
provider: 株式会社QUICK
source_created: 2026-11-09
published: 2026-11-17
revised: 2026-11-17
editorial_reviewed: 2026-11-17
resource: QUICK Reflexivity usage example: Test how often large US IPOs remain below their offer price
status: published
translation_status: current
publication_mode: faithful-source-preserving
prompt_status: present
prompt_basis: source-verbatim
-->

# 米大型IPOが公募価格割れを続けるケースを検証する

<!-- locale-switcher:start -->
**Languages:** [English](../../../../en/05-use-cases/03-asset-class/04-equities/test-how-often-large-us-ipos-remain-below-their-offer-price.md) · **日本語** · [한국어](../../../../ko/05-유스케이스/03-운용자산별/04-주식/미국-대형-IPO의-공모가-하회-사례-검증.md) · [简体中文](../../../../zh-cn/05-使用案例/03-按资产类别/04-股票/检验美国大型-IPO-长期跌破发行价的案例.md) · [繁體中文（臺灣）](../../../../zh-tw/05-使用案例/03-依資產類別/04-股票/檢驗美國大型-IPO-長期跌破招股價的案例.md) · [繁體中文（香港）](../../../../zh-hk/05-使用案例/03-按資產類別/04-股票/檢驗美國大型-IPO-長期跌破招股價的案例.md)
<!-- locale-switcher:end -->

[← ユースケース一覧](../../README.md)

**活用例の日付:** 2026-11-09  
**中心となる機能:** Alfred

大型IPOの過去20年の終値を調べ、上場来の恒常的な公募割れと一時的な公募割れを分けます。

> [!NOTE]
> 数値、予測、画面構成は記載日の調査例です。最新の相場やすべての利用環境での提供状況を示すものではありません。

## 使用したプロンプト

> [!IMPORTANT]
> データセンター関連銘柄の値下がりでAnthropicのIPO価格も下がりそうです。米国株式市場において大型IPO後の株価が、売り出し価格をずっと下回っている企業があるかどうか、過去20年間を分析してください。

## 調査の目的と進め方

1. 大型IPOの過去20年の終値を調べ、上場来の恒常的な公募割れと一時的な公募割れを分けます。
2. 要約だけで判断せず、関連する企業、テーマ、イベントや市場の元データを確認します。
3. 分析期間と指標の定義、別の説明要因を確認してから現在の投資判断につなげます。

## この例で確認できること

大型IPOの過去20年の終値を調べ、上場来の恒常的な公募割れと一時的な公募割れを分けます。

大型IPO36件の検証では上場後ずっと公募価格割れ2社、提供時点の公募割れ21件、中央値-16.4%と整理しました。

## 画面と分析図表

![Reflexivityの画面・分析図表 1](../../../../assets/usecases/quick/RX-USECASE-0100/01-source-screen.png)

## 提供時点の詳しい分析

以下は当時の分析内容と数値を保持したスナップショットです。最新の相場見通しとして読むものではありません。

要約 結論から言うと、*上場後一度も公募価格を上回って引けなかった大型IPOは存在します*。ただし非常にまれです。過去20年の米国の主要な大型IPO
36件を日次終値で検証しました。厳密に「上場来ずっと公募価格割れ」なのは StubHub(STUB)とVenture Global(VG)
の2社だけでした。一方、「初日などごく短期間を除き、ほぼずっと割れている」企業は 9社 あります。サンプル全体では
21件が現在公募価格割れで、公募価格比リターンの中央値は-16.4%
です。大型IPOが公募価格を下回ること自体は珍しくありません。
指標の定義は次のとおりです。

   - *公募価格比リターン*:(直近終値 ÷ 公募価格 − 1)× 100
   - *公募割れ日数比率*:終値が公募価格を下回った営業日数 ÷ 上場来営業日数

株価はいずれも株式分割調整後の終値ベースです。
主な発見

   1. *一度も公募価格を上回っていない企業(厳密な該当例)*

   - *StubHub Holdings, Inc.(STUB)*
   - 2025年上場、公募価格 $23.50
   - 上場来最高終値は初日の $22.00
   - 直近は $6.14(公募価格比 -73.9%)
   - *Venture Global, Inc.(VG)*
   - 2025年上場、公募価格 $25.00
   - 上場来最高終値は $24.00
   - 直近は $11.53(公募価格比 -53.9%)

2. *初日だけ上回り、その後ほぼ一貫して割れている企業*

   - *Lyft(LYFT)*:公募割れ日数比率 99.8%、公募価格比 -76.3%
   - *Full Truck Alliance(YMM)*:公募割れ日数比率 99.6%、公募価格比 -51.8%
   - *Rivian(RIVN)*:この20年で米国最大級のIPOの一つです。公募割れ日数比率 96.3%、公募価格比 -82.6%
   - 次の企業も、上記3社とあわせて 上場来営業日の90%以上で公募価格を下回っている グループに入ります。

企業 公募割れ日数比率
SailPoint(SAIL) 94.3%
Klarna(KLAR) 93.9%
Coupang(CPNG) 92.6%
Lineage(LINE) 91.5%

   1. *長期の公募割れから回復した例*

   - *Robinhood(HOOD)*:公募割れ日数比率は 59.9% でしたが、現在は +112.9%
   - *Uber(UBER)*:公募割れ日数比率は 46.4% でしたが、現在は +52.4%
   - *Meta(META、旧Facebook)*:現在は公募価格比 +1505.7%

いずれも 長期間公募価格を下回った後、現在は公募価格を上回っている 例です。

   1. *AI・データセンター関連の直近IPO*

   - *Cerebras(CBRS)*:2026年5月上場、公募価格 $185.00、公募価格比 -51.5%
   - *CoreWeave(CRWV)*:高値 $183.58 から $46.40 まで下落し、公募価格比は +16.0%
   です。CoreWeaveは高値から大きく下落したが公募価格はなお上回っている 状況です
   - *Figma(FIG)*:公募価格比 -43.0%

初日に大きく上昇したIPOほど、その後の反落も大きい傾向が見られます。

   1. *Anthropic IPOの前提確認*:ご指摘の流れは報道で確認できます。

   - 報道では、一部投資家は1.2〜1.3兆ドルの評価額を議論しており、従来の1.4〜1.5兆ドルから低下した と伝えられています。
   - 評価額への難色から、Anthropic IPOのロードショー開始が遅れる可能性がある とも報じられています。
   - データセンター面では、UBSが米中間選挙後の新設停止リスクを挙げ、2028年の追加容量の約30%がリスクにさらされる と指摘しています。
   - なお、IPO前に評価額が下がること自体は、上場後の公募割れリスクを下げる要因にもなり得ます。

データ 上場来の公募価格割れ日数比率と公募価格比リターン(上位15社)
米国大型IPOの公募価格比パフォーマンス(公募価格割れ日数比率順)
企業 上場日 公募価格 上場来最高終値 直近終値 公募割れ日数比率 公募価格比 区分
StubHub Holdings, Inc 2025-09-17 $23.50 $22.00 $6.14 100.0% -73.9% 一度も上回らず
Venture Global, Inc. 2025-01-24 $25.00 $24.00 $11.53 100.0% -53.9% 一度も上回らず
Lyft 2019-03-29 $72.00 $78.29 $17.09 99.8% -76.3% ほぼ常時割れ
Full Truck Alliance Co. Ltd 2021-06-22 $19.00 $21.50 $9.16 99.6% -51.8%
ほぼ常時割れ
Rivian Automotive, Inc 2021-11-10 $78.00 $172.01 $13.61 96.3% -82.6% ほぼ常時割れ
SailPoint, Inc 2025-02-13 $23.00 $25.70 $19.21 94.3% -16.5% ほぼ常時割れ
Klarna Group plc 2025-09-10 $40.00 $45.82 $13.60 93.9% -66.0% ほぼ常時割れ
Coupang, Inc 2021-03-11 $35.00 $50.45 $16.29 92.6% -53.5% ほぼ常時割れ
Lineage, Inc 2024-07-25 $78.00 $88.57 $39.13 91.5% -49.8% ほぼ常時割れ
Bumble Inc 2021-02-11 $43.00 $78.89 $5.97 87.4% -86.1% 現在割れ
Rocket Companies, Inc. 2020-08-06 $18.00 $41.60 $15.06 77.4% -16.3% 現在割れ
Kenvue 2023-05-04 $22.00 $27.50 $19.31 73.5% -12.2% 現在割れ
Snap Inc. 2017-03-02 $17.00 $83.11 $4.96 71.8% -70.8% 現在割れ
Peloton Interactive 2019-09-26 $29.00 $167.42 $5.61 71.5% -80.7% 現在割れ
Kinder Morgan 2011-02-11 $30.00 $44.57 $29.96 70.0% -0.1% 現在割れ
Figma, Inc 2025-07-31 $33.00 $122.00 $18.81 64.2% -43.0% 現在割れ
Robinhood Markets, Inc 2021-07-29 $38.00 $152.46 $80.91 59.9% +112.9% 公募価格超え
Klaviyo, Inc 2023-09-20 $30.00 $49.19 $20.71 59.7% -31.0% 現在割れ
Mobileye Global Inc 2022-10-26 $21.00 $47.02 $5.73 56.3% -72.7% 現在割れ
Birkenstock Holding Limited 2023-10-11 $46.00 $63.57 $37.32 47.8% -18.9%
現在割れ
Uber Technologies 2019-05-10 $45.00 $100.10 $68.59 46.4% +52.4% 公募価格超え
Blackstone 2007-06-22 $31.00 $199.05 $119.50 43.4% +285.5% 公募価格超え
Cerebras Systems Inc 2026-05-14 $185.00 $311.07 $89.68 37.4% -51.5% 現在割れ
General Motors 2010-11-18 $33.00 $92.43 $86.16 29.6% +161.1% 公募価格超え
Albertsons Companies, Inc. 2020-06-26 $16.00 $27.64 $12.79 24.3% -20.1% 現在割れ
Corebridge Financial, Inc. 2022-09-15 $21.00 $36.24 $34.09 24.1% +62.3%
公募価格超え
Instacart, Inc. (Maplebear Inc.) 2023-09-19 $30.00 $60.88 $58.12 13.1%
+93.7% 公募価格超え
Meta Platforms (Facebook) 2012-05-18 $38.00 $790.00 $610.15 8.4% +1505.7%
公募価格超え
Snowflake Inc. 2020-09-16 $120.00 $401.89 $275.88 3.7% +129.9% 公募価格超え
Alibaba Group 2014-09-19 $68.00 $317.14 $109.45 1.9% +61.0% 公募価格超え
Arm Holdings Limited 2023-09-14 $51.00 $439.46 $174.62 1.3% +242.4% 公募価格超え
CoreWeave, Inc 2025-03-28 $40.00 $183.58 $46.40 1.0% +16.0% 公募価格超え
Visa Inc. 2008-03-19 $11.00 $436.57 $422.65 0.0% +3742.3% 公募価格超え
Airbnb, Inc. 2020-12-10 $68.00 $216.84 $189.99 0.0% +179.4% 公募価格超え
Medline Inc 2025-12-17 $29.00 $49.99 $39.64 0.0% +36.7% 公募価格超え
Reddit, Inc 2024-03-21 $34.00 $270.71 $95.10 0.0% +179.7% 公募価格超え
示唆

   - 「上場来一度も公募価格を超えない」のは極めて例外的です。今回のサンプルでは2社だけで、いずれも初値から公募割れでした。
   -
   一方、「初日だけ上回り、その後ずっと割れる」パターン(Lyft、Rivian、Coupang、Klarnaなど)は大型案件でも繰り返し発生しています。
   - これらに共通するのは、高い評価額での上場、赤字や成長鈍化、上場直後の熱狂です。
   - 初日の上昇幅が大きいほど、その後に公募割れが長期化する例が目立ちます(Rivian、Bumble、Coupang)。
   -
   AnthropicのようにIPO前に評価額が切り下げられた場合、公募価格の割高感は相対的に和らぎます。ただし、AI・データセンター株全体の調整が続けば、公募割れリスクは残ります。

制約・注意点

   - サンプルは主要な大型IPOを抽出したもので、網羅的ではありません。Oatly、Groupon、Lufaxは株式併合調整により公募価格との比較が困難なため除外した
   一方、Visaは2015年の4:1分割調整後の公募価格 $11 で比較しています。
   - 一部の公募価格(Meta、Alibaba、Snap、Visa、GM、Blackstone、Kinder
   Morgan、Kenvue)はIPOカレンダーにデータがなかったため、企業IRや報道ページの値を使用しました。
   - DoorDashは価格データを取得できず、対象外です。
   - 上場廃止・買収された企業(例:Twitter)は含まれておらず、生存バイアスがあります。
   - 終値ベースのため、日中の一時的な公募価格超えは反映していません。リターンは配当を含まない価格リターンです。

ご希望であれば、調達額10億ドル以上の案件を網羅したリストでの再検証や、初値上昇率とその後の公募割れ確率の関係の分析も行えます。 情報源
エンティティ（39）

   - ACI:NYSE
   - BIRK:NYSE
   - CRBG:NYSE
   - KLAR:NYSE
   - KVYO:NYSE
   - LU:NYSE
   - LYFT:NASD
   - MDLN:NASD
   - MBLY:NASD
   - OTLY:NASD
   - RDDT:NYSE
   - RKT:NYSE
   - SAIL:NASD
   - SNOW:NYSE
   - ABNB:NASD
   - UBER:NYSE
   - ARM:NASD
   - META:NASD
   - BMBL:NASD
   - CBRS:NASD
   - CART:NASD
   - BABA:NYSE
   - CPNG:NYSE
   - SNAP:NYSE
   - FIG:NYSE
   - CRWV:NASD
   - GM:NYSE
   - BX:NYSE
   - HOOD:NASD
   - LINE:NASD
   - PTON:NASD
   - RIVN:NASD
   - STUB:NYSE
   - VG:NYSE
   - YMM:NYSE
   - V:NYSE
   - KMI:NYSE
   - GRPN:NASD
   - kvue_nyse

時系列データ（39）

   - BIRK:NYSE.price
   - BMBL:NASD.price
   - CART:NASD.price
   - CBRS:NASD.price
   - CPNG:NYSE.price
   - CRBG:NYSE.price
   - FIG:NYSE.price
   - HOOD:NASD.price
   - KLAR:NYSE.price
   - KVYO:NYSE.price
   - LU:NYSE.price
   - LYFT:NASD.price
   - MBLY:NASD.price
   - PTON:NASD.price
   - RIVN:NASD.price
   - RKT:NYSE.price
   - SAIL:NASD.price
   - ABNB:NASD.price
   - UBER:NYSE.price
   - ACI:NYSE.price
   - STUB:NYSE.price
   - VG:NYSE.price
   - ARM:NASD.price
   - META:NASD.price
   - BABA:NYSE.price
   - V:NYSE.price
   - CRWV:NASD.price
   - KMI:NYSE.price
   - GRPN:NASD.price
   - kvue_nyse.price
   - LINE:NASD.price
   - MDLN:NASD.price
   - OTLY:NASD.price
   - RDDT:NYSE.price
   - SNOW:NYSE.price
   - YMM:NYSE.price
   - SNAP:NYSE.price
   - GM:NYSE.price
   - BX:NYSE.price

ニュース（18件）

   - Jim Cramer Says Bears Want to ‘Derail’ Anthropic IPO as AI Valuation
   Fears Mount: ‘That Will Be the Straw’
   - Anthropic IPO Hype Builds as LAZR ETF Expands Exposure to AI’s
   Private-Market Giant
   - Investors Said To Discuss Anthropic IPO Value Of $1.2T - $1.3T
   - Market Chatter: Anthropic Faces Pressure for Lower IPO Valuation Near
   $1.5 Trillion
   - Anthropic IPO Reality Check: What Recent Listings Suggest for ANT Stock
   - Market Chatter: Anthropic IPO Value of $1.2 Trillion to $1.3 Trillion
   Being Discussed by Investors
   - Market Chatter: Anthropic IPO Faces Investor Pushback Over $1.5
   Trillion Valuation
   - Update: Market Chatter: Anthropic IPO Faces Investor Pushback Over
   $1.5 Trillion Valuation
   - Anthropic IPO Faces Real Risk as AI Bubble Fears Linger and Blackstone
   Sounds a Warning
   - Market Chatter: Anthropic Seeks Up to $3.5 Billion From Japanese
   Investors Through IPO
   - $3 Trillion Wiped Out, But This Strategist Says AI's Biggest Problem
   Isn't Demand: 'Compute Will Become More Scarce'
   - Jim Cramer Has a Warning for AI Data Center Investors Ahead of MSFT,
   GOOGL and AMZN Earnings: ‘Too Early to Say That the Coast Is Clear’
   - US Midterm Results Raise Risks for Data Center, AI Infrastructure
   Buildout, UBS Says
   - CoreWeave and Nebius Tumble 15% as Amazon and Big Tech Hyperscalers
   Outlast AI Data Center Selloff
   - Oracle’s AI Trouble Is Wall Street’s New Headache: 2 ETFs to Watch as
   Data Center Fears Grow
   - AI Stocks Could Fall Further Despite Surging GPU Demand, Research Firm
   Warns
   - Hong Kong Stocks Fall as AI Selloff Deepens, Regulatory Fears Rattle
   Markets
   - Broadcom Stock Is Surging Friday: What's Going On?

ウェブリンク（24）

   - [Link recorded in original source]
   -
   [Link recorded in original source]
   -
   [Link recorded in original source]
   -
   [Link recorded in original source]
   - [Link recorded in original source]
   - [Link recorded in original source]
   -
   [Link recorded in original source]
   -
   [Link recorded in original source]
   -
   [Link recorded in original source]
   -
   [Link recorded in original source]
   -
   [Link recorded in original source]
   -
   [Link recorded in original source]
   -
   [Link recorded in original source]
   -
   [Link recorded in original source]
   - [Link recorded in original source]
   -
   [Link recorded in original source]
   -
   [Link recorded in original source]
   - [Link recorded in original source]
   -
   [Link recorded in original source]
   -
   [Link recorded in original source]
   -
   [Link recorded in original source]
   -
   [Link recorded in original source]
   -
   [Link recorded in original source]
   - [Link recorded in original source]

## 解釈上の注意

数値、予測、画面構成は記載日の調査例です。最新の相場やすべての利用環境での提供状況を示すものではありません。

## 関連機能

- [Alfred](https://github.com/reflexivity-kb/platform/blob/main/ja/03-%E8%A3%BD%E5%93%81/Alfred.md)

リンク先の製品マニュアルにはアクセス権が必要な場合があります。

---

本コンテンツは株式会社QUICKから提供された活用例です。数値や市場の見方は提供時点のものです。

[← ユースケース一覧](../../README.md)
