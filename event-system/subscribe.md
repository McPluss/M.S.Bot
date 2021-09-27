---
description: 订阅某个事件
---

# 订阅事件

## 🕒订阅API

订阅某一个事件

当事件触发时执行所对应的回调函数

### 订阅

{% tabs %}
{% tab title="JavaScript" %}
```javascript
event.subscribe(event : String, function : Function);
```
{% endtab %}
{% endtabs %}

| 参数 | 类型 | 详解 |
| :---: | :---: | :---: |
| event | String | [事件名称](event-list.md) |
| function | Function | 当事件触发时所执行的函数 |

### 订阅事件函数

在每一个事件触发的时候，都会执行所对应的函数。

每一个函数都会包含一个回调参数（大概）参数详见[事件列表](https://null.com)

