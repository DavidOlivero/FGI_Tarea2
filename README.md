<p align="center">
    <img src="https://www.latex-project.org/about/logos/latex-project-logo_288x288.svg" alt="Logo de latex">
</p>

<h2 align="center">Proyecto de LaTeX para la solución del ejercicio 2 de fundamentos de gestión integral</h2>

### Requisitos previos para compilar el proyecto
- Tener instalado Latexmk
- Tener instalado Perl
- Tener instalado un editor LaTeX

_**Nota**_: Si usa visual studio code como editor debe instalar las siguientes extenciones `Latex Workshop` y `Latex Previewer`.

El proyecto debe ser compilado en xelatex debido a unas configuraciones especiales de fuentes, para ello puede compilar manualmente usando el comando `xelatex main` o si usa un editor LaTeX cambie el compilador desde configuraciones. Si usa vscode con las extenciones instaladas, puede compilar con xelatex directamente desde la opción TeX que se agrega desde la barra de erramientas en la parte derecha o izquierda y ejecutar el proyecto con la opción `Recipe: latexmk (xelatex)`.

_**Nota**_: Una vez compile, es posible que latexmk le pida instalar ciertas herramientas, debe instalarlas todas para que el proyecto funcione correctamente.

Si después de compilar le aparecen errores o advertencias con relación al paquete `biblatex` para manejar las citas, solo debe ejecutar el comando `biber main` desde su terminal, de esta maner biber hará las configuraciones necesarias para el paquete biblatex, luego vuelva a compilar el proyecto con xelatex.