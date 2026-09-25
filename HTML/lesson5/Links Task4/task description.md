# 🔗 HTML Links Task

## 🎯 Objective

Practice using HTML links with:

* Website URLs
* `target="_blank"`
* Images as clickable links
* Email links
* Phone links
* SMS links

---

## 📋 Requirements

Create a new HTML page called:

```text
links.html
```

Set the page title to:

```text
My Links
```

### 1. Website Links

Add a section titled:

```text
Useful Websites
```

Add links to **three different websites**.

Requirements:

* One link must open in the **same tab**.
* Two links must open in a **new tab** using `target="_blank"`.

Example:

```html
<a href="https://example.com">Example</a>
```

---

### 2. Image Link

Add an image to your page.

When the user clicks the image, it should open a website in a **new tab**.

Requirements:

* Use an `<img>` element inside an `<a>` element.
* Add meaningful `alt` text to the image.
* Use `target="_blank"`.

---

### 3. Email Link

Create a section titled:

```text
Contact Me
```

Add an email link that opens the user's default email application.

Use the `mailto:` URI scheme.

Example format:

```html
<a href="mailto:example@email.com">Send Me an Email</a>
```

---

### 4. Phone Link

Add a phone link that allows the user to start a phone call.

Use the `tel:` URI scheme.

Example format:

```html
<a href="tel:1234567890">Call Me</a>
```

---

### 5. SMS Link

Add an SMS link that opens the messaging application.

Use the `sms:` URI scheme.

Example format:

```html
<a href="sms:1234567890">Send Me a Text</a>
```

---

## ⭐ Challenge

Create a small **"My Links"** page that contains:

* A heading
* A short paragraph
* 3 website links
* 1 clickable image
* 1 email link
* 1 phone link
* 1 SMS link

Organize your links into appropriate sections.

---

## 💡 Hint

Remember the basic syntax:

```html
<a href="URL">Link Text</a>
```

For a new tab:

```html
<a href="URL" target="_blank">Link Text</a>
```

For URI schemes:

```html
<a href="mailto:...">Email</a>
<a href="tel:...">Call</a>
<a href="sms:...">Text</a>
```

---

## Technologies

* HTML