# 📘 Part 5: Links and Anchors in HTML

## 🧠 What Are Links in HTML?
Links (anchors) let you navigate from one page to another or specific sections within a page. The `<a>` tag is used to define a hyperlink.

---

## 🔗 Basic Syntax
```html
<a href="URL">Link Text</a>
```

---

## 🧪 Example Code
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>HTML Links</title>
</head>
<body>

  <h2>External Link</h2>
  <p><a href="https://www.google.com" target="_blank">Visit Google</a></p>

  <h2>Internal Link</h2>
  <p><a href="about.html">About Page</a></p>

  <h2>Email Link</h2>
  <p><a href="mailto:example@example.com">Send Email</a></p>

  <h2>Telephone Link</h2>
  <p><a href="tel:+8801234567890">Call Us</a></p>

  <h2>Anchor Link (Jump to Section)</h2>
  <p><a href="#footer">Go to Footer</a></p>

  <h2>Image as Link</h2>
  <a href="https://github.com/">
    <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub Logo" width="50">
  </a>

  <h2 id="footer">Footer Section</h2>
  <p>You have reached the footer!</p>

</body>
</html>
```

---

## 🔍 Output Preview Summary

- ✅ **Visit Google** — opens in a new tab
- ✅ **About Page** — links to `about.html`
- ✅ **Send Email** — opens the default email app
- ✅ **Call Us** — initiates a phone call on mobile
- ✅ **Go to Footer** — jumps to the bottom section
- ✅ **GitHub Logo** — image as clickable link

---

## 📌 Attributes of `<a>` Tag

| Attribute         | Description                                      |
|------------------|--------------------------------------------------|
| `href`           | The URL to link to                               |
| `target="_blank"`| Opens link in a new tab/window                   |
| `mailto:`        | Opens default email client                       |
| `tel:`           | Initiates a phone call on mobile devices         |
| `#id`            | Jumps to an element with the given ID on page    |

---

## ⚠ Best Practices

- Use `target="_blank"` for external links to open them in new tabs.
- Use **descriptive link text**, e.g., "Visit Google" instead of "Click here".
- Avoid using `<a>` for styling only — use `<button>` or `<span>` instead.

---