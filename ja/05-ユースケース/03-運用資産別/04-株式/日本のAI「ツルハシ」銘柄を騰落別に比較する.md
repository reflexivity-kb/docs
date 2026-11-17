<!--
id: RX-USECASE-0086
type: use-case
language: ja
locale: ja
author: Reflexivity GTM Team
provider: 株式会社QUICK
source_created: 2026-11-12
published: 2026-11-17
revised: 2026-11-17
editorial_reviewed: 2026-11-17
resource: QUICK Reflexivity usage example: Compare winners and laggards among Japanese AI picks-and-shovels stocks
status: published
translation_status: current
publication_mode: faithful-source-preserving
prompt_status: present
prompt_basis: source-verbatim
-->

# 日本のAI「ツルハシ」銘柄を騰落別に比較する

<!-- locale-switcher:start -->
**Languages:** [English](../../../../en/05-use-cases/03-asset-class/04-equities/compare-winners-and-laggards-among-japanese-ai-picks-and-shovels-stocks.md) · **日本語** · [한국어](../../../../ko/05-유스케이스/03-운용자산별/04-주식/일본-AI-인프라-관련주의-강세·약세-비교.md) · [简体中文](../../../../zh-cn/05-使用案例/03-按资产类别/04-股票/比较日本-AI-基础设施受益股的强弱.md) · [繁體中文（臺灣）](../../../../zh-tw/05-使用案例/03-依資產類別/04-股票/比較日本-AI-基建受惠股的強弱.md) · [繁體中文（香港）](../../../../zh-hk/05-使用案例/03-按資產類別/04-股票/比較日本-AI-基建受惠股的強弱.md)
<!-- locale-switcher:end -->

[← ユースケース一覧](../../README.md)

**活用例の日付:** 2026-11-12  
**中心となる機能:** Alfred

米中間選挙後の日本株をプラス・マイナスのグループに分け、既存設備需要とデータセンター新設への依存度を比較します。

> [!NOTE]
> 数値、予測、画面構成は記載日の調査例です。最新の相場やすべての利用環境での提供状況を示すものではありません。

## 使用したプロンプト

> [!IMPORTANT]
> 米国中間選挙後、AI関連の「ツルハシ」銘柄にも選別の動きが起こり、日本企業でも大きく株価への影響を受けていると思われます。 主な銘柄をピックアップして、プラスとマイナスのグループに分け、プラスの理由とマイナスの理由を分析してください。

## 調査の目的と進め方

1. 米中間選挙後の日本株をプラス・マイナスのグループに分け、既存設備需要とデータセンター新設への依存度を比較します。
2. 要約だけで判断せず、関連する企業、テーマ、イベントや市場の元データを確認します。
3. 分析期間と指標の定義、別の説明要因を確認してから現在の投資判断につなげます。

## この例で確認できること

米中間選挙後の日本株をプラス・マイナスのグループに分け、既存設備需要とデータセンター新設への依存度を比較します。

11月2日〜11日の日経平均-2.91%に対し、日本酸素HD+8.97%、三菱電機+3.39%など、同じAI関連でも差がありました。

## 画面と分析図表

![Reflexivityの画面・分析図表 1](../../../../assets/usecases/quick/RX-USECASE-0086/01-source-screen.png)

## 提供時点の詳しい分析

以下は当時の分析内容と数値を保持したスナップショットです。最新の相場見通しとして読むものではありません。

概要
2026年米中間選挙では、民主党が上院54議席・下院228議席を獲得し両院の多数派を奪還しました。これを受け、AIの「ツルハシ」銘柄は
*新規データセンター建設への依存度*を軸に選別されています。
選挙翌日の米国では既存設備を持つ大手ITが上昇する一方、半導体・電力など『建てる側』が売られる選別が起きました。11月5日にはSOXが12.2%安となり、全面安に発展しています。
東京市場では、日経平均が11/2→11/11で-2.91%でした（終値ベースの最大下落は-8.95%）。AI関連の内部では明暗がはっきり分かれています。
*基準は選挙前の最終営業日である11/2の終値です（11/3は日本の祝日）。騰落率は「11/11終値 ÷ 11/2終値 − 1」で計算しています。*
主なポイント *プラス（相対優位）グループ*：いずれも日経平均を上回った銘柄です。

   - *日本酸素HD*
   +8.97%：半導体製造用の特殊ガスを手がけます。11/4に好決算を発表し、上期最終利益は796億円（前年574億円）でした。
   - *三菱電機*
   +3.39%：最大2000億円の自社株買いが下支えしました。電力系ソフトのPCI完全子会社化など、電力・送配電の色彩も強めています。
   - *日立製作所* -0.40%、*富士電機* -1.90%、*ソシオネクスト* -1.68%：ほぼ横ばいで、日経平均よりは強い動きでした。

