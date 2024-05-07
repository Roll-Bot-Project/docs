---
description: 交互式地创建一个抽奖
---

# 创建抽奖

```
/roll add
```

> 你也可以使用参数在一条命令内填写所有内容，详见 [add-by-option.md](../advanced/add-by-option.md "mention")

## 快捷创建

你可以使用 `-n` 参数选择所有可能的默认项，此时你只需要提供奖品列表即可创建一个抽奖

即：

```
/roll add -n
```

## 创建项

### 标题

显示在查询列表上的名称

回复 n 使用默认内容：<用户名> 的抽奖

### 详细描述

抽奖的详细描述，将在 [list.md](list.md "mention") 指令中显示

回复 n 使用默认内容：<用户名> 的抽奖

### 奖品

你要抽的奖品，格式为 `<奖品名称>*[数量(留空为1)]`，每行视为一个独立奖品

例如：

{% code lineNumbers="true" %}

```
挂画*2     // 两个挂画
抱枕       // 一个抱枕

// 66个[支 持 空 格 和*多*个*乘*号*2]
支 持 空 格 和*多*个*乘*号*2*66
```

{% endcode %}

### 自动开奖

抽奖的开奖时间，格式为 年-月-日-时-分（分钟可省略）

回复 n 则不使用自动开奖

例如：

{% code lineNumbers="true" %}

```
2077-11-4-5-14    // 2077年11月4日5时14分
2042-2-6-23       // 2042年2月6日23时00分
```

{% endcode %}

### 抽奖类型

选择自动开奖的抽奖类型，仅需回复数字

0：中奖人可重复

1：中奖人不可重复

回复 n 则使用默认类型：1

### 加入口令

创建一个加入口令，使得用户可以直接发送口令来加入抽奖

回复 n 则不使用加入口令

## 权限

要创建一个抽奖，你必须为 [bot-admin.md](../permission/bot-admin.md "mention") 或 [channel-admin.md](../permission/channel-admin.md "mention")

如果在设置中启用了 `allowNormalUserAdd` 项，则 [channel-member.md](../permission/channel-member.md "mention") 也可以进行创建操作

## 本地化 & 别称

该指令也可使用如下方式触发

```
/r add

/创建抽奖
```
