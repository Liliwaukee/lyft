# Lyft

* **Track:** _Common Core
* **Curso:** _Creando un sitio web interactivo con JavaScript
* **Unidad:** _1.Maquetado web con HTML & CSS

El reto consiste en replicar el maquetado del sitio de Lyft (https://www.lyft.com/).

***

El sitio se dividió en 5 secciones

* Nav
* Section (3)
* Footer

Como elementos externos vamos a necesitar la tipografía Montserrat y los iconos de Iconmoon, ambos los vamos a ligar en la etiqueta "head".

## Nav
- Para el menú de navegación se crearon 2 "divs" de 50% de ancho de la pantalla, con las propiedades "display:inline-block" y "float:left" se colocan de forma horizontal una del lado de otra.

## Section "Sign-up"
- En esta sección se colocará el mini formulario.
- Al input se le modificarán las propiedades de "border" y se le dará estilo sólo al "border-bottom", además se le quitará la sombra con "box-shadow: none".
- Al "button" se le modifica background-color y el color de la tipografía.
- El texto esta dentro de "p", ambos contenidos en un "div".

## Section "Benefits"
- Para esta sección el fondo será una gradación, los valores son: linear-gradient(#76278F, #2B1E66), los cuales se agregará en background de section "benefits".
- La sección se dividirá en 2 "divs", uno para el texto y otro para la imagen. La imagen ocupará el 75% de su contenedor.

## Section "Videos"
- Se seccionará en 3 "divs", uno para cada video y su respectivo texto. A su vez cada "div" se subdividirá en 2 divs, el "div" para contener el texto tendrá un ancho de 33% y el "div" para el video será de 67%.
- El video se insertará con un "iframe", el atributo "height" se aumenta para que sea proporcional con el diseño de la página.

## Footer
- El footer se dividirá en 4 columnas, cada columna será un "div".
- Los 3 primeros bloques son texto, se insertarán en listas "ul" y se les quitará la viñeta con "list-style-type:none".
- La última columna contiene los logos de las tiendas en línea y se manipulará su ancho en css.
- Los iconos de redes sociales se seleccionan en Iconmoon y se descarga la carpeta.
- La linea se inserta con un "hr" y se manipula su width.
- El texto de copyright se mete en una etiqueta "p" y se centra con "text-align:center".
