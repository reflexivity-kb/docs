<!--
id: RX-USECASE-0108
type: use-case
language: ja
locale: ja
author: Reflexivity GTM Team
provider: 株式会社QUICK
source_created: 2026-10-28
published: 2026-11-17
revised: 2026-11-17
editorial_reviewed: 2026-11-17
resource: QUICK Reflexivity usage example: List US earnings with ET/JST release times and research questions
status: published
translation_status: current
publication_mode: faithful-source-preserving
prompt_status: present
prompt_basis: source-verbatim
-->

# 米国決算当日の注目銘柄をETとJSTで一覧する

<!-- locale-switcher:start -->
**Languages:** [English](../../../../en/05-use-cases/03-asset-class/04-equities/list-us-earnings-with-et-jst-release-times-and-research-questions.md) · **日本語** · [한국어](../../../../ko/05-유스케이스/03-운용자산별/04-주식/미국-실적-발표-시각을-ET·JST로-정리.md) · [简体中文](../../../../zh-cn/05-使用案例/03-按资产类别/04-股票/按美国东部时间和日本时间列示财报.md) · [繁體中文（臺灣）](../../../../zh-tw/05-使用案例/03-依資產類別/04-股票/按美國東岸時間和日本時間列示業績.md) · [繁體中文（香港）](../../../../zh-hk/05-使用案例/03-按資產類別/04-股票/按美國東岸時間和日本時間列示業績.md)
<!-- locale-switcher:end -->

[← ユースケース一覧](../../README.md)

**活用例の日付:** 2026-10-28  
**中心となる機能:** Alfred, Events

指定日に決算発表する銘柄を米東部時間・日本時間併記で一覧し、各社の注目材料を整理します。

> [!NOTE]
> 数値、予測、画面構成は記載日の調査例です。最新の相場やすべての利用環境での提供状況を示すものではありません。

## 使用したプロンプト

> [!IMPORTANT]
> 米国時間10月28日に決算発表のある主な銘柄と、それらの企業の業績に対する市場の見方について発表時間は米国東地区時間と日本時間を併記し、一覧で表示してください。

## 調査の目的と進め方

1. 指定日に決算発表する銘柄を米東部時間・日本時間併記で一覧し、各社の注目材料を整理します。
2. 要約だけで判断せず、関連する企業、テーマ、イベントや市場の元データを確認します。
3. 分析期間と指標の定義、別の説明要因を確認してから現在の投資判断につなげます。

## この例で確認できること

指定日に決算発表する銘柄を米東部時間・日本時間併記で一覧し、各社の注目材料を整理します。

10月28日の決算銘柄を米東部夏時間（EDT）と日本時間（JST）で併記し、予想EPSと注目材料を付けました。

この例には画面画像が添付されていません。

## 提供時点の詳しい分析

以下は当時の分析内容と数値を保持したスナップショットです。最新の相場見通しとして読むものではありません。

