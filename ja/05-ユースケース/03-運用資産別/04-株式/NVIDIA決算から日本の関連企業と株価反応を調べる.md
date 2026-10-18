<!--
id: RX-USECASE-0079
type: use-case
language: ja
locale: ja
author: Reflexivity Research
kb_imported: 2026-10-17
status: draft
translation_status: localized_from_en_canonical
original_language: en
source_type: reflexivity-platform-demo
source_manifest: RX-USECASE-0079
prompt_status: present
prompt_basis: localized_from_en_verbatim
-->

# NVIDIA決算から日本の関連企業と株価反応を調べる

<!-- locale-switcher:start -->
**Languages:** [English](../../../../en/05-use-cases/03-asset-class/04-equities/japanese-nvidia-supply-chain-earnings-reactions.md) · **日本語** · [한국어](../../../../ko/05-유스케이스/03-운용자산별/04-주식/NVIDIA-실적발표와-일본-공급망-기업-주가반응-분석하기.md) · [简体中文](../../../../zh-cn/05-使用案例/03-按资产类别/04-股票/筛选-NVIDIA-相关日本供应链-及其财报后股价反应.md) · [繁體中文（台灣）](../../../../zh-tw/05-使用案例/03-依資產類別/04-股票/從-NVIDIA-財報篩選日本供應鏈企業及股價反應.md) · [繁體中文（香港）](../../../../zh-hk/05-使用案例/03-按資產類別/04-股票/從-NVIDIA-業績篩選日本供應鏈企業及股價反應.md)
<!-- locale-switcher:end -->

[← 運用資産別](../README.md) · [ユースケース一覧](../../README.md)

**対象ユーザー：** 日本株運用者、半導体アナリスト、テーマ運用者  
**主な資産：** 日本株、半導体サプライチェーン  
**調査の対象期間：** 2024年11月～2026年8月のNVIDIA決算8回

> 数値や市場状況は該当期間の研究例であり、最新の市況や投資推奨ではありません。

**[Reflexivityで調査例を開く →](https://app.reflexivity.com/alfred?mode=research&conversationId=06d26e49-ffa1-410c-9725-de2c78214b28&scrollTo=top)**

## 使用したプロンプト

> [!IMPORTANT]
> 東京エレクトロンとアドバンテストを除き、NVIDIAとのサプライチェーン上の結びつきが強い日本上場企業を特定してください。NVIDIAの直近8回の決算発表後の東証翌営業日の平均株価変化率、NVIDIAと同じ方向に動いた割合を示し、企業を順位づけしてください。

## 米国の半導体決算を日本株の調査候補へ展開する

NVIDIAの決算は、基板、材料、製造装置、電子部品に関わる日本企業にも注目が波及します。東京エレクトロンとアドバンテストを除外し、産業上のつながりから日本上場の候補12社を抽出しました。

## 候補企業の価格反応と方向一致

![NVIDIA決算前後の日本の関連企業の値動きと方向一致率](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0079-nvidia-japanese-suppliers.png)

*図1：平均株価変動率と方向一致率を同一の目盛りに描いています。前者は数%程度、後者は数十%であるため、棒の長さを指標間で直接比較しないでください。*

| 企業 | 平均測定リターン | 方向一致 |
| --- | ---: | ---: |
| イビデン | +4.24% | 4/8 |
| ディスコ | +2.28% | 3/8 |
| KOKUSAI ELECTRIC | +2.32% | 2/8 |
| 村田製作所 | +1.56% | 5/8 |
| 浜松ホトニクス | +0.55% | 6/8 |

リターンの大きさと同方向に動いた頻度、サプライチェーンでの近さは異なる評価軸です。

## 米日市場の時差に注意する

NVIDIAは通常、**米国市場引け後**に決算を発表します。米国の決算発表日の翌東証営業日が米国の最初の決算反映セッションより先に終わる場合、測定値が正しい「決算後」の反応になりません。必要に応じて日本の2営業日目に置き換えて再検証します。

また、産業・ナレッジグラフ上の関係は直接の納入契約や売上依存度を一次開示で確認したことを意味しません。この順位は投資推奨ではなく、企業開示と時系列を確認する調査候補です。

## 関連資料のお問い合わせ

同じ質問を **LSEG Workspaceなど別の調査環境で再現した結果**については、アクセス権と再配布条件を確認のうえ、個別提供の可否をご案内します。**jim@reflexivity.com** 宛に文書番号 **RX-USECASE-0079** を添えてお問い合わせください。

---

[← 運用資産別](../README.md) · [ユースケース一覧](../../README.md)
