

# Repositorio del workshop *accesibilidad en epub*, financiado por el Fondo del libro del Ministerio de las Culturas de Chile.

En este repositorio encontrarás el programa, los *slides*, la bibliografía & documentos descargables necesarios para seguir el curso.`


La web del curso está construida a partir de _Course-in-a-Box_,  una herramienta gratuita para crear y publicar cursos en línea, sin necesidad de tener experiencia previa en codificación. 

Para crear tu propio curso, simplemente haz un fork de este repositorio. La documentación detallada está disponible en [course-in-a-box.p2pu.org](https://course-in-a-box.p2pu.org).

Para realizar cambios en la propia plantilla, un buen lugar para empezar son los directorios [`_layouts`](/_layouts), [`_includes`](/_includes) y [`css`](/css). Estos directorios contienen todos los archivos de diseño y estilo utilizados.

¿Preguntas? Pregunta en el [Foro de la Comunidad] de P2PU (https://community.p2pu.org/c/tech/course-in-a-box/78).

# Ejecutar localmente
- [instalar docker](https://docs.docker.com/engine/install/) 
- Ejecuta ``docker run -i -t --rm -u 1000:1000 -p 4000:4000 -v `pwd`:/opt/app -v `pwd`/.bundler/:/opt/bundler -e BUNDLE_PATH=~/opt/bundler -w /opt/app ruby:2.7 bash -c "bundle install && bundle exec jekyll serve --watch -H 0.0.0.0"```

---
Course-in-a-Box está construido por [Peer 2 Peer University](https://www.p2pu.org) y compartido bajo una licencia MIT.

El contenido del curso ("Módulos") se comparte bajo una licencia [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
