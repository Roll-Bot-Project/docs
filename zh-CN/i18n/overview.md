---
description: 国际化功能
---

# 简介

Roll Bot 为不同的时区以及语言提供了支持。

## 时区

Roll Bot 使用 [偏移量 (Offset)](https://zh.wikipedia.org/wiki/UTC%E5%81%8F%E7%A7%BB%E9%87%8F) 记录时区，并在解析、发送时间时使用。

由于偏移量是固定的值，因此使用夏令时的用户可能需要多次调整他们的偏移量。

## 语言偏好

Roll Bot 使用 [IETF语言标签 (IETF language tag)](https://zh.wikipedia.org/wiki/IETF%E8%AA%9E%E8%A8%80%E6%A8%99%E7%B1%A4) 记录语言偏好，并在发送内容时使用。

目前 Roll Bot 支持的语言包括 `zh-CN` `en-US` `de-DE`

## 优先级

Roll Bot 处理时区和语言偏好时采用如下优先级：

**频道设置 > 用户设置 > 默认设置**

你可以在设置中调整 `i18n.output` 项以修改这一顺序
