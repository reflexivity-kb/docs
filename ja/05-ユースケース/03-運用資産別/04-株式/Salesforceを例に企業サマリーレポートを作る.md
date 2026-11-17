<!--
id: RX-USECASE-0098
type: use-case
language: ja
locale: ja
author: Reflexivity GTM Team
provider: 株式会社QUICK
source_created: 2026-11-10
published: 2026-11-17
revised: 2026-11-17
editorial_reviewed: 2026-11-17
resource: QUICK Reflexivity usage example: Create a reusable company summary report using Salesforce
status: published
translation_status: current
publication_mode: faithful-source-preserving
prompt_status: present
prompt_basis: source-verbatim
-->

# Salesforceを例に企業サマリーレポートを作る

<!-- locale-switcher:start -->
**Languages:** [English](../../../../en/05-use-cases/03-asset-class/04-equities/create-a-reusable-company-summary-report-using-salesforce.md) · **日本語** · [한국어](../../../../ko/05-유스케이스/03-운용자산별/04-주식/Salesforce-예시로-기업-요약-보고서-작성.md) · [简体中文](../../../../zh-cn/05-使用案例/03-按资产类别/04-股票/以-Salesforce-为例制作公司摘要报告.md) · [繁體中文（臺灣）](../../../../zh-tw/05-使用案例/03-依資產類別/04-股票/以-Salesforce-為例製作企業摘要報告.md) · [繁體中文（香港）](../../../../zh-hk/05-使用案例/03-按資產類別/04-股票/以-Salesforce-為例製作企業摘要報告.md)
<!-- locale-switcher:end -->

[← ユースケース一覧](../../README.md)

**活用例の日付:** 2026-11-10  
**中心となる機能:** Alfred, Asset Overview, Themes

企業概要、最近の話題、決算、1年間の財務、関連テーマ、株価チャートの順序をプロンプトで指定します。

> [!NOTE]
> 数値、予測、画面構成は記載日の調査例です。最新の相場やすべての利用環境での提供状況を示すものではありません。

## 使用したプロンプト

> [!IMPORTANT]
> アナリストレポートのような体裁で、企業のレポートを作成してください。 * *企業名はSalesforceです。 * *最初に企業概要、その次に最近の話題を記載してください。* *そ**の下には、１か月以内に決算発表があれば、決算内容のサマリーを載せてください。 * *その下には、過去１年分の業績の表と、直近の業績に関するコメントを記載。 * *その下には、この企業が属するテーマとそのテーマのパフォーマンスや市場の受け止め方を記載してください。 * *その下には過去１年間の日足のチャートを載せてください。

## 調査の目的と進め方

1. 企業概要、最近の話題、決算、1年間の財務、関連テーマ、株価チャートの順序をプロンプトで指定します。
2. 要約だけで判断せず、関連する企業、テーマ、イベントや市場の元データを確認します。
3. 分析期間と指標の定義、別の説明要因を確認してから現在の投資判断につなげます。

## この例で確認できること

企業概要、最近の話題、決算、1年間の財務、関連テーマ、株価チャートの順序をプロンプトで指定します。

Salesforceを例に、企業概要、ニュース、決算、過去1年の財務表、関連テーマ、日足チャートを同じ構成で出力しました。

## 画面と分析図表

![Reflexivityの画面・分析図表 1](../../../../assets/usecases/quick/RX-USECASE-0098/01-source-screen.png)

![Reflexivityの画面・分析図表 2](../../../../assets/usecases/quick/RX-USECASE-0098/02-source-screen.png)

## 提供時点の詳しい分析

以下は当時の分析内容と数値を保持したスナップショットです。最新の相場見通しとして読むものではありません。

サマリーを載せてください。 *
*その下には、過去１年分の業績の表と、直近の業績に関するコメントを記載。 *
*その下には、この企業が属するテーマとそのテーマのパフォーマンスや市場の受け止め方を記載してください。 *
*その下には過去１年間の日足のチャートを載せてください。*
Salesforce, Inc.（CRM）企業レポート *基準日: 2026年11月10日（株価は2026-11-09終値 $214.94）*
サマリー

   - AIマーケティング・顧客接点領域で大型M&Aを相次いで発表しています。Braze買収（約$5.66B）とCresta
   Intelligence買収（推定$2.7B）などです。市場はバリュエーションと統合リスクを警戒し、株価は10月29日に-4.63%、11月6日に-3.94%と下落しました。
   - 過去1か月以内に決算発表はありません（直近の発表は2026年8月26日）。直近のQ2
   FY2027は、EPSがコンセンサスを+90.94%上回り、通期ガイダンスも引き上げました。
   - 株価は1年で-11.08%、年初来で-18.86%です。Enterprise Software・Agentic
   AIテーマと同様に軟調に推移しています。

