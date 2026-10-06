---
layout: essay
type: essay
title: "UI Frameworks Will Change Your Life"
# All dates must be YYYY-MM-DD format!
date: 2026-10-06
published: true
labels:
  - Bootstrap 5
  - HTML
  - CSS
  - ICS 314
---

## What is a UI Framework?
A UI Framework is like a set of pre-built tools that are ready to use. In HTML and CSS, you are creating everything from scratch. However, by using a UI framework like Bootstrap 5, it can make you life a whole lot easier.

## Why Should I Bother?
Bootstrap can make your design so much simpler. What once was many lines of code, split into two files can now be done in less lines in just one file. For example, creating a button. Using just HTML, you need CSS to style the button and make it look nice. Using bootstrap, you can do the work of 8 CSS lines in 1.

<table>
<tr>
<th>HTML and CSS</th>
<th>Bootstrap</th>
</tr>

<tr>
<td>

### HTML

```html
<button class="button">Click Me</button>
```

### CSS

```css
.button {
    background-color: #0d6efd;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    font-size: 16px;
}

.button:hover {
    background-color: #0b5ed7;
}
```

</td>

<td>

### Bootstrap

```html
<button class="btn btn-primary">Click Me</button>
```

</td>
</tr>
</table>

## Why Use Bootstrap?

The regular HTML and CSS version requires both HTML and CSS to create and style the button. Bootstrap already has button styles built in, so you only need to add Bootstrap classes to the HTML.

The Bootstrap version is much shorter:

- **HTML and CSS:** 11 lines
- **Bootstrap:** 1 line

Bootstrap can save time because common styles and components are already created for you.
