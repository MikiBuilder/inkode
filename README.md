<div align="center">

```
██╗███╗   ██╗██╗  ██╗ ██████╗ ██████╗ ███████╗
██║████╗  ██║██║ ██╔╝██╔═══██╗██╔══██╗██╔════╝
██║██╔██╗ ██║█████╔╝ ██║   ██║██║  ██║█████╗  
██║██║╚██╗██║██╔═██╗ ██║   ██║██║  ██║██╔══╝  
██║██║ ╚████║██║  ██╗╚██████╔╝██████╔╝███████╗
╚═╝╚═╝  ╚═══╝╚═╝  ╚═╝ ╚═════╝ ╚═════╝ ╚══════╝
```

**Editorial portfolio template — one file, no build tools.**

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-0e0e0e?style=flat-square)

</div>

---

## ✦ What is this?

A single-file portfolio template built with raw HTML, CSS and JavaScript. No frameworks, no npm, no build step — just open `index.html` and it works.

Designed with an **editorial aesthetic**: expressive typography, ink-on-paper palette, smooth GSAP animations and a custom cursor. The kind of portfolio that doesn't look like every other portfolio.

---

## ✦ Features

| | |
|---|---|
| 🎬 | Page loader with slide-out transition |
| 🖱️ | Custom cursor with magnetic hover effect |
| 📜 | Infinite marquee ticker |
| 🎞️ | GSAP scroll-triggered reveals |
| 🔢 | Parallax hero background number |
| 📱 | Fully responsive — mobile first |
| ⚡ | Zero dependencies, zero build |
| 🎨 | 4 CSS variables to retheme everything |

---

## ✦ Preview

> Deploy on GitHub Pages and your live URL will be:
> `https://your-username.github.io/inkode`

---

## ✦ Quick start

```bash
# 1. Clone
git clone https://github.com/mikibuilder/inkode.git

# 2. Open — that's it
open index.html
```

---

## ✦ Customize

### Name & initials
```html
<a href="#hero" class="nav-logo">YN</a>          <!-- your initials -->
<span id="loader-name">YOUR NAME</span>           <!-- full name in loader -->
<span>© 2026 Your Name</span>                     <!-- footer -->
```

### Hero headline
```html
<h1 class="hero-title">
  <span>Creative</span>        <!-- line 1 — black -->
  <em>Developer</em>           <!-- line 2 — red italic -->
  <span>& Designer</span>      <!-- line 3 — black -->
</h1>
```

### Add a project
```html
<a href="https://your-project.com" class="project-item">
  <span class="project-num">05</span>
  <div class="project-info">
    <h3>Project Name</h3>
    <p>Category · Stack · Year</p>
  </div>
  <span class="project-arrow">→</span>
</a>
```

### Retheme with 4 variables
```css
:root {
  --ink:    #0e0e0e;   /* text & dark elements  */
  --paper:  #f0ece3;   /* background            */
  --accent: #c8f000;   /* hover fills & links   */
  --red:    #e63a2e;   /* hero italic line      */
}
```

---

## ✦ Deploy to GitHub Pages

```
1. Push index.html to a public repo
2. Settings → Pages → Branch: main → / (root) → Save
3. Done → https://your-username.github.io/inkode
```

---

## ✦ Stack

- **HTML5** — semantic markup
- **CSS3** — custom properties, grid, clamp(), keyframes
- **JavaScript** — vanilla, no dependencies
- **[GSAP 3](https://gsap.com)** — ScrollTrigger, timeline animations (CDN)
- **[Google Fonts](https://fonts.google.com)** — Bebas Neue · DM Serif Display · DM Mono

---

## ✦ License

MIT — use it, modify it, ship it. Keep the credit somewhere.

---

<div align="center">
  <sub>Built with obsessive attention to detail.</sub>
</div>

