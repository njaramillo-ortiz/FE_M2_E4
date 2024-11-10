# FrontEnd - Ejercicio 4 (Modulo 2)

Este proyecto tiene como objetivo realizar mejoras a la página del hospital desarrollada en los ejercicios 1-3, aplicando SASS y Bootstrap.

Para mayor claridad, decidimos realizar este ejercicio desde cero y luego integrar parte del contenido realizado por cada integrante del equipo en los ejercicios anteriores, además de dividir el trabajo por páginas y secciones semánticas (header, footer, etc).

## Equipo

- [Denisse Rossel - @Byskachita](https://github.com/Byskachita)
- [Catherine Rebolledo - @cathy-98](https://github.com/cathy-98)
- [Nicolás Jaramillo - @njaramillo-ortiz](https://github.com/njaramillo-ortiz)

## Instrucciones de uso

Clonar el repositorio desde GitHub, o en su defecto descargar los contenidos como zip.

Luego, abrir `index.html` en su navegador favorito.

## Estructura del proyecto

    ├── /css                 # Archivos css preprocesados con SASS
    ├── /img                 # Imágenes
    ├── /js                  # Librerías javascript
    ├── /styles              # SASS con estructura 7-1, usando solo carpetas relevantes
    ├──── /abstracts         # Variables y mixins
    ├──── /base              # Estilos base / generales
    ├──── /layout            # Estilos para estructuras semanticas
    ├──── /pages             # Estilos para paginas especificas
    ├──── /vendors           # Estilos de terceros incluidos (bootstrap)
    ├──── main.scss          # Contiene todas las referencias de SASS
    ├── index.html           # Página de inicio
    ├── team.html            # Página del equipo médico
    ├── contact.html         # Página de contacto
    └── README.md            # Ud. se encuentra aqui

## Modularización SASS

Se utilizaron 5 de las 7 carpetas sugeridas en la estructura 7-1: abstracts, base, layout, pages y vendors.

- `abstracts` incluye archivos para las variables y mixins del proyecto.
- `base` incluimos un archivo base que contiene estilos de uso general.
- `layout` incluye archivos que definen los estilos para el header, footer, grid y navbar del sitio.
- `pages` incluye un archivo para cada página del sitio: index, team y contact.
- `vendors` incluye los estilos de Bootstrap.

Se implementó Sass para modularizar los estilos y hacer el código más mantenible y fácil de entender. Se organizaron los estilos en archivos específicos:

Variables: Se crearon variables de colores, tamaños de fuente y otros valores reutilizables, lo que facilita los cambios globales en el sitio sin tener que buscar y reemplazar valores en todo el código.

Mixins: Se utilizaron mixins para reutilizar bloques de código, como el borde redondeado para las tarjetas. Esto mejora la eficiencia y mantiene el código

## Personalización Bootstrap

    En este proyecto, Bootstrap se utilizó principalmente para gestionar la grilla de diseño responsivo. Las clases de la grid system de Bootstrap ayudaron a dividir el contenido en columnas y aseguraron que el sitio fuera adaptable a diferentes tamaños de pantalla.

Aunque se usó Bootstrap para la parte de la grilla, se evitó el uso del resto de las clases de diseño de Bootstrap. En su lugar, se personalizó el resto del proyecto con SASS, lo que permitió un mayor control sobre los estilos y la apariencia.

## Footer en Todo el Proyecto
El footer fue diseñado para ser consistente en todo el sitio. Se usó la misma estructura de clases y estilos en todas las páginas para asegurar la uniformidad.

Estructura del Footer: El footer se encuentra en todas las páginas del sitio, con información de contacto, dirección y enlaces a las redes sociales. Además, el fondo oscuro y los textos claros permiten un contraste adecuado, mejorando la accesibilidad.

Impacto del Footer: El footer está presente de manera uniforme en todas las páginas del sitio, y cualquier cambio que se realice en los estilos del footer se reflejará automáticamente en todas las páginas.

## Colores Usados
Se definieron una serie de colores para ser utilizados en todo el proyecto, los cuales están definidos en el archivo _variables.scss. Los colores clave son:

$primary-color: #007bff (usado para encabezados y botones)
$secondary-color: #495057 (para subtítulos y otros elementos de contraste)
$background-color: #f8f9fa (fondo claro para la mayoría de las secciones)
$dark-color: #343a40 (fondo oscuro para el footer)
$text-light-color: #ffffff (texto blanco para el footer)
$link-color: #007bff (para enlaces)
$link-hover-color: #0056b3 (para el hover de enlaces)
Estos colores se aplican de manera consistente en todo el sitio web, asegurando una identidad visual coherente.

## Creditos

Imágenes obtenidas de:

- [Pexels](https://www.pexels.com)