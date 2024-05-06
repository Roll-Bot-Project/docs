---
description: 频道语言偏好决定了频道内所有用户与 Roll Bot 交互时使用的语言
---

# 频道语言偏好

> Roll Bot 目前支持的语言包括： `zh` `en`

```
/roll locale -c [语言偏好]
```

语言偏好不是必填的，留空将返回群组当前设置的语言偏好

## 优先级

[pin-dao-yu-yan-pian-hao.md](pin-dao-yu-yan-pian-hao.md "mention") > [yong-hu-yu-yan-pian-hao.md](yong-hu-yu-yan-pian-hao.md "mention") > 默认语言偏好

你可以在设置中调整 `i18n.output` 项以修改这一顺序

## 权限

要修改频道语言偏好，你必须为 [bot-guan-li-yuan.md](../quan-xian/bot-guan-li-yuan.md "mention") 或 [pin-dao-guan-li-yuan.md](../quan-xian/pin-dao-guan-li-yuan.md "mention")

## 本地化 & 别称

该指令也可使用如下方式触发

```
/r locale -c [语言偏好]

/语言 -c [语言偏好]
```
