# Frontend S1 - Tienda Gamer

Actividad formativa correspondiente a la Semana 1 de Frontend, enfocada en la creación de la estructura básica de una página web utilizando HTML.

El proyecto simula la página principal de una tienda de videojuegos y utiliza etiquetas HTML semánticas para organizar su contenido.

## Estructura del proyecto

```text
frontend-s1/
├── img/
│   ├── silksong.jpg
│   ├── thewitcher.jpg
│   └── masseffect.jpg
├── index.html
├── README.md
└── .gitignore
```

## Elementos HTML utilizados

La página fue construida utilizando HTML5 e incluye:

* Estructura básica mediante `<!DOCTYPE html>`, `<html>`, `<head>` y `<body>`.
* Definición del idioma del documento mediante `lang="es"`.
* Metadatos para codificación UTF-8 y visualización en distintos dispositivos.
* `<header>` para el encabezado principal de la tienda.
* `<nav>` para el menú de navegación.
* `<main>` para identificar el contenido principal.
* `<section>` para organizar la sección de productos destacados.
* `<footer>` para la información de contacto.
* Encabezados `<h1>`, `<h2>` y `<h3>` para establecer una jerarquía de contenido.
* Párrafos `<p>` para las descripciones.
* Listas `<ul>` y `<li>` para organizar la navegación y los productos.
* Imágenes `<img>` con atributo `alt` para describir su contenido.
* Enlaces `<a>` para navegación interna, correo electrónico y acceso a un sitio externo.

## Navegación

El menú permite navegar dentro de la misma página utilizando identificadores:

* **Inicio:** dirige al contenido principal.
* **Productos:** dirige a la sección de productos destacados.
* **Contacto:** dirige al pie de página con la información de contacto.

## Productos destacados

La página presenta tres videojuegos:

* Hollow Knight: Silksong
* The Witcher 3: Wild Hunt
* Mass Effect Legendary Edition

Cada producto incluye un título, una imagen y una breve descripción.

## Validaciones realizadas

Durante el desarrollo se realizaron las siguientes comprobaciones:

* Visualización y pruebas locales mediante **Live Server**.
* Prueba de funcionamiento de los enlaces internos de Inicio, Productos y Contacto.
* Formateo del documento HTML mediante las herramientas de Visual Studio Code.
* Validación mediante la extensión **html-validate** de Visual Studio Code, sin problemas detectados.
* Validación final mediante **W3C Nu HTML Checker**, sin errores.
* Revisión de la estructura semántica y de los atributos `alt` utilizados en las imágenes.

## Herramientas utilizadas

* Visual Studio Code
* HTML5
* Live Server
* html-validate
* W3C Nu HTML Checker
* Git
* GitHub
