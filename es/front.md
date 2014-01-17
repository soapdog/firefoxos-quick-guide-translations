{frontmatter}

## Agradecimientos

A mi esposa Lili, ¡la mejor esposa del mundo!

¡A Mozilla por creer siempre en nosotros, por mantener la web abierta y libre y situar en primer lugar a los usuarios!

¡A la Comunidad Brasileña de Mozilla por recibirme tan bien y ser simplemente impresionantes!

¡A mi mentor del GSoC Marcos Caceres, al equipo WebApi de Mozilla, a los equipos Mozilla Tech Evangelists y Dev Engagement por ser más que impresionantes!

¡A Google por el Google Summer of Code 2013! Este programa es una maravilla.

## Este libro está en una Beta perpetua

Mi plan es actualizar este libro a menudo, expandiendo sus contenidos y revisando el texto con las cuestiones que encuentren los lectores. Dado que algunas APIs están siendo implementadas para Firefox OS, querrás asegurarte de que estás leyendo una versión actualizada del libro.

## Mí, Yo mismo, y Yo

En este libro encontraras algunas partes donde expreso mi opinión personal y tomo decisiones que pueden ser diferentes a lo que otros programadores harían - particularmente si ayuda a explicar una idea más facilmente. Siempre trararé de aclarar y explicar mis argumentos cuando de una opinión. De todas formas, si hay algún error en lo que estoy diciendo, revisaré el texto y actualizare el libro. Mira la sección Comentarios & Pull Request para más información.

## Cómo llegó a ser este libro

Originalmente, había estado escribiendo este libro en mi tiempo libre - pero gracias a la ayuda de mi mentor del Google Summer of Code(GSoC), Marcos Caceres, este libro se convirtió en parte de mi proyecto del GSoC - cuyo objetivo era crear recursos útiles para desarrolladores de Firefox OS. Con lo cual, muchas gracias a Google por financiar este proyecto y al equipo de Mozilla Web API por permitirme unirme a ellos durante el verano.

## Mantenerse al día

Este libro se distribuye de forma ***libre*** usando [Leanpub](http://leanpub.com). 

Podrás registrar tu correo electrónico para recibir actualizaciones automáticas cuando lo descargues de [la página del libro en Leanpub](http://leanpub.com/quickguidefirefoxosdevelopment). El plan es actualizar el libro varias veces al mes.Si has conseguido este libro de un amigo o de algún otro sitio, deberías considerar ir a la página web de arriba, descargarlo y registrarte para asegurarte de que recibes los avisos de actualización.

## Donaciones

Escribir un libro requiere mucho trabajo y me gustaría dedicar más tiempo de mi vida para este tipo de actividades después del Google Summer of Code 2013 haya terminado. Aquellos que piensan que este libro es útil(o interesante) pueden mover el deslizador del precio en la página de descarga de Leanpub de cero a la cantidad deseada y darme algo de dinero. Aquellos que prefieran donar usando PayPal, puedo recibir donaciones en la cuenta *agarzia@mac.com*.

Independientemente de las donaciones, deberías rellenar tu correo electrónico en la página de descargas para asegurarte de que una vez que el libro sea actualizado,¡recibas la noticia!.

## Cómo contactar con el autor

Para enviar comentarios y sugerencias por favor, envía un correo electrónico a [fxosquickguide@andregarzia.com](mailto:fxosquickguide@andregarzia.com). Mi página web es [http://andregarzia.com](http://andregarzia.com). Mi cuenta de Twitter es [@soapdog](http://twitter.com/soapdog).

Si quieres ayudar a mejorar el contenido de este libro, por favor mira la sección Sugerencias & Pull Request.

## Ilustración de la portada

La portada fué creada por Raphael Eckhardt, un diseñador e ilustrador de Brasil. Puedes ver su trabajo y contactar con él(es freelancer) en [http://raphaeleckhardt.com/](http://raphaeleckhardt.com/).

## A quién va dirigido este libro

Este libro está escrito para los lectores con un nivel intermedio de conocimiento de HTML, CSS y JavaScript que quieran construir aplicaciones móviles para Firefox OS. Enseñar HTML, CSS y JavaScript esta fuera del alcance de este libro. Os daré links para unos buenos libros de referencia.

## Mejores prácticas contra Explicación para Principiantes

Los desarrolladores experimentados podrán notar que a veces no sigo las buenas prácticas en el código fuente de los ejemplos del libro. A pesar de que estoy evitando el uso de anti-patrones aquí, estoy tratando de mantener el uso de las funciones inmediatas y otras prácticas similares a un mínimo. La razón principal para esto es que el código fuente sea amigable para los principiantes ya que es un libro de introducción. Los programadores experimentados sabrán cuándo y cómo cambiar las cosas mientras que los programadores principiantes entenderán que está pasando. Todo el código funciona y como puedo actualizar el libro, puedo revisar el código y utilizar mejores prácticas dependiendo de las sugerencias de los lectores.

Si quieres adentrarte en el mundo de la alta calidad en la codificación de JavaScript aquí hay algunos buenos libros:

* [JavaScript: The Good Parts](http://shop.oreilly.com/product/9780596517748.do): The JavaScript Book.
* [JavaScript Patterns](http://shop.oreilly.com/product/9780596806767.do): Patterns and best practices.
* [JavaScript Enlightenment](): Advanced JavaScript techniques.
* [Maintainable JavaScript](http://shop.oreilly.com/product/0636920027713.do): Writing code that is easy to maintain and work with.

## Sugerencias & Pull Requests

Este es un libro Gratis y Abierto y estoy emocionado por recibir todas las sugerencias que la gente pueda darme. Todo el contenido del libro está en [Repositorio de GitHub](https://github.com/soapdog/firefoxos-quick-guide) y está contruido usando Markdown (con algunas extensiones de Leanpub). Para enviarme sugerencias, correciones de errores y mejoras solo enviadme un pull request. Gracias de antemano por todas las contribuciones.

El repositorio de Git de este libro está en [https://github.com/soapdog/firefoxos-quick-guide](https://github.com/soapdog/firefoxos-quick-guide).

## Traducciones

Este libro fue escrito originalmente en Portugués y traducido al Inglés por mi. Ambas versiones están disponibles gratis en la web en:

* [Portuguese Version](http://leanpub.com/guiarapidofirefoxos): Guia Rapido para Desenvolvimendo para Firefox OS.
* [English Version](http://leanpub.com/quickguidefirefoxosdevelopment): Quick Guide for Firefox OS App Development.

Doy la bienvenida a toda ayuda para traducir este libro a todavía más idiomas(y para corregir mi inglés chapurreado).

## Historial de versiones

### Versión 0.2
El libro fue revisado por Marcos Caceres del equipo WebAPI de Mozilla. El contenido de cada capítulo fue comprobado para correciones técnicas, y muchos errores gramaticales y tipográficos fueron corregidos.

### Versión 0.1

Esta es la primera versión del libro. I am yet to run this through an editor and it was not revised for typos, grammar mistakes and general bad things. English is not my first language so please correct me when I am wrong. What you're reading here begun on the 20th of August of 2013 as a quick guide to be distributed at [BrazilJS Conference](http://braziljs.com.br/) that happened on the 22nd and 23rd. So you're basically reading a quick draft written in two days.

Estoy utilizando el sistema de [Leanpub](http://leanpub.com) para escribir este libro. Este sistema me permite iterar rápidamente y gestionar este proyecto, mientras me mantiene cuerdo. Esta versión es una traducción cuasi-literal de la versión originla en Portugués.

{mainmatter}