# 属性选择器

```css
/* 单属性匹配 */
[title] {
    border: 2px solid black;
}

/* 完全属性值匹配 */
[title = "点击登陆"] {
    border: 2px solid black;
}

/* 属性值 模糊匹配 */
[title *="登陆"] {
    border: 2px solid black;
}

/* 只开头 属性值开头 */
[title ^="点击"] {
    border: 2px solid black;
}

/* 匹配结尾 属性值开头 */
[title $="点击"] {
    border: 2px solid black;
}
```