# 01. Introducción

## ¡Bienvenidxs!

Estamos encantados de darles la bienvenida a este emocionante curso, donde aprenderán los fundamentos de GitHub y cómo aprovechar al máximo esta increíble plataforma de desarrollo colaborativo. GitHub se ha convertido en la herramienta de elección por millones de desarrolladores en todo el mundo, y este curso les brindará las habilidades necesarias para comenzar a utilizarlo de manera efectiva.

Durante este curso, exploraremos los conceptos básicos de GitHub, incluyendo cómo configurar su cuenta, crear y clonar repositorios, realizar cambios, colaborar con otros desarrolladores y mucho más. También les proporcionaremos consejos y buenas prácticas para garantizar una gestión eficiente de su flujo de trabajo.

Nuestro objetivo es ayudarles a familiarizarse con GitHub y demostrarles cómo puede mejorar su productividad, facilitar la colaboración en equipo y llevar su desarrollo de software al siguiente nivel. No importa si son principiantes en el mundo de la programación o si ya tienen experiencia con control de versiones, este curso está diseñado para adaptarse a todos los niveles de conocimiento.

Recuerden que el aprendizaje es un proceso continuo, y GitHub es una herramienta en constante evolución. Así que, estén abiertos a explorar, hacer preguntas y compartir ideas. Juntos, crearemos un entorno de aprendizaje enriquecedor y estimulante.

Estamos emocionados de acompañarles en esta aventura y esperamos que aprovechen al máximo este curso.

¡Buena suerte y feliz codificación!

El equipo de GitHub 101

## Introducción

