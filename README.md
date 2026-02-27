# Portfolio Template

Plantilla de portfolio personal. Diseño editorial, tipografía expresiva y animaciones fluidas con GSAP. Un solo archivo `index.html` — sin build, sin dependencias locales.

---

## Vista previa en GitHub Pages

**Settings → Pages → Branch: main → / (root) → Save**

URL: `https://tu-usuario.github.io/nombre-repositorio`

---

## Qué cambiar

### 1. Tu nombre
Busca `YOUR NAME` y `YN` en el HTML:
```html
<a href="#hero" class="nav-logo">YN</a>
<span id="loader-name">YOUR NAME</span>
<span>© 2026 Your Name</span>
```

### 2. Hero
```html
<span>Creative</span>
<em>Developer</em>        ← línea en rojo cursivo
<span>& Designer</span>
```

### 3. Proyectos
```html
<a href="URL-DEL-PROYECTO" class="project-item">
  <span class="project-num">01</span>
  <div class="project-info">
    <h3>Nombre del proyecto</h3>
    <p>Categoría · Tecnología · Año</p>
  </div>
  <span class="project-arrow">→</span>
</a>
```

### 4. Contacto
```html
<a href="mailto:hello@yourname.com" class="contact-email">
  hello@yourname.com
</a>
<li><a href="https://github.com/TU-USUARIO">GitHub</a></li>
<li><a href="https://linkedin.com/in/TU-USUARIO">LinkedIn</a></li>
```

### 5. Colores
```css
:root {
  --ink:    #0e0e0e;   /* negro principal */
  --paper:  #f0ece3;   /* fondo crema */
  --accent: #c8f000;   /* verde lima */
  --red:    #e63a2e;   /* cursiva hero */
}
```

---

## Subir a GitHub Pages

1. Crea repositorio en GitHub (**público** para Pages gratis)
2. Sube `index.html`
3. **Settings → Pages → Branch: main → / (root) → Save**
4. En ~1 minuto disponible en `https://tu-usuario.github.io/nombre-repo`

---

## Stack
- HTML5 + CSS3 + JS vanilla
- GSAP 3 (CDN)
- Google Fonts: Bebas Neue, DM Serif Display, DM Mono
