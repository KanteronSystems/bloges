---
date: 2017-06-28T10:24:16-04:00
title: Nuevo Blog
tags: ["blog"]
image: "httpss://images.pexels.com/photos/270404/pexels-photo-270404.jpeg"
comments: true     # set false to hide Disqus comments
share: true        # set false to share buttons
thumbnailImagePosition: left
thumbnailImage: //images.pexels.com/photos/270404/pexels-photo-270404.jpeg
coverImage: //images.pexels.com/photos/270404/pexels-photo-270404.jpeg
metaAlignment: center
coverMeta: out
---

Tenemos un nuevo blog, este (blog.kanteron.com) que solía ser nuestra URL principal. Ahora nuestra web está en www.kanteron.com  

<!--more-->

Hemos decidido cambiar de blog.  
No por una cuestión de estilo, sino por dos motivos técnicos:
  
1. El blog anterior estaba basado en WordPress, un CMS (Sistema de Gestión de Contenidos) que generaba el blog desde una base de datos. Eso hacía que la gestión de los datos fuese mucho más engorrosa y poco trasparente de lo que nos gusta
2. El rendimiento y la seguridad de un blog basado en base de datos es MUY inferior comparado con uno como este, basado en un "Generador Estático"

Para hacerse una idea, el blog anterior obtenía en los tests de rendimiento un 38/100, y este obtiene un 99/100:

- Tiempo de inicio de carga de 428ms a 21ms
- Tiempo completo de carga de 741ms a 21ms
- Ahora tiene HTTPS, HTTP2 y certificado SSL

Además ahora está hospedado en un CDN (Red de Servidor de Contenido) con lo que carga más deprisa en todo el mundo.

Después de probar con Jekyll, GitHub pages, Nikola, Octopress, y varias alternativas más, hemos decidido usar Hugo con Gulp, Webpack, y Netlify, manteniendo el contenido en formato de archivos de texto plano (markdown) bajo sistema de versioneado de GitHub.

Por cierto, migrar miles de posts del blog anterior ha sido cuestión de minutos, con sólamente un pequeño error en una línea.

¡Una maravilla!