**¿Qué es GitHub?**
<br>
GitHub es un servicio basado en la nube que aloja un sistema de control de versiones [(VCS)](https://es.wikipedia.org/wiki/VCS_(desambiguaci%C3%B3n)) llamado [Git](https://docs.github.com/es/get-started/using-git/about-git), en otras palabras es una plataforma de colaboración que utiliza Git para el control de versiones, es decir, se utiliza para compartir y contribuir al software de [código abierto](https://docs.github.com/es/get-started/quickstart/github-glossary#c%C3%B3digo-abierto).
<br>

📺 Vídeo: [¿Qué es GitHub?](https://youtu.be/DinilgacaWs)

**¿Qué es un repositorio?**
<br>
Un [repositorio](https://docs.github.com/es/get-started/quickstart/github-glossary#repository) es un proyecto que contiene todos los archivos del mismo, tales como imagenes, carpetas, entre otros tipos de archivos. Así como el historial de revisiones de cada uno de ellos. Aqui puedes debatir y administrar el trabajo de tu proyecto dentro.
<br>

📺 Video: [¿Qué es un repositorio?](https://youtu.be/6NOwXGqHUds)

**¿Qué es una rama?**
<br>
En GitHub, una [rama (branch en inglés)](https://docs.github.com/es/get-started/quickstart/github-glossary#branch) es una versión paralela de un repositorio que permite a los desarrolladores trabajar en distintos aspectos de un proyecto de forma aislada. Cuando se crea una rama, se copian todos los archivos y el historial de cambios del repositorio principal, y a partir de ahí se pueden realizar modificaciones sin afectar la rama principal (también conocida como rama "master" o `main`).

Las ramas son útiles para varios propósitos, como desarrollar nuevas características, solucionar problemas, experimentar con cambios importantes o colaborar con otros desarrolladores. Cada rama puede tener su propio conjunto de cambios y contribuciones independientes del resto del proyecto. Esto permite un flujo de trabajo colaborativo y paralelo, ya que cada desarrollador puede trabajar en su propia rama sin interferir con el trabajo de los demás.
<br>

📺 Vídeo: [¿Qué son las ramas?](https://youtu.be/LL47l59Ld5I)

**¿Qué es un commit?**:
<br>
Una [commit](https://docs.github.com/es/get-started/quickstart/github-glossary#confirmaci%C3%B3n) es un conjunto de cambios en los archivos y carpetas del proyecto.
<br>

📺 Vídeo: [¿Qué es un commit?](https://youtu.be/j9zAL52wuLg)

**¿Qué es una solicitud de extracción (pull request)?**
<br>
Un [pull request](https://docs.github.com/es/get-started/quickstart/github-glossary#pull) es una petición para integrar nuestras propuestas o cambios de código a un proyecto.

Un pull request es una petición que el propietario de un fork de un repositorio hace al propietario del repositorio original para que este último incorpore los commits que están en el fork. Estos muestran los cambios en su rama a otras personas y les permite aceptar, rechazar o sugerir cambios adicionales a su rama.
<br>

📺 Vídeo: [¿Qué es y cómo hacer un Pull Request?](https://youtu.be/Zqft6yNRuNs)

**¿Qué es un merge?**:
<br>
Un [merge](https://docs.github.com/es/get-started/quickstart/github-glossary#merge) o fusión en español se refiere al proceso de combinar cambios de una rama (branch) a otra en un repositorio.

El "merge" combina los cambios de una rama con otra mediante la creación de un nuevo commit que refleje esos cambios en la rama de destino. GitHub utiliza un algoritmo de fusión llamado "merge commit" para combinar las diferencias entre las dos ramas. Este "merge commit" registra el historial de cambios y permite mantener un registro de los cambios realizados en cada rama.
<br>

📺 Vídeo: [¿Cómo hacer un merge?](https://youtu.be/vu4Rv1SmzwM)

**¿Qué es un archivo README?**
<br>
Un archivo [README](https://docs.github.com/es/get-started/quickstart/github-glossary#archivo-l%C3%A9ame) en GitHub es una práctica común en la mayoría de los repositorios de código. README es una abreviatura de "read me" que significa "léeme" en inglés. Este archivo tiene la extensión ".md", lo que indica que está escrito en formato [Markdown](https://docs.github.com/es/get-started/quickstart/github-glossary#markdown), un lenguaje de marcado ligero para formatear texto.

El README se utiliza para proporcionar información básica y relevante sobre el proyecto alojado en el repositorio de GitHub. Su objetivo es brindar a los visitantes y colaboradores una visión general del proyecto, instrucciones de instalación, documentación, ejemplos de uso y cualquier otra información que pueda ser útil.

El contenido de un archivo README puede variar según el proyecto, pero generalmente incluye los siguientes elementos:

- **Título y descripción**: Un breve resumen del proyecto que lo describe de manera concisa.
- **Requisitos**: Los requisitos previos necesarios para utilizar o contribuir al proyecto, como versiones de software o bibliotecas adicionales.
- **Instalación**: Instrucciones paso a paso sobre cómo instalar y configurar el proyecto.
- **Uso**: Cómo utilizar el proyecto, incluidos ejemplos de código o comandos.
- **Contribución**: Directrices para que otros contribuyan al proyecto, como pautas de estilo de código, estructura de directorios y procesos de solicitud de extracción.
- **Documentación adicional**: Enlaces a documentación adicional, como guías detalladas, tutoriales o ejemplos.
- **Licencia**: Información sobre la licencia del proyecto y los derechos de autor.

**¿Qué es un perfil README?**
<br>
Un perfil README es practicamente una introducción de quien eres, es decir, una mini biografia que se muestra en nuestro perfil de GitHub. Aquí podemos compartir información relevante hacia la comunidad en GitHub.com. Lo interesante es que el portal muestra susodicho archivo en la parte superior de nuestra página de perfil. Si quieres saber más u obtener mayor información, consulta "[Administrar el README de tu perfil](https://docs.github.com/es/enterprise-cloud@latest/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme#about-your-profile-readme)".

📺 Vídeo: [CREA tu Github README Profile paso a paso](https://www.youtube.com/live/1eEnboVooiY?feature=share)

<br>

 ![vgglProfileREADME](../../images/vgglProfileREADME.jpeg)

---

[Volver al índice](README.md)
