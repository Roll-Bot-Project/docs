---
description: Use a reminder to notify the drawing of a message
---

# Introduction

Roll Bot provides alarm features via **Reminder**Reminder is a reminder time template that specifies a specific time or time mode for sending a reminder message, e.g.：

- Reminder on **June 14, 22:30** (scheduled time)
- Reminder 45 minutes before the end of the **pull prize** (pre-end)
- **Daily 23:00** Reminder once
- **every 2 hours** reminder (interval reminder)

By creating the alarm and applying it to the drawing of the award, Roll Bot can automatically remind users to participate in the drawing of the award.

## 提醒器

提醒器用于保存提醒的模式，以便重复使用。

### 定时提醒器

在指定时间提醒一次

### 结束前提醒器

抽奖结束前一定时间提醒一次

### 间隔提醒器

每隔一定时间提醒一次

## Default Reminder

The default alarm will be enabled from the `remoind.defaultReminers` entry in the settings when creating the prize.

## Reminder message push range

The push range for reminders will be the same as for a drawing of rewards by default, and will change with the selection open range.

You can[自行指定提醒消息的推送范围](../advanced/edit-rol.md), the range of the alarm will no longer be synced dynamically.

Please note that reminders can only be sent within the open range of their prizes.

## Visible range of reminders

In order to avoid excessive information disruption, when a reminder is created, you can only query the alarm created by yourself.
