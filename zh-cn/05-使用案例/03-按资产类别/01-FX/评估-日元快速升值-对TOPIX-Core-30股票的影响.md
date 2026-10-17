<!--
id: RX-USECASE-0080
type: use-case
language: zh-cn
locale: zh-CN
author: Reflexivity Research
kb_imported: 2026-10-17
status: draft
translation_status: localized_from_en_canonical
original_language: en
source_type: reflexivity-platform-demo
source_manifest: RX-USECASE-0080
prompt_status: present
prompt_basis: localized_from_en_verbatim
-->

# 评估日元快速升值对TOPIX Core 30股票的影响

<!-- locale-switcher:start -->
**Languages:** [English](../../../../en/05-use-cases/03-asset-class/01-FX/usdjpy-appreciation-topix-core30-sensitivity.md) · [日本語](../../../../ja/05-ユースケース/03-運用資産別/01-FX/急激な円高でTOPIX-Core-30銘柄の影響を比較する.md) · [한국어](../../../../ko/05-유스케이스/03-운용자산별/01-FX/엔화-급등-시-TOPIX-Core-30-종목별-민감도-비교하기.md) · **简体中文** · [繁體中文（台灣）](../../../../zh-tw/05-使用案例/03-依資產類別/01-FX/評估-日圓快速升值-對TOPIX-Core-30個股的影響.md) · [繁體中文（香港）](../../../../zh-hk/05-使用案例/03-按資產類別/01-FX/評估-日圓急升-對TOPIX-Core-30股票的影響.md)
<!-- locale-switcher:end -->

[← 按资产类别浏览](../README.md) · [全部使用案例](../../README.md)

**适用用户：** 日本股票、外汇投资经理及风险管理人员  
**资产类别：** 外汇、日本股票  
**研究观察期：** 1990至2024年历史事件及2024年夏季套息平仓

> 下列价格、估计和情景为指定时期的研究演示，不代表实时行情或投资建议。

**[在Reflexivity中打开研究示例（英文）→](https://app.reflexivity.com/alfred?mode=research&conversationId=b6641a7b-b55b-4696-bf5f-4ad9b762c713&scrollTo=top)**

## 使用的提示词

> [!IMPORTANT]
> 如果USD/JPY像2024年7至8月日元套息交易平仓时一样，在一个月内下跌8%，TOPIX Core 30哪些股票受影响最大、哪些最小？请基于各股票对日元的历史敏感度，并比较出口企业与内需企业。

## 将日元升值转化为个股敏感度研究

USD/JPY一个月下跌8%可能影响出口商的日元计价收入，但不同企业还受到国内需求、全球风险偏好等因素影响。2024年7月3日至8月5日，USD/JPY约从 **161.70降至144.20**。

研究选择1990至2024年间**21个交易日内USD/JPY跌幅至少8%的13次历史事件**，对TOPIX Core 30成分股计算事件后一个月价格收益的中位数。

## 历史条件收益

![日元大幅升值后TOPIX Core 30历史一个月收益中位数](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0080-yen-shock-topix30.png)

*图1：历史事件后的条件收益中位数，并非下一次汇率变化的预测，也不是直接估计的外汇回归Beta。*

| 公司 | 一个月收益中位数 | 有效事件数 |
| --- | ---: | ---: |
| 三菱商事 | −4.90% | 13 |
| 丰田汽车 | −4.32% | 13 |
| 索尼集团 | −3.57% | 13 |
| 本田汽车 | −2.84% | 13 |
| 瑞穗金融 | +6.68% | 6 |
| Hoya | +7.69% | 13 |
| MUFG | +9.43% | 6 |

在所选分组中，出口企业平均约 **−2.74%**，内需企业约 **+4.31%**。但公司历史样本量不一致，有的仅有两次有效事件。汇率、利率及市场避险冲击混杂，因此不能将回报完全归因于日元。下一步应增加企业外币收入和套保披露、滚动外汇Beta等验证。

## 申请其他研究示例

如希望了解同一问题在 **LSEG Workspace等其他研究环境中的再现结果**，请发送邮件至 **jim@reflexivity.com**，并注明文档编号 **RX-USECASE-0080**。能否另行提供资料，需视访问权限及数据再分发许可而定。

---

[← 按资产类别浏览](../README.md) · [全部使用案例](../../README.md)
