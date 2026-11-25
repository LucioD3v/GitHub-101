# Autoevaluación: fundamentos de GitHub

Estas preguntas son originales y sirven para repasar los conceptos del curso. No son preguntas oficiales ni representan un examen de certificación. Cuando se defina una certificación objetivo, cada pregunta podrá relacionarse con sus objetivos públicos.

Intenta responder antes de abrir cada explicación.

## Git y GitHub

### 1. ¿Cuál describe mejor la relación entre Git y GitHub?

- A. Git es una plataforma para alojar sitios web y GitHub es un formato de archivo.
- B. Git es un sistema de control de versiones; GitHub es una plataforma para alojar repositorios Git y colaborar.
- C. Git y GitHub son dos nombres para la misma aplicación.

<details>
<summary>Ver respuesta y explicación</summary>

**Respuesta: B.** Git registra y administra el historial de cambios. GitHub ofrece servicios para alojar repositorios Git y colaborar en ellos.

</details>

## Repositorios, commits y ramas

### 2. ¿Qué suele contener un repositorio?

- A. Los archivos del proyecto y su historial de cambios.
- B. Solo la versión más reciente de cada archivo, sin historial.
- C. Únicamente las solicitudes de incorporación de cambios.

<details>
<summary>Ver respuesta y explicación</summary>

**Respuesta: A.** Un repositorio reúne los archivos del proyecto y el historial de cambios que Git registra.

</details>

### 3. ¿Para qué sirve crear una rama?

- A. Para trabajar en cambios de forma aislada antes de proponerlos a otra rama.
- B. Para borrar el historial de la rama principal.
- C. Para convertir un Issue en un archivo.

<details>
<summary>Ver respuesta y explicación</summary>

**Respuesta: A.** Una rama permite desarrollar cambios sin modificar directamente la rama de destino, por ejemplo `main`.

</details>

### 4. ¿Qué representa un commit?

- A. Una conversación sobre una tarea.
- B. Un conjunto registrado de cambios en el historial del repositorio.
- C. Una copia independiente del repositorio en otra cuenta.

<details>
<summary>Ver respuesta y explicación</summary>

**Respuesta: B.** Un commit guarda cambios en el historial de Git y normalmente incluye un mensaje que los describe.

</details>

## Issues y pull requests

### 5. ¿Cuándo conviene crear un Issue?

- A. Para documentar o conversar sobre una tarea, un problema o una mejora.
- B. Para fusionar automáticamente una rama.
- C. Para guardar una versión del proyecto sin historial.

<details>
<summary>Ver respuesta y explicación</summary>

**Respuesta: A.** Los Issues ayudan a organizar el trabajo y conversar sobre problemas o propuestas; por sí mismos no modifican los archivos.

</details>

### 6. ¿Qué permite hacer un pull request?

- A. Proponer cambios de una rama para revisarlos y conversar antes de integrarlos.
- B. Cambiar la contraseña de todas las personas colaboradoras.
- C. Crear una copia local del repositorio en el navegador.

<details>
<summary>Ver respuesta y explicación</summary>

**Respuesta: A.** Un pull request compara cambios entre ramas y facilita su revisión y discusión antes de fusionarlos.

</details>

### 7. ¿Qué significa seleccionar **Request changes** en una revisión?

- A. La persona revisora solicita cambios antes de que se integre el pull request.
- B. El pull request se fusiona de inmediato.
- C. El Issue relacionado se elimina.

<details>
<summary>Ver respuesta y explicación</summary>

**Respuesta: A.** La revisión comunica que se esperan cambios antes de aprobar la integración. La persona autora puede responder y subir commits a la misma rama.

</details>

### 8. ¿Qué hace `Closes #12` en la descripción de un pull request?

- A. Cierra el Issue al fusionar el pull request en la rama predeterminada.
- B. Cierra el repositorio para nuevas contribuciones.
- C. Crea automáticamente una rama llamada `12`.

<details>
<summary>Ver respuesta y explicación</summary>

**Respuesta: A.** Las palabras clave como `Closes` vinculan el pull request con un Issue y lo cierran cuando el cambio se integra en la rama predeterminada.

</details>

## Fusionar cambios

### 9. ¿Qué ocurre al fusionar un pull request?

- A. Los cambios propuestos se integran en la rama de destino.
- B. Se borra todo el historial del repositorio.
- C. Se convierte el repositorio en un Issue.

<details>
<summary>Ver respuesta y explicación</summary>

**Respuesta: A.** La fusión incorpora los cambios de la rama de origen en la rama de destino. El método de fusión puede variar según la configuración del repositorio.

</details>

### 10. ¿Quién puede enviar una revisión formal de tu pull request?

- A. La persona autora debe aprobar su propio pull request.
- B. Otra persona con al menos permisos de lectura en el repositorio.
- C. Cualquier visitante sin importar sus permisos.

<details>
<summary>Ver respuesta y explicación</summary>

**Respuesta: B.** Cualquier persona con acceso de lectura puede revisar y comentar los cambios. La persona autora no puede revisar su propio pull request.

</details>

---

[Volver al índice](README.md)
