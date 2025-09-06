# 📘 Part 6: Images in HTML

## 🧠 What is the `<img>` Tag?

The `<img>` tag is used to display images on a web page. It’s a **self-closing** tag and requires at least two attributes:

- `src` — the image source path
- `alt` — alternative text (shown if image fails to load)

---

## 🧪 Basic Syntax

```html
<img src="image-path" alt="description" />
```

---

## 🧪 Example Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>HTML Images</title>
</head>
<body>

  <h2>Local Image</h2>
  <img src="images/my-photo.jpg" alt="My Profile Photo" width="200">

  <h2>External Image</h2>
  <img src="https://via.placeholder.com/150" alt="Placeholder Image">

  <h2>Image with Height and Width</h2>
  <img src="https://via.placeholder.com/100x100" alt="Sized Image" width="100" height="100">

  <h2>Broken Image Example</h2>
  <img src="wrong-path.jpg" alt="Image Not Found">

</body>
</html>
```

---

## 🔍 Output Preview Summary

- ✅ **Local Image** — Displays an image from your project folder
- ✅ **External Image** — Loads image from the internet
- ✅ **Sized Image** — Shows image with specific width and height
- ❌ **Broken Image** — Displays `alt` text if the image doesn't load

---

## 📌 Attributes of `<img>` Tag

| Attribute        | Description                                         |
|------------------|-----------------------------------------------------|
| `src`            | Source of the image                                 |
| `alt`            | Alternate text if image fails to load               |
| `width`          | Width in pixels or percent                          |
| `height`         | Height in pixels or percent                         |
| `loading="lazy"` | Loads image only when it becomes visible (optional) |

---

## ✅ Best Practices

- ✅ Always include `alt` text for **accessibility** and **SEO**
- ✅ Use `width` and `height` to control image size and layout
- ✅ Optimize image size for **faster loading**
- ✅ Use `loading="lazy"` on long pages for better performance

---

Happy Learning! 🌟