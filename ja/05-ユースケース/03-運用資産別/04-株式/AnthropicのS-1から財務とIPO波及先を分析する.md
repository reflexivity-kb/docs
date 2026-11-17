<!--
id: RX-USECASE-0087
type: use-case
language: ja
locale: ja
author: Reflexivity GTM Team
provider: 株式会社QUICK
source_created: 2026-10-27
published: 2026-11-17
revised: 2026-11-17
editorial_reviewed: 2026-11-17
resource: QUICK Reflexivity usage example: Read Anthropic’s IPO filing and map its market impact
status: published
translation_status: current
publication_mode: faithful-source-preserving
prompt_status: present
prompt_basis: source-verbatim
-->

# AnthropicのS-1から財務とIPO波及先を分析する

<!-- locale-switcher:start -->
**Languages:** [English](../../../../en/05-use-cases/03-asset-class/04-equities/read-anthropics-ipo-filing-and-map-its-market-impact.md) · **日本語** · [한국어](../../../../ko/05-유스케이스/03-운용자산별/04-주식/Anthropic-S-1-기반-재무-및-IPO-파급-분석.md) · [简体中文](../../../../zh-cn/05-使用案例/03-按资产类别/04-股票/解读-Anthropic-S-1-与-IPO-连锁影响.md) · [繁體中文（臺灣）](../../../../zh-tw/05-使用案例/03-依資產類別/04-股票/解讀-Anthropic-S-1-與-IPO-連鎖影響.md) · [繁體中文（香港）](../../../../zh-hk/05-使用案例/03-按資產類別/04-股票/解讀-Anthropic-S-1-與-IPO-連鎖影響.md)
<!-- locale-switcher:end -->

[← ユースケース一覧](../../README.md)

**活用例の日付:** 2026-10-27  
**中心となる機能:** Alfred, Asset Overview

提出されたS-1から売上・損益・計算資源契約を読み、恩恵企業と競合への影響を整理します。契約総額と確定債務は区別します。

> [!NOTE]
> 数値、予測、画面構成は記載日の調査例です。最新の相場やすべての利用環境での提供状況を示すものではありません。

## 使用したプロンプト

> [!IMPORTANT]
> Anthoropicの発行したS-1を読んで、直近と今後の財務情報を分析してください。 またこの会社のIPOにより恩恵を受ける会社や大きな影響を受ける会社についても調べてください。

## 調査の目的と進め方

1. 提出されたS-1から売上・損益・計算資源契約を読み、恩恵企業と競合への影響を整理します。契約総額と確定債務は区別します。
2. 要約だけで判断せず、関連する企業、テーマ、イベントや市場の元データを確認します。
3. 分析期間と指標の定義、別の説明要因を確認してから現在の投資判断につなげます。

## この例で確認できること

提出されたS-1から売上・損益・計算資源契約を読み、恩恵企業と競合への影響を整理します。契約総額と確定債務は区別します。

S-1に示された急成長と大幅赤字、計算資源の長期支払義務を対比し、確定契約と報道上の総額を分けて読みます。

