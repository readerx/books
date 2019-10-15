## 块级元素和行内元素

* 块级元素是指单独撑满一行的元素，如 div、ul、li、table、p、h1 等元素。这些元素的 display 值默认是 `block`、`table`、`list-item` 等。
* 内联元素又叫行内元素，指只占据它对应标签的边框所包含的空间的元素，这些元素如果父元素宽度足够则并排在一行显示的，如 span、a、em、i、img、td 等。这些元素的 display 值默认是 `inline`、`inline-block`、`inline-table`、`table-cell` 等。

---

## CSS 样式表规则

CSS 样式表由大量样式规则组成。每条样式规则分成两个部分：选择器（selector）和声明块（declaration block）。

选择器指明本条规则对哪些网页元素生效，声明块描述样式规则的具体内容。

```
h1 {
  color: red;
}
```

声明块的内容，放在一对大括号里面。大括号之中是一个或多个键值对，每个键值对用分号结尾。
声明块可以写成多行，也可以写成一行。缩进和换行只是为了增加可读性，CSS 引擎会忽略它们。
CSS 允许重复声明某个样式，这时最后声明的键值对会覆盖前面的键值对。

---

## 注释

CSS 使用 `/* ... */` 表示注释，可以是单行，也可以是多行。

