---
description: 频道时区决定了频道内所有用户与 Roll Bot 交互时使用的时区
---

# 频道时区

> 偏移量是时区与 UTC 标准时间的差距，格式为 +时:分:秒 或 -时:分:秒
>
> 例如 `+5` 或 `-9:30`

```
/roll time -c [偏移量]
```

偏移量不是必填的，留空将返回频道当前设置的偏移量

## 优先级

[channel-timezone.md](channel-timezone.md "mention") > [user-timezone.md](user-timezone.md "mention") > [默认时区](../configuration/basic.md#defaulttimeoffset)

你可以在设置中调整 `i18n.output` 项以修改这一顺序

## 权限

要修改频道时区，你必须为 [bot-admin.md](../permission/bot-admin.md "mention") 或 [channel-admin.md](../permission/channel-admin.md "mention")

## 本地化 & 别称

该指令也可使用如下方式触发

```
/r time -c [偏移量]

/时区 -c [偏移量]
```