- [関連する一次情報](https://www.sec.gov/Archives/edgar/data/2130357/000162828026067168/anthropicpbc-sx1.htm)

## 画面と分析図表

![Reflexivityの画面・分析図表 1](../../../../assets/usecases/quick/RX-USECASE-0087/01-source-screen.png)

## 提供時点の詳しい分析

以下は当時の分析内容と数値を保持したスナップショットです。最新の相場見通しとして読むものではありません。

サマリー Anthropic, PBCは2026年10月26日にNasdaq上場（シンボルANT）を目指すForm
S-1をSECに提出した。主幹事はGoldman SachsとMorgan
Stanley（ほかJPMorgan・Citigroupも関与）。急成長と巨額赤字・巨額コンピュート契約が特徴です。
主要な発見

   - 直近の売上は爆発的に拡大。2025年の売上は約46億ドル（前年比およそ12倍）、純損失は約420億ドルだった。
   - 2026年上期の売上は163億ドルに急増したが、純損失は会計調整の影響で807億ドルに拡大した。
   - 2026年第3四半期の売上は168億ドルに達した。
   - 顧客集中度は高く、ネット・レベニュー・リテンション率は約900%で、顧客の上位5社が売上の約25%を占める（スイッチングリスクの裏返し）。
   -
   将来コミットメントは巨大。将来のコンピュート/インフラの最低コミットメントは約2,656億ドル、名前の挙がった企業との契約総額は約6,370億ドルに上る。
   -
   IPO目標評価額は2兆ドル超で、直近のプライベート評価額9,650億ドル（2026年5月シリーズH）から約107%上昇を狙う。2028年の売上見通し約1,900〜2,000億ドルがその根拠とされる。

財務の推移（チャート） Anthropic 売上の推移（S-1開示より）
直近の財務情報（直近）
項目 金額 期間
売上 約46億ドル FY2025
純損失 約420億ドル FY2025
売上 163億ドル 2026年上期
純損失 807億ドル（大半は非現金の会計調整） 2026年上期
売上 168億ドル 2026年Q3
今後の財務見通し（今後）

   - 評価額: IPO目標評価額は2兆ドル超。2026年最大級のIPOとなる見込み。
   - コスト構造:
   名前の挙がった企業との契約総額は約6,370億ドルに上るため、今後数年の費用が大きく膨らむ。約80%はキャンセル不能とされ、収益化できなければ赤字継続のリスク。
   -
   Anthropic自身が「売上成長率は変動し、やがて鈍化する」と警告。収益の5〜7%がポリシー違反利用（蒸留など）由来で、取り締まり強化が売上を押し下げる可能性。
   - クラウド依存: 2025年の売上の47%がAmazonとGoogleのクラウド経由で計上されたと開示。

IPOで恩恵を受ける／大きな影響を受ける企業 AnthropicのIPOで恩恵を受ける主要コンピュート/クラウド・パートナー
企業 関係 契約規模 (ドル) 直近株価 (USD)
Broadcom (AVGO) カスタムチップ/5年マスターリース 約1,612億 333.05
Alphabet / Google (GOOGL) 投資家＋クラウド＋TPU供給 追加1,250〜1,500億 (TPU, 2028-31) 317.9
Microsoft (MSFT) クラウド/コンピュート契約 最低449億 (2026-2033) 532.08
Amazon (AMZN) 戦略投資家＋AWSクラウド 金額非開示 (売上の47%がAWS/Google経由) 249.37
AMD GPU供給 (金額非固定) 金額非開示 535.7
NVIDIA (NVDA) GPU供給（業界標準）／競合代替リスク S-1で固定額の明示なし 216.55
*恩恵を受ける側（コンピュート供給・投資家）*

   - Broadcomとは5年間のマスターリースで約1,612億ドルを支払う契約 : カスタムAIチップの最大の受注先。直近株価 $333.05。
   - Googleとは2028〜2031年にTPUコンピュートで追加1,250〜1,500億ドルの支払いが見込まれる。投資家でもありクラウドでもある。直近株価
   $317.9。
   - Microsoftとは2026年11月〜2033年5月に最低449億ドルを支出する契約。直近株価 $532.08。
   - Amazon（AMZN）: 戦略投資家＋AWS。評価益とクラウド売上の両面で恩恵。直近株価 $249.37。
   - AMD: GPU供給（固定額非開示）。直近株価 $535.7。

*大きな影響を受ける側*

   - NVIDIA（NVDA）: 業界標準GPUだが、AnthropicがBroadcomのカスタムシリコンやGoogle
   TPUへ多様化していることは、将来の需要配分を占ううえで注目点。直近株価 $216.55。
   -
   競合のOpenAI（非上場）・Alphabet（Gemini）・Microsoft（自社AI）は、Anthropicの上場による資金調達力強化で競争が激化。

留意事項・データ品質
AnthropicはIPO前の非上場企業であり、財務数値は提出済みS-1に関する一次・二次報道から再構成したもの。当社の社内時系列データに同社の株価系列は存在しません。純損失の大部分は非現金の会計調整によるもので、営業損失（2025年で約80億ドル規模との報道）とは区別が必要です。契約金額は公開S-1で一部空欄のため、合計額は報道により幅があります（名前付き約6,370億ドル／リーク版約5,180億ドル）。
必要であれば、Broadcom・Alphabet・AMDなど上場プロキシの株価がS-1提出前後でどう動いたかを時系列で検証したり、Anthropicの営業損失と純損失の差（会計調整の内訳）をさらに深掘りできます。
情報源ニュース（15件）

   - Anthropic Hits $65 Billion Annualized Revenue Run Rate as Claude
   Drives Explosive Growth Ahead of Potential IPO: Report
   - Anthropic Isn't Public Yet. There's Already an ETF Filed to Short It
   at 2x
   - Anthropic IPO Faces New Hurdle As NYC Comptroller Urges Delay: Claude
   Parent's Market Debut Odds Slide
   - Anthropic’s Founders Are Making a Power Grab Before Going Public
   - Anthropic Picks Nasdaq for Its $2 Trillion IPO, Tells Investors It
   Expects a Second Consecutive Profitable Quarter: Reports
   - Anthropic IPO Filing Reveals AI Boom’s Next Test: 7 ETFs With
   Pre-Launch Exposure
   - Anthropic Prepares to Show Investors New Revenue Figures Ahead of
   Potential IPO
   - Anthropic's Q3 Revenue Surged 45% to $16.8 Billion, Profitable on
   Adjusted Basis as Dario Amodei Courts Investors: Report
   - Anthropic Could Take Major IPO Step as Soon as Friday: What Investors
   Need to Know
   - Market Chatter: Anthropic's IPO Valuation Relies on $190 Billion to
   $200 Billion 2028 Revenue Forecast
   - Reed Hastings Could Get Richer From Anthropic IPO: Here's How Many
   Shares Netflix Co-Founder Owns
   - EXCLUSIVE: Anthropic IPO Could Be ‘Heavily Oversubscribed,’ IPO
   Adviser Says
   - Eric Schmidt Wrote a Check to Anthropic Before the AI Boom: Here’s How
   Big the Payoff Could Get
   - Anthropic Could Be Worth More Than Bitcoin by Year-End, Polymarket
   Traders Say
   - Anthropic Bets Big On AI, Bleeds Billions: Key Details From The
   Reported IPO Prospectus

ウェブリンク（16）

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
   - [Link recorded in original source]
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

## 解釈上の注意

数値、予測、画面構成は記載日の調査例です。最新の相場やすべての利用環境での提供状況を示すものではありません。

## 関連機能

- [Alfred](https://github.com/reflexivity-kb/platform/blob/main/ja/03-%E8%A3%BD%E5%93%81/Alfred.md)
- [Asset Overview](https://github.com/reflexivity-kb/platform/blob/main/ja/03-%E8%A3%BD%E5%93%81/%E9%8A%98%E6%9F%84%E6%A6%82%E8%A6%81.md)

リンク先の製品マニュアルにはアクセス権が必要な場合があります。

---

本コンテンツは株式会社QUICKから提供された活用例です。数値や市場の見方は提供時点のものです。

[← ユースケース一覧](../../README.md)
