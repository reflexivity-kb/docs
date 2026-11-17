<!--
id: RX-USECASE-0102
type: use-case
language: ja
locale: ja
author: Reflexivity GTM Team
provider: 株式会社QUICK
source_created: 2026-10-30
published: 2026-11-17
revised: 2026-11-17
editorial_reviewed: 2026-11-17
resource: QUICK Reflexivity usage example: Map circular financing among AI investors and compute suppliers
status: published
translation_status: current
publication_mode: faithful-source-preserving
prompt_status: present
prompt_basis: source-verbatim
-->

# AI投資家と計算資源供給者の循環型資金関係を可視化する

<!-- locale-switcher:start -->
**Languages:** [English](../../../../en/05-use-cases/03-asset-class/04-equities/map-circular-financing-among-ai-investors-and-compute-suppliers.md) · **日本語** · [한국어](../../../../ko/05-유스케이스/03-운용자산별/04-주식/AI-투자자와-컴퓨트-공급사의-순환-금융-구조-분석.md) · [简体中文](../../../../zh-cn/05-使用案例/03-按资产类别/04-股票/梳理-AI-投资者与算力供应商的循环融资.md) · [繁體中文（臺灣）](../../../../zh-tw/05-使用案例/03-依資產類別/04-股票/梳理-AI-投資者與算力供應商的循環融資.md) · [繁體中文（香港）](../../../../zh-hk/05-使用案例/03-按資產類別/04-股票/梳理-AI-投資者與算力供應商的循環融資.md)
<!-- locale-switcher:end -->

[← ユースケース一覧](../../README.md)

**活用例の日付:** 2026-10-30  
**中心となる機能:** Alfred, Knowledge Graph

AnthropicのS-1を使い、出資者とクラウド・半導体の供給関係を結び、確定契約と推計額を区別します。

> [!NOTE]
> 数値、予測、画面構成は記載日の調査例です。最新の相場やすべての利用環境での提供状況を示すものではありません。

## 使用したプロンプト

> [!IMPORTANT]
> NVIDIA、Anthoropic、Meta、Google、Amazon、Microsoftなど取引先の増資や債券を引き受ける契約が多く発生しています。これらAI関連企業の出資とビジネスの関係性をわかりやすく表にしてください。Anthoropicの発行したS-1の内容も参考にして回答してください。

## 調査の目的と進め方

1. AnthropicのS-1を使い、出資者とクラウド・半導体の供給関係を結び、確定契約と推計額を区別します。
2. 要約だけで判断せず、関連する企業、テーマ、イベントや市場の元データを確認します。
3. 分析期間と指標の定義、別の説明要因を確認してから現在の投資判断につなげます。

## この例で確認できること

AnthropicのS-1を使い、出資者とクラウド・半導体の供給関係を結び、確定契約と推計額を区別します。

確定済みの計算資源支払義務約4,170億ドルと、追加発注1,250億〜1,500億ドルを分け、報道総額と照合します。