要約です。時刻は米国東部時間（ET）と日本時間（JST）を併記しています。
寄り付き前（Before Open）に発表
銘柄 発表時刻 ET 発表時刻 JST 予想EPS 市場の注目点・見方
Phillips 66 (PSX
[Reflexivity asset link in source]) 7:00
(10/28) 20:00 (10/28) 11.83 精製マージン急伸と100億ドル自社株買い。高めのバリュエーションが試される
Biogen (BIIB
[Reflexivity asset link in source]) 7:00 20:00
1.99 Leqembi皮下投与の立ち上がり、Apellis統合、MS事業の浸食が焦点
ADP [Reflexivity asset link in source] 7:00
20:00 2.77 AIによる高い顧客定着率、マージン持続性。処理日数の影響に注意
Garmin (GRMN
[Reflexivity asset link in source]) 7:00 20:00
2.38 多角化による成長の底堅さ、AMOLED拡大と航空バックログ
Aon (AON [Reflexivity asset link in source])
6:30 19:30 3.31 統合シナジーとマージン規律。ウェルス事業の弱さが要注意点
Boston Scientific (BSX
[Reflexivity asset link in source]) 6:30 19:30
0.73 電気生理（EP）の強さとマージン持続性、WATCHMAN安定化が試金石
GE Vernova (GEV
[Reflexivity asset link in source]) 6:26 19:26
4.02 送電スーパーサイクル、洋上風力の黒字化、データセンター電力需要
GE HealthCare (GEHC
[Reflexivity asset link in source]) 6:20 19:20
1.21 マージン拡大、過去最高のバックログ消化、AIワークフロー収益化
Amphenol (APH
[Reflexivity asset link in source]) 8:00 21:00
0.73 AIインフラと通信需要の拡大が成長ハードルを引き上げ
Deutsche Bank (DB
[Reflexivity asset link in source]) 5:00 18:00
0.82 :
UBS [Reflexivity asset link in source] Group
(UBS) 1:45 14:45 0.95 発表済み：EPS 0.85で予想を約10.5%下回る（ミス）
引け後（After Close）に発表 : 最注目
銘柄 発表時刻 ET 発表時刻 JST 予想EPS 市場の注目点・見方
Microsoft (MSFT) 16:05 (10/28) 5:05 (10/29) 4.72
AI収益化の変曲点、Azureマージン耐性、CapEx効率が試される
Alphabet (GOOGL) 16:03 5:03 (10/29) 2.99 AIインフラの変曲点、クラウド加速 vs
CapEx、検索の底堅さとマージン規律
Ford (F) 16:05 5:05 (10/29) 0.40 ソフト定義型収益の拡大、EV損失の抑制、配当の持続性
T-Mobile US (TMUS
[Reflexivity asset link in source]) 16:05 5:05
(10/29) 2.90 合併シナジーのピーク、光ファイバー拡大、解約率と競争激化
ServiceNow (NOW
[Reflexivity asset link in source]) 16:10 5:10
(10/29) 0.93 AI収益化のスケール、プラットフォーム統合、バリュエーション試練
Chipotle (CMG
[Reflexivity asset link in source]) 16:10 5:10
(10/29) 0.29 客数回復 vs マージン圧力、デジタル収益性、"Autocado"導入
KLA (KLAC [Reflexivity asset link in source])
16:05 5:05 (10/29) 1.18 AI需要、先端パッケージングの変曲点、マージン持続性
Fortinet (FTNT
[Reflexivity asset link in source]) 16:05 5:05
(10/29) 0.84 ファイアウォール更新サイクル＋AI追い風、高バリュエーション試練
Equinix (EQIX
[Reflexivity asset link in source]) 16:05 5:05
(10/29) 9.28 AI収益化の勢い vs 連続的な軟化、ガイダンス信頼性
Carvana (CVNA
[Reflexivity asset link in source]) 16:05 5:05
(10/29) 0.44 黒字成長の変曲点、販売台数の勢い、負債削減とマージン耐性
eBay (EBAY [Reflexivity asset link in source])
16:05 5:05 (10/29) 1.35 マージン規律と広告の勢い、AIによるテイクレート拡大
主要2社の株価はこちらで確認できます（Microsoft
[Reflexivity asset link in source]／Alphabet
[Reflexivity asset link in source]／Ford
[Reflexivity asset link in source]）。
補足：

   - この日（10/28）は米国が夏時間（EDT, UTC−4）で、冬時間移行は11/1です。JSTはいずれも+13時間。

## 解釈上の注意

数値、予測、画面構成は記載日の調査例です。最新の相場やすべての利用環境での提供状況を示すものではありません。

## 関連機能

- [Alfred](https://github.com/reflexivity-kb/platform/blob/main/ja/03-%E8%A3%BD%E5%93%81/Alfred.md)
- [Events](https://github.com/reflexivity-kb/platform/blob/main/ja/03-%E8%A3%BD%E5%93%81/%E3%82%A4%E3%83%99%E3%83%B3%E3%83%88.md)

リンク先の製品マニュアルにはアクセス権が必要な場合があります。

---

本コンテンツは株式会社QUICKから提供された活用例です。数値や市場の見方は提供時点のものです。

[← ユースケース一覧](../../README.md)