1. 企業概要 Salesforce,
Inc.（CRM）は、クラウド型CRM（顧客関係管理）の世界最大手です。マルチテナント型SaaSモデルで、営業・サービス・マーケティング・データ・コラボレーションを統合したプラットフォームを提供しています。

   - *事業・製品:* 「Agentic CRM」戦略の中核として、Agentforce、Data Cloud（Data
   360）、Slack、Sales Cloud、Service Cloud、MuleSoft/Tableauを展開しています。
   - *AI関連ARR:* 決算リキャップの見出しベースで、2つの数値が報告されています。範囲が異なるため、直接比較はできません。
   - Q4 FY2026: Agentforce/Data Cloud 合算ARR $1.8B
   - Q1 FY2027: Agentforce単体ARR $1.2B超
   - *地域:* 最大市場は米国です。欧州では英国、アジア太平洋では日本が主要市場です。インドは開発拠点として機能しています。
   - *競合:*
   Microsoft（MSFT）、Oracle（ORCL）、HubSpot（HUBS）、ServiceNow（NOW）、Adobe（ADBE）、Pegasystems（PEGA）、Sprinklr（CXM）などです。

2. 最近の話題

   - *Braze買収（10/20）:*
   Brazeを1株$47.50の現金、約$5.66Bで買収することで合意しました。発表当日、CRM株はプレマーケットで3%超下落しています。また、一部アナリストが格下げし、買収価値を精査する動きとなりました。
   - *M&A攻勢:* 企業カレンダーによると、次の3件の買収契約を締結しています。
   - 10/12: Loops B.V.
   - 10/29: 防衛AI物流のRune Technologies
   - 11/2: Cresta Intelligence（推定$2.7B）
   - *提携:* Docusignとエージェント型契約管理をネイティブ統合（10/13）しました。
   - *アナリスト評価:* DBSは目標株価を$240から$300へ引き上げました。アナリストの平均目標株価は$282.78です。
   - *株価の動き:* 10/22に+3.52%と反発しました。その後は10/29に-4.63%、11/6に-3.94%と下落しています。
   - *9月の論点:* Agentforceの成果報酬型価格への移行、9/16のグローバル障害、AIforceの投入が注目されました。

3. 決算サマリー（過去1か月）
過去1か月以内（10/10〜11/10）に決算発表はありません。参考として、2026年8月26日に発表された直近のQ2
FY2027の決算内容を記載します。

   - *実績:*
   調整後EPSは$5.90で、予想の$3.09を+90.94%上回りました。売上は$11.345Bで、予想比+0.24%でした。cRPOは恒常通貨ベースで14%に加速し、通期ガイダンスは$200M引き上げられました。
   - *ガイダンス:* FY2027は売上$46.1B〜$46.4B・調整後EPS
   $16.67〜$16.71、Q3は売上$11.42B〜$11.50B・調整後EPS $3.42〜$3.44です。
   - *株価反応:* 翌営業日（8/27）の株価は+22.58%でした。
   - *次回決算:* Q3 FY2027の発表日は、取得データでは確認できていません。前年のQ3は12月上旬に発表されています。

4. 業績（過去1年・四半期）
売上・営業利益・純利益・EPSはGAAPベースで、会社が公表する調整後EPSとは異なります。FCFは営業CFから設備投資を差し引いた値です。
Salesforce 四半期業績（直近4四半期・GAAP）
四半期 売上高 売上YoY 営業利益率 純利益 希薄化EPS FCF
Q2 FY2027 $11.35B +10.8% 21.4% $3.53B $4.29 $1.10B
Q1 FY2027 $11.13B +13.3% 21.8% $2.11B $2.42 $6.56B
Q4 FY2026 $11.20B +12.1% 19.2% $1.94B $2.07 $5.32B
Q3 FY2026 $10.26B +8.6% 23.9% $2.09B $2.19 $2.18B
*直近業績へのコメント*

   - *成長:* 売上高YoY成長率は、Q2で10.8%と、Q1の13.3%から減速しました。一方、先行指標であるcRPOは加速しています。
   - *収益性:*
   GAAP営業利益率は21.4%で、20%台前半を維持しています。Q2のGAAP純利益は$3.53B、EPSは$4.29と大きく伸びました。ただし営業利益は横ばいのため、営業外要因が寄与したとみられます。
   - *キャッシュフロー・資本政策:*
   FCFは季節性が強く、Q2は$1.10B、Q1は$6.56Bでした。Q1にはCF計算書上で$27.5Bの自社株買いを計上しています。

