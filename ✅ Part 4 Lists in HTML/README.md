# 📘 Part 4: Lists in HTML

## 🧠 What are HTML Lists?

Lists are used to group related items. HTML supports **three main types** of lists:

- **Ordered List (`<ol>`)** – Numbered items
- **Unordered List (`<ul>`)** – Bullet points
- **Description List (`<dl>`)** – Term-definition pairs

---

## 🧪 Example Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>HTML Lists</title>
</head>
<body>

  <h2>Ordered List</h2>
  <ol>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
  </ol>

  <h2>Unordered List</h2>
  <ul>
    <li>Frontend</li>
    <li>Backend</li>
    <li>Full Stack</li>
  </ul>

  <h2>Nested List</h2>
  <ul>
    <li>Web Development
      <ul>
        <li>Frontend</li>
        <li>Backend</li>
      </ul>
    </li>
    <li>Mobile Development</li>
  </ul>

  <h2>Description List</h2>
  <dl>
    <dt>HTML</dt>
    <dd>HyperText Markup Language</dd>
    <dt>CSS</dt>
    <dd>Cascading Style Sheets</dd>
  </dl>

</body>
</html>

🔍 Output Preview
✔ Ordered List:

HTML

CSS

JavaScript

✔ Unordered List:

Frontend

Backend

Full Stack

✔ Nested List:

Web Development

Frontend

Backend

Mobile Development

✔ Description List:

HTML: HyperText Markup Language

CSS: Cascading Style Sheets

📌 Best Practices

| Use Case                | Recommended List Type               |
| ----------------------- | ----------------------------------- |
| Steps, processes        | `<ol>`                              |
| General information     | `<ul>`                              |
| Hierarchical grouping   | Nest `<ul>` or `<ol>` inside `<li>` |
| Definitions / Key-Value | `<dl>`                              |

✅ Use <ol> when order matters (e.g., a recipe).
✅ Use <ul> for unordered, equal-priority items.
✅ Nest lists properly inside <li> elements.
✅ Use <dl> only when you need to show definitions or key-value style content.