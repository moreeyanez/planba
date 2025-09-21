# 📌 PlanBA

## 🌟 Descripción
**PlanBA** es un sitio web que busca resolver la clásica pregunta: *¿qué hacemos este finde?*  
La idea surgió a partir de una problemática familiar: mis padres siempre terminan haciendo lo mismo porque no encuentran fácilmente nuevas propuestas en Buenos Aires.  

Este sitio ofrece una recopilación de actividades para realizar en la ciudad, tanto de día como de noche. El objetivo es brindar una solución práctica, organizada y atractiva para que cualquier persona pueda descubrir nuevos planes en la ciudad mágica de Buenos Aires.  

---
## ✨ Características Principales
- Accesibilidad
  - Etiquetas semánticas: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`.
  - Encabezados jerárquicos: un solo `<h1>` por página, `<h2>`/`<h3>` para secciones y subsecciones.
  - Atributos ARIA en componentes dinámicos (dropdowns, menús, enlaces).
  - alt descriptivos en las imágenes.
- SEO & Metadatos
  - `<title>` claros y referenciales
  - <meta name="description"> y <meta name="keywords"> específicos por página.
  - Uso de URLs amigables y anclas consistentes.
- Rendimiento
  - Imágenes optimizadas a WebP con peso < 1 MB.
- Responsive Design
  - Meta viewport configurado (width=device-width, initial-scale=1.0).
  - Grid de Bootstrap 5 (row y clases col-6 col-sm-4 col-md-3).
  - Adaptación de menús y botones para pantallas móviles.
- Arquitectura de Estilos
  - SCSS modular: variables, mixins, componentes y páginas separadas.
  - Nomenclatura kebab-case y metodología BEM en clases CSS.

---

## 🎨 Wireframe
El diseño inicial del proyecto está basado en un **wireframe** que marca la estructura de las secciones principales del sitio:  
- **Inicio**: Categorías de actividades + actividades destacadas.  
- **Actividades**: Listado filtrado por categoría.  
- **Recomendaciones**: Opiniones y experiencias de usuarios.  
- **Sobre Nosotros**: Breve descripción del propósito del sitio.  
- **Contacto**: Formulario para enviar experiencias y sugerencias.  

https://drive.google.com/file/d/1r7sfpTnaPTlc3h4W5vF9UjImYJmEhAh_/view?usp=sharing 

---

## ⚙️ Tecnologías utilizadas
- **HTML5** → estructura del contenido.  
- **CSS3 (Flexbox & Grid)** → estilos y diseño responsivo.  
- **Google Fonts (Raleway + secundaria)** → tipografía.
- **Sass/SCSS** → preprocesador modular con:
  - Variables (_variables.scss) para colores, tipografías y breakpoints
  - Mixins (_mixins.scss) para funciones reutilizables
  - Partials (_base.scss, _componentes.scss, _pages.scss) para reset, componentes y estilos específicos por página
  - Nested rules y BEM para mantener el CSS organizado y escalable
- **Bootstrap 5** → utilidades, grid y componentes preconstruidos

---

## 🚀 Objetivo académico
Este proyecto forma parte de la cursada de **Desarrollo Web en CoderHouse**, cumpliendo con las consignas de cada pre-entrega.   

---

## 📂 Estructura del proyecto
```bash
PlanBA/
├── assets/
│   └── imagenes    # Imágenes convertidas a WebP y comprimidas (<1 MB)
├── css/
│   ├── estilos.css            # CSS compilado desde SCSS
│   ├── estilos.css.map
│   └── styles.css             # Archivo previo a la implementación de scss
├── scss/
│   ├── _base.scss             # Reset y reglas globales
│   ├── _variables.scss        # Colores, tipografía y breakpoints
│   ├── _mixins.scss           # Funciones y mixins reutilizables
│   ├── _componentes.scss      # Estilos de tarjetas, botones y utilidades
│   ├── _pages.scss            # Reglas específicas para cada página
│   └── estilos.scss           # Archivo principal de scss
├── pages/
│   ├── actividades.html       # Listado de actividades con categorías y tarjetas
│   ├── contacto.html          # Formulario de contacto
│   ├── gracias.html           # Página de agradecimiento post-formulario
│   ├── recomendaciones.html   # Sugerencias de recorridos
│   └── sobreNosotros.html     # Información del proyecto y autoría
├── index.html                 # Landing page
└── README.md                  # Documentación del proyecto
```
## 👩‍💻 Autor
Creado por **Morena Yañez**  
📚 Proyecto académico - Curso Desarrollo Web (CoderHouse)
