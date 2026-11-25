# 05. Pull requests y revisión

## Abrir una solicitud de incorporación de cambios

Para este paso lo primero que deberemos de realizar será el crear/agregar un nuevo archivo, debido a que nos encontramos en la nueva rama que acabamos de generar, por ello sigamos los siguientes pasos:

1. En la pestaña **< > Código (Code)**, en el menú de encabezado de nuestro repositorio, asegúremonos de encontrarnos situados en la rama, la cual en este ejemplo nombramos: `dev`.

2. Acto seguido elijamos el menú desplegable "Add file (Agregar archivo)" y seleccionemos (demos clic) en la opción "Create new file (Crear nuevo archivo)".
<br>

 ![crear-nuevo-archivo](../../images/crear-nuevo-archivo.jpg)

 3. En la nueva vista, aparecerá un campo vacío con una leyenda en sombreado "Name your file...", el cual nos indica que le brindemos un nombre, llamemoslo `LICENSE.md`.

**Nota**: `.md` es una extensión de archivo que crea un archivo [Markdown](https://docs.github.com/es/get-started/quickstart/github-glossary#markdown). Para obtener mayor información sobre Markdown visite [Sintaxis básica de escritura y formato](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) en la documentación de GitHub o realizando el curso de habilidades [Comunicación mediante Markdown](https://github.com/skills/communicate-using-markdown).

4. A continuación y de forma "mágica" se mostrará la leyenda "Choose a license template", misma que podemos seleccionar o, en el área Editar, podemos pegar el siguiente contenido:
<br>

 ![licencia-plantilla](../../images/licencia-plantilla.jpg)

```
  Derechos de autor.

  Por la presente se otorga permiso, sin cargo, a cualquier persona que obtenga una copia de este software y los archivos de documentación asociados (el "Software"), para operar con el Software sin restricciones, incluidos, entre otros, los derechos de uso, copia, modificación, fusión , publicar, distribuir, otorgar sublicencias y/o vender copias del Software, y permitir que las personas a las que se les proporcione el Software lo hagan, sujeto a las siguientes condiciones:

  El aviso de derechos de autor anterior y este aviso de permiso se incluirán en todas las copias o partes sustanciales del Software.

  EL SOFTWARE SE PROPORCIONA "TAL CUAL", SIN GARANTÍA DE NINGÚN TIPO, EXPRESA O IMPLÍCITA, INCLUYENDO, ENTRE OTRAS, LAS GARANTÍAS DE COMERCIABILIDAD, IDONEIDAD PARA UN FIN DETERMINADO Y NO VIOLACIÓN. EN NINGÚN CASO LOS AUTORES O LOS TITULARES DE LOS DERECHOS DE AUTOR SERÁN RESPONSABLES DE CUALQUIER RECLAMACIÓN, DAÑOS U OTRA RESPONSABILIDAD, YA SEA EN UNA ACCIÓN DE CONTRATO, AGRAVIO O DE CUALQUIER OTRO TIPO, QUE SURJA DE, FUERA DE O EN RELACIÓN CON EL SOFTWARE O EL USO U OTROS TRATOS EN EL SOFTWARE.
```
<br>

 ![licencia-texto](../../images/licencia-texto.jpg)

 5. Posteriormente hagamos clic en el botón **Commit changes** para que al igual que en el paso anterior donde creamos el archivo `README`nos aparezca una ventana emergente que nos solicite ingresar un breve mensaje de confirmación que describa los cambios que realizamos. Recordemos que este mensaje ayuda a otros a saber qué estamos añadiendo en nuestro commit. Como nos podemos dar cuenta, GitHub ofrece un mensaje predeterminado simple, pero en esta ocasión vamos a cambiarlo un poco para practicar.
 <br>

 Primero, en el título escribamos: "Se añade archivo LICENSE.md". En la descripción extendida ingresemos: Se crea archivo de Licencia en formato markdown que expresa los derechos de autor.

6. Por último confirmemos los cambios dando clic en **Commit changes**
<br>

  ![licencia-commit](../../images/licencia-commit.jpg)

¡Excelente! - Ya estas dominando el realizar commits, ¿sencillo no?

Ahora que se realizó un cambio en el proyecto y se añadio, es hora de compartir el cambio propuesto a través de una solicitud de extracción o como se conoce normalmente: PR (Pull Request), el cúal se definió en la Introducción.

### Actividad: Generando nuestro primer Pull Request :keyboard:

Una vez realizado lo anterior, es probable que hayan notado un pequeño mensaje que muestra el envío reciente a la rama y proporciona un botón que dice **Contribute (Contribuir)**. Al desplegarlo, podremos observar dos opciones: **Compare (Comparar)** y **Open pull request (Abrirl solicitud de extracción)**.

![Comparar y abrir Pull Request](../../images/comparar-y-abrir-pull-request.jpg)

Para realizar el PR hagamos clic en **Open pull request**, al realizar esto se nos mostrará una vista como la siguiente:

![Abriendo Pull Request](../../images/abriendo-pull-request.jpg)

Si nos encontramos en esta pantalla, vayamos directamente al paso número 6. Caso contrario que no hayamos dado clic en susodicha opción, deberemos de realizar los siguientes pasos:

1. Dar clic en la pestaña **Pull requests** en el menú de encabezado del repositorio.

![Pestaña Pull Request](../../images/pestaña-pul-request.jpg)

2. Dar clic en **New pull request (Nueva solicitud de extracción)**.

![Nuevo Pull Request](../../images/nuevo-pull-request.jpg)

3. En la nueva pantalla se mostrarán dos menús desplegables:  **base:main** y **compare:main**, asegúresemos de que la primera, la base seleccionada siempre sea **main**, porque es la "rama principal y original".

![Comparación de ramas](../../images/comparacion-de-ramas.jpg)

4. Del segundo menú desplegable **compare:**, seleccionemos nuestra rama `dev`.

![Comparación rama Dev](../../images/comparacion-rama-dev.jpg)

5. Demos clic en el botón situado a la derecha **Create pull request**.
6. Aquí deberemos de añadir un título para la solicitud de envio, aunque si nos percatamos, de forma predeterminada, el título será automáticamente el nombre del commit previamente ingresado.
7. El siguiente campo lo ayuda a proporcionar una descripción de los cambios que realizó. Si creaste un Issue en la lección anterior, incluye `Closes #<número>` para vincularlo.
<br>

![Enviando mi primer PR ](../../images/enviando-mi-primer-pr.jpg)

8. Por último hagamos clic en **Create pull request**. Posteriormente seremos redirigidos automáticamente a la nueva solicitud de extracción.

![PR en proceso ](../../images/pr-en-proceso.jpg)

¡Listo! Ya creaste tu primer pull request. En la siguiente sección, pide a otra persona que revise los cambios antes de fusionarlos. :tada:

## Revisar un pull request

La revisión permite conversar sobre los cambios antes de incorporarlos al proyecto. Con el pull request abierto, pide a otra persona que lo revise antes de fusionarlo.

### Actividad: revisar los cambios

1. Pide a otra persona con al menos permisos de lectura en el repositorio que revise tu pull request y abra la pestaña **Files changed**.
2. Puede dejar un comentario en una línea concreta o seleccionar **Review changes** para enviar una revisión con una de estas opciones: **Comment**, **Approve** o **Request changes**.
3. Lee los comentarios, responde y, si hacen falta cambios, súbelos a la misma rama. Después, pide que revisen el pull request de nuevo.
4. Cuando la revisión esté resuelta, continúa con la siguiente lección para aprender a fusionar el pull request. Si incluye `Closes #<número>`, el Issue vinculado se cerrará al fusionarlo en la rama predeterminada.

No puedes enviar una revisión a tu propio pull request. Si estás aprendiendo a solas, puedes explorar las pestañas **Conversation** y **Files changed**, pero necesitarás otra persona con al menos permisos de lectura para practicar una revisión.

Consulta la guía oficial sobre [revisiones de pull requests](https://docs.github.com/es/pull-requests/reference/pull-request-reviews).

---

[Volver al índice](README.md)