5. 所属テーマとパフォーマンス・市場の受け止め方 関連テーマは、Enterprise Software、Agentic AI、SaaS、Cloud
Computing、Data Analytics、Data Centersです。
Salesforce関連テーマのパフォーマンス（2026-11-09時点）
テーマ 1M 3M 6M 1Y
SaaS -5.7% +6.0% +48.9% +17.0%
Data Analytics +9.2% +7.2% +41.2% +13.5%
Cloud Computing -16.1% -7.4% +20.2% +11.1%
Data Centers -20.9% -15.3% -13.4% +28.8%
Agentic AI -11.3% -9.3% +4.0% -12.1%
Enterprise Software -6.7% +2.4% +32.9% -13.1%
参考：CRM株価 : +11.5% +18.2% -11.1%
関連テーマの1年累積パフォーマンス推移

   - *パフォーマンス:* CRMの1年リターン（-11.08%）は、Enterprise Software（-13.1%）やAgentic
   AI（-12.1%）とほぼ同等です。一方、SaaS（+17.0%）には劣後しています。
   - *直近1か月:* Agentic AI（-11.3%）とCloud Computing（-16.1%）が調整しました。堅調だったのはData
   Analytics（+9.2%）のみです。
   - *市場の受け止め方:*
   10月下旬には、「SaaSpocalypse（AIによるSaaS代替）」懸念の後退が報じられ、ソフトウェア株は一時反発しました。しかし11月に入ると、AI関連株の大規模な時価総額消失やAIバリュエーション懸念が広がり、AI関連テーマ全体の重荷となっています。CRMについては、AIエージェントの収益化期待と、大型M&Aによる資本配分への懸念が綱引きしている状況です。

6. 株価チャート（過去1年・日足） Salesforce（CRM）過去1年の日足終値と移動平均
CRM 株価統計（2026-11-09終値 $214.94）
指標 値
1日変化 +1.29ドル（+0.60%）
月初来 -6.21%
3か月 +11.52%
6か月 +18.22%
1年 -11.08%
年初来 -18.86%
52週高値 $266.23（2025-12-29）
52週安値 $150.12（2026-06-22）
株価は2025-12-29に52週高値$266.23をつけた後に下落し、2026-06-22に52週安値$150.12で底を打ちました。Q2決算を受けて急反発したものの、足元では20日移動平均（$235.20）と50日移動平均（$238.68）をいずれも下回っています。
留意事項

   - 次回決算日は、取得データでは確認できていません。
   - GAAP EPSと調整後EPSは定義が異なります。
   - AI関連ARRは決算リキャップの見出しに基づくもので、集計範囲（Agentforce単体か、Data
   Cloudとの合算か）が四半期ごとに異なります。
   - テーマのパフォーマンスは均等加重バスケットに基づいています。一部のニュースは見出しのみ取得しています。
   - 本レポートは情報提供を目的としたものであり、投資推奨ではありません。

ご希望があれば、Braze・Cresta買収の財務インパクト（希薄化・負債）や、ServiceNow・Microsoftとのバリュエーション比較も深掘りします。
情報源エンティティ（1）

   - CRM:NYSE

時系列データ（1）

   - CRM:NYSE.price

財務諸表（2）

   - CRM:NYSE - 損益計算書
   - CRM:NYSE - キャッシュフロー

決算インサイト（1件）

   - Salesforce clears on earnings and lifts outlook

カタリストインサイト（8件）

   - Salesforce signs definitive agreement to acquire m3ter
   - AIforce launch puts Salesforce ecosystem reach to the test
   - Salesforce leadership reshuffle raises continuity questions
   - Salesforce shifts Agentforce to outcome-based pricing
   - Salesforce global outage puts platform resilience in focus
   - Salesforce agrees to buy Braze for $5.66B
   - Salesforce buys Rune to deepen defense AI
   - Salesforce signs Listen Labs to deepen AI customer insight