- [関連する一次情報](https://www.sec.gov/Archives/edgar/data/2130357/000162828026067168/anthropicpbc-sx1.htm)

## 画面と分析図表

![Reflexivityの画面・分析図表 1](../../../../assets/usecases/quick/RX-USECASE-0102/01-source-screen.png)

## 提供時点の詳しい分析

以下は当時の分析内容と数値を保持したスナップショットです。最新の相場見通しとして読むものではありません。

要約 Anthropic, PBC は2026年10月26日に S-1 を提出しました。S-1 からは、主要株主である
Amazon・Google・Microsoft・NVIDIA（加えて Broadcom）が、同時に Anthropic
の最大の計算資源供給者でもあることがわかります。出資した資金がクラウド利用料やチップ代として出資者に戻る*「循環型ファイナンス」*の構図です。
支払義務の規模は、定義によって次のように異なります。

   - *確定済みの支払義務:* S-1 上の確定済み計算資源支払義務は約4,170億ドル。2026〜2027年に開始する契約が対象です。
   - *追加発注を含む合計:*
   2028〜2031年納入の追加発注1,250億〜1,500億ドルを加えると合計5,420億〜5,670億ドル。追加発注分は価格が未確定です。
   - *報道ベースの総額:* GeekWire が報じた7,500億ドル超は見積額や重複を含む契約総額で、確定済み支払義務とは定義が異なる。

主なポイント

   - *Amazon.com, Inc.（AMZN）*
   - 投資の中心は転換社債（債券）です。Amazon の累計投資は転換社債80億ドルと優先株100億ドルの合計約180億ドルです。
   - 2026年4月に発表された最大250億ドルは追加出資の「枠」であり、上記の払込済み額とは別です。
   - 評価額は、Amazon は Anthropic
   持分全体を1,904億ドルと評価しており、そのうち元本62億ドルの転換社債分は979億ドルです。社債分は元本の約15.8倍にあたります。
   - 転換後の持分は12%が上限です。同じ社債をAnthropic は1,086億ドルで計上しています。
   - 見返りの取引は、累計投資約180億ドルに対し、AWS への最低コミットメントは1,100億ドルで約6.1倍です。
   - *Alphabet Inc.（GOOGL）*
   - Google は2026年3月に400億ドル（100億ドル確定、300億ドル条件付）の出資を約束し、5月の Series H
   後の残枠は200億ドルです。
   - 資金の戻り先では TPU が最大で、Google 本体へ1,145億ドル、Broadcom の TPU リースへ1,612億ドルが向かいます。
   - *Broadcom Inc.（AVGO）*
   - 供給者が顧客の債券を引き受ける「ベンダー・ファイナンス」の典型です。
   - Anthropic は TPU のリース賃料に充てるため、Broadcom に最大420億ドルの転換社債を発行できる契約を結んでいます。
   - Broadcom は Apollo に移管したリースを、最大290億ドルまでバックストップしています。
   - *Microsoft Corporation（MSFT）・NVIDIA Corporation（NVDA）*
   - Microsoft は出資上限50億ドルに対し、Azure コミットメントは449億ドルで約9.0倍です。
   - NVIDIA は出資上限100億ドルに対し、NVIDIA GPU を使う Nscale・Lambda
   への契約は合計約859億ドルで約8.6倍です。
   - *Anthropic の損益への影響*
   - 上期純損失807億ドルのうち724億ドル（89.6%）は、転換社債などの非現金の公正価値変動です。
   - 出資者側の評価益と Anthropic 側の評価損は、表裏一体の関係にあります。
   - *Anthropic 以外の相互出資（各出典による）*
   - CNBC（2026年5月）によると、NVIDIA
   の2026年の株式投資コミットメントは400億ドル超です。このうち最大の案件は、2026年2月の OpenAI への300億ドルです。
   - OpenAI の発表と GeekWire（2026年2月）によると、Amazon は OpenAI
   に500億ドルを出資し（2026年7月に完了）、OpenAI は1,000億ドルの AWS 追加利用を約束しました。
   - 2025年10月の OpenAI 再編により、Microsoft は OpenAI Group PBC
   の27%を保有しています。OpenAI は2,500億ドルの Azure 追加購入を約束しています。
   - Meta Platforms, Inc.（META）は社債型の調達を活用しています。例として、Hyperion データセンターのSPV
   債273億ドルがあります。

表・チャート Anthropic を中心にみた出資と計算資源契約（S-1ベース）
出資者 出資・資金供給の形態 出資額（判明分） Anthropic からの支払い（ビジネス関係） 支払い ÷ 出資
Amazon.com, Inc. (AMZN) 転換社債（元本62億ドル＝Anthropic
の負債全額）＋無議決権優先株100億ドル。転換後持分は12%が上限 累計 約180億ドル（2026年4月に最大250億ドルの追加枠） AWS
に最低1,100億ドル（〜2036年4月）、Trainium を採用 約6.1倍
Alphabet Inc. (GOOGL) 優先株（Series G-2・H）＋条件付きの社債・無議決権株。2025年初の持分は約14%
2026年に200億ドル払込み、2030年までに残枠200億ドル Google に直接1,145億ドル（〜2033年7月）＋Broadcom 経由の
TPU リース :
Broadcom Inc. (AVGO) Anthropic が Broadcom
に最大420億ドルの転換社債を発行可能（リース賃料専用）。Apollo に移管したリースを最大290億ドルまでバックストップ
最大420億ドル（2026年8月時点で未発行） TPU 機器リース賃料1,612億ドル（5年） :
Microsoft Corporation (MSFT) 株式出資（2025年11月発表） 最大50億ドル Azure
に最低449億ドル（2026年11月〜2033年5月。当初300億ドルから増額） 約9.0倍
NVIDIA Corporation (NVDA) 株式出資（2025年11月発表、2026年の調達ラウンドにも参加） 最大100億ドル NVIDIA
GPU を使う Nscale 446億ドル＋Lambda 413億ドル。Azure も NVIDIA 基盤 約8.6倍
SpaceX（旧 xAI／SpaceXAI） 出資関係なし（純粋な供給者） :
最大1,205億ドル（〜2029年、月約31億ドル、90日前通知で解約可） :
AI大手の相互出資・信用供与と取引関係（主要案件）
資金の出し手 受け手 形態 金額・時期 見返りとなるビジネス（資金の還流先）
NVDA OpenAI 株式 300億ドル（2026年2月） NVIDIA GPU の主要購入者
NVDA CoreWeave／Nebius／IREN 株式・出資権 各20億ドル／20億ドル／最大21億ドル（2026年） NVIDIA
基盤のデータセンターを構築（IREN は最大5GW）
NVDA Intel 株式 50億ドル（評価額250億ドル超） 製品の共同開発
AMZN OpenAI 株式 500億ドル（2026年7月に完了） OpenAI が AWS を8年間で1,000億ドル追加利用、Trainium
2GW
MSFT OpenAI 株式（持分27%） 評価額1,350億ドル（2025年10月） OpenAI が Azure を2,500億ドル追加購入
GOOGL TeraWulf／Cipher（Fluidstack 経由） リース債務のバックストップ＋ワラント（株式）
18億ドル（約8%）／14億ドル（5.4%） TPU を設置するデータセンター容量の確保
Blue Owl・PIMCO ほか META（Hyperion JV） SPV 社債＋JV 出資（Meta の持分は20%） SPV
債273億ドル（満期2049年） Meta がリースバックで利用し、残存価値を保証（オフバランス）
META Scale AI／CoreWeave 株式49%／クラウド購入契約 143億ドル／142億ドル＋210億ドル 学習データ／GPU 計算資源
Anthropic の取引先別計算資源コミットメント（S-1、10億ドル）
読み解き *パターンは3つあります。*

   1. *株式出資とクラウド・チップ利用の約束をセットにする型:* AMZN・GOOGL・MSFT・NVDA →
   Anthropic、AMZN・NVDA・MSFT → OpenAI。
   2. *供給者が顧客の債券・リースを引き受けたり保証したりする型:* Broadcom の転換社債枠とバックストップ、Google
   によるネオクラウドのリース債務バックストップ＋ワラント（TeraWulf、Cipher）。
   3. *自社データセンターをオフバランスの SPV 債で調達する型:* Meta の Hyperion。

*リスク:*

   - S-1 は、計算資源の不足と過剰の両方をリスクとして挙げています。
   - SpaceXAI の契約のように90日前の通知で解約できるものもあり、契約ごとの拘束力は大きく異なります。
   - 需要が鈍化すると、出資の評価損とクラウド売上の減少が同時に出資者に及ぶ「wrong-way risk」が生じます。

制約・注意事項

   - S-1 本文（SEC EDGAR）は直接取得しておらず、数値は S-1 を引用した報道・分析記事に基づくものです。
   - Amazon・Google・Microsoft の現在の持株比率は、S-1 には記載されていません。
   - 契約額には重複があります（例：Google の TPU と Broadcom のリース）。そのため単純に合算できません。
   - 「支払い ÷ 出資」は、最低額または上限ベースのコミットメントを出資額で割った概算値です。
   - 公開価格レンジと発行株数は、今後の S-1 修正版で開示される見込みです。

S-1 修正版で公開価格と株数が出た段階で、Amazon・Alphabet の上場後の持分価値と評価益を試算することもできます。 情報源
ニュース（10件）

   - Anthropic Could Take Major IPO Step as Soon as Friday: What Investors
   Need to Know
   - Update: Anthropic Files for IPO as Financials, Safety Risks Take
   Center Stage
   - Anthropic Files for IPO
   - Anthropic Files for IPO as Financials, Safety Risks Take Center Stage
   - Anthropic IPO Filing Reveals AI Boom’s Next Test: 7 ETFs With
   Pre-Launch Exposure
   - Reed Hastings Could Get Richer From Anthropic IPO: Here's How Many
   Shares Netflix Co-Founder Owns
   - Anthropic IPO Hype Builds as LAZR ETF Expands Exposure to AI’s
   Private-Market Giant
   - Michael Burry Says Anthropic’s IPO Filing Has a Lot, but ‘Nothing That
   Changes’ His View: Big Short Investor Calls Out ‘Slowing’ Revenue Growth
   - Anthropic IPO Faces New Hurdle As NYC Comptroller Urges Delay: Claude
   Parent's Market Debut Odds Slide
   - Kevin O'Leary Says Anthropic IPO Offers What SpaceX Didn't: 'Could Be
   a Hot Trade'

ウェブリンク（90）

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
   -
   [Link recorded in original source]
   -
   [Link recorded in original source]
   - [Link recorded in original source]
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
   -
   [Link recorded in original source]
   -
   [Link recorded in original source]
   - [Link recorded in original source]
   - [Link recorded in original source]
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
   - [Link recorded in original source]
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
   - [Link recorded in original source]
   - [Link recorded in original source]
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
- [Knowledge Graph](https://github.com/reflexivity-kb/platform/blob/main/ja/03-%E8%A3%BD%E5%93%81/Knowledge-Graph.md)

リンク先の製品マニュアルにはアクセス権が必要な場合があります。

---

本コンテンツは株式会社QUICKから提供された活用例です。数値や市場の見方は提供時点のものです。

[← ユースケース一覧](../../README.md)
