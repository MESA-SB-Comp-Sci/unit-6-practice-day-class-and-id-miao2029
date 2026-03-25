# Unit 6 — CSS Selectors Practice  |  Task 2 (3/18)
CSS practice: Writing class and ID rules and applying them to HTML elements.

---

> 💡 Start in `styles.css` — then apply your rules in `index.html`

---

## 📌 Before You Start — Applying Multiple Classes

One of the most powerful things about classes is that you can apply **more than one class to the same element**. Just add them to the `class` attribute with a space between each name.

**Example in HTML:**
```html
<p class="dark-bg light-text spaced-out">
  This paragraph has three classes applied to it!
</p>
```

**What that does in CSS:**
```css
/* Each class controls one thing */
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

All three rules apply to that one paragraph at the same time. This is why classes are so powerful — you can mix and match them on any element you want.

> 💡 You are free to apply any of your rules to any element inside the `<body>` of your HTML. The choice is yours — experiment and see what happens!

---

## Level 1 — Fully Guided  *(Tasks 1 – 5)*

We give you the rule name, the property, and the value.
Your job is to write the rule using the correct syntax.

```
Class rules use a dot      →   .name { }
ID rules use a hashtag     →   #name { }
```

---

**Task 1** — Write a CLASS rule called `dark-bg`
- Property: `background-color`
- Value: `#1e1e1e`
- What it does: changes the background to a dark charcoal color

📖 [background-color — W3Schools](https://www.w3schools.com/cssref/pr_background-color.php)

---

**Task 2** — Write a CLASS rule called `light-text`
- Property: `color`
- Value: `#ffffff`
- What it does: changes the text to white so it is easy to read on a dark background

📖 [color — W3Schools](https://www.w3schools.com/cssref/pr_text_color.php)

---

**Task 3** — Write a CLASS rule called `rounded`
- Property: `border-radius`
- Value: `10px`
- What it does: rounds the corners of an element

📖 [border-radius — W3Schools](https://www.w3schools.com/cssref/css3_pr_border-radius.php)

---

**Task 4** — Write a CLASS rule called `spaced-out`
- Property: `padding`
- Value: `20px`
- What it does: adds space inside the element so the content does not feel cramped

📖 [padding — W3Schools](https://www.w3schools.com/cssref/pr_padding.php)

---

**Task 5** — Write an ID rule called `page-title`
- Property 1: `font-size` → Value: `48px`
- Property 2: `text-align` → Value: `center`
- What it does: makes the main title large and centered on the page

📖 [font-size — W3Schools](https://www.w3schools.com/cssref/pr_font_font-size.php)
📖 [text-align — W3Schools](https://www.w3schools.com/cssref/pr_text_text-align.php)

---

## Level 2 — Semi Guided  *(Tasks 6 – 10)*

**Tasks 6, 7, 8** — We give you the name and a description. You decide the properties and values.

**Tasks 9, 10** — We give you only a description. You decide the name AND the properties and values.

Each rule must have at least **2 properties**.

---

**Task 6** — Write a CLASS rule called `card`

Make an element look like a card. It should have a background color, a border, and some padding so the content has breathing room.

📖 [border — W3Schools](https://www.w3schools.com/cssref/pr_border.php)
📖 [padding — W3Schools](https://www.w3schools.com/cssref/pr_padding.php)

---

**Task 7** — Write a CLASS rule called `warning`

Make an element stand out as a warning. Think about what colors would make someone stop and pay attention.

📖 [background-color — W3Schools](https://www.w3schools.com/cssref/pr_background-color.php)
📖 [color — W3Schools](https://www.w3schools.com/cssref/pr_text_color.php)

---

**Task 8** — Write a CLASS rule called `img-style`

Style an image so it has a border and rounded corners.

📖 [border — W3Schools](https://www.w3schools.com/cssref/pr_border.php)
📖 [border-radius — W3Schools](https://www.w3schools.com/cssref/css3_pr_border-radius.php)

---

**Task 9** — You decide the name for this CLASS rule

Make text look like a label or a tag. It should have a background color, rounded corners, and padding to make it look like a small badge.

📖 [border-radius — W3Schools](https://www.w3schools.com/cssref/css3_pr_border-radius.php)
📖 [padding — W3Schools](https://www.w3schools.com/cssref/pr_padding.php)

---

**Task 10** — You decide the name for this ID rule

Style a footer section at the bottom of the page. It should have a dark background, light text, and the text should be centered.

📖 [text-align — W3Schools](https://www.w3schools.com/cssref/pr_text_text-align.php)
📖 [color — W3Schools](https://www.w3schools.com/cssref/pr_text_color.php)

---

## Level 3 — Open Ended  *(Tasks 11 – 13)*

You decide everything — the name, the properties, and the values.

- Write at least **2 class rules**
- Write at least **1 ID rule**
- Each rule must have at least **2 properties**
- Apply all of them somewhere in your `index.html`

Good luck! 🎯

---

## Bonus Challenges

Try these if you finish early!

- [ ] **Bonus 1** — Apply two or more classes to the same element
- [ ] **Bonus 2** — Combine `dark-bg` and `light-text` on one element and see what happens
- [ ] **Bonus 3** — Add a `margin` property to at least one of your Level 3 rules
- [ ] **Bonus 4** — Style all five images using only the `img-style` class
- [ ] **Bonus 5** — Write more than 13 CSS rules total

---

## Reference

Need help remembering how a property works? Use this reference:

👉 [Full CSS Property List — W3Schools](https://www.w3schools.com/cssref/css3_pr_all.php)