ナレッジグラフ

   - Salesforce, Inc. - セールスフォース のテーマ別エクスポージャー
      - Enterprise Software
      - Agentic AI
      - Data Centers
   - Salesforce, Inc. - セールスフォース のブランド・製品
      - Agentforce
      - Data Cloud
      - Slack
   - Salesforce, Inc. - セールスフォース の主要競合 3 社
      - Microsoft Corporation - マイクロソフト
      - Oracle Corporation - オラクル
      - HubSpot, Inc. - ファディ・インターナショナル・グループ,
   - Salesforce, Inc. - セールスフォース の地域別エクスポージャー
      - 米国
      - 英国
      - インド

ニュース（35件）

   - Why Is Salesforce Stock Falling on Thursday?
   - Top Midday Stories: Salesforce to Acquire Braze for $5.66 Billion; GM
   Q3 EPS, Revenue Top Estimates But Stock Falls
   - OpenAI Jumps 32%, Airtable Crashes 56% As Private Market Returns
   Diverge
   - Update: Strong Quarterly Results Help Push US Equity Indexes Higher
   While AI Trade Sentiment Remains Positive
   - Why Is Braze Stock Surging on Tuesday?
   - DBS Bank Adjusts Salesforce Price Target to $300 From $240
   - Salesforce-Braze Deal Draws Downgrades as Analysts Assess Acquisition
   Value
   - Salesforce to Acquire Defense Tech Firm Rune Technologies to Expand
   Military AI Logistics Capabilities
   - Sector Update: Tech
   - Salesforce Bets $5.7 Billion on AI Marketing With Braze Acquisition
   - Health Care Stocks Hit Record Highs, GM Drops Nearly 8%: Stock Market
   Today
   - Salesforce Strikes $5.66 Billion Deal to Buy Customer Engagement
   Platform Braze
   - Why Is Salesforce Stock Falling on Friday?
   - Salesforce to Acquire Braze for $5.66 Billion
   - --Salesforce to Acquire Braze for $5.66 Billion
   - Salesforce To Purchase 500,000 Methane-Reduction Carbon Credits From
   Mitti Labs By 2030
   - Salesforce Needs to Integrate Braze While Preserving Its Innovation,
   Truist Says
   - Sector Update: Tech Stocks Mixed Late Afternoon
   - Sector Update: Tech Stocks Decline Premarket Tuesday
   - Top Midday Gainers
   - Sector Update: Tech
   - Sector Update: Tech Stocks Mixed Tuesday Afternoon
   - Eric Schmidt Wrote a Check to Anthropic Before the AI Boom: Here’s How
   Big the Payoff Could Get
   - Accenture Earnings Lift Software and IT Services Stocks: Cognizant,
   IBM, Wipro Rise on Thursday
   - Oracle Expands AI Software Offerings Ahead of Investor Day
   - Tech Selloff Drags Chinese Shares Lower
   - ‘Money Will Be Made and Money Will Be Lost’: KKR Sounds Off on AI Boom
   and Private Credit
   - ZenaTech Launches AI Software Suite, Planned Integration Across Its
   DaaS Land Survey Operations
   - ServiceNow Stock Rebounds as SaaSpocalypse Fears Fade: What to Expect
   from Earnings
   - Chinese Stocks Fall as Nvidia Tightens China AI Access
   - Mastercard To Resell Rezolve AI Software Worldwide
   - $3 Trillion Wiped Out, But This Strategist Says AI's Biggest Problem
   Isn't Demand: 'Compute Will Become More Scarce'
   - Jim Cramer Says Bears Want to ‘Derail’ Anthropic IPO as AI Valuation
   Fears Mount: ‘That Will Be the Straw’
   - Why Is Salesforce Stock Surging on Thursday?
   - After Braze, Could Klaviyo Be Big Tech’s Next Billion-Dollar Bet?

## 解釈上の注意

数値、予測、画面構成は記載日の調査例です。最新の相場やすべての利用環境での提供状況を示すものではありません。

## 関連機能

- [Alfred](https://github.com/reflexivity-kb/platform/blob/main/ja/03-%E8%A3%BD%E5%93%81/Alfred.md)
- [Asset Overview](https://github.com/reflexivity-kb/platform/blob/main/ja/03-%E8%A3%BD%E5%93%81/%E9%8A%98%E6%9F%84%E6%A6%82%E8%A6%81.md)
- [Themes](https://github.com/reflexivity-kb/platform/blob/main/ja/03-%E8%A3%BD%E5%93%81/%E3%83%86%E3%83%BC%E3%83%9E.md)

リンク先の製品マニュアルにはアクセス権が必要な場合があります。

---

本コンテンツは株式会社QUICKから提供された活用例です。数値や市場の見方は提供時点のものです。

[← ユースケース一覧](../../README.md)
