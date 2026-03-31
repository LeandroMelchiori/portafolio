# Portafolio Personal - Leandro Melchiori

## Descripción del Proyecto

Este proyecto es un **Trabajo Práctico (TP)** correspondiente a la **Práctica Formativa Obligatoria 1 (PFO1)** de la carrera de Desarrollo Web del IFTS N.º 29. Consiste en una Landing Page de Portafolio Personal desarrollada únicamente con **HTML y CSS puro** (y JavaScript mínimo para interactividad), sin frameworks externos. El sitio presenta información personal, proyectos destacados, habilidades técnicas, películas favoritas y un formulario de contacto.

🌐 **URL GitHub Pages:** *(completar luego de publicar)*

---

## Checklist - Práctica Formativa Obligatoria 1

### Estructura del Proyecto:
- [x] Archivo `index.html` ubicado en la raíz.
- [x] Carpeta `css` que contiene el archivo `styles.css`.
- [x] Carpeta `img` para recursos gráficos.
- [x] Archivo `README.md` creado, que incluye una breve descripción del TP y este checklist.

### Repositorio y Publicación:
- [x] Repositorio en GitHub creado.
- [x] Proyecto subido al repositorio.
- [] Proyecto publicado utilizando Vercel.
- [] En el `README.md` se indica la URL de Vercel.

### Uso de Google Fonts:
- [x] Enlace a Google Fonts incluido en la sección `head` del HTML.
- [x] La tipografía importada se aplica en el sitio.
- [x] **¿Por qué elegiste esa fuente?**
  > Elegí **Inter** como fuente principal porque es una tipografía sans-serif diseñada específicamente para interfaces digitales: tiene excelente legibilidad en pantallas de alta densidad y comunica un perfil tech/profesional sin ser fría. Como fuente secundaria usé **JetBrains Mono** para etiquetas de código y tecnologías, reforzando la identidad de desarrollador.

### HTML:
- [x] El documento inicia con la declaración `DOCTYPE` y usa el atributo `lang="es"`.
- [x] Se han incluido las metaetiquetas obligatorias: `charset` y `viewport`.
- [x] Se ha definido un título descriptivo: *"Leandro Melchiori - Portafolio Personal"*.
- [x] Se han vinculado correctamente el archivo CSS y el enlace a Google Fonts.

**Secciones obligatorias en `main`:**
- [x] Barra de navegación (`nav`) presente con 5 enlaces: Sobre mí, Proyectos, Habilidades, Películas y Contacto.
- [x] Sección `#sobre-mi` con párrafo descriptivo e imagen de perfil con `alt`.
- [x] Sección `#proyectos` con 6 tarjetas de proyectos usando CSS Grid.
- [x] Sección `#habilidades` con tabla de tecnologías y lista de hobbies.
- [x] Sección `#contacto` con formulario: Nombre, Apellido, Email, Teléfono y botón submit.
- [x] Sección `#peliculas` con 3 películas favoritas (título, imagen y descripción).
- [x] Se han insertado al menos 4 comentarios explicativos en el código HTML.

### CSS:
- [x] Existe el archivo `styles.css` con estilos personalizados.
- [x] Se utilizan selectores basados en clases e identificadores (`.card`, `.btn`, `#tarjetas`, `#contacto`, etc.).
- [x] La tipografía importada desde Google Fonts se aplica correctamente en todos los elementos via `font-family: var(--font-main)`.

**Layout y Organización:**
- [x] El layout de la sección `#proyectos` usa **CSS Grid** con `grid-template-columns: repeat(auto-fill, minmax(17rem, 1fr))`.
- [x] **¿Qué ventajas encontraste al utilizar Flexbox o Grid?**
  > CSS Grid me permitió que las tarjetas se reorganicen solas según el ancho disponible sin necesidad de media queries específicas para cada breakpoint. Flexbox lo usé para alinear elementos internos (header, footer, hero). La combinación de ambas técnicas hace que el layout sea completamente fluido y responsive.

**Estilización de Componentes:**
- [x] Se han personalizado los estilos de tablas (`.skills-table`), botones (`.btn`), enlaces (`a`) y formularios (`.form-group input`).
- [x] Se han ajustado las dimensiones de imágenes y contenedores con unidades relativas: `%`, `rem`, `vh`, `min()`, `clamp()`.
- [x] Se ha implementado al menos una animación o transición.
- [x] **¿Qué animación o transición implementaste?**
  > Implementé múltiples transiciones: (1) **hover en tarjetas** con `translateY(-6px)` + `box-shadow` de color primario, dando sensación de elevación; (2) **zoom en imágenes** al hacer hover (`scale(1.04)`); (3) **transición del header** al hacer scroll, que agrega fondo con `backdrop-filter: blur`; (4) animación `fadeIn` en keyframes para la entrada suave de secciones. Las elegí porque refuerzan la interactividad sin distraer del contenido.

### Consideraciones Adicionales:
- [x] El diseño es responsivo: se adapta con media queries para 900px y 640px de ancho.
- [x] Se aplicaron buenas prácticas de accesibilidad: atributo `alt` en todas las imágenes, `aria-label` en iconos SVG y `for` en labels del formulario.
- [x] Se añadieron comentarios en el HTML describiendo la función de cada sección y mejoras futuras.
