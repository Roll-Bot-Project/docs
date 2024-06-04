---
description: 用户时区决定了用户与 Roll Bot 交互时使用的本地时间
---

# 用户时区

> 偏移量是时区与 UTC 标准时间的差距，格式为 +时:分:秒 或 -时:分:秒
>
> 例如 `+8` 或 `-9:30 或 −00:25:21 (如果你在1880年的爱尔兰)`

```
/roll time [偏移量]
```

偏移量不是必填的，留空将返回你当前设置的偏移量

## 优先级

[channel-timezone.md](channel-timezone.md "mention") > [user-timezone.md](user-timezone.md "mention") > [默认时区](../configuration/basic.md#defaulttimeoffset)

你可以在设置中调整 `i18n.output` 项以修改这一顺序

## 重置用户时区设置

你可以在命令中使用 `-d` 参数重置你的时区设置：

```
/roll time -d
```

## 本地化 & 别称

该指令也可使用如下方式触发

```
/r time [偏移量]

/时区 [偏移量]
```
