# Scripts

##### pirotexnia.py
- [ ] Script que mande llamar todos los módulos para armar el libro
- [ ] Que cada módulo corra sobre los archivos correspondientes
- [ ] ¿Queremos que corra ``latexmk`` sobre el principal para tener todos los auxiliares fresquitos?
- [ ] Crear un archivo de configuración ``config_ptn.py`` con listas de ambientes, comandos, excepciones, etc.
- [ ] Quizá ofrecer parámetros opcionales o _banderas_ para modificar la salida por omisión.


##### tex2html.py
- [ ] Como parámetro principal debe ir el archivo que queremos convertir ``archivo.tex`` con la idea de poderlo invocar como ``$ tex2html.py archivo.tex``
- [ ] Quizá ofrecer parámetros opcionales o _banderas_ para modificar la salida por omisión.

##### mkbiblio.py
- [ ] Su archivo de entrada será el ``bbl`` generado por biber/LaTeX
- [ ] Deberá, según el formato de bibliografía que se use, convertir las citas de LaTeX a html (con hipervínculos a la entrada).

##### mktoc.py
- [ ] Su archivo de entrada será el ``toc`` generado por LaTeX
- [ ] Script para hacer el _Índice general_ en html

##### makeindex
Aquí hay de dos sopas:
- Usamos ``makeindex`` con un estilo ``ist`` sobre el ``idx`` o
- Usamos el ``ind`` generado por LaTeX y hacemos un script ``mkindex.py``

## Bibliotecas útiles de python

Para búsquedas:
- re
- pyparsing

Para manejo de archivos:
- argparse
- os.path
- shutil
- textwrap / dedent
- subprocess (para ejecutar comandos del sistema dentro de python)

##  Programas y paquetes de LaTeX que usaremos
Para bibliografía:
- biblatex (paquete)
- biber (programa)

Para índice alfabético o analítico:
- imakeidx (paquete)
- makeindex (programa)

