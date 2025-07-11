# Pastelería Gluten Free

Proyecto para Coderhouse – Entrega 3  
Sitio web de una pastelería 100% libre de gluten. Maquetado con Bootstrap 5 y estilos personalizados con SASS/SCSS.

## 🚀 Demo

🔗 [Sitio publicado](https://fionaamina.github.io/pasteleria-glutenfree/)

## 📁 Estructura del proyecto

pasteleria-glutenfree/
│
├── index.html
├── productos.html
├── contacto.html
├── css/
│ └── estilos.css # Compilado desde main.scss
├── scss/
│ ├── _variables.scss # Variables reutilizables
│ ├── _mixins.scss # Mixins de media queries y animaciones
│ ├── _base.scss # Estilos globales de body, tipografías, etc.
│ ├── _layout.scss # Estructura de secciones (main, footer, etc.)
│ ├── _components.scss # Botones, animaciones, tarjetas
│ └── main.scss # Archivo principal que importa los parciales
└── .gitignore

## 🛠 Tecnologías utilizadas

- HTML5 semántico
- SCSS/SASS con estructura modular
- Bootstrap 5 (CDN)
- Git y GitHub para control de versiones
- GitHub Pages para despliegue

## ✨ Funcionalidades destacadas

- Diseño **responsive** con Bootstrap Grid y media queries SASS (`@mixin mobile`)
- Botones generados dinámicamente con `@each` a partir de variables
- Estilos personalizados con `@variables`, `@extend`, `@include`
- **Animaciones suaves** en tarjetas con `@keyframes`
- Organización modular con `main.scss` y partials por categoría
- Código limpio, indentado, semántico y accesible

## 💻 Cómo levantar el proyecto localmente

1. Clonar el repositorio:
```bash
git clone https://github.com/fionaamina/pasteleria-glutenfree.git
cd pasteleria-glutenfree
