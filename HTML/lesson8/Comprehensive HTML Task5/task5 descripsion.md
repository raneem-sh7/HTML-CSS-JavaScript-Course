# 🧩 HTML Course — Final Practice Task

## 📌 Overview

Create a **Personal Portfolio Web Page** using the HTML concepts covered in Lessons 1–8.

The main goal of this task is to practice **Semantic HTML, CSS Classes & IDs, and Responsive Design**.

---

## 🎯 Requirements

### 1. Basic HTML Structure

Create a complete HTML document containing:

* `<!DOCTYPE html>`
* `<html>`
* `<head>`
* `<title>`
* `<body>`

Set an appropriate title for your page.

---

### 2. Semantic HTML ⭐

Use semantic HTML elements to structure your page.

Your page must include:

* `<header>`
* `<nav>`
* `<main>`
* `<section>`
* `<article>`
* `<aside>`
* `<footer>`

### Suggested Structure

```text
<header>
    <nav>
        ...
    </nav>
</header>

<main>
    <section>
        ...
    </section>

    <section>
        <article>
            ...
        </article>
    </section>

    <aside>
        ...
    </aside>
</main>

<footer>
    ...
</footer>
```

**Important:** Use semantic tags where appropriate instead of using `<div>` for everything.

---

## 3. Classes & IDs ⭐⭐⭐

Create at least:

* **3 different classes**
* **2 IDs**

For example:

```html
<h1 class="title">My Portfolio</h1>
<p class="description">...</p>
```

Use the `<style>` tag to define your CSS.

Example:

```css
.title {
    ...
}

.description {
    ...
}

#about {
    ...
}
```

### Requirements

* Use at least **one element with multiple classes**.
* Use at least **one element containing both an `id` and a `class`**.
* Make your IDs unique.
* Demonstrate that an ID selector has higher specificity than a class selector.

---

## 4. Colors & Inline Styling

Use at least:

* One color name
* One hexadecimal color
* One RGB color

Example:

```html
<p style="color: red;">Color Name</p>

<p style="color: #0000FF;">Hex Color</p>

<p style="color: rgb(0, 128, 0);">RGB Color</p>
```

Try to avoid using inline styles for everything. Use classes when possible.

---

## 5. Text Formatting

Include examples of at least three text-formatting elements:

* `<b>`
* `<em>`
* `<small>`
* `<del>`

Example:

```html
<p>
    I am learning <b>HTML</b> and <em>Web Development</em>.
</p>
```

---

## 6. Headings, Paragraphs & Line Breaks

Your page must contain:

* `<h1>`
* At least two other heading levels
* `<p>`
* `<br>`
* `<pre>`

Use the headings in a logical hierarchy.

---

## 7. Links ⭐

Add navigation links inside your `<nav>`.

Include:

* A normal URL link
* A link that opens in a new tab using `target="_blank"`
* An email link using `mailto:`
* A phone link using `tel:`

Example:

```html
<a href="https://github.com/" target="_blank">
    GitHub
</a>

<a href="mailto:example@email.com">
    Email Me
</a>
```

---

## 8. Clickable Image

Add an image that works as a clickable link.

Example:

```html
<a href="https://github.com/" target="_blank">
    <img src="github.png" alt="GitHub">
</a>
```

Make sure the image has a meaningful `alt` attribute.

---

## 9. Table

Create a table showing something related to your portfolio.

For example:

**My Skills**

| Skill      | Level    | Experience |
| ---------- | -------- | ---------- |
| HTML       | Good     | 1 Year     |
| CSS        | Beginner | 6 Months   |
| JavaScript | Beginner | 3 Months   |

Your HTML table must contain:

* `<table>`
* `<tr>`
* `<th>`
* `<td>`
* `colspan`

---

# 📱 10. Responsive Design ⭐⭐⭐

Make your page responsive.

Inside `<head>`, add:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Add at least **one media query**:

```css
@media (max-width: 600px) {
    ...
}
```

On smaller screens, change at least one thing, such as:

* Font size
* Layout
* Width
* Navigation
* Image size

Also make sure your images don't overflow the screen:

```css
img {
    max-width: 100%;
    height: auto;
}
```

### 📱 Test Your Page

Check your page on:

* Desktop
* Tablet
* Mobile

The content should remain readable and usable on all screen sizes.

---

# 🧱 11. `<div>` vs Semantic Elements ⭐⭐⭐

Use at least **one `<div>`** in your project.

Add a comment explaining why you used it.

Example:

```html
<!-- <div> is a non-semantic container used to group HTML elements -->
<div class="skills-container">
    ...
</div>
```

Make sure you don't replace semantic elements such as `<header>` or `<footer>` with `<div>` when a suitable semantic element exists.

---

# 💡 Suggested Portfolio Content

Your portfolio could contain:

### Header

* Your name
* Short introduction
* Navigation links

### About Section

* Short paragraph about yourself
* An image

### Skills Section

* HTML
* CSS
* JavaScript
* Python

### Projects Section

Create at least two `<article>` elements describing your projects.

### Skills Table

Show your skills and experience.

### Aside

Add additional information such as:

* GitHub
* Contact information
* Favorite technology

### Footer

Add:

* Copyright
* Email
* Social/portfolio links

---

# ⭐ Main Focus

While completing the task, pay special attention to:

### 1. Semantic HTML

Ask yourself:

> "Am I using the correct HTML element for the meaning of this content?"

### 2. Classes & IDs

Remember:

```text
.class → reusable
#id    → unique
```

### 3. Responsive Design

Ask yourself:

> "Will this page still work properly on a mobile screen?"

---

# ✅ Checklist

Before submitting, make sure you have:

* [ ] Complete HTML structure
* [ ] Headings and paragraphs
* [ ] Text formatting
* [ ] Colors
* [ ] Links
* [ ] Clickable image
* [ ] Table
* [ ] `<div>`
* [ ] `<header>`
* [ ] `<nav>`
* [ ] `<main>`
* [ ] `<section>`
* [ ] `<article>`
* [ ] `<aside>`
* [ ] `<footer>`
* [ ] At least 3 classes
* [ ] At least 2 unique IDs
* [ ] Multiple classes on one element
* [ ] An element with both `id` and `class`
* [ ] `<meta name="viewport">`
* [ ] At least one media query
* [ ] Responsive images
* [ ] Tested on different screen sizes

---

## 🚀 Bonus

If you finish everything above, try to:

1. Add a second page such as `projects.html`.
2. Connect the pages using `<a>` links.
3. Create a consistent navigation bar.
4. Use classes instead of inline styles wherever possible.
5. Improve the mobile layout using additional media queries.
