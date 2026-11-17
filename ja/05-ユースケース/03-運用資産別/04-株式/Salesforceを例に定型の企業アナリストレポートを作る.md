<!--
id: RX-USECASE-0100
type: use-case
language: ja
locale: ja
author: Reflexivity GTM Team
source_type: partner-provided-use-case
provider: QUICK
source_manifest: RX-USECASE-0100
source_created: 2026-11-10
published: 2026-11-17
revised: 2026-11-17
editorial_reviewed: 2026-11-17
resource: QUICK-provided Reflexivity research example
status: published
translation_status: current
prompt_status: present
prompt_basis: source-verbatim
-->

# Salesforceを例に定型の企業アナリストレポートを作る

<!-- locale-switcher:start -->
**言語:** [English](../../../../en/05-use-cases/03-asset-class/04-equities/build-a-reusable-salesforce-analyst-style-company-report.md) · **日本語** · [한국어](../../../../ko/05-유스케이스/03-운용자산별/04-주식/Salesforce를-예로-재사용-가능한-기업-분석-보고서-작성하기.md) · [简体中文](../../../../zh-cn/05-使用案例/03-按资产类别/04-股票/以-Salesforce-为例制作可复用的公司研究报告.md) · [繁體中文（臺灣）](../../../../zh-tw/05-使用案例/03-依資產類別/04-股票/以-Salesforce-為例製作可重複使用的公司研究報告.md) · [繁體中文（香港）](../../../../zh-hk/05-使用案例/03-按資產類別/04-股票/以-Salesforce-為例製作可重複使用的企業研究報告.md)
<!-- locale-switcher:end -->

[← Use Cases](../../README.md)

**QUICK | 2026-11-10**

## 使用したプロンプト

> [!IMPORTANT]
> アナリストレポートのような体裁で、企業のレポートを作成してください。企業名はSalesforceです。最初に企業概要、その次に最近の話題を記載してください。その下には、１か月以内に決算発表があれば、決算内容のサマリーを載せてください。その下には、過去１年分の業績の表と、直近の業績に関するコメントを記載。その下には、この企業が属するテーマとそのテーマのパフォーマンスや市場の受け止め方を記載してください。その下には過去１年間の日足のチャートを載せてください。

## 調査の流れ

Alfredで企業名をSalesforceに指定し、企業概要、最近の話題、直近1か月の決算、過去4四半期の業績表、所属テーマと1年間の日足チャートの順で出力します。企業名を替えれば構成を再利用できます。

## 提供時点の結果

11月10日の原資料はSalesforceを例とし、Q2 FY2027売上113.5億ドル（前年比+10.8%）、cRPO、GAAPのEPS、FCF、SaaSやAI関連テーマと日足チャートを掲載しました。

## 読み方と留意点

GAAPと調整後EPS、決算年度と暦年を混同しません。このプロンプトは構成の雛形であり、すべての銘柄で同じデータが取得できることを保証しません。

## 関連機能

- [Alfred](https://github.com/reflexivity-kb/platform/blob/main/ja/03-%E8%A3%BD%E5%93%81/Alfred.md)

製品マニュアルの閲覧にはアクセス権が必要な場合があります。

## 提供元

本コンテンツは株式会社QUICKより提供されたReflexivity活用例です。数値は提供日時点の分析で、現在の予測ではありません。

[← Use Cases](../../README.md)
