<!--
id: RX-USECASE-0096
type: use-case
language: ja
locale: ja
author: Reflexivity GTM Team
provider: 株式会社QUICK
source_created: 2026-10-29
published: 2026-11-17
revised: 2026-11-17
editorial_reviewed: 2026-11-17
resource: QUICK Reflexivity usage example: Compare major US technology earnings, EPS surprises and stock reactions
status: published
translation_status: current
publication_mode: faithful-source-preserving
prompt_status: present
prompt_basis: source-verbatim
-->

# 主要米国IT企業の決算と株価反応を横断比較する

<!-- locale-switcher:start -->
**Languages:** [English](../../../../en/05-use-cases/03-asset-class/04-equities/compare-major-us-technology-earnings-eps-surprises-and-stock-reactions.md) · **日本語** · [한국어](../../../../ko/05-유스케이스/03-운용자산별/04-주식/미국-주요-IT-기업의-실적·EPS-서프라이즈-비교.md) · [简体中文](../../../../zh-cn/05-使用案例/03-按资产类别/04-股票/横向比较美国大型科技公司的财报与股价反应.md) · [繁體中文（臺灣）](../../../../zh-tw/05-使用案例/03-依資產類別/04-股票/橫向比較美國大型科技公司的業績與股價反應.md) · [繁體中文（香港）](../../../../zh-hk/05-使用案例/03-按資產類別/04-股票/橫向比較美國大型科技公司的業績與股價反應.md)
<!-- locale-switcher:end -->

[← ユースケース一覧](../../README.md)

**活用例の日付:** 2026-10-29  
**中心となる機能:** Alfred

売上・利益・予想EPSとの差・発表後の株価反応を同じ形式で比較し、投資支出への市場評価も確認します。

> [!NOTE]
> 数値、予測、画面構成は記載日の調査例です。最新の相場やすべての利用環境での提供状況を示すものではありません。

## 使用したプロンプト

> [!IMPORTANT]
> 先週と今週に発表された主要な米国IT企業の決算発表の結果をまとめてください。売上高、利益に加え、予想EPSと実際の差を表示してください。 またそれぞれについてその後の市場の反応と、各社の今後の戦略と業績見込みについても記載してください。

## 調査の目的と進め方

1. 売上・利益・予想EPSとの差・発表後の株価反応を同じ形式で比較し、投資支出への市場評価も確認します。
2. 要約だけで判断せず、関連する企業、テーマ、イベントや市場の元データを確認します。
3. 分析期間と指標の定義、別の説明要因を確認してから現在の投資判断につなげます。

## この例で確認できること

売上・利益・予想EPSとの差・発表後の株価反応を同じ形式で比較し、投資支出への市場評価も確認します。

10月19〜28日発表のIT企業12社を比較し、11社が予想EPSを上回っても株価は一様に上昇しないことを示しました。

## 画面と分析図表

![Reflexivityの画面・分析図表 1](../../../../assets/usecases/quick/RX-USECASE-0096/01-source-screen.png)

## 提供時点の詳しい分析

以下は当時の分析内容と数値を保持したスナップショットです。最新の相場見通しとして読むものではありません。

要約に基づいており、決算説明会の全文は精査していません。

アマゾンとインテルの決算発表後に、この表を更新しましょうか？ 情報源エンティティ（12）

   - TXN:NASD
   - LRCX:NASD
   - KLAC:NASD
   - CDNS:NASD
   - STX:NASD
   - GOOGL:NASD
   - NFLX:NASD
   - IBM:NYSE
   - NOW:NYSE
   - MSFT:NASD
   - META:NASD
   - TSLA:NASD

時系列データ（12）

   - IBM:NYSE.price
   - LRCX:NASD.price
   - CDNS:NASD.price
   - STX:NASD.price
   - MSFT:NASD.price
   - GOOGL:NASD.price
   - NFLX:NASD.price
   - NOW:NYSE.price
   - TXN:NASD.price
   - KLAC:NASD.price
   - META:NASD.price
   - TSLA:NASD.price

財務諸表（12）

   - TSLA:NASD - 損益計算書
   - IBM:NYSE - 損益計算書
   - NOW:NYSE - 損益計算書
   - TXN:NASD - 損益計算書
   - STX:NASD - 損益計算書
   - MSFT:NASD - 損益計算書
   - GOOGL:NASD - 損益計算書
   - META:NASD - 損益計算書
   - NFLX:NASD - 損益計算書
   - LRCX:NASD - 損益計算書
   - KLAC:NASD - 損益計算書
   - CDNS:NASD - 損益計算書

決算インサイト（12件）

   - Microsoft opens FY27 with another beat
   - Cloud surge offset by ad miss and negative FCF
   - Core ads strong, legal charge masks earnings quality
   - Tesla beats on EPS, but sales stay flat
   - Netflix beat Q3, but Q4 guide softened
   - IBM beats and lifts cash outlook
   - Beat-and-raise, but EPS miss hit shares
   - TXN beats and guides above expectations
   - Lam delivers beat with strong margin outlook
   - KLA posted a clean beat-and-raise
   - Beat-and-raise keeps Cadence on offense
   - Seagate beat again, but the bar stays high

## 解釈上の注意

数値、予測、画面構成は記載日の調査例です。最新の相場やすべての利用環境での提供状況を示すものではありません。

## 関連機能

- [Alfred](https://github.com/reflexivity-kb/platform/blob/main/ja/03-%E8%A3%BD%E5%93%81/Alfred.md)

リンク先の製品マニュアルにはアクセス権が必要な場合があります。

---

本コンテンツは株式会社QUICKから提供された活用例です。数値や市場の見方は提供時点のものです。

[← ユースケース一覧](../../README.md)
