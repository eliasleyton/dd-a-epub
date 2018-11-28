# dd-epub

Repositorio que pretende recopilar y adaptar las publicaciones de ONG Derechos Digitales en formato amables con la lectura como ePub.

# Cómo contribuir

Se utiliza Markdown para el formato base de los textos y `pandoc` para convertirlos a ePub.

Como instalar Pandoc (en ingles): <https://pandoc.org/installing.html> 

Convertir archivo Markdown a ePub.

```bash
pandoc book.md -o book.epub
```

# Estilos

Para poder agregar los meta-tags del formato ePub con pandoc la cabezera del documento debe ser de la siguiente manera.

```
title: Propuesta de estándares legales para la vigilancia en Chile (2018)

description: Tercera parte de la serie “La construcción de estándares legales para la vigilancia en América Latina”, con recomendaciones que pretenden guiar la acción estatal en un conjunto de puntos críticos, donde el sistema normativo todavía no cumple con los estándares provenientes de principios fundamentales de democracia, dignidad y libertad, y del desarrollo del derecho internacional de los derechos humanos.

autor: María Paz Canales y J. Carlos Lara

cover-image: cover.png
````

* **title**: Es el título del libro, y el nombre que se verá en una biblioteca tipo iBooks o similar.
* **description**: Descripción del libro o texto. Dato entregado en el link de publicación de la ONG más abajo.
* **autor**: Autor del texto, también entregado en el link de publicaciones de la ONG más abajo.
* **cover-image**: nombre de la imagen que debe estar en la misma carpeta donde esta el archivo de *.md en el cual se  trabaja.

Guiá sobre Markdown <https://joedicastro.com/pages/markdown.html>

# Links

ONG Derechos Digitales <https://www.derechosdigitales.org> 
Publicaciones ONG  Derechos Digitales <https://www.derechosdigitales.org/tipo_publicacion/publicaciones/> 

Guiá sobre Markdown <https://joedicastro.com/pages/markdown.html> 
Como instalar Pandoc (en ingles): <https://pandoc.org/installing.html> 