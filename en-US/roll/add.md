---
description: Interactive creation of a drawing
---

# Create a drawing award

```
/roll add
```

> If you want to create a private chat to hide the creation process (e.g. avoid brush screens or hide joining passwords), see：[#chou-jiang-de-kai-fang-fan-wei](overview.md#chou-jiang-de-kai-fang-fan-wei "mention")

## Quick Create

You can select all possible default items using the `-n` parameter, you can create a drawing at this point by simply providing a list of prizes

It is：

```
/roll add -n
```

## Create Item

### Title

Name displayed on query list

Reply-by using default：<Username>

### Description

A detailed description of the drawing will be displayed in the [list.md](list.md "mention") directive

Reply-by using default：<Username>

### Prizes

You are about to draw a prize in the format `<Prize name>*[Amount (Leave empty 1)]`, each line is considered to be an independent prize

e.g.：

{% code lineNumbers="true" %}

```
The applet *2// Two paintings
with a total / / one with

// 66 [empty space and *more * by *2]
empty space and *more * by *2*66
```

{% endcode %}

### Automatic awards

Award opening time, in the form of Year-mm-days-hour-minutes (minutes may be omitted)

Replyn does not use automatic award

e.g.：

{% code lineNumbers="true" %}

```
2077-11-4-5-14    // November 4, 2077, 5:14 AM
2042-2-6-23       // February 6, 2042, 11:00 PM
```

{% endcode %}

### Pickup Type

Select the type of prize to start automatically, just reply numbers

The prizer in 0：can repeat

The prizer in 1：cannot repeat

Reply with n to use the default type: 1

### Add Token

Create a new password that allows users to send a password directly to add a premium

Reply to n without adding password

## Permissions

To create a draw you must be [bot-admin.md](../permission/bot-admin.md "mention") or [channel-admin.md](../permission/channel-admin.md "mention")

If `allowNormalUserAdd` is enabled in Settings, then [channel-member.md](../permission/channel-member.md "mention") can also be created

## Localization & Alias

This command can also be triggered by

```
/r add

/ Create Pickup
```
