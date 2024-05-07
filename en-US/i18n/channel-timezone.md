---
description: The channel time zone determines the timezone used by all users in the channel when interacting with Roll Bot
---

# Channel timezone

> Offset is the difference between time zone and UTC standard time, formatted as +:mm:second or -hour:mm:second
>
> e.g. `+5` or `-9:30`

```
/roll time - c [偏移量]
```

Offset is not required. Leave empty to return the channel offset

Note that since the offset at the beginning of the `-` will be identified as an argument, use the `" "` package for your offset

e.g.：

```
/roll time -c "-7"
```

## Priority

[channel-timezone.md](channel-timezone.md "mention") > [user-timezone.md](user-timezone.md "mention") > [默认时区](../configuration/basic.md#defaulttimeoffset)

You can adjust the `i18n.output` entry in the settings to change this order

## Permissions

To modify the channel time zone, you must be [bot-admin.md](../permission/bot-admin.md "mention") or [channel-admin.md](../permission/channel-admin.md "mention")

## Localization & Alias

This command can also be triggered by

```
/r time -c [偏移量]

/timezone -c [偏移量]
```
