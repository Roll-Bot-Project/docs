---
description: 频道语言偏好决定了频道内所有用户与 Roll Bot 交互时使用的语言
---

# 频道语言偏好

> Roll Bot 目前支持的语言包括： `zh-CN` `en-US` de-DE

```
/roll locale -c [语言偏好]
```

语言偏好不是必填的，留空将返回群组当前设置的语言偏好

## 优先级

[channel-language-prefer.md](channel-language-prefer.md "mention") > [user-language-prefer.md](user-language-prefer.md "mention") > 默认语言偏好

你可以在设置中调整 `i18n.output` 项以修改这一顺序

## 重置频道语言偏好设置

你可以在命令中使用 `-d` 参数重置当前频道的语言偏好设置：

```
/roll locale -c -d
```

## 权限

要修改频道语言偏好，你必须为 [bot-admin.md](../permission/bot-admin.md "mention") 或 [channel-admin.md](../permission/channel-admin.md "mention")

## 本地化 & 别称

该指令也可使用如下方式触发

```
/r locale -c [语言偏好]

/语言 -c [语言偏好]
```