*マイナス（大幅安）グループ*：いずれも日経平均を約7〜17pt下回った銘柄です。

   - *フジクラ* -19.97%、*古河電工* -13.87%：データセンター向け光ファイバーの銘柄です。
   - 古河電工は一時-28.86%まで下落しました。
   - フジクラは上期最終利益1803億円と大幅増益にもかかわらず、安値からの戻りは+5.37%にとどまります。
   - *キオクシアHD* -15.64%、*イビデン* -13.98%、*アドバンテスト*
   -12.11%：AIサーバー向けのメモリー・基板・テスターで、米半導体株の急落に連動しました。
   - *ソフトバンクグループ*
   -12.59%：米AIデータセンター向け発電設備の調達見直しで上期最終赤字に転落し、ABBロボティクス買収も中国で阻止された。
   - *村田製作所* -13.93%、*太陽誘電*
   -9.93%：MLCCの銘柄です。村田は選挙前に約1兆円のMLCC増産投資を発表して約8%安となっており、そこに選挙後の売りが重なりました。

米中間選挙後の日本のAIツルハシ銘柄 騰落率(11/2→11/11)
AIツルハシ銘柄 プラス/マイナスグループ別 騰落率
グループ 銘柄(コード) AI関連の役割 騰落率 11/2→11/11 対日経平均 選挙後最大下落 安値からの戻り
プラス(相対優位) 日本酸素HD (4091) 半導体用特殊ガス/産業ガス +8.97% +11.88pt +1.16% +7.72%
プラス(相対優位) 三菱電機 (6503) 電力・FA・空調 +3.39% +6.30pt -5.45% +9.34%
プラス(相対優位) 日立製作所 (6501) 送配電(日立エナジー) -0.40% +2.51pt -8.61% +8.98%
プラス(相対優位) ソシオネクスト (6526) カスタムSoC -1.68% +1.23pt -14.29% +14.71%
プラス(相対優位) 富士電機 (6504) パワー半導体・電力機器 -1.90% +1.01pt -11.55% +10.90%
マイナス(大幅安) フジクラ (5803) データセンター向け光ファイバー -19.97% -17.06pt -24.05% +5.37%
マイナス(大幅安) キオクシアHD (285A) NANDメモリー -15.64% -12.73pt -26.82% +15.29%
マイナス(大幅安) イビデン (4062) AIサーバー向けIC基板 -13.98% -11.07pt -26.26% +16.66%
マイナス(大幅安) 村田製作所 (6981) MLCC -13.93% -11.02pt -23.00% +11.78%
マイナス(大幅安) 古河電気工業 (5801) 光ファイバー・電線 -13.87% -10.96pt -28.86% +21.07%
マイナス(大幅安) ソフトバンクグループ (9984) AI投資(スターゲート等) -12.59% -9.68pt -22.90% +13.38%
マイナス(大幅安) アドバンテスト (6857) 半導体テスター -12.11% -9.20pt -21.68% +12.23%
マイナス(大幅安) 太陽誘電 (6976) MLCC -9.93% -7.02pt -20.72% +13.62%
プラスの理由

   1. *新設データセンターに依存しない需要があること。*
   UBSはデータセンターが送電網増強費用を負担する可能性を指摘しています。規制が強まっても、送配電・電力機器（日立、三菱電機、富士電機）の需要は残るか、むしろ増える構図です。
   2. *半導体製造全般に効く消耗品であること。*
   産業ガス（日本酸素HD）は工場の稼働に連動するため、データセンターの着工数には直接左右されません。
   3. *好決算と株主還元が重なったこと。*
   選挙と同じタイミングで、日本酸素HDの増益決算や三菱電機の大型自社株買いといった企業固有の材料が出ました。
   4. ※1〜3の共通点の整理は、価格データとニュースに基づく分析者の推論です。

マイナスの理由

   1. *データセンター新設への感応度が高いこと。*
   光ファイバーやAIサーバー部材は、建設の延期・中止が受注に直結します。UBSは2028年想定の容量追加の約30%がリスクと試算しています。
   2. *高バリュエーションで、ポジションが混雑していたこと。*
   上昇を主導してきた銘柄ほど利益確定売りが大きく出ました。フジクラが好決算でも戻りの鈍い点に、それが表れています。
   3. *米国企業の決算への失望が重なったこと。* クアルコム・アームの見通しへの失望がSOXの急落を増幅し、テスターやメモリーに波及しました。
   4. *固有の悪材料があったこと。* SBGの赤字と買収頓挫、村田の大型投資による需給悪化懸念です。

