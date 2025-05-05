<!-- =====================================================================================
💼 HTML Final #1:
Client brief: “My Personal Webspace”
===================================================================================== -->

<!--
🧠 Project Overview
You’ve been contracted as a Junior Front-End Developer to build a personal website based on precise client specifications.

✅ Focus: Semantic HTML, technical accuracy.
❌ Not a design or content-writing task — all content is provided.

Your mission: Implement the HTML perfectly, using everything you’ve learned.
======================================================================================

-->

<!--

🧩 Concepts Covered

- HTML anatomy: <!DOCTYPE>, <html>, <head>, <body>
- Semantic elements: <header>, <nav>, <main>, <footer>, <article>, <section>, <aside>
- Page title and structure
- Text elements: <h1>–<h6>, <p>, <br>, <div>, whitespace and indentation
- Lists: <ul>, <ol>
- Links: absolute, relative, anchor links, open in new tab
- Attributes: href, src, alt, target, required, etc.
- Tables: <thead>, <tbody>, <tfoot>, colspan, rowspan, borders
- Forms: <label>, input types, validation, required fields
- Media: <img>, <audio>, <video>, <figure>, <figcaption>, <iframe>
- CSS basics: inline or internal styling
- # Comment syntax

-->

<!--

📁 Required Folder Structure

my-personal-webspace/
├── index.html
├── portfolio.html
├── contact.html
└── assets/
├── images/
├── media/
└── css/
======================================================================================
-->

<!--

📝 Page 1 — index.html (Homepage)

Tasks:

- Proper HTML structure (<!DOCTYPE html>, <html lang="en">, etc.)
- <head>:
  - <meta charset="UTF-8">
  - <title>My Personal Webspace</title>
- <header>:
  - <h1>Jane Coder</h1>
  - <p>Front-End Developer in Training</p>
  - <nav> with 3 links:
    - Home → index.html
    - Portfolio → portfolio.html
    - Contact → contact.html
- <main>:
  - <section id="about-me">
    - <h2>About Me</h2>
    - Paragraph about learning HTML/CSS
    - <img> with src="assets/images/profile.jpg" and proper alt text
    - <div> containing:
      - <ol>: Learning goals
      - <br>
      - <ul>: Favorite tools
    - <aside>: Fun fact
    - <figure>:
      - <img> + <figcaption>: Screenshot of my first webpage
    - <video controls>:
      - source: assets/media/intro.mp4
- <footer>:
  - <p>© 2025 Jane Coder. All rights reserved.</p>
  - Internal anchor link to bottom (<a href="#bottom">Go to bottom</a>)
  - External link: MDN Web Docs (target="_blank")
  - <div id="bottom"></div>
- # Add an HTML comment at the bottom.
  -->

<!--

📝 Page 2 — portfolio.html (Projects)

Tasks:

- Reuse the same <header> and <nav>.
- <main>:
  - <h2>My Projects</h2>
  - <table border="1">:
    - <thead>: Column titles (Project Name, Description, Tools, Status)
    - <tbody>:
      - At least 3 project rows (create fake data)
      - 1 row using colspan
      - 1 row using rowspan
    - <tfoot>: Summary row
  - Two <figure> elements:
    - Weather app image + caption
    - Portfolio preview image + caption
  - Embed a video:
    - Use either an <iframe> (YouTube) or <video> (local file)
  - <aside>: Tip about organized code
- # Add an HTML comment at the bottom.
  -->

<!--

📝 Page 3 — contact.html (Contact Form)

Tasks:

- <form> inside <main>, wrapped in <article>.
- Proper <label for=""> and matching id attributes.
- Required fields:
  - Full Name (text, required, minlength=3)
  - Email Address (email, required)
  - Password (password, required, pattern=".{6,}")
  - Age (number, min=13, max=120)
  - Satisfaction (range, 0–10)
  - Message (<textarea>, maxlength=500)
  - Reason for Contact (<select>)
  - How did you find me? (<datalist>)
  - Preferred Contact Method (radio buttons: Email, Phone)
  - Subscribe to (checkboxes: News, Events)
- Submit button with value: "Send Message"
- # Add an HTML comment at the bottom.
  -->

<!--

🧪 Final Touches

- Validate your HTML via https://validator.w3.org
- Check your indentation, whitespace, and structure
- Make sure every file looks polished; ask AI for Feedback.
-->
<!--
✅ Submission Instructions
- Folder name: html-final-1-my-personal-webspace
- Upload to GitHub
- # Deadline: 18.04.2025
  -->
