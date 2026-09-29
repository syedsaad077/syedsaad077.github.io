<h1 align="center">
  <br>
  <a href="https://syedsaad077.github.io/"><img src="assets/img/logo.png" alt="Syed Saad Hasan Portfolio" width="200"></a>
  <br>
  Syed Saad Hasan — Portfolio
  <br>
</h1>

<h4 align="center">My personal academic and professional portfolio website 🚀.</h4>

<p align="center">
  <a href="https://github.com/syedsaad077/SyedSaadHasan.github.io/stargazers">
    <img src="https://img.shields.io/github/stars/syedsaad077/SyedSaadHasan.github.io?style=flat&color=yellow" alt="Stars">
  </a>
  <a href="https://github.com/syedsaad077/SyedSaadHasan.github.io/issues">
    <img src="https://img.shields.io/github/issues/syedsaad077/SyedSaadHasan.github.io" alt="Issues">
  </a>
  <a href="https://syedsaad077.github.io/">
    <img src="https://img.shields.io/badge/Live-Portfolio-brightgreen?style=flat" alt="Live Portfolio">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=HTML5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white" alt="CSS3">
  <img src="https://shields.io/badge/JavaScript-F7DF1E?logo=JavaScript&logoColor=000&style=flat-square" alt="JavaScript">
</p>

<p align="center">
  <a href="https://syedsaad077.github.io/">🌐 View Live Portfolio</a> •
  <a href="https://github.com/syedsaad077/SyedSaadHasan.github.io/issues/new">🐛 Report Bug</a> •
  <a href="mailto:saadh3416@gmail.com">📧 Contact Me</a>
</p>

---

## 👤 About Me

Hi! I'm **Syed Saad Hasan**, a **Cybersecurity & Automation Specialist** based in New Delhi, India. I completed my B.Tech in Computer Science and Engineering at Jamia Hamdard (2026) and specialize in network security, security automation, AI workflow automation, and secure API integration.

I have hands-on experience building AI automation agents, security scanning pipelines, and backend microservices. My academic excellence was recognized by the U.S. Embassy in New Delhi through the prestigious English Access Microscholarship Program.

---

## ✨ Features

- 🎓 **Academic & Professional** — Showcases education, experience, projects, and achievements
- 📱 **Fully Responsive** — Works seamlessly on all screen sizes
- 🌙 **Dark Mode** — Toggle between light and dark themes
- 🌍 **Multi-Language** — Supports English and Turkish (easily extendable)
- ⚡ **Blazingly Fast** — Lightweight, no heavy frameworks
- 🎨 **Customizable** — Easy to personalize colors, content, and sections
- 🛡️ **Cybersecurity & Automation Focus** — Highlights my expertise in network security, AI automation, and DevSecOps workflow automation

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure & Markup |
| CSS3 | Styling & Animations |
| JavaScript | Interactivity & Logic |
| Bootstrap 5 | Responsive Layout |
| Font Awesome | Icons |

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/syedsaad077/SyedSaadHasan.github.io.git
   ```
2. Open `index.html` in your browser — no build tools required!

---

## 🌍 Multi-Language Support

To add a new language:

1. Add your language to `assets/js/languages.json` (ISO 3166 alpha-2 code):

   ```json
   "en": {
     "flag": "https://flagcdn.com/w20/us.png"
   },
   "de": {
     "flag": "https://flagcdn.com/w20/de.png"
   }
   ```

2. Add the `language` class and `data-` attributes to any element you want translated:

   ```html
   <p class="language" data-en="Hello" data-de="Hallo">Hello</p>
   ```

---

## ➕ Adding a New Section

Want to add a new section (e.g., `Publications`)? Here's how:

1. **Add a nav item** in `index.html`:
   ```html
   <li class="nav-item">
     <a class="nav-link" id="publications" href="#" data-en="Publications">Publications</a>
   </li>
   ```

2. **Add the content div** inside `id="section-content"`:
   ```html
   <div class="col-md-8 offset-md-1 mb-5" id="publicationsContent" style="display: none;">
     <!-- Your content here -->
   </div>
   ```

3. **Wire up navigation** in `assets/js/main.js`:
   ```javascript
   $('#publications').click(function(e) {
     if (!$(e.target).hasClass('active')) {
       clearActiveLinks();
       activateLink(e);
       clearActiveDivs();
       activateDiv('#publicationsContent');
     }
   });
   ```

---

## 📊 Google Analytics (Optional)

1. Go to [Google Analytics](https://analytics.google.com/) and create a new property.
2. Copy your **Measurement ID** (looks like `G-XXXXXXXXXX`).
3. Paste it into `assets/js/config.json`.

---

## 📬 Contact

| Channel | Details |
|---|---|
| 📧 Email | [saadh3416@gmail.com](mailto:saadh3416@gmail.com) |
| 💼 LinkedIn | [linkedin.com/in/saad3416](https://www.linkedin.com/in/saad3416/) |
| 🐙 GitHub | [github.com/syedsaad077](https://github.com/syedsaad077) |
| 🌐 Portfolio | [syedsaad077.github.io](https://syedsaad077.github.io/) |

---

## 📄 License

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

---

<p align="center">Made with ❤️ by <a href="https://github.com/syedsaad077">Syed Saad Hasan</a></p>
