---
description: 订阅某个事件
---

# 订阅事件

## 🕒订阅API

订阅某一个事件

当事件触发时执行所对应的回调函数

### 订阅

```javascript
event.subscribe(event : String, function : Function);
```

* 参数解析
  * event : `String`    
    事件名称，详见[事件列表](null)
  * function : `Function`    
    当事件发生时所触发的函数    
    所传入得参数详见[事件列表](null)
    

