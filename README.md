# jQuery Input Limiter plugin

>This jQuery plugin will allow you to limit input into form fields. It can display a message as the user types to let them know how many characters they have remaining.

[原文档](http://rustyjeans.com/jquery-plugins/input-limiter/)

改动后文件为： jquery.inputlimiter2.js（支持中文字符输入限制）

## 基础用法

```html
<input tupe="text" name="name" id="ipt1" />
```


```js
$(function() {
    $('#ipt1').inputlimiter({
        limit: 10
    });
});
```

其他配置项请参照[原文档](http://rustyjeans.com/jquery-plugins/input-limiter/)。