# Metal Craft Solutions — Landing Page

**Precision Industrial Fabrications**

## Estructura del Proyecto

```
metalcraft/
├── index.html          ← Página principal
├── css/
│   └── style.css       ← Todos los estilos
├── js/
│   └── main.js         ← JavaScript (animaciones, tabs, form)
├── images/             ← Carpeta para tus imágenes (vacía, agregar fotos aquí)
└── README.md           ← Este archivo
```

## Cómo subir a GitHub Pages

1. Crea un repositorio nuevo en GitHub (ej: `metalcraft-web`)
2. Sube todos estos archivos al repositorio
3. Ve a **Settings → Pages**
4. En "Source" selecciona `main` branch y carpeta `/ (root)`
5. Haz clic en **Save**
6. Tu sitio estará en: `https://tu-usuario.github.io/metalcraft-web/`

## Cómo agregar tus imágenes

Coloca tus imágenes en la carpeta `/images/` y reemplaza los placeholders en `index.html`.

### Para la sección "Nosotros":
```html
<!-- Reemplaza el div .about-placeholder con: -->
<img src="images/foto-taller.jpg" alt="Metal Craft Solutions" style="width:100%;height:100%;object-fit:cover;">
```

### Para la galería:
```html
<!-- Reemplaza el div .gallery-placeholder con: -->
<img src="images/proyecto-1.jpg" alt="Proyecto Offshore" style="width:100%;height:100%;object-fit:cover;">
```

## Personalización

- **Colores**: edita las variables CSS en `:root` al inicio de `style.css`
- **Teléfono**: busca `529381104721` en `index.html` y reemplázalo
- **Instagram**: busca `metal_craft_solutions_` y actualiza el handle
- **Textos**: todo el contenido está en `index.html`, bien comentado por secciones

## Tecnologías

- HTML5 semántico
- CSS3 (variables, grid, flexbox, animaciones)
- JavaScript vanilla (sin dependencias)
- Google Fonts (Bebas Neue + Barlow)
- 100% estático — compatible con GitHub Pages
