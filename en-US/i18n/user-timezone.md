---
description: The user time zone determines the local time to use when users interact with Roll Bot
---

# User timezone

> Offset is the difference between time zone and UTC standard time, formatted as +:mm:second or -hour:mm:second
>
> e.g. `+8` or `-9:30 or -00:25:21 (if you were in Ireland in 1880)`

```
/roll time [偏移量]
```

Offset is not required. Leave empty to return the offset you currently set

Note that since the offset at the beginning of the `-` will be identified as an argument, use the `" "` package for your offset

e.g.：

```
/roll time "-7"
```

## Priority

[channel-timezone.md](channel-timezone.md "mention") > [user-timezone.md](user-timezone.md "mention") > [默认时区](../configuration/basic.md#defaulttimeoffset)

You can adjust the `i18n.output` entry in the settings to change this order

## Localization & Alias

This command can also be triggered by

```
/r time [偏移量]

/timezone [偏移量]
```
