---
description: Channel language preferences determine the language in which all users in the channel interact with Roll Bot
---

# Channel language preferences

> Current language by Roll Bot includes： `en-US` `en-US` de-DE

```
/roll locale - c [语言偏好]
```

Language preferences are not required. Leave empty to return the language preferences currently set by the group

## Priority

[channel-language-prefer.md](channel-language-preference.md "mention") > [user-language-prefer.md](user-language-preference.md "mention") > Default Language Preferences

You can adjust the `i18n.output` entry in the settings to change this order

## Reset channel language preferences

You can reset the language preferences of the current channel using the `-d` parameter in the command to：

```
/roll locale -c -d
```

## Permissions

To modify channel language preferences, you must be [bot-admin.md](../permission/bot-admin.md "mention") or [channel-admin.md](../permission/channel-admin.md "mention")

## Localization & Alias

This command can also be triggered by

```
/r locale -c [语言偏好]

/Language-c [语言偏好]
```
