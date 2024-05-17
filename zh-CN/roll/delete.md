---
description: 手动或交互式地删除一个抽奖
---

# 删除抽奖

```
/roll delete [抽奖编号]
```

> 抽奖编号不是必填的，留空将交互式地删除抽奖

## 权限

要删除一个抽奖，你必须为 [roll-creator.md](../permission/roll-creator.md "mention") 或 [bot-admin.md](../permission/bot-admin.md "mention")

如果在设置中启用了 `allowGuildAdminDelete` 项，则抽奖范围内的 [channel-admin.md](../permission/channel-admin.md "mention") 也可以进行删除操作

## 本地化 & 别称

该指令也可使用如下方式触发

```
/r delete [抽奖编号]
/r rm [抽奖编号]

/删除抽奖 [抽奖编号]
```
