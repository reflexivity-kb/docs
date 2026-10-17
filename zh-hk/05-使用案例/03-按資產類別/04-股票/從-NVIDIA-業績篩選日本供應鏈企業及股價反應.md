<!--
id: RX-USECASE-0079
type: use-case
language: zh-hk
locale: zh-HK
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

# 從NVIDIA業績篩選日本供應鏈企業及股價反應

[← 按資產類別瀏覽](../README.md) · [所有使用案例](../../README.md)

**適用對象：** 日本股票、半導體及主題基金經理  
**資產類別：** 日本股票、半導體供應鏈  
**研究期間：** 2024年11月至2026年8月NVIDIA業績八次

> 圖表與數值反映指定時期的研究示例，不代表即時市場報價或投資建議。

**[在Reflexivity打開研究示例（英文）→](https://app.reflexivity.com/alfred?mode=research&conversationId=3d561345-1c4e-4605-8d5c-dbb9c73342ed&scrollTo=top)**

## 使用的提問

> [!IMPORTANT]
> 撇除東京威力科創及愛德萬測試，哪些日本上市公司與NVIDIA的供應鏈關係最強？請根據NVIDIA最近八次業績公布，列出各家公司在東京交易所下一交易日的平均股價變動、與NVIDIA同方向升跌的比例，並列出排名。

## 將美國晶片業績延伸至日本上市公司

NVIDIA的業績可能影響日本的封裝基板、材料、設備及電子零件供應商。先依產業及知識圖譜關係建立12家日本上市公司的研究名單，並按題目排除東京威力科創與愛德萬測試。

## 股價反應與同向頻率

![NVIDIA業績與日本相關企業平均股價變動及方向一致率](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0079-nvidia-japanese-suppliers.png)

*圖1：平均價格回報與方向一致率共用一個刻度；前者約數個百分點，後者為數十個百分點，不能直接跨指標比較長條長度。*

| 公司 | 平均觀測變動 | 同向次數 |
| --- | ---: | ---: |
| Ibiden | +4.24% | 4/8 |
| Disco | +2.28% | 3/8 |
| Kokusai Electric | +2.32% | 2/8 |
| Murata | +1.56% | 5/8 |
| Hamamatsu Photonics | +0.55% | 6/8 |

平均變動幅度、方向一致頻率與產業關聯強度應分開判讀。

## 美國與日本交易時段錯位

NVIDIA多在**美股盤後**公布業績。有些「美國業績日之後第一個東京交易日」會早於美股第一次反映業績的交易時段，因此不一定是真正的公告後反應。應核對發布時間，必要時改用東證第二個交易日。

知識圖譜上的相關性也不等於經公司公告確認的直接供應契約或營收依賴程度。這份排序是後續基本面研究候選，並非買進建議。

## 其他研究數據

如需索取相同問題在 **LSEG Workspace等其他研究平台的重現結果**，可電郵 **jim@reflexivity.com** 並註明文件編號 **RX-USECASE-0079**。能否個別提供仍需依數據使用權限及再分發授權判定。

---

[← 按資產類別瀏覽](../README.md) · [所有使用案例](../../README.md)
