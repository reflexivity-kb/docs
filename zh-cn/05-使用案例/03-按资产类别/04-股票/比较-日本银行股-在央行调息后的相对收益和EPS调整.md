<!--
id: RX-USECASE-0078
type: use-case
language: zh-cn
locale: zh-CN
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

# 比较日本银行股在央行调息后的相对收益和EPS调整

[← 按资产类别浏览](../README.md) · [全部使用案例](../../README.md)

**适用用户：** 日本股票、银行业及多资产投资经理  
**资产类别：** 日本股票、金融  
**研究观察期：** 2024年3月至2026年10月14日

> 下列价格、估计和情景为指定时期的研究演示，不代表实时行情或投资建议。

**[在Reflexivity中打开研究示例（英文）→](https://app.reflexivity.com/alfred?mode=research&conversationId=cfe0f411-8375-4f25-bfee-d5436222ec8c&scrollTo=top)**

## 使用的提示词

> [!IMPORTANT]
> 自2024年以来，日本央行每次调整政策利率后20个交易日，MUFG、SMFG和瑞穗的股价相对TOPIX表现如何？同一观察期内，这三家银行未来12个月EPS的一致预期发生了什么变化？

## 利率上升不等于银行股必然上涨

银行利差可能受益于日本央行加息，但日元套息交易平仓和整体风险偏好变化也会影响价格。本案例同时比较**调息后20个交易日相对TOPIX的超额收益**与**同期未来12个月EPS一致预期修正**。

截至2026年10月14日，有五次政策调整具备完整的20个交易日窗口。2026年9月18日的事件因窗口尚未结束而未纳入。

## 相对TOPIX的收益

![MUFG SMFG瑞穗在BOJ调息后的20个交易日超额收益](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0078-bank-excess-returns.png)

*图1：超额收益单位为百分点，并非三家银行的绝对收益率。*

| 事件 | MUFG | SMFG | 瑞穗 |
| --- | ---: | ---: | ---: |
| 2024年7月 | −9.95点 | −8.69点 | −9.46点 |
| 2025年1月 | +3.76点 | +4.13点 | +8.21点 |
| 2025年12月 | +8.15点 | +0.85点 | +10.59点 |
| 2026年6月 | +10.33点 | +7.51点 | +8.12点 |

2024年7月的日元套息交易平仓期间，三家银行均明显跑输TOPIX。后来几次事件则显示出不同的表现。

## 盈利预期修正

![日本三大银行BOJ事件后12个月EPS预期变动](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0078-bank-eps-revisions.png)

*图2：同一20交易日窗口内的12个月远期EPS一致预期修正率。*

2026年6月窗口中的EPS修正幅度为MUFG **+7.47%**、SMFG **+7.95%**、瑞穗 **+3.65%**。

MUFG和SMFG的部分预期使用**美元计价ADR覆盖数据**，而瑞穗采用日元序列。变化率并不能自动消除币种和一致预期口径差异。结果也不是剔除了其他宏观冲击的单一政策因果估计。

## 申请其他研究示例

如希望了解同一问题在 **LSEG Workspace等其他研究环境中的再现结果**，请发送邮件至 **jim@reflexivity.com**，并注明文档编号 **RX-USECASE-0078**。能否另行提供资料，需视访问权限及数据再分发许可而定。

---

[← 按资产类别浏览](../README.md) · [全部使用案例](../../README.md)
