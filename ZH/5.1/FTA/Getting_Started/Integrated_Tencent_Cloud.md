# 集成腾讯云云监控

故障自愈的腾讯云版本默认集成腾讯云监控，定时从腾讯云云监控拉取告警。

```plain
提示：该功能仅在腾讯云版的蓝鲸上支持
```

## 1. 设置告警策略并关联告警对象

在腾讯云设置对应的`告警策略`并`关联告警对象`。
![-w666](media/14955047240702.jpg)

在产生腾讯云告警时，你能在告警列表中找到对应的告警，这样故障自愈才能处理。
![-w883](media/14955048096192.jpg)


##  2. 把腾讯云告警接入到自愈
在接入自愈选择告警类型时可以找到`腾讯云监控`对应的`告警类型`
![-w500](media/14949454396797.jpg)


## 3.腾讯云云监控自愈执行历史

![-w424](media/14955061074598.jpg)