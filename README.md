# La Cueva del Pirata - Página Web

Proyecto de una página web responsiva desarrollada con **TailwindCSS**, diseñada para representar el bar "La Cueva del Pirata". Incluye formularios de valoración, reseñas de usuarios y un carrusel de imágenes.

---

## Índice

- [Descripción](#descripción)
- [Tecnologías](#tecnologías)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Instalación y Uso](#instalación-y-uso)
- [Accesibilidad](#accesibilidad)
- [Responsive Design](#responsive-design)
- [Características](#características)
- [Mejoras Potenciales](#mejoras-potenciales)
- [Autores](#autor)

---

## Descripción

El proyecto consiste en una página web que muestra la oferta de cócteles de La Cueva del Pirata, junto con un sistema de reseñas en el que los usuarios pueden valorar su experiencia y dejar comentarios. Además, se incluye un carrusel de imágenes del local y un menú de navegación simple y accesible.

---

## Tecnologías

- **HTML5**
- **TailwindCSS** (CDN)
- **JavaScript** (para el menú de navegación y carrusel)
- **Font Awesome** (para iconos sociales)
- **Google Maps** (enlaces directos)

---

## Estructura del Proyecto

```
├── index.html                (Página de inicio)
├── cocteles.html             (Lista de cócteles)
├── mojito_corsario.html      (Ejemplo de detalle de cóctel)
├── contacto.html             (Formulario de contacto)
├── resenhas.html             (Reseñas de clientes)
├── img/                      (Imágenes del sitio)
│   ├── logo.webp
│   ├── imagen-home.webp
│   └── ... (otros recursos gráficos)
└── css/
    └── styles.css            (Archivos de estilos adicionales si aplica)
```

---

## Instalación y Uso

1. Clonar el repositorio o descargar los archivos.
2. Abrir `index.html` en cualquier navegador web.
3. No es necesario instalar dependencias ya que TailwindCSS se utiliza a través de CDN.

---

## Accesibilidad

- **Enlaces y botones**: Añadido `focus:outline-none` y `focus:ring-2 focus:ring-white` para mejorar el enfoque visual en la navegación por teclado.
- **Etiquetas ARIA**: Se han aplicado `aria-label` en los botones y enlaces relevantes.
- **Textos Alternativos**: Las imágenes incluyen atributos `alt` descriptivos.

---

## Responsive Design

- La página es **Mobile First**, con adaptaciones a resoluciones de tablet y escritorio.
- Se utiliza `flex` y `grid` para estructurar el contenido, con clases de TailwindCSS como `md:` y `lg:` para gestionar las diferentes vistas.
- Las reseñas y formularios se adaptan con `max-w-4xl` y `w-full` para mantener la consistencia en tamaños.

---

## Características

- **Formulario de valoración** con estrellas interactivas y subida de imagen.
- **Carrusel de imágenes** del local, con botones para cambiar de slide.
- **Sistema de reseñas** visualmente destacadas, que muestra perfiles de usuario, valoración y comentario.
- **Menú responsive** con botón hamburguesa en vista móvil.
- **Footer informativo** con redes sociales y datos de contacto.

---

## Mejoras Potenciales

- Añadir validación de formularios (por ejemplo, nombre obligatorio).
- Sustituir el `input type="file"` por una integración real de subida de imágenes.
- Implementar una base de datos para guardar y recuperar reseñas dinámicamente.
- Agregar animaciones suaves con `@tailwindcss/forms` o `Framer Motion` si se implementa en React.

---

## Autores

**Diego Coello, Ana Iglesias y Paula Vargas**  
La Cueva del Pirata - Proyecto Frontend de Usabilidad con TailwindCSS  
Módulo: Diseño de Interfaces Web
2º CS Desarrollo de Aplicaciones Web, CPR Liceo La Paz, curso 2024-25
