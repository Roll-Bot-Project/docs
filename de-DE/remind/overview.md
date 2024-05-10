---
description: Verwenden Sie Erinnerungen, um über Lotteriebenachrichtigungen informiert zu werden
---

# Einführung

Roll Bot 通过 **提醒器** 提供提醒功能。提醒器是一个提醒的时间模板，它指定了发送提醒消息的具体时间或时间模式，例如：

- 在 **6月14日 22:30** 进行提醒（定时提醒器）
- 在 **抽奖结束前 45 分钟** 进行提醒（结束前提醒器）
- **每天 23:00** 进行一次提醒（间隔提醒器）
- **每2小时** 进行一次提醒（间隔提醒器）

通过创建提醒器并将其应用于抽奖，Roll Bot 可以自动提醒用户参与抽奖。

## Standardbenachrichtigung für Lotterie

创建抽奖时，将根据设置中 `remind.defaultReminders` 项为其启用默认的提醒器。

## Bereich für die Benachrichtigungsbereitstellung

提醒消息的推送范围默认与抽奖开放范围相同，且会随抽奖开放范围同步变化。

你可以[自行指定提醒消息的推送范围](../advanced/edit-roll.md)，指定后该提醒的范围将不再动态同步。

请注意，提醒消息仅能在其抽奖的开放范围内发送。

## 提醒器的可见范围

为了避免过多信息干扰，提醒器创建后，你只能查询到你自己创建的提醒器。
