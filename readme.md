# HTML Deep Dive – Day 1: HTML Basics & Structure

Welcome to Day 1 of the HTML Deep Dive series! In this session, you'll learn the foundational building blocks of HTML including structure, formatting, lists, links, and media embedding.

---

## 📚 Topics Covered

### ✅ 1. What is HTML?

- HyperText Markup Language
- Standard language for creating web pages

### ✅ 2. Basic Document Structure

- `<!DOCTYPE html>` declaration
- `<html>`, `<head>`, and `<body>` tags
- Metadata with `<meta>` and `<title>`

### ✅ 3. HTML Elements, Tags, and Attributes

- Syntax and nesting
- Self-closing tags
- Global attributes (id, class, title, etc.)

### ✅ 4. Headings and Paragraphs

- `<h1>` to `<h6>` for headings
- `<p>` for paragraphs
- `<br>` for line breaks

### ✅ 5. Text Formatting

- `<strong>`, `<em>`, `<mark>`, `<sub>`, `<sup>`, `<del>`, `<ins>`, `<small>`, etc.

### ✅ 6. Links and Anchors

- `<a href="...">` for hyperlinks
- `target="_blank"` for new tab
- Email and phone links

### ✅ 7. Images

- `<img src="..." alt="...">`
- Best practices for accessibility
- Width/height attributes

### ✅ 8. Lists

- Ordered (`<ol>`) and unordered (`<ul>`)
- Nesting `<li>` elements

### ✅ 9. Comments

- `<!-- This is a comment -->`

### ✅ 10. Div and Span

- `<div>` for block-level containers
- `<span>` for inline text styling

---

## 🧪 Practice Challenges

### 📌 Challenge 1: Portfolio Page

Create a static HTML portfolio with:

- Your name in a heading
- A short bio paragraph
- A profile image
- List of skills or hobbies
- A link to your social media or GitHub

### 📌 Challenge 2: Recipe Page

- Recipe title (heading)
- Description paragraph
- Unordered list of ingredients
- Ordered list of cooking steps
- Image of the final dish

---

## ✅ What's Next?

# 📅 Day 2: Semantic HTML, Forms, Tables & Accessibility

This day focuses on structuring web content meaningfully using semantic HTML, creating complex forms, designing accessible tables, and implementing web accessibility best practices using ARIA.

---

## ✅ 1. Semantic HTML

Semantic elements clearly describe their meaning to both the browser and the developer.

### 🧱 Common Semantic Tags:

| Tag            | Purpose                                    |
| -------------- | ------------------------------------------ |
| `<header>`     | Represents the header of a section or page |
| `<nav>`        | Defines navigation links                   |
| `<main>`       | Main content area                          |
| `<section>`    | Thematic grouping of content               |
| `<article>`    | Independent, self-contained content        |
| `<aside>`      | Secondary content like sidebars            |
| `<footer>`     | Footer of a section or page                |
| `<figure>`     | Groups media and its caption               |
| `<figcaption>` | Caption for `<figure>` content             |

### ✅ Example:

````html
<main>
  <article>
    <header><h1>Blog Title</h1></header>
    <p>Blog content here...</p>
    <footer>Author: Mouna</footer>
  </article>
</main>

# 📅 Day 3: HTML Forms & Multimedia

Today’s focus is on two major areas in HTML:
- Creating **user-friendly and accessible forms**
- Embedding and customizing **multimedia** (audio, video, images)

---

## ✅ 1. HTML Forms (Review + Advanced Concepts)

HTML forms are essential for collecting user input. We’ll cover structured layout, validation, and accessibility enhancements.

### 🧾 Key Elements:
- `<form>`, `<input>`, `<textarea>`, `<select>`, `<button>`
- Grouping: `<fieldset>` and `<legend>`
- Accessibility: `label`, `aria-*`, `tabindex`

### ✅ Example:
```html
<form>
  <fieldset>
    <legend>Contact Info</legend>

    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required />

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" />

    <label for="interest">Area of Interest:</label>
    <select id="interest" name="interest">
      <option value="html">HTML</option>
      <option value="css">CSS</option>
      <option value="js">JavaScript</option>
    </select>

    <label for="message">Message:</label>
    <textarea id="message" name="message"></textarea>

    <button type="submit">Submit</button>
  </fieldset>
</form>
````

# 📅 Day 4: HTML Layout Techniques + Meta Tags + SEO

Today’s focus is on **structuring entire pages**, **using meta tags**, and **optimizing your site for search engines** (SEO).

---

## ✅ 1. HTML Layout Techniques

Proper layout improves readability, maintainability, and responsiveness.

### 🧱 Semantic Layout Tags:

| Tag         | Use Case                         |
| ----------- | -------------------------------- |
| `<header>`  | Site or section header           |
| `<nav>`     | Primary navigation               |
| `<main>`    | Main content section             |
| `<section>` | Related content block            |
| `<article>` | Independent content (blog, news) |
| `<aside>`   | Side content (ads, links, info)  |
| `<footer>`  | Site or section footer           |

### ✅ Example Page Layout:

```html
<body>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <a href="#projects">Projects</a>
      <a href="#about">About</a>
    </nav>
  </header>

  <main>
    <section id="projects">
      <h2>Projects</h2>
      <article>
        <h3>Weather App</h3>
        <p>Built with HTML, CSS, JS & OpenWeather API.</p>
      </article>
    </section>

    <aside>
      <h4>Skills</h4>
      <ul>
        <li>HTML5</li>
        <li>CSS3</li>
        <li>JavaScript</li>
      </ul>
    </aside>
  </main>

  <footer>
    <p>© 2025 Mouna MC</p>
  </footer>
</body>
```