見通し

   -
   UBSは、規制の中心は新規許認可の厳格化で、資金・顧客の裏付けのない投機的案件が主に圧迫されるとの見方です。過度な悲観は修正される余地があり、古河電工は安値から+21.07%戻しています。
   - 次の焦点は11月18日のエヌビディア決算と、州レベルでの規制の具体化です。

留意点

   - 分析期間は11/2終値〜11/11終値の7営業日と短く、決算・原油・為替などの影響を選挙要因から厳密には分離できていません。
   - グループ分けは11/11終値時点のものです。リバウンド局面のため、順位は短期間で入れ替わる可能性があります。
   - 対象は主要なAI関連大型株（24銘柄）に限定しています。

ご希望であれば、フジクラ・古河電工の米データセンター向け比率や受注動向を決算資料から掘り下げ、規制の影響を定量化できます。 情報源エンティティ（71）

   - 4062:JPX
   - 4004:JPX
   - 5802:JPX
   - 6501:JPX
   - 6503:JPX
   - 6857:JPX
   - 5801:JPX
   - 285A:JPX
   - 6981:JPX
   - 6762:JPX
   - 6971:JPX
   - 6976:JPX
   - 4063:JPX
   - 3436:JPX
   - 7011:JPX
   - 7735:JPX
   - 6526:JPX
   - 6504:JPX
   - 4091:JPX
   - 7203:JPX
   - NKY
   - 8035:JPX
   - 5803:JPX
   - 9984:JPX
   - 6920:JPX
   - 6146:JPX
   - AMD:NASD
   - AVGO:NASD
   - MRVL:NASD
   - NVDA:NASD
   - MU:NASD
   - QCOM:NASD
   - SNDK:NASD
   - ARM:NASD
   - TSM:NYSE
   - STX:NASD
   - WDC:NASD
   - AMAT:NASD
   - LRCX:NASD
   - KLAC:NASD
   - ANET:NYSE
   - CIEN:NYSE
   - CRDO:NASD
   - COHR:NYSE
   - LITE:NASD
   - INTC:NASD
   - VRT:NYSE
   - ALAB:NASD
   - ETN:NYSE
   - SMCI:NASD
   - GEV:NYSE
   - DELL:NYSE
   - PWR:NYSE
   - CSCO:NASD
   - TLN:NASD
   - OKLO:NYSE
   - CEG:NASD
   - CRWV:NASD
   - VST:NYSE
   - NRG:NYSE
   - EQIX:NASD
   - DLR:NYSE
   - NBIS:NASD
   - ORCL:NYSE
   - META:NASD
   - SPX
   - MSFT:NASD
   - AMZN:NASD
   - NASA100
   - GOOGL:NASD
   - SMH:NASD

時系列データ（71）

   - 6762:JPX.price
   - 6971:JPX.price
   - 5802:JPX.price
   - 7735:JPX.price
   - 6526:JPX.price
   - 4091:JPX.price
   - NKY.price
   - 8035:JPX.price
   - 5803:JPX.price
   - 9984:JPX.price
   - 6920:JPX.price
   - 6146:JPX.price
   - 4062:JPX.price
   - 6981:JPX.price
   - 6976:JPX.price
   - 4063:JPX.price
   - 3436:JPX.price
   - 4004:JPX.price
   - 6501:JPX.price
   - 7011:JPX.price
   - 6503:JPX.price
   - 6504:JPX.price
   - 7203:JPX.price
   - 6857:JPX.price
   - 5801:JPX.price
   - 285A:JPX.price
   - AMD:NASD.price
   - AVGO:NASD.price
   - MU:NASD.price
   - NVDA:NASD.price
   - QCOM:NASD.price
   - MRVL:NASD.price
   - ARM:NASD.price
   - WDC:NASD.price
   - TSM:NYSE.price
   - STX:NASD.price
   - SNDK:NASD.price
   - AMAT:NASD.price
   - LRCX:NASD.price
   - KLAC:NASD.price
   - LITE:NASD.price
   - ANET:NYSE.price
   - COHR:NYSE.price
   - DELL:NYSE.price
   - CSCO:NASD.price
   - CIEN:NYSE.price
   - INTC:NASD.price
   - CRDO:NASD.price
   - ALAB:NASD.price
   - ETN:NYSE.price
   - SMCI:NASD.price
   - PWR:NYSE.price
   - VRT:NYSE.price
   - TLN:NASD.price
   - GEV:NYSE.price
   - CEG:NASD.price
   - VST:NYSE.price
   - CRWV:NASD.price
   - NBIS:NASD.price
   - NRG:NYSE.price
   - EQIX:NASD.price
   - OKLO:NYSE.price
   - AMZN:NASD.price
   - ORCL:NYSE.price
   - GOOGL:NASD.price
   - META:NASD.price
   - DLR:NYSE.price
   - MSFT:NASD.price
   - NASA100.price
   - SMH:NASD.price
   - SPX.price

ニュース（147件）

   - SoftBank, Grab, Petros Plan $1 Billion AI Buildout in Malaysia
   - Japanese Stocks Fall After Technology Selloff Revives AI Investment
   Concerns; Oil Gains
   - SCREEN Holdings Attributable Profit Jumps in Fiscal H1
   - Sigurd Microelectronics Acquires NT$768 Million Machinery from Tokyo
   Electron
   - SoftBank-Backed Grab Posts Lower Q3 Attributable Profit; Revenue Up
   - UBS Adjusts SoftBank Group's Price Target to 8,600 Yen
   - ASE Technology Unit to Buy Machinery, Equipment for NT$3 Billion
   - SoftBank Turns to Loss in Fiscal H1 on AI Data Center Procurement Hit
   - Ibiden to Invest 151 Billion Yen to Boost AI Server IC Substrate
   Production
   - Ibiden to Invest 151 Billion Yen in IC Package Substrate Capacity
   - Furukawa Electric Posts Higher Fiscal H1 Attributable Profit; Net
   Sales Up
   - Goldman Sachs Adjusts Furukawa Electric's Price Target to 4,100 Yen
   - SoftBank Confirms China Prohibition of Purchase of ABB's Robotics
   Business
   - Mohamed El-Erian Says America’s AI ‘Let It Rip’ Approach Has Fallen
   Short as Midterm Backlash Grows : Bill Ackman Says ‘We Have to Be Primary
   in AI’
   - US Midterm Results Raise Risks for Data Center, AI Infrastructure
   Buildout, UBS Says
   - US Midterm Results Point to Tighter Data-Center Restrictions, Morgan
   Stanley Says
   - AI Capacity Risks Following Democrats' Win Overblown, UBS Says
   - Democrats' Midterm Victory Negative For AI Sentiment, Morgan Stanley
   Says
   - Japanese Stocks Fall After Democrats Sweep US Midterm Elections; Oil
   Prices Rise
   - BofA Keeps Siemens Energy at Buy on Positive Peer Read-across for Grid
   Business
   - 2026 Midterms Prediction Market Odds Update: Democratic Senate Chances
   Fall to 73%
   - US Elections, Crude Prices, Chip-Wreck Roil Asian Stock Markets
   - -- Democrats Win Control of Congress in 2026 US Midterm Elections
   - OpenAI Pledges to Shield American Households From AI Data Center Power
   Costs: ‘We’ll Pay the Full Cost of the Electricity We Use’
   - Update: US Equity Indexes Surge After Democrats Win Midterm Elections
   - AI Stocks Fall as Democratic Midterm Wins Raise Data Center Concerns
   - Chuck Schumer Says Republicans Threatened to Interfere With Midterm
   Elections, Credits Democrats And 'Tens of Thousands' of Poll Watchers: 'Our
   Democracy Is Stronger...'
   - Australian Stocks Rally as Investors Cheer US Midterm Results; NextDC
   Surges on Share Raid Disclosure
   - Japanese Stocks Fall On Global Technology Selloff; Oil Prices Rise
   - US Midterm Polls Close With Control of Congress at Stake
   - Democratic Sweep Raises US-Iran Deal Odds, Rystad Energy Says as Oil
   Slumps Following Midterm Results
   - Trump Media & Technology Group Stock Falls 16% After Midterm Results
   - Update: Equities Mixed Intraday as Traders Await US Midterm Election
   Results
   - Market Chatter: Democrats Win Control of US Congress in 2026 Midterm
   Elections; Gold Rises
   - Why South Korea’s Largest US ETF Rallied While Seoul Sold Off : and
   What the Midterms Mean Next
   - Japanese Stocks Fall as Investors Weigh AI Regulatory Risks After
   Democratic Sweep; Oil Falls
   - Sector Update: Tech Stocks Gain Late Afternoon
   - SanDisk Surges 10% Following Post-Midterm Crash as Wall Street Debates
   Chip Demand
   - Beyond AI ETFs: 4 Investment Themes Wall Street Could Bet on After
   Midterms
   - Tech Rebound, US Elections Roil Asian Stock Markets
   - Update: US Equity Futures Rise Pre-Bell as Traders Assess Implications
   of Democrat Win in US Midterm Elections
   - Japanese Stocks Open Higher as Democratic Midterm Sweep Sends Oil
   Tumbling
   - Japanese Stocks Slip at Opening
   - Update: US Equity Futures Mixed Pre-Bell as AI Stocks Dip Following
   Democrats' Midterm Win
   - Mitsubishi Electric to Buy Back Up to 200 Billion Yen in Shares and
   Cancel Treasury Stock
   - Mitsubishi Electric Posts Higher Fiscal H1 Attributable Profit;
   Revenue Up
   - Market Chatter: SoftBank Group's $5.4 Billion Deal for ABB's Robotics
   Unit Blocked in China
   - Mitsubishi Electric Completes Full Acquisition of PCI Energy Solutions
   - ASE Technology Unit to Acquire NT$4.97 Billion of Equipment
   - SoftBank, Grab, PETROS Commit $1.85 Billion for Malaysia AI
   Infrastructure
   - Update: SoftBank Group's $5.4 Billion Deal for ABB's Robotics Unit
   Blocked in China
   - Fujikura Posts Higher Fiscal H1 Attributable Profit; Net Sales Up
   - Nippon Sanso Logs Higher Fiscal H1 Attributable Net Income; Revenue Up
   - Murata Manufacturing to Invest 1 Trillion Yen in MLCC Production
   Expansion; Shares Fall 8%
   - Ibiden Logs Higher H1 Attributable Profit; Net Sales Up
   - Tokyo Electron Posts Higher H1 Attributable Net Income; Net Sales Up
   - Advantest Posts Higher Fiscal Q2 Net Profit; Revenue Up
   - Market Chatter: SoftBank, ABB Explore Separating China Business After
   Beijing Blocks Robotics Deal
   - Mitsubishi Electric Posts Higher Fiscal H1; Revenue Up
   - SoftBank Group Posts H1 Attributable Loss; Revenue Up
   - Tokyo Electron to Launch 150 Billion Yen Share Buyback
   - Murata Manufacturing Posts Higher H1 Attributable Profit; Revenue Up;
   Shares Down 7%
   - Hitachi Posts Lower Fiscal H1 Net Profit; Revenue Up
   - Fujikura to Receive $250 Million in Dividends From US Unit
   - Fujikura Agrees to Transfer 60.8% Stake in Consolidated Unit Nishi
   Nippon Electric
   - Japan Earnings Wrap: Sumitomo Realty & Development, Shiseido Rise;
   Honda, SoftBank Group Decline
   - Japanese Stocks Open Marginally Higher as U.S. Tech Lifts Sentiment
   - UBS Adjusts Advantest's Price Target to 45,100 Yen
   - Nanya Technology to Acquire Machinery Worth NT$3.91 Billion from Tokyo
   Electron
   - Arista Networks Insider Sold Shares Worth $43,928,304, According to a
   Recent SEC Filing
   - IBM Nighthawk r3 Quantum Processor Targets 1,000 Qubits in 2027
   - What Is Going on With AMD Stock on Wednesday?
   - OKLO Jumps After DOE Clears Groves-1 to Run Without Restrictions
   - What's Going on With Alphabet Stock on Tuesday?
   - Talen Energy Receives Seven-Year Capacity Deal Worth $100 Million
   Annually
   - Exchange-Traded Funds, Equity Futures Higher Pre-Bell Wednesday as
   Nvidia Stock Recovers
   - Cyclicals Lead Sectors In Wednesday Trading As Defensives Trail
   - Sector Update: Tech Stocks Advance Premarket Wednes

（以下は掲載範囲外）

## 解釈上の注意

数値、予測、画面構成は記載日の調査例です。最新の相場やすべての利用環境での提供状況を示すものではありません。

## 関連機能

- [Alfred](https://github.com/reflexivity-kb/platform/blob/main/ja/03-%E8%A3%BD%E5%93%81/Alfred.md)

リンク先の製品マニュアルにはアクセス権が必要な場合があります。

---

本コンテンツは株式会社QUICKから提供された活用例です。数値や市場の見方は提供時点のものです。

[← ユースケース一覧](../../README.md)
