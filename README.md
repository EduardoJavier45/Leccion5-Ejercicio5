# Proyecto Bootstrap - Lección 5 Ejercicio 5

## Descripción del Proyecto

Este proyecto consiste en dos páginas web desarrolladas con el framework Bootstrap 5.3.2, diseñadas para demostrar la creación de interfaces responsivas y componentes avanzados.

---

## Estructura del Proyecto

```
Leccion5-Ej5/
├── README.md          # Documentación del proyecto
├── pagina1.html       # Primera página (estructura básica)
└── index.html         # Segunda página (componentes avanzados)
```

---

## Página 1 - Estructura Básica (`pagina1.html`)

### Características:
- **Encabezado con color de fondo**: Cabecera con fondo azul (bg-primary) y texto blanco
- **Título**: "Página Bootstrap"
- **Subtítulo**: "Esta página es responsiva"
- **Diseño de 3 columnas**:
  - Columna 1, 2 y 3 con títulos descriptivos
  - Contenido Lorem Ipsum en cada columna
- **Responsividad completa**: Las columnas se adaptan automáticamente
  - En pantallas grandes (≥768px): 3 columnas horizontales
  - En pantallas pequeñas (<768px): Columnas apiladas verticalmente

### Tecnologías utilizadas:
- HTML5
- Bootstrap 5.3.2 (CSS y JS)
- Sistema de Grid de Bootstrap (col-12 col-md-4)

---

## Página 2 - Componentes Avanzados (`index.html`)

### Características:

#### 1. **Navbar (Menú de Navegación)**
- Diseño oscuro (navbar-dark bg-dark)
- Menú responsive con botón hamburguesa
- Opciones del menú:
  - Carrusel (enlace a la sección del carrusel)
  - Inicio (activo)
  - Enlace
  - Deshabilitado
- **Barra de búsqueda** en el extremo derecho con:
  - Campo de input
  - Botón de búsqueda

#### 2. **Carrusel (Slider)**
- 3 diapositivas con transición automática
- Imágenes aleatorias de Lorem Picsum (1200x500px)
- Indicadores de navegación en la parte inferior
- Controles de navegación (anterior/siguiente)
- Captions con:
  - Título
  - Descripción
  - Botón principal en cada diapositiva

#### 3. **Sección de Columnas con Imágenes**
- 3 tarjetas (cards) con diseño uniforme
- Cada card contiene:
  - Imagen responsive (400x300px)
  - Título
  - Párrafo descriptivo con texto Lorem Ipsum
- Diseño responsivo:
  - Desktop: 3 columnas horizontales
  - Móvil: Columnas apiladas

#### 4. **Footer (Pie de página)**
- Fondo oscuro con texto blanco
- Copyright 2025
- Enlace "Volver hacia arriba" con símbolo ↑

### Tecnologías utilizadas:
- HTML5
- Bootstrap 5.3.2 (CSS y JS con Popper)
- Imágenes de Lorem Picsum
- Componentes Bootstrap:
  - Navbar
  - Carousel
  - Cards
  - Grid System
  - Forms

---

## Requisitos Técnicos

### Dependencias:
- Bootstrap 5.3.2 (cargado desde CDN)
  - CSS: `bootstrap.min.css`
  - JS: `bootstrap.bundle.min.js` (incluye Popper)

### Navegadores compatibles:
- Chrome (última versión)
- Firefox (última versión)
- Safari (última versión)
- Edge (última versión)

---

## Características de Responsividad

### Breakpoints utilizados:
- **col-12**: Ocupa todo el ancho en pantallas pequeñas
- **col-md-4**: 3 columnas (33.33% cada una) en pantallas medianas y grandes (≥768px)

### Componentes responsivos:
- Navbar colapsable con menú hamburguesa
- Grid system adaptable
- Imágenes que escalan automáticamente (w-100)
- Cards con altura uniforme (h-100)
- Carousel con controles táctiles

---

## Cómo visualizar el proyecto

1. Abrir `pagina1.html` en un navegador para ver la estructura básica
2. Abrir `index.html` en un navegador para ver los componentes avanzados
3. Redimensionar la ventana del navegador para probar la responsividad

---

## Autor

Eduardo Javier Perez Espindola

## Fecha

6 de diciembre de 2025

## Framework

Bootstrap 5.3.2
