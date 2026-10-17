<!--
id: RX-USECASE-0079
type: use-case
language: zh-cn
locale: zh-CN
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

# 筛选NVIDIA相关日本供应链及其财报后股价反应

[← 按资产类别浏览](../README.md) · [全部使用案例](../../README.md)

**适用用户：** 日本股票、半导体及主题投资经理  
**资产类别：** 日本股票、半导体供应链  
**研究观察期：** 2024年11月至2026年8月的8次NVIDIA财报

> 下列价格、估计和情景为指定时期的研究演示，不代表实时行情或投资建议。

**[在Reflexivity中打开研究示例（英文）→](https://app.reflexivity.com/alfred?mode=research&conversationId=3d561345-1c4e-4605-8d5c-dbb9c73342ed&scrollTo=top)**

## 使用的提示词

> [!IMPORTANT]
> 除东京电子和爱德万测试之外，哪些日本上市公司与NVIDIA的供应链关系最强？请依据NVIDIA最近八次财报，统计这些公司在东京证券交易所随后一个交易日的平均股价变动、与NVIDIA同向涨跌的频率，并给出排名。

## 从美国芯片事件寻找日本股票研究线索

NVIDIA财报可能影响日本的封装基板、材料、设备及电子元件企业。先按行业和知识图谱关系筛选出12家日本上市公司，并按题目要求排除东京电子与爱德万测试。

## 股价变动与同向频率

![日本供应链候选公司围绕NVIDIA财报的股价表现和同向频率](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0079-nvidia-japanese-suppliers.png)

*图1：平均股价变动率与同向频率共用一个坐标轴，前者约数个百分点、后者约数十个百分点；不可跨指标直接比较柱形长度。*

| 公司 | 平均测量变动 | 与NVDA同向 |
| --- | ---: | ---: |
| Ibiden | +4.24% | 4/8 |
| Disco | +2.28% | 3/8 |
| Kokusai Electric | +2.32% | 2/8 |
| Murata | +1.56% | 5/8 |
| Hamamatsu Photonics | +0.55% | 6/8 |

平均收益幅度、同向次数与产业关系强度是三种不同指标。Ibiden的平均变动幅度较大，而Hamamatsu Photonics同向次数最多。

## 必须校正的时区问题

NVIDIA通常在**美股收盘后**发布财报。有时所谓“美国财报日之后的首个东京交易日”发生在美股尚未对新财报作出反应之前，因此不能直接视为真实财报后的市场反应。应按准确发布时间和东京交易日重新对齐，必要时检查第二个东京交易日。

知识图谱关联也不等于直接供应合同或可核实的NVIDIA收入占比。此列表仅作为进一步核对公司公告的研究候选，并非投资推荐。

## 申请其他研究示例

如希望了解同一问题在 **LSEG Workspace等其他研究环境中的再现结果**，请发送邮件至 **jim@reflexivity.com**，并注明文档编号 **RX-USECASE-0079**。能否另行提供资料，需视访问权限及数据再分发许可而定。

---

[← 按资产类别浏览](../README.md) · [全部使用案例](../../README.md)
