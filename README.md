# Calculadora-de-Coste-Real-y-Actualizado-de-Inmuebles
# Acerca del archivo LÉAME del repositorio

Puedes agregar un archivo README a tu repositorio para comentarle a otras personas por qué tu proyecto es útil, qué pueden hacer con tu proyecto y cómo lo pueden usar.

## Acerca de los archivos README

Puedes agregar un archivo README a un repositorio para comunicar información importante sobre tu proyecto. Un README, junto con una licencia del repositorio, un archivo de citación, directrices de contribución y un código de conducta, comunica lo que se espera de tu proyecto y te ayuda a gestionar las contribuciones.

Para obtener más información sobre cómo proporcionar instrucciones para el proyecto, consulte [Agregar un código de conducta a tu proyecto](/es/communities/setting-up-your-project-for-healthy-contributions/adding-a-code-of-conduct-to-your-project) y [Configurar tu proyecto para contribuciones saludables](/es/communities/setting-up-your-project-for-healthy-contributions).

Un archivo README suele ser el primer elemento que verá un visitante cuando entre a tu repositorio. Los archivos README habitualmente incluyen información sobre:

* Qué hace el proyecto.
* Por qué el proyecto es útil.
* Cómo pueden comenzar los usuarios con el proyecto.
* Dónde pueden recibir ayuda los usuarios con tu proyecto
* Quién mantiene y contribuye con el proyecto.

Si coloca el archivo README en el directorio oculto `.github`, raíz o `docs` de su repositorio, GitHub reconocerá y mostrará automáticamente su README a los visitantes del repositorio.

Si un repositorio contiene más de un archivo README, el archivo que se muestra se elige de las ubicaciones en el siguiente orden: el directorio `.github`, luego el directorio raíz del repositorio y finalmente el directorio `docs`.

Cuando se visualiza el README en GitHub, cualquier contenido que supere los 500 KiB se truncará.

Si agregas un archivo de README a la raíz de un repositorio público con el mismo nombre que tu nombre de usuario, dicho README aparecerá automáticamente en tu página de perfil. Puede editar el ARCHIVO LÉAME de perfil con GitHub Flavored Markdown para crear una sección personalizada en su perfil. Para más información, consulta [Administrar el README de tu perfil](/es/account-and-profile/how-tos/profile-customization/managing-your-profile-readme).

## Tabla generada automáticamente del contenido de los archivos Markdown

Para la vista representada de cualquier archivo Markdown en un repositorio, incluidos los archivos LÉAME, GitHub generará automáticamente una tabla de contenido basada en los encabezados de sección. Para ver la tabla de contenido de un archivo LÉAME, haga clic en el icono <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-list-unordered" aria-label="Table of Contents" role="img"><path d="M5.75 2.5h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5Zm0 5h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5Zm0 5h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5ZM2 14a1 1 0 1 1 0-2 1 1 0 0 1 0 2Zm1-6a1 1 0 1 1-2 0 1 1 0 0 1 2 0ZM2 4a1 1 0 1 1 0-2 1 1 0 0 1 0 2Z"></path></svg> de menú "Esquema" en la esquina superior de la página representada.

## Enlaces de sección en archivos Markdown y páginas blob

Puede vincular directamente a cualquier sección que tenga un encabezado. Para ver el delimitador generado automáticamente en un archivo representado, mantenga el puntero sobre el encabezado de sección para exponer el icono de <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-link" aria-label="the link" role="img"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg> y haga clic en el icono para mostrar el delimitador en el explorador.

![Captura de pantalla de un archivo README de un repositorio. A la izquierda de un encabezado de sección, se destaca un icono de vínculo en naranja oscuro.](/assets/images/help/repository/readme-links.png)

Para obtener información más detallada sobre los vínculos de sección, consulta [Vínculos de sección](/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#section-links).

## Enlaces relativos y rutas de imágenes en los archivos Markdown

Puedes definir enlaces relativos y rutas de imagen en los archivos representados para ayudar a que los lectores naveguen hasta otros archivos de tu repositorio.

Un enlace relativo es un enlace que es relativo al archivo actual. Por ejemplo, si tiene un archivo Léame en la raíz del repositorio y tiene otro archivo en *docs/CONTRIBUTING.md*, el vínculo relativo a *CONTRIBUTING.md* en el archivo Léame podría tener este aspecto:

```text
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```

GitHub transformará de manera automática el enlace relativo o la ruta de imagen en cualquier rama en la que te encuentres actualmente, de modo que el enlace o ruta siempre funcione. La ruta de acceso del vínculo será relativa al archivo actual. Los vínculos que comienzan por `/` serán relativos a la raíz del repositorio. Puede usar todos los operandos de vínculo relativos, como `./` y `../`.

El texto del vínculo debe estar en una sola línea. El ejemplo siguiente no funcionará.

```markdown
[Contribution
guidelines for this project](docs/CONTRIBUTING.md)
```

Los enlaces relativos son más sencillos para los usuarios que clonan tu repositorio. Puede que los enlaces absolutos no funcionen en los clones de tu repositorio. Recomendamos usar enlaces relativos para consultar los archivos dentro de tu repositorio.

## Wikis

Un archivo LÉAME debe contener solo la información necesaria para que los desarrolladores comiencen a usar y hacer contribuciones en tu proyecto. La documentación más grande es mejor para los wikis. Para más información, consulta [Acerca de las wikis](/es/communities/documenting-your-project-with-wikis/about-wikis).

## Información adicional

* [Agregar un archivo a un repositorio](/es/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
* [5 sugerencias para hacer que su GitHub página de perfil sea accesible](https://github.blog/2023-10-26-5-tips-for-making-your-github-profile-page-accessible/) en el GitHub blog
* [Facilitación de la rápida creación y reanudación de codespaces](/es/codespaces/setting-up-your-project-for-codespaces/setting-up-your-repository/facilitating-quick-creation-and-resumption-of-codespaces)
