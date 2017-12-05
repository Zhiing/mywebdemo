# 后代选择器

```css
div {
    padding: 20px;
    background: rgba(255, 0, 0, .2)
}

/* 选中class a 下的所有标签 */
/* .a * {
    border: 2px solid black;
} */

/* 后代准确选择 1 */
.a .c {
    border: 2px solid black;
}

/* 后代准确选择 2 */
/* .b .c {
    border: 2px solid black;
} */

/* 选择 .c 的后代 .d */
.c .d {
    color: blueviolet;
}

/* html .d {
    color: blueviolet;
} 
body .c .d{
    olor: blueviolet;
} */

```