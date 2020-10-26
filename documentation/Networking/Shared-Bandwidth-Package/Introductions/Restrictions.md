# 使用限制

### 共享带宽包限制

- 创建按用量计费模式的共享带宽包后，最早可以于下月账单出完后删除，即至少使用完1个完整的自然月。

- 包年包月模式的共享带宽包仅支持到期后删除


- 只允许删除带宽包内无EIP的共享带宽包。

- 共享带宽包欠费时不支持添加EIP。



### EIP 限制

- 共享带宽包仅支持添加按配置和按用量计费的弹性公网IP，包年包月的弹性公网IP不支持加入共享带宽包，已欠费的公网IP不支持加入共享带宽包

- 仅支持加入与共享带宽包同地域同线路的标准公网IP

- 一个公网IP只能加入一个共享带宽包

- 公网IP加入共享带宽包后，原有的计费模式和带宽上限失效；公网IP从共享带宽包中移除后，恢复原有的计费模式和带宽上限




### 资源配额限制

| 资源                                                | 默认上限（个） | 提升配额                                 |
| --------------------------------------------------- | -------------- | ---------------------------------------- |
| 同账号同地域可持有的包年包月/按配置的共享带宽包数量 | 无限制           | 不支持提升数量                           |
| 同账号同地域最多可持有按用量的共享带宽包数量        | 5              | 如需提升共享带宽包数量，请[提交工单](https://ticket.jdcloud.com/applyorder/submit)申请。 |
| 每个共享带宽包可加入的EIP数量                       | 20             | 如需添加更多弹性公网IP，请[提交工单](https://ticket.jdcloud.com/applyorder/submit)申请。 |

## 相关参考
- [管理公网IP](../Getting-Started/Manage-IP.md)
- [计费概述](../Pricing/Billing-Overview.md)
- [计费规则](../Pricing/Billed-Rules.md)
- [价格总览](../Pricing/Price-Overview.md)
- [增强95消峰计费](../Pricing/Charge-By-Usage/Top5-Eliminate.md)
- [查看共享带宽包监控信息](../Operation-Guide/View-Monitoring.md)
- [创建共享带宽包](../Operation-Guide/Create-Bwp.md)
- [修改共享带宽包](../Operation-Guide/Modify-Bwp.md)
- [删除共享带宽包](../Operation-Guide/Delete-Bwp.md)