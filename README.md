# LMGSI-02-Lunar-Landing-HTML-CSS
Lunar Landing HTML y CSS

A continuación detallamos los pasos en la creación estructural de la página web, mediante archivos html.

Creación de 4 bloques:
-cpanelbox  (contenedor del panel de control con los distintos paneles de visualización de parámetros)
-shipbox (contenedor de la nave y su zona de movimiento)
-menubox (contenedor del menú desplegable con sus diferentes opciones)
-moonbox (contenedor de la imagen lunar, donde aterrizará la nave)

En la marca <head> especificamos:
-El título
-La descripción
-El tipo de teclado
-La configuración del área visible dependiendo del dispositivo
-La  dirección donde se encuentra el archivo .css(utilizamos la técnica Media Queries, para establecer una regla de selección de .css en función del ancho de la pantalla del dispositivo desde el cual estemos accediendo al archivo .html.
  
  En la marca <body> tenemos:
  
  -los 4 bloques
  -Caja contenedora de la imagen de la nave
  
  En el bloque cpanelbox creamos:
  - 3 cajas con clase "cpanel"
  - dentro de cada una de elass tenemos un parámetro escrito y un valor el cual tiene una identificación, la cual utilizaremos posteriormente con JavaScript en función de la velocidad,fuel y altura de la nave.
  -Cada caja también tiene otro contenedor que será una barra visual que creceráo crecerá en función del valor del parámetro.
