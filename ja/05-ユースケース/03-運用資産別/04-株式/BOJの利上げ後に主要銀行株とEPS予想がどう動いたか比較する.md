<!--
id: RX-USECASE-0078
type: use-case
language: ja
locale: ja
author: Reflexivity Research
kb_imported: 2026-10-17
status: draft
translation_status: localized_from_en_canonical
original_language: en
source_type: reflexivity-platform-demo
source_manifest: RX-USECASE-0078
prompt_status: present
prompt_basis: localized_from_en_verbatim
-->

# BOJの利上げ後に主要銀行株とEPS予想がどう動いたか比較する

<!-- locale-switcher:start -->
**Languages:** [English](../../../../en/05-use-cases/03-asset-class/04-equities/japanese-bank-returns-vs-topix-after-boj-hikes.md) · **日本語** · [한국어](../../../../ko/05-유스케이스/03-운용자산별/04-주식/BOJ-금리변경-후-일본-은행주와-EPS-변화-분석하기.md) · [简体中文](../../../../zh-cn/05-使用案例/03-按资产类别/04-股票/比较-日本银行股-在央行调息后的相对收益和EPS调整.md) · [繁體中文（台灣）](../../../../zh-tw/05-使用案例/03-依資產類別/04-股票/比較-日本銀行股-在BOJ利率調整後的超額報酬與EPS修正.md) · [繁體中文（香港）](../../../../zh-hk/05-使用案例/03-按資產類別/04-股票/比較-日本銀行股-在BOJ調息後的超額回報與EPS預期調整.md)
<!-- locale-switcher:end -->

[← 運用資産別](../README.md) · [ユースケース一覧](../../README.md)

**対象ユーザー：** 日本株運用者、銀行アナリスト、マルチアセット運用者  
**主な資産：** 日本株、銀行  
**調査の対象期間：** 2024年3月～2026年10月14日

> 数値や市場状況は該当期間の研究例であり、最新の市況や投資推奨ではありません。

**[Reflexivityで調査例を開く →](https://app.reflexivity.com/alfred?mode=research&conversationId=bc6b5c73-5d73-4c6e-8bec-af825d1e1605&scrollTo=top)**

## 使用したプロンプト

> [!IMPORTANT]
> 2024年以降のBOJ政策金利変更ごとに、その後20営業日間のMUFG、SMFG、みずほの株価がTOPIXに対してどう動いたか比較してください。同期間の各行の今後12カ月のEPSコンセンサス予想の変化も示してください。

## 利上げ局面でも銀行株の反応は一様ではない

金利上昇は利ざや改善の期待を高める一方、円キャリー取引の巻き戻しや相場全体のリスク回避によって銀行株が下落することもあります。ここでは **TOPIX対比20営業日の超過リターン**と**同じ期間の12カ月先EPS予想改定率**を比較します。

2026年10月14日時点で20営業日が経過した政策変更は5件でした。2026年9月18日の変更は観測期間未了のため除外しています。

## 銀行株の相対リターン

![BOJ政策変更後のMUFG SMFG みずほのTOPIX対比超過収益率](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0078-bank-excess-returns.png)

*図1：政策変更後20営業日間のTOPIX対比の超過収益（ポイント）です。*

| 政策イベント | MUFG | SMFG | みずほ |
| --- | ---: | ---: | ---: |
| 2024年7月 | −9.95pt | −8.69pt | −9.46pt |
| 2025年1月 | +3.76pt | +4.13pt | +8.21pt |
| 2025年12月 | +8.15pt | +0.85pt | +10.59pt |
| 2026年6月 | +10.33pt | +7.51pt | +8.12pt |

2024年7月の円キャリー巻き戻しを含む期間では3行がそろってTOPIXを下回り、その後のイベントでは反応が大きく異なりました。

## EPS予想の改定

![3銀行のイベント後12カ月先EPSコンセンサス改定率](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0078-bank-eps-revisions.png)

*図2：同じ20営業日間の先行12カ月EPS予想変化率です。*

2026年6月の改定率はMUFG **+7.47%**、SMFG **+7.95%**、みずほ **+3.65%** でした。EPS予想と相対株価リターンは必ずしも一致しません。

**比較上の留意点：** MUFGとSMFGの予想系列には米ドル建てADRベースのデータが含まれ、みずほは円建て系列です。変化率に直しても予想カバレッジや通貨換算差の影響は完全には消えません。政策変更だけが株価反応の原因だと結論づけないでください。

## 関連資料のお問い合わせ

同じ質問を **LSEG Workspaceなど別の調査環境で再現した結果**については、アクセス権と再配布条件を確認のうえ、個別提供の可否をご案内します。**jim@reflexivity.com** 宛に文書番号 **RX-USECASE-0078** を添えてお問い合わせください。

---

[← 運用資産別](../README.md) · [ユースケース一覧](../../README.md)
