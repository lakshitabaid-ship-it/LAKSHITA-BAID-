# Lakshita Baid — Portfolio Website

A simple multi-page personal portfolio built with **HTML and CSS only**.

## Pages
- `index.html` — Home
- `about.html` — About
- `education.html` — Education
- `experience.html` — Experience and Partnership Cell
- `speaking.html` — Speaking and Leadership
- `projects.html` — Projects
- `contact.html` — Contact

## Run locally
Open `index.html` in a web browser. No build tools, package installation, or server are required.

## Add your portrait later
1. Add your photograph to `assets/images/` and name it `portrait.jpg`.
2. In `index.html`, replace the `<div class="portrait-placeholder"> ... </div>` block with:
   `<img class="portrait" src="assets/images/portrait.jpg" alt="Portrait of Lakshita Baid">`
3. Add this CSS to `style.css`:
   `.portrait { width: 100%; max-width: 380px; min-height: 390px; object-fit: cover; border-radius: 48% 48% 22px 22px; }`

## Technology
- HTML5
- CSS3
- No JavaScript
- No JavaScript libraries or frameworks

The Google Fonts import is optional; the site falls back to system fonts if the fonts cannot load.
