## 解决元素 float 之后出现的 BUG ：

在 float 元素的父元素添加 clearfix 类

```css
.clearfix::after {
    content: '';
    display: block;
    clear: both;
}
```


## 鼠标移入显示边框小技巧：

先给默认透明边框，写鼠标移入效果时再填充颜色。