# 第六单元 — CSS 选择器练习  |  任务 2 (3/18)
CSS 练习：编写 class 和 ID 规则并在 HTML 元素上应用它们。

---

> 💡 先从 `styles.css` 开始 — 然后在 `index.html` 中应用你的规则

---

## 📌 开始之前 — 应用多个 Class

class 最强大的功能之一是你可以在**同一个元素上应用多个 class**。只需在 `class` 属性中用空格分隔每个名称即可。

**HTML 示例：**
```html
<p class="dark-bg light-text spaced-out">
  这个段落应用了三个 class！
</p>
```

**CSS 中的效果：**
```css
/* 每个 class 控制一件事 */
.dark-bg {
  background-color: #1e1e1e;
}

.light-text {
  color: #ffffff;
}

.spaced-out {
  padding: 20px;
}
```

三条规则同时应用在同一个段落上。这就是 class 如此强大的原因 — 你可以在任何元素上自由组合使用它们。

> 💡 你可以自由地将任何规则应用到 HTML 的 `<body>` 里的任何元素上。选择权在你 — 多试试，看看会发生什么！

---

## 第一级 — 完全引导  *(任务 1 – 5)*

我们给你规则名称、属性和值。
你的任务是用正确的语法写出规则。

```
Class 规则使用点号    →   .name { }
ID 规则使用井号      →   #name { }
```

---

**任务 1** — 编写一个名为 `dark-bg` 的 CLASS 规则
- 属性：`background-color`
- 值：`#1e1e1e`
- 作用：将背景更改为深灰色

📖 [background-color — W3Schools](https://www.w3schools.com/cssref/pr_background-color.php)

---

**任务 2** — 编写一个名为 `light-text` 的 CLASS 规则
- 属性：`color`
- 值：`#ffffff`
- 作用：将文字颜色改为白色，使其在深色背景上易于阅读

📖 [color — W3Schools](https://www.w3schools.com/cssref/pr_text_color.php)

---

**任务 3** — 编写一个名为 `rounded` 的 CLASS 规则
- 属性：`border-radius`
- 值：`10px`
- 作用：将元素的边角变为圆角

📖 [border-radius — W3Schools](https://www.w3schools.com/cssref/css3_pr_border-radius.php)

---

**任务 4** — 编写一个名为 `spaced-out` 的 CLASS 规则
- 属性：`padding`
- 值：`20px`
- 作用：在元素内部添加空间，使内容不会感觉拥挤

📖 [padding — W3Schools](https://www.w3schools.com/cssref/pr_padding.php)

---

**任务 5** — 编写一个名为 `page-title` 的 ID 规则
- 属性 1：`font-size` → 值：`48px`
- 属性 2：`text-align` → 值：`center`
- 作用：使页面主标题变大并居中显示

📖 [font-size — W3Schools](https://www.w3schools.com/cssref/pr_font_font-size.php)
📖 [text-align — W3Schools](https://www.w3schools.com/cssref/pr_text_text-align.php)

---

## 第二级 — 半引导  *(任务 6 – 10)*

**任务 6、7、8** — 我们给你名称和描述。你来决定属性和值。

**任务 9、10** — 我们只给你描述。你来决定名称、属性和值。

每条规则必须有至少 **2 个属性**。

---

**任务 6** — 编写一个名为 `card` 的 CLASS 规则

让一个元素看起来像一张卡片。它应该有背景颜色、边框，以及一些 padding 使内容有足够的空间。

📖 [border — W3Schools](https://www.w3schools.com/cssref/pr_border.php)
📖 [padding — W3Schools](https://www.w3schools.com/cssref/pr_padding.php)

---

**任务 7** — 编写一个名为 `warning` 的 CLASS 规则

让一个元素看起来像一个警告。想想什么样的颜色能让人停下来注意。

📖 [background-color — W3Schools](https://www.w3schools.com/cssref/pr_background-color.php)
📖 [color — W3Schools](https://www.w3schools.com/cssref/pr_text_color.php)

---

**任务 8** — 编写一个名为 `img-style` 的 CLASS 规则

为图片添加样式，使其有边框和圆角。

📖 [border — W3Schools](https://www.w3schools.com/cssref/pr_border.php)
📖 [border-radius — W3Schools](https://www.w3schools.com/cssref/css3_pr_border-radius.php)

---

**任务 9** — 你来决定这个 CLASS 规则的名称

让文字看起来像一个标签或标记。它应该有背景颜色、圆角和 padding，使其看起来像一个小徽章。

📖 [border-radius — W3Schools](https://www.w3schools.com/cssref/css3_pr_border-radius.php)
📖 [padding — W3Schools](https://www.w3schools.com/cssref/pr_padding.php)

---

**任务 10** — 你来决定这个 ID 规则的名称

为页面底部的 footer 部分设置样式。它应该有深色背景、浅色文字，并且文字居中显示。

📖 [text-align — W3Schools](https://www.w3schools.com/cssref/pr_text_text-align.php)
📖 [color — W3Schools](https://www.w3schools.com/cssref/pr_text_color.php)

---

## 第三级 — 开放式  *(任务 11 – 13)*

你来决定一切 — 名称、属性和值。

- 至少编写 **2 条 class 规则**
- 至少编写 **1 条 ID 规则**
- 每条规则必须有至少 **2 个属性**
- 在 `index.html` 中应用所有规则

祝你好运！🎯

---

## 附加挑战

如果你提前完成，可以试试这些！

- [ ] **附加 1** — 在同一个元素上应用两个或更多 class
- [ ] **附加 2** — 将 `dark-bg` 和 `light-text` 同时应用到一个元素上，看看效果如何
- [ ] **附加 3** — 在至少一条第三级规则中添加 `margin` 属性
- [ ] **附加 4** — 只用 `img-style` class 为所有五张图片设置样式
- [ ] **附加 5** — 总共编写超过 13 条 CSS 规则

---

## 参考资料

需要帮助记住某个属性的用法？使用这个参考资料：

👉 [完整 CSS 属性列表 — W3Schools](https://www.w3schools.com/cssref/css3_pr_all.php)