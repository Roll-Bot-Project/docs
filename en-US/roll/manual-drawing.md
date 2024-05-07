---
description: 手动进行开奖
---

# 手动开奖

```
/roll end [抽奖编号]
或
/roll draw [抽奖编号]
```

> 抽奖编号不是必填的，留空将交互式地手动开奖

## 权限

要手动开奖，你必须为 [roll-creator.md](../permission/roll-creator.md "mention") 或 [bot-admin.md](../permission/bot-admin.md "mention")

如果在设置中启用了 `allowGuildAdminEnd` 项，则抽奖范围内的 [channel-admin.md](../permission/channel-admin.md "mention") 也可以进行手动开奖操作

## 本地化 & 别称

该指令也可使用如下方式触发

```
/r end [抽奖编号]

/r draw [抽奖编号]

/开奖 [抽奖编号]
```
