GeoinquietosSVQ_slides
======================

El objetivo del proyecto es dotar de una guía de cómo realizar una presentación mediante trasparencias para cualquier charla de las que hacemos en Geoinquietos Sevilla.

Pasos a seguir:

* Creamos usuario en GitHub
* Creamos proyecto en Github
* Creamos GitHub Pages
* Desde la carpeta principal del proyecto hacemos un "git fetch origin"
* Cambiamos de rama con git checkout gh-pages
* Comenzamos a crear las trasparencias
* Nos creamos el submodulo de reveal.js con git submodule add https://github.com/hakimel/reveal.js.git revealjs
* !! Muy importante que sea https, porque sino despues en las gh-pages dará un error
* Se debe hacer un git submodule init y un git submodule update en la raiz del proyecto
* Podemos empezar a crearnos nuestras trasparencias
* Para poder ver cómo va quedando, podemos montar un servidor en local
* Instalar node.js
* Instalar Grunt
* Nos vamos a la carpeta reveal.js
* Hacemos un npm install
* Por último un grunt serve
* Todos los cambios que vayamos haciendo se verán en http://localhost:8000/
* Hay otra forma de hacerlo y es a través del editor online slid.es
* Creamos trasparencias con el estilo más sencillo posible
* Exportamos el código HTML y lo insertamos en nuestro index.html

Slides on:

http://moiarcsan.github.io/GeoinquietosSVQ_slides/
