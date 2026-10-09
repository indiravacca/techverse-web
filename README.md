# 🚀 TechVerse — Tienda de Tecnología Premium

## 📋 Descripción

**TechVerse** es un sitio web estático de una tienda de accesorios tecnológicos premium. El proyecto demuestra el uso de HTML semántico, CSS moderno con Flexbox y Grid, diseño responsivo con Media Queries, formularios funcionales con Formspree, y contenido multimedia integrado.

---

## ✨ Características

- **HTML Semántico**: Estructura dividida en `<header>`, `<nav>`, `<main>`, `<section>` y `<footer>`.
- **Formulario de Contacto**: Formulario funcional con campos de Nombre, Correo Electrónico y Mensaje, integrado con [Formspree](https://formspree.io/) para el envío de datos.
- **Estilos CSS Externos**: Archivo `styles.css` con estilos aplicados a Header, Footer, navegación, Google Fonts (Inter y Outfit) y propiedades de background (degradados, color, imagen).
- **Diseño Responsivo**:
  - **Flexbox**: Sección de Productos organizada en cards responsivas.
  - **CSS Grid**: Sección de Reseñas con distribución en grid.
  - **Media Queries**: Adaptación a pantallas de escritorio, tablet y móvil.
- **Contenido Multimedia**: Imágenes de productos, video embebido con `<iframe>` (YouTube) y galería de imágenes.
- **Navegación**: Lista desordenada `<ul>` con enlaces de navegación interna (Inicio, Productos, Reseñas, Media, Contacto).
- **Animaciones**: Micro-animaciones con Intersection Observer API para aparición al hacer scroll.

---

## 📁 Estructura del Proyecto

```
techverse-web/
├── index.html      ← Página principal con HTML semántico
├── styles.css      ← Hoja de estilos externa (Flexbox, Grid, Media Queries)
└── README.md       ← Este archivo
```

---

## 🛠️ Tecnologías Utilizadas

| Tecnología      | Uso                                           |
|-----------------|-----------------------------------------------|
| HTML5           | Estructura semántica del sitio                |
| CSS3            | Estilos, Flexbox, Grid, Media Queries         |
| Google Fonts    | Tipografías Inter y Outfit                    |
| Formspree       | Manejo del envío del formulario de contacto   |
| JavaScript      | Menú móvil, scroll activo, animaciones        |
| YouTube Embed   | Video embebido con iframe                     |

---

## 🚀 Cómo Usar

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/techverse-web.git
   ```

2. **Abrir en Visual Studio Code:**
   - Abre la carpeta `techverse-web` con VS Code.
   - Instala la extensión **Live Server** si no la tienes.
   - Haz clic derecho en `index.html` → **"Open with Live Server"**.

3. **O simplemente** abre `index.html` directamente en tu navegador.

---

## 🌐 Despliegue

### GitHub Pages
1. Subi el proyecto a un repositorio público de GitHub.
2. Ve a **Settings → Pages**.
3. En **Source**, selecciona la rama `main` y carpeta `/ (root)`.
4. GitHub generará la URL: `https://tu-usuario.github.io/techverse-web/`

### Netlify (alternativa)
1. Ve a [netlify.com](https://www.netlify.com/) e inicia sesión.
2. Arrastra la carpeta `techverse-web` al panel de Netlify.
3. Netlify generará una URL pública automáticamente.

---

## 📬 Formulario de Contacto

El formulario utiliza **Formspree** para procesar los envíos. Para personalizarlo:

1. Crea una cuenta en [formspree.io](https://formspree.io/).
2. Crea un nuevo formulario y copia tu endpoint.
3. Reemplaza la URL en el atributo `action` del `<form>` en `index.html`:
   ```html
   <form action="https://formspree.io/f/TU-ID" method="POST">
   ```

---

## 📱 Responsivo

El sitio se adapta a tres breakpoints principales:

| Breakpoint    | Dispositivo       | Comportamiento                          |
|---------------|-------------------|-----------------------------------------|
| `> 1024px`    | Desktop           | Layout completo, grid de 3 columnas     |
| `768–1024px`  | Tablet            | Grid de 2 columnas, contacto apilado    |
| `< 768px`     | Móvil             | Una columna, menú hamburguesa           |
| `< 480px`     | Móvil pequeño     | Fuente reducida, layout vertical        |

---

## 📝 Licencia

Este proyecto fue creado con fines educativos.

---

## 👤 Autora

**Indira Vaca**

Proyecto de desarrollo web.
