---
title: Lenguajes y herramientas
---
Cuando hablamos de un libro electrónico, hablamos en realidad de varias tecnologías distintas que confluyen en un estándar. Este estándar es el Epub3 y es un archivo que incluye:
- HTML para estructurar el contenido
- CSS para darle a esa estructura un estilo de presentación
- XML para codificar la metadata asociada a la publicación

Para trabajar con estos lenguajes, necesitaremos un editor de texto. 
Y luego necesitaremos algún software extra para checkear si nuestros archivos están correctos y para facilitar un poco la tarea de codificación.

## EPUB
Por lo general, se utiliza Epub como sinónimo de ebook, pero esto no es así. Epub es un formato para representar documentos electrónicos, y un ebook puede ser uno cualquiera de los cientos de formatos que existen para representar un documento (PDF, ASCII, word, HTML, docbook, y un montón más). EPUB es un estandar y como tal define dos cosas: un conjunto de lenguajes para representar el contenido de un libro, y la manera que un sistema de lectura encuentra el libro y lo __presenta__ al lector.
## HTML
HTML o (lenguaje de marcado de hipertexto) es el lenguaje de la web. Todos los sitios web en los que has visitado están hechos con HTML, y l también los EPUBs. Es un lenguaje de marcado para describir páginas web. El aspecto del HTML es el siguiente
```<h1>El quijote de la Mancha</h1><p class="author">Miguel de Cervantes y Saavedra</p><p class="first">En algún lugar de la mancha</p>````

## CSS
CSS es un lenguaje de hojas de estilo3 utilizado para describir la presentación de un documento escrito en un lenguaje de marcas, como el HTML. CSS son las siglas de Cascading Style Sheets (hojas de estilo en cascada), porque se pueden proporcionar múltiples instrucciones de estilo contradictorias, pero hacer que el navegador ordene su prioridad, en cascada, de acuerdo con un conjunto de reglas. En otras palabras, puedes anular los estilos por defecto del navegador, y también puedes anular tus propios estilos en ciertas situaciones, como en diferentes tamaños de navegador. El CSS tiene este aspecto:

````h1 {font-size: 16px; color: black; }````

## XML
XML significa lenguaje de marcas extensible. Un lenguaje de marcas es un conjunto de códigos, o etiquetas, que describe el texto de un documento digital. El lenguaje de marcas más famoso es el lenguaje de marcas de hipertexto (HTML), que se utiliza para dar formato a las páginas web.  Mientras que el HTML indica a una aplicación de navegador el aspecto que debe tener un documento, el XML describe lo que contiene el documento. En otras palabras, XML se ocupa de cómo se organiza la información, no de cómo se muestra. En un Epub el XML se utiliza para describir la información asociada al libro, o sea: su metadata. Y se ve así:

````<dc:title xmlns:dc="http://purl.org/dc/elements/1.1/">El quijote de la Mancha</dc:title>````

## Editor de texto:
Para trabajar con código (o un lenguaje de etiquetado, como en este caso) necesitamos un editor de texto (no un procesador de texto, Word no sirve). Puede ser cualquiera, incluso el Block de notas, pero de utilizar este, el trabajo sería exasperante. Para trabajar con código existen Editores de texto especializados, que nos ayudan a automatizar tareas. Para trabajar con epub, existe un editor dedicado que nos hará todo el trabajo mucho más fácil. Se llama Sigil.

## Herramientas de validación:

Para evaluar si nuestro documento cumple con los estándares de accesibilidad, cuando lo terminemos es conveniente validarlo. para esto, existe un software que se llama ACE y fue desarrollado por Daisy Consortium, la organización internacional que trabaja para facilitar la lectura de personas cond ificultades de acceso al libro impreso.


