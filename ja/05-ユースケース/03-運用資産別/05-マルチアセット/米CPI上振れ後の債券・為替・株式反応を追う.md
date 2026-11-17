<!--
id: RX-USECASE-0088
type: use-case
language: ja
locale: ja
author: Reflexivity GTM Team
provider: 株式会社QUICK
source_created: 2026-11-11
published: 2026-11-17
revised: 2026-11-17
editorial_reviewed: 2026-11-17
resource: QUICK Reflexivity usage example: Trace the bond, FX and equity reaction to a US CPI surprise
status: published
translation_status: current
publication_mode: faithful-source-preserving
prompt_status: present
prompt_basis: source-verbatim
-->

# 米CPI上振れ後の債券・為替・株式反応を追う

<!-- locale-switcher:start -->
**Languages:** [English](../../../../en/05-use-cases/03-asset-class/05-multi-asset/trace-the-bond-fx-and-equity-reaction-to-a-us-cpi-surprise.md) · **日本語** · [한국어](../../../../ko/05-유스케이스/03-운용자산별/05-멀티에셋/미국-CPI-서프라이즈-이후-채권·환율·주식-반응.md) · [简体中文](../../../../zh-cn/05-使用案例/03-按资产类别/05-多资产/追踪美国-CPI-超预期后的债汇股反应.md) · [繁體中文（臺灣）](../../../../zh-tw/05-使用案例/03-依資產類別/05-多資產/追蹤美國-CPI-高於預期後的債匯股反應.md) · [繁體中文（香港）](../../../../zh-hk/05-使用案例/03-按資產類別/05-多資產/追蹤美國-CPI-高於預期後的債匯股反應.md)
<!-- locale-switcher:end -->

[← ユースケース一覧](../../README.md)

**活用例の日付:** 2026-11-11  
**中心となる機能:** Alfred

CPI上振れ後の米国債利回り、ドル、株価指数を並べ、短期金利の織り込みとリスク資産の反応を確認します。

> [!NOTE]
> 数値、予測、画面構成は記載日の調査例です。最新の相場やすべての利用環境での提供状況を示すものではありません。

## 使用したプロンプト

> [!IMPORTANT]
> 11月10日に発表された10月の消費者物価指数（CPI）が予想を上回りました。この結果を受けて、アメリカの債券市場、外国為替市場、株式市場の反応を市場ごとにまとめてください。

## 調査の目的と進め方

1. CPI上振れ後の米国債利回り、ドル、株価指数を並べ、短期金利の織り込みとリスク資産の反応を確認します。
2. 要約だけで判断せず、関連する企業、テーマ、イベントや市場の元データを確認します。
3. 分析期間と指標の定義、別の説明要因を確認してから現在の投資判断につなげます。

## この例で確認できること

CPI上振れ後の米国債利回り、ドル、株価指数を並べ、短期金利の織り込みとリスク資産の反応を確認します。

11月10日のCPIは前月比+0.4%（予想+0.3%）、米2年債利回りは+20.1bpとされ、発表直後の市場反応として分析しました。

この例には画面画像が添付されていません。

## 提供時点の詳しい分析

以下は当時の分析内容と数値を保持したスナップショットです。最新の相場見通しとして読むものではありません。

要約
11月10日（米国時間）に発表された10月の米消費者物価指数（CPI）は、前月比0.4%（予想0.3%）、コアは0.3%（予想0.2%）と、いずれも予想を上回りました。この結果を受けて、FRBが12月に
*利上げ*
するとの見方が強まりました。現在の論点は利下げではなく利上げです。市場の反応は、債券が売られて利回りが急上昇し、ドルが買われ、株式はハイテク株を中心に下落するというものでした。
主なポイント
*1. 債券市場：短期債を中心に利回りが急上昇（ベアフラット化）*

   -
   2年債利回りは20.1bp上昇の4.75%、10年債は13.8bp上昇の5%となりました。金融政策の影響を受けやすい短期ゾーンの上昇幅が大きく、利上げ観測をそのまま反映した動きです。
   -
   金利先物市場が織り込む12月の25bp利上げ確率は90%へ上昇（前日84%、1週間前77%）しました。残りの確率は50bpの大幅利上げを示しています。この選択肢は前日・前週には織り込まれていませんでした。

*2. 外国為替市場：日米金利差の拡大でドル高*

   -
   ドル円はNY終値158.74円（取引レンジ158.14〜158.85円）でした。前日比では約+0.53%の円安・ドル高です。日米金利差の拡大を意識した円売り・ドル買いが加速しました。
   - ユーロとポンドも対ドルで下落しました。ドルはカナダドルに対し0.5%高の1.4190となり、同じ記事によると金先物は2.2%下落しました。

*3. 株式市場：テクノロジー株を中心に主要3指数が下落*

   -
   Nasdaq総合は0.7%安、S&P500は0.4%安、ダウは0.3%安で取引を終えました。日中はNasdaqが一時1.5%安まで下げましたが、引けにかけて下げ幅を縮めました。
   -
   セクター別では、テクノロジーが最も下落し、金融が上昇をけん引、Nvidiaは5.5%安でした。ただし、Nvidiaの下落にはCEOに関する個別報道も影響しており、CPIだけが要因ではありません。

データ
10月CPI上振れ後の米国市場の反応（2026年11月10日）
市場 指標 11月10日の水準 変化
債券 米2年債利回り 4.75% +20.1bp
債券 米10年債利回り 5% +13.8bp
金利予想 12月25bp利上げ確率 90% +6pt
為替 ドル円 158.74円 +0.53%
為替 米ドル/カナダドル 1.4190 +0.5%
株式 Nasdaq総合 25,065.87 -0.7%
株式 S&P500 7,520.93 -0.4%
株式 ダウ平均 52,231.89 -0.3%
計算・定義

   - 「サプライズ」は、実績から市場予想を引いた差（前月比、%ポイント）です。CPIは+0.1pt、コアCPIは+0.1ptでした。
   -
   S&P500の騰落率を社内データの11月9日終値（7,549.94）と報道の終値から計算すると-0.38%となり、報道の-0.4%と整合します。

留意点

   - BLSは政府閉鎖による前年データ欠如のため10月の前年比を公表しなかったため、サプライズは前月比で判断しています。
   -
   社内の時系列データは11月9日分までしか更新されておらず、11月10日の水準はニュース報道に基づいています。社内データの前日終値比では2年債利回りの上昇幅は18.9bpで、報道の20.1bpとは基準時点の違いによる差があります。
   - ユーロドルとドル指数の11月10日終値は取得できなかったため、方向のみを記載しています。
   -
   同じ日にADP週次雇用統計の上振れやFRB高官のタカ派発言（ウォラー理事、ローガン総裁）も重なっています。そのため、市場の反応をすべてCPIで説明することはできません。

12月9日のFOMCに向けて、利上げ確率や2年債利回りの推移を引き続き追跡することもできます。 情報源エンティティ（8）

   - SPX
   - DX:ICE
   - EURUSD
   - US_G2Y
   - USDJPY
   - US_G10Y
   - US_G30Y
   - NDX

時系列データ（8）

   - USDJPY.price
   - SPX.price
   - US_G10Y.yield
   - EURUSD.price
   - US_G2Y.yield
   - DX:ICE.price
   - US_G30Y.yield
   - NDX.price

イベント（1件）

   - 米国 の経済イベント

ニュース（20件）

   - Swiss Stocks Rise as US Inflation Data Takes Center Stage
   - US Consumer Prices Rise 0.4% in October, Exceeding Forecasts as Fed
   Hike Looms (UPDATED)
   - Update: US Equity Indexes Decline as Fed Policy Tightening Bets Jump
   After Inflation Beats Forecast
   - Update: Equities Fall as Nvidia Leads Tech Sell-Off
   - Update: Equities Fall Intraday, Yields Surge Following Inflation Report
   - Update: US Equity Indexes Drop as Inflation Data Strengthens Case for
   Fed Rate Increase
   - October Consumer Inflation Cools Less Than Expected, Fueling Bets For
   December Rate Hike
   - Update: US Equity Indexes Drop as October's Inflation Print Boosts Fed
   Policy Tightening Odds
   - Update: US Equity Indexes Fall as Fed's Policy Tightening Odds Rise
   After Inflation Beats Forecast
   - Sector Update: Financial
   - Why Is Applied Digital Stock Falling Tuesday?
   - The US Greenback Rises Against the Canadian Dollar as Higher US CPI
   Adds to Rate Hike Expectations
   - UAE Equities Blink Green Ahead of Key US Inflation Data
   - --US October CPI Rises 0.4% Vs. Expected 0.3% Increase, Prior 0.6% Gain
   - Top Midday Stories: US Consumer Prices Rise Faster Than Expected in
   October; Nvidia Slides After China Chip Report
   - US Dollar Rises Early Tuesday Ahead of October Consumer Price Data
   - October US Consumer Prices Rise More Than Expected, Slower Growth Than
   in September
   - CPI, Crude Views Support Wall Street Pre-Bell; Asia, Europe Up
   - ASX Preview: Australian Shares to Fall as US Fed Rate Bets Rise;
   Commonwealth Bank of Australia Reports Higher Fiscal Q1 Cash Net Profit
   - Stock Futures Mostly Up Ahead of Key Consumer Inflation Report

ウェブリンク（9）

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
   - [Link recorded in original source]
   -
   [Link recorded in original source]

## 解釈上の注意

数値、予測、画面構成は記載日の調査例です。最新の相場やすべての利用環境での提供状況を示すものではありません。

## 関連機能

- [Alfred](https://github.com/reflexivity-kb/platform/blob/main/ja/03-%E8%A3%BD%E5%93%81/Alfred.md)

リンク先の製品マニュアルにはアクセス権が必要な場合があります。

---

本コンテンツは株式会社QUICKから提供された活用例です。数値や市場の見方は提供時点のものです。

[← ユースケース一覧](../../README.md)
