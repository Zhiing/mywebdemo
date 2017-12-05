## 字体属性 

```css
p {
    /* 字体 */
    font-family: "微软雅黑", "Microsoft Yahei";
    /* 字重 (范围 100 - 900) (粗体 bold) */
    font-weight: normal;
    /* 字体大小 相对于 (母元素100% 继承 inhenit) */
    font-size: 12px;
}
```

## 文本属性

```css
p {
    /* 字体的对齐方式 居中 center 两端 justify */
    text-align: left;
    /* 行高 (字体大小的两倍 2 比例) (像素 可以小于字体大小 20px)*/
    line-height: 2;
    /* 文字样式 (下划线 underline) (删除线 line-through) (无 none)*/
    text-decoration: line-through;
}

/* 去除 a 标签的的下划线 */
a {
    text-decoration: none;
}
```