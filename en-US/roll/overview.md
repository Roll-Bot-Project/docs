---
description: Main features of Roll Bot
---

# Introduction

**Pickup** is the main feature provided by Roll Bot. A drawing will contain：

- Title
- Description&#x20
- Prizes
- Times for auto-awards
- Join Key
- Open Range
- Use reminders

You can create a new drawing by the [add.md](add.md "mention") directive and use the [edit-roll.md](../advanced/edit-roll.md "mention") directive after creation to edit it.

## Pick up password

If the lottery is set, users can easily join the lottery by sending a passphrase within the channel.By joining the passwords, users can quickly join the lottery without having to view any instruction instructions.

## Open range of prizes

Default is only open to the current channel when the drawing is created.在创建后，你可以通过 [edit-roll.md](../advanced/edit-roll.md "mention") 指令来编辑抽奖的开放范围。这可以使多个频道的用户均可以参与抽奖。同一平台的同一用户只能参与一次。在跨平台环境下使用时，如果用户未使用 `bind` 指令绑定其不同平台的用户，则他将被视为不同的用户。

Private chat is seen as a channel that only contains you and Roll Bot, which means you can create a premium in a private chat and modify its open range.使用此方法可以隐藏创建抽奖的过程，避免刷屏。
