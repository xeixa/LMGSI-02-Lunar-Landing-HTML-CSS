# LMGSI-02-Lunar-Landing-HTML-CSS
## Lunar Landing HTML y CSS

A continuación detallamos los pasos en la creación estructural de la página web, mediante archivos html.

### Creación de 4 bloques:
* _cpanelbox_  (contenedor del panel de control con los distintos paneles de visualización de parámetros)
* _shipbox_ (contenedor de la nave y su zona de movimiento)
* _menubox_ (contenedor del menú desplegable con sus diferentes opciones)
* _moonbox_ (contenedor de la imagen lunar, donde aterrizará la nave)

### En la marca _head_ especificamos:
* El título
* La descripción
* El tipo de teclado
* La configuración del área visible dependiendo del dispositivo
* La  dirección donde se encuentra el archivo .css(utilizamos la técnica Media Queries, para establecer una regla de selección de .css en función del ancho de la pantalla del dispositivo desde el cual estemos accediendo al archivo .html.
  
### En la marca _body_ tenemos: 
  * Los 4 bloques
  * Caja contenedora de la imagen de la nave
  
### En el bloque cpanelbox creamos:
  * 3 cajas con clase "cpanel"
  * Dentro de cada una de ellas tenemos un parámetro escrito y un valor el cual tiene una identificación, la cual utilizaremos posteriormente con JavaScript en función de la velocidad,fuel y altura de la nave.
  * Cada caja también tiene otro contenedor que será una barra visual que crecerá o decrecerá en función del valor del parámetro.
  * Cada caja(barra o caja de parámetros tiene un border outset).
  * Cada barrá tiene un degradado horizontal de colores.
  * Cada caja de parámetros tiene un degradado de colores
  
### Dejamos el bloque shipbox sin nada en su interior de momento, posteriormente añadiremos contenido.
  
### En el bloque menubox tenemos:
  * Dos elementos pause y play los cuales son un enlace a index.html(mi idea es llegar a crear un único sprite que varie en función
  de _pause(sprite)_ y _play(sprite)_ mediante JS. De momento para poder trabajar con sprites he puesto ambos con una iterracción .hover del ratón, que provoca un cambio en el color del sprites
  * Un menú desplegable con las siguientes opciones:
  * Reiniciar (enlace a _index.html_)
  * Ayuda (enlace a _help.html_)
  * Ajustes (enlace a _settings.html_)
  * Creditos enlace a _credits.html_)
  * Visualmente el menú desplegable tiene un border outset con diferentes colores para la caja Menú como para el desplegable, tanto el      borde como el color interno.
  * Una vez entramos a una de las opciones del menú, ésta aparece con un color más oscuro, excepto en reiniciar, ya que ésta opción no nos abre una opción estática sino de reinicio de partida(he optado por quitarle la class active).
  
### Por último, en el bloque moonbox tenemos:
  * imagen de la luna donde aterriza la nave.
  * esta imagen está centrada en medio de la pantalla.
  
Como comentario de observación, destacar que he optimizado el _mob.css_ para la pantalla en vertical. No he indagado mucho en el código necesario para distinguir de .css entre el móvil en horizontal y vertical, es por ello, que si fuese competencia de estudio me gustaría que se nos facilitase dicha información.


[RAWGIT DEL LUNAR LANDING ver. HTML/CSS](https://rawgit.com/xeixa/LMGSI-02-Lunar-Landing-HTML-CSS/master/LMGSI-02-Lunar_Landing(HTML%20y%20CSS)/index.html)


[VALIDATOR W3](https://validator.w3.org/nu/?doc=https%3A%2F%2Frawgit.com%2Fxeixa%2FLMGSI-02-Lunar-Landing-HTML-CSS%2Fmaster%2FLMGSI-02-Lunar_Landing%28HTML%2520y%2520CSS%29%2Findex.html)


[JIGSAW W3](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Frawgit.com%2Fxeixa%2FLMGSI-02-Lunar-Landing-HTML-CSS%2Fmaster%2FLMGSI-02-Lunar_Landing%28HTML%2520y%2520CSS%29%2Findex.html&profile=css3&usermedium=all&warning=1&vextwarning=&lang=es)
