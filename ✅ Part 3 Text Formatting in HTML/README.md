# 📘 Part 3: Text Formatting in HTML

## 🧠 What is Text Formatting?
Text formatting tags in HTML help **style or emphasize** parts of your content — like making text **bold**, *italic*, or <u>underlined</u>.

They are useful for:
- Improving readability
- Highlighting important information
- Providing semantic meaning to certain parts of your content

---

## 🧪 Example Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Text Formatting</title>
</head>
<body>

  <h2>Basic Text Formatting</h2>

  <p><b>This text is bold using &lt;b&gt;</b></p>
  <p><strong>This text is bold using &lt;strong&gt; (semantic)</strong></p>

  <p><i>This text is italic using &lt;i&gt;</i></p>
  <p><em>This text is italic using &lt;em&gt; (semantic)</em></p>

  <p><u>This text is underlined using &lt;u&gt;</u></p>

  <p><mark>This text is highlighted using &lt;mark&gt;</mark></p>

  <p><small>This text is smaller using &lt;small&gt;</small></p>

  <p><del>This text is deleted using &lt;del&gt;</del></p>

  <p><ins>This text is inserted using &lt;ins&gt;</ins></p>

  <p>This is <sub>subscript</sub> and this is <sup>superscript</sup>.</p>

</body>
</html>

🔍 Output Preview

Basic Text Formatting Output
Bold using <b>
Bold using <strong>

Italic using <i>
Italic using <em>

<u>Underline using <u></u>

<mark>Highlight using <mark></mark>

<small>Small text using <small></small>

<del>Deleted using <del></del>

<ins>Inserted using <ins></ins>

This is subscript: H<sub>2</sub>O
This is superscript: x<sup>2</sup>

📝 Note: Output preview may vary slightly by browser style.

📌 Best Practices

| Tag        | Semantic Meaning | Use When You Want To...                     |
| ---------- | ---------------- | ------------------------------------------- |
| `<strong>` | ✅ Yes            | Show strong importance                      |
| `<em>`     | ✅ Yes            | Emphasize text                              |
| `<b>`      | ❌ No             | Make text bold without any semantic meaning |
| `<i>`      | ❌ No             | Make text italic without meaning            |
| `<u>`      | ❌ No             | Underline without emphasis (rarely used)    |
| `<mark>`   | ❌ No             | Highlight text like using a marker          |
| `<del>`    | ✅ Yes            | Show deleted text (like revision history)   |
| `<ins>`    | ✅ Yes            | Show inserted text (like revision history)  |
