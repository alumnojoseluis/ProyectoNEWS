# Visualización del proyecto finalizado.

https://rawgit.com/alumnojoseluis/ProyectoNEWS/master/news.html

## PLANTEAMIENTO

-Realizar página web de noticias auto rellenable con scroll. Se
cargarán noticias al llegar abajo con el scroll.

-Se utilizará HTML, jQUERY, BOOTSTRAP.

## ESPECIFICACIONES

- Publicidad de anchura 336px en Desktop. Situación derecha.
- Publicidad de altura 90px en Mobile. Situación abajo y fija.
- Noticias con las características siguientes:
    - Title ; 8 palabras.
    - Imgbig ( > resolución) y Imgmid (< resolución).
    - Description ; mín. 300 palabras.
    - Datetime.
- Dos páginas HTML:
 - 1º Varias noticias.
 - 2º Una sola noticia.

## PROYECTO

### -Descripción:

Consiste en un noticiario sobre tecnología, en donde se van
redactando las últimas noticias de este género siguiendo la línea del
planteamiento y especificaciones arriba señaladas.

### -Boceto y diseño final maquetación proyecto.

**************FOTOOOOS


### -Contenido de los archivos

- **news.html** contiene portada con 3 noticias escritas en el
    mismo.
- **news1.html** y **news2.html**
    - Contiene desarrollo de la noticia primera y segunda,
    respectivamente, de las de la portada (**news.html**).
       - Especificaciones:
          - texto
          - 2 imágenes
          - 1 video
          - etiquetas meta (**open graph**) con:

              >título

              >descripción

              >imagen grande

              >nombre aplicación

              >url

- **rss/rss.xml**, contiene sindicación del contenido de news1.html
    y news2.html.
- **js/news.js**
    - Carga y presenta noticias de 1.json y de 2.json
    mediante:
       - -botón +NOTICIAS o,
       - -evento scroll bottom
    - Carga Facebook
    - Activa/Desactiva scroll (ACTIVAR/PARAR SCROLL)

- **img/...**, contiene archivos de las imágenes con los siguientes formatos:
      - **.ico**, utilizado de favicono.
      - **.png**, utilizado para las imágenes del logotipo del proyecto, de RSS y de Facebook, como también el de la publicidad.
      - **.jpg**, utilizado para las imágenes del tapiz, cabecera y noticias.
      **Comentar que las imágenes de noticias se distinguen entre:**
      -**menor resolución, IMGMID, anotadas como new#.jpg**
      -**mayor resolución, IMGBIG, anotadas como new#_#.jpg**
      
Para la optimización se han utilizado [http://optimizilla.com/es/](http://optimizilla.com/es/)
y [http://webresizer.com/resizer/?lang=es](http://webresizer.com/resizer/?lang=es)

- **css/news.css**, contiene el estilo tanto para versión desktop
    como mobile, como también llamada externa para la fuente
    texto.
- **data/1.json** y **2.json** , contienen 3 noticias cada uno.

## OTRAS CARACTERÍSTICAS A SEÑALAR

-Favicono

-Botón upload

-Botón rss. Comentar en este punto que sólo están activados los
dos primeros enlaces, es decir, los dos que tienen página de noticia
entera (**noticia.html**). Por lo tanto el tercer enlace está desactivado.

-Fuentes externas, en este caso se ha utilizado la fuente
**Carrois+Gothic+SC** para detallar el desarrollador que aparece en
el pie de la página.

-Iconos **glyphicon**

-Fuente del texto del encabezado son de tipo perfiladas.

-Distintos estilos en las fuentes de la página de noticia, como
pueden ser, cursiva, negrita, texto justificado, en bloque, centrado,
entre otros.

-Caja sombreada para dar volumen al enlace noticia.


-Adaptabilidad; **Respnsive Design**.

-Programación indentada.

-En el branch Versión-Minify está el proyecto minificado.
