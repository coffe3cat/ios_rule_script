# Microsoft

## 前言

本项目的Microsoft分流规则由爬虫程序自动维护。

定时爬取互联网上开源的Microsoft分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。

含有OneDriver分流规则

最后检查时间：2020-10-17 08:01:42。

## 规则统计

总计规则：99 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN | 2 |
| DOMAIN-KEYWORD | 4 |
| DOMAIN-SUFFIX | 91 |
| USER-AGENT | 2 |
## 重复统计

Microsoft分流规则，与本项目其他分流规则重复情况统计。

点击重复数量可以查看重复规则明细。

| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [Adobe](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Adobe)    | 34   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Microsoft/Adobe.list)   |   2.94%  |
|  [Advertising](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Advertising)    | 157435   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Microsoft/Advertising.list)   |   0.00%  |
|  [AdvertisingLite](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AdvertisingLite)    | 131289   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Microsoft/AdvertisingLite.list)   |   0.00%  |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Apple)    | 51   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Microsoft/Apple.list)   |   3.92%  |
|  [AppleBlock](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AppleBlock)    | 6   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Microsoft/AppleBlock.list)   |   16.67%  |
|  [AppleNews](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AppleNews)    | 9   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Microsoft/AppleNews.list)   |   11.11%  |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/BlackList)    | 778   | [13](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Microsoft/BlackList.list)   |   1.67%  |
|  [China](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/China)    | 593   | [12](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Microsoft/China.list)   |   2.02%  |
|  [Download](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Download)    | 11   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Microsoft/Download.list)   |   9.09%  |
|  [Global](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Global)    | 842   | [10](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Microsoft/Global.list)   |   1.19%  |
|  [Proxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Proxy)    | 5984   | [27](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Repeat/Microsoft/Proxy.list)   |   0.45%  |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Surge 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Microsoft/Microsoft.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Surge/Microsoft/Microsoft.list

## 数据来源

本项目的Microsoft分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，建议不要与本项目的Microsoft分流规则混合使用，以免造成规则重复。

- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Microsoft/OneDrive.list
- https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Microsoft.list
- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/OneDrive.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/OneDrive.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/Microsoft.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/OneDrive.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Microsoft.list


感谢以上分流规则作者的辛勤付出（排名不分先后）。

如果你有更好的分流规则，欢迎提交给我，我会将它加到数据源中继续完善。

## 最后

### 正则过滤

爬虫程序在清洗原始规则数据时，可根据正则定向过滤规则，以达到保留特定规则的目的。经过正则过滤的规则，无法100%涵盖原始规则数据，请知悉。

### 黑名单

爬虫程序内置部分规则黑名单，在对原始数据进行清洗时，自动将可能引起异常的黑名单规则去除。经过黑名单去除的规则，无法100%涵盖原始规则数据，请知悉。

### 完善规则

如果你：

1. 有更优的原始规则数据
2. 有更多的黑名单规则数据
3. 有更好的优化建议
4. 在使用分流规则时出现异常
5. 有其他问题

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的Microsoft分流规则。

感谢

[@zjcfynn](https://github.com/zjcfynn) [@Tartarus2014](https://github.com/Tartarus2014)

提供规则数据源及改进建议
