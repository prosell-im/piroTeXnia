# piroTeXnia

Convertidor de LaTeX a html para TUL de TeXedores

## Objetivo general

Una meta de la Sección de Publicaciones del Instituto es poder ofrecer libros cuyo contenido se pueda acceder de distintas formas:

* libro impreso,
* en línea (html),
* digital (epub, pdf protegido, ...).

Para ello, es indispensable contar con un convertidor de LaTeX a html que de manera (casi) automática genere el código html a partir de los archivos de LaTeX. Aunque existen ya varias opciones, nos gustaría contar con una propia que nos permita *jugar* con la salida para poder modificar de forma clara su comportamiento.

## Convertidor(es)

El proceso de convertir de LaTeX a html debe partir de los archivos fuente de la versión que se usa para el libro impreso, ya que éste es el que contiene los comandos necesarios de la formación *fina*, sobre el cual se trabajarían cambios en posteriores reimpresiones o ediciones.

Para facilitar la conversión, es bueno tener archivos de LaTeX con una sintaxis muy limpia, lo que llamo *estricta*. Desde esta perspectiva debemos contar con una idea clara de qué se debe y puede incluir como comandos o entornos de maquetación que sólo juegan un papel relevante para el impreso pero sobran para el libro en línea.

Es necesario, entonces, contar con un manual técnico de uso de LaTeX para editores de TeXedores.

Los programas, scripts en ``python3``, se encuentran en la carpeta ``Convertidores``.

## Manual de LaTeX para editores
En la carpeta ``ManualLaTeX`` estará el manual de uso para editores de _TeXedores_.
## Notas curso de LaTeX
Dentro de la carpeta ``NotasCurso`` están los archivos que se han ido generando durante el curso.
