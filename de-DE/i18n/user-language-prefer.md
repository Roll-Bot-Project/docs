---
description: 用户语言偏好决定了用户与 Roll Bot 交互时使用的语言
---

# 用户语言偏好

> Roll Bot 目前支持的语言包括： `zh-CN` `en-US` de-DE

```
/roll locale [语言偏好]
```

语言偏好不是必填的，留空将返回你当前设置的语言偏好

## 优先级

[channel-language-prefer.md](channel-language-prefer.md "mention") > [user-language-prefer.md](user-language-prefer.md "mention") > 默认语言偏好

你可以在设置中调整 `i18n.output` 项以修改这一顺序

## 本地化 & 别称

该指令也可使用如下方式触发

```
/r locale [语言偏好]

/语言 [语言偏好]
```
