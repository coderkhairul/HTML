# 📘 Part 8: Forms in HTML

## 🧠 What is a Form?

A **form** is used to collect user input. It’s one of the most important parts of any interactive website — like login forms, search bars, and contact pages.

---

## 🔧 Basic Form Tags

| Tag         | Description                            |
|-------------|----------------------------------------|
| `<form>`    | The container for input elements       |
| `<input>`   | User input field (text, email, etc.)   |
| `<label>`   | Defines label for an input field       |
| `<textarea>`| Multiline text input                   |
| `<button>`  | Clickable button                       |
| `<select>`  | Drop-down list                         |
| `<option>`  | Items inside a drop-down list          |

---

## 🧪 Example Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>HTML Form Example</title>
</head>
<body>

  <h2>Registration Form</h2>

  <form action="/submit" method="post">
    <label for="name">Name:</label><br>
    <input type="text" id="name" name="name" placeholder="Your Name" required><br><br>

    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" placeholder="example@mail.com" required><br><br>

    <label for="password">Password:</label><br>
    <input type="password" id="password" name="password" required><br><br>

    <label>Gender:</label><br>
    <input type="radio" id="male" name="gender" value="male">
    <label for="male">Male</label>
    <input type="radio" id="female" name="gender" value="female">
    <label for="female">Female</label><br><br>

    <label for="hobby">Hobbies:</label><br>
    <input type="checkbox" name="hobby" value="coding"> Coding
    <input type="checkbox" name="hobby" value="gaming"> Gaming<br><br>

    <label for="country">Country:</label><br>
    <select id="country" name="country">
      <option value="bd">Bangladesh</option>
      <option value="us">United States</option>
      <option value="uk">United Kingdom</option>
    </select><br><br>

    <label for="bio">Bio:</label><br>
    <textarea id="bio" name="bio" rows="4" cols="30" placeholder="Tell us something about yourself..."></textarea><br><br>

    <button type="submit">Register</button>
  </form>

</body>
</html>
```

---

## 🔍 Output Preview

A form with:

- Text field
- Email field
- Password input
- Gender radio buttons
- Hobby checkboxes
- Country dropdown
- Bio textarea
- Submit button

---

## 📌 Best Practices

- Use `<label>` tags for accessibility.
- Always specify `name` attributes — they are required for form submission.
- Use `required` for fields that must be filled.
- Use `method="post"` when sending sensitive data like passwords.
- Use `placeholder` for helpful hints inside input fields.

---

> ✨ HTML Forms are powerful tools for user interaction. Design them clearly and accessibly to improve user experience.
