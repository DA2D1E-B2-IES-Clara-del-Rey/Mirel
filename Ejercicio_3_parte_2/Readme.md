# Capitúlo 2
# GitHub y Git: Resumen y conceptos clave

**GitHub** es una plataforma de control de versiones basada en **Git**, un sistema de control de versiones distribuido gratuito y de código abierto. GitHub permite a los usuarios colaborar en proyectos de software, mantener un registro de cambios y trabajar en diferentes versiones del proyecto.

## Características principales de GitHub

- Control de acceso por usuario o equipo
- Capacidades de colaboración
- Herramientas de gestión de tareas
- Seguimiento de problemas, ideas, comentarios y tareas
- Fácil publicación segura de páginas web y wikis
- Herramientas de comunicación y difusión integradas
- Integración fácil en el flujo de trabajo a través de interfaces gráficas de usuario (GUIs)

## Conceptos clave de GitHub y Git

- **Repositorio (Repo):** Un lugar central de almacenamiento de archivos supervisado por un sistema de control de versiones
- **Commit:** Cuando se realiza un cambio en un archivo del repositorio, se puede "commit" ese cambio al repositorio local o remoto
- **Pull:** Transfiere "commits" de un repositorio remoto a un repositorio local
- **Push:** Transfiere "commits" de un repositorio local a un repositorio remoto
- **Branch:** Una rama permite trabajar de forma aislada en los archivos actuales o de producción
- **Fork:** Hacer una copia del repositorio original en GitHub (y luego localmente si es necesario) para trabajar en él y luego enviar los cambios al propietario a través de una solicitud de Pull (Pull request)
- **Clone:** Hacer una copia del repositorio original en una máquina local. De esta manera, los colaboradores pueden sincronizar fácilmente los cambios en los repositorios locales y remotos

## Funcionalidades clave de GitHub

- **Interfaz gráfica de usuario (GUI):** GitHub proporciona una interfaz gráfica de usuario para facilitar el trabajo con Git
- **Seguridad y privacidad:** GitHub ofrece buenas políticas de privacidad, seguridad y cumplimiento
- **Licensing:** GitHub facilita la aplicación de licencias a los repositorios para proteger los derechos de autor y permitir el uso adecuado del código

El flujo de trabajo de un proyecto basado en GitHub puede incluir varios actores, entornos y roles, como usuarios y comunidades, editores, revisores y público en general. Con GitHub, se puede colaborar en proyectos, realizar un seguimiento de los cambios y mantener versiones diferentes del proyecto de manera eficiente y organizada.
## Archivos clave en un repositorio de GitHub

Algunos archivos comunes en un repositorio de GitHub que debes conocer son:

- **README.md:** Este archivo se utiliza para explicar el proyecto, mostrar su grado de madurez, dirigir a los archivos o carpetas de documentación o cualquier otra información que el propietario considere relevante para los visitantes o usuarios.
- **LICENSE:** El archivo LICENSE muestra la licencia legal del repositorio, lo cual es importante cuando el repositorio es público y se deben preservar ciertos derechos o cuando el proyecto contiene el trabajo de otras personas con su propia licencia.
- **CITATION.cff:** Explica cómo los autores desean que se cite su proyecto. Aunque también es un archivo de texto sin formato, se necesita un formato legible por máquina. Más detalles en [GitHub Docs: About CITATION files](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files).
- **.gitignore:** Este archivo es muy útil cuando trabajas localmente y contribuyes al proyecto mediante pull requests, pero necesitas mantener ciertos archivos y/o carpetas fuera del control de versiones, es decir, ignorarlos sin incluirlos en el repositorio de GitHub.
- **CODE_OF_CONDUCT:** Cuando el repositorio está orientado a la comunidad y muchas personas interactúan en el proyecto, un texto claro sobre el comportamiento esperado de los participantes puede ser fundamental.

Otros archivos también pueden ser importantes según la complejidad del proyecto o el número de participantes: AUTHORS, CHANGELOG, CONTRIBUTING, ACKNOWLEDGMENTS, etc.

## Consideraciones de privacidad y seguridad en GitHub

La seguridad en GitHub puede mejorarse mediante la configuración del protocolo SSH, que permite autenticar a los usuarios y otorgarles acceso a un repositorio específico (público o privado). Esta opción debe utilizarse en casos en los que se manejen datos confidenciales.

En términos de privacidad, el factor humano es fundamental, ya que las principales vulnerabilidades provienen del uso incorrecto de archivos y/o datos confidenciales. Para evitar que ciertos archivos y carpetas sean supervisados por el control de versiones y compartidos en repositorios remotos, puedes utilizar un archivo `.gitignore` que liste todos los archivos y carpetas a excluir.

## Licencias de repositorio en GitHub

Al elegir una licencia para tu repositorio, GitHub ofrece automáticamente el texto legal apropiado para una serie de licencias populares y, por defecto, asigna la autoría al propietario del repositorio. Algunas licencias comunes incluyen:

- Dominio público: Creative Commons Zero v1.0 Universal, The Unlicense
- Permisivas: Apache License 2.0, MIT License, BSD 2-Clause "Simplified" License, BSD 3-Clause "New" or "Revised" License, Boost Software License 1.0, Mozilla Public License 2.0
- Menos permisivas: GNU General Public License v3.0, GNU Affero General Public License v3.0, GNU General Public License v2.0, GNU Lesser General Public License v2.1, Eclipse Public License 2.0

La elección de la licencia correcta no siempre es fácil. GitHub mantiene un sitio que puede ayudarte a elegir la adecuada: [Choose an open source license | Choose a License](https://choosealicense.com/).
## Cómo contribuir a un proyecto de código abierto en GitHub

Contribuir a un proyecto de código abierto en GitHub implica los siguientes pasos:

1. **Fork del repositorio:** Haz un fork del repositorio al que deseas contribuir en tu cuenta de GitHub. Esto crea una copia del repositorio en tu cuenta, permitiéndote trabajar en él de forma aislada.

2. **Clonar el repositorio:** Clona el repositorio forkeado en tu computadora para trabajar en el proyecto localmente.

3. **Crear una rama (branch):** Crea una nueva rama en la que trabajarás en tu contribución. Esto te permite separar tus cambios del código base original y facilita la revisión y fusión de tus cambios más adelante.

4. **Realizar cambios:** Realiza los cambios necesarios en el código o la documentación según lo requiera el proyecto. Asegúrate de seguir las pautas de estilo y las convenciones de código del proyecto.

5. **Commit y push de los cambios:** Haz un commit de tus cambios en la rama que has creado y luego haz push de esos cambios a tu repositorio forkeado en GitHub.

6. **Crear un Pull Request (PR):** Abre un Pull Request en el repositorio original, solicitando la incorporación de tus cambios. Asegúrate de seguir las pautas de contribución del proyecto y proporcionar una descripción clara y concisa de los cambios que has realizado.

7. **Revisión y discusión:** Los mantenedores del repositorio revisarán tu PR y podrían solicitar cambios o discutir aspectos de tus contribuciones. Mantente receptivo y dispuesto a hacer ajustes si es necesario.

8. **Fusión (merge) de tus cambios:** Una vez que tu PR haya sido revisado y aprobado, los mantenedores del repositorio lo fusionarán con la rama principal del proyecto.

9. **Actualizar tu fork:** Después de que tus cambios hayan sido fusionados, es posible que desees actualizar tu repositorio forkeado con los cambios más recientes del repositorio original. Para hacer esto, sincroniza tu fork con el repositorio upstream.

Recuerda que cada proyecto puede tener sus propias reglas y pautas de contribución, así que asegúrate de leer la documentación del proyecto antes de comenzar a contribuir.

## Recursos útiles para aprender Git y GitHub

- [Pro Git book](https://git-scm.com/book/en/v2) - Libro gratuito y completo sobre Git, disponible en varios idiomas.
- [GitHub Guides](https://guides.github.com/) - Colección de guías cortas y prácticas para aprender GitHub.
- [Git y GitHub para poetas](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV) - Serie de videos en YouTube que enseñan Git y GitHub desde cero.
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf) - Hoja de referencia rápida de comandos Git comunes.
- [GitHub Learning Lab](https://lab.github.com/) - Aprende Git y GitHub mediante cursos prácticos y guiados directamente en GitHub.

## Anexo I: Comparativa de plataformas de control de versiones

Las tres soluciones más populares en el área de alojamiento de código y control de versiones utilizando Git son GitHub, GitLab y BitBucket.

### 5.1.1 Comparativa de características principales

| Características             | GitHub        | GitLab        | BitBucket     |
| --------------------------- | ------------- | ------------- | ------------- |
| Número de usuarios          | 73 millones   | 30 millones   | 10 millones   |
| Repositorios privados       | Gratis        | Gratis        | Gratis        |
| Repositorios públicos       | Gratis        | Gratis        | Gratis        |
| Navegación                  |               |               |               |
| Usabilidad                  |               |               |               |
| Interfaz gráfica de usuario | GitHub Desktop (Gratis y Código Abierto) | Sourcetree (Gratis pero Propietario) | Sourcetree (Gratis pero Propietario) |
| Almacenamiento de archivos grandes | Sí         | Sí             | Sí             |
| Código abierto              | Sí             | Sí             | No             |
| Integración con herramientas de terceros | Sí   | Sí             | Sí             |
| Alojamiento de sitios estáticos | GitHub Pages | GitLab Pages  | Bitbucket Cloud (con limitaciones) o mediante complemento comercial: Pages for Bitbucket Server |

### Planes actuales - Primavera 2022

| Planes         | GitHub         | GitLab         | BitBucket      |
| -------------- | -------------- | -------------- | -------------- |
| Gratis         | Sí             | Sí             | Sí             |
| Equipo Mediano | $44 por usuario/año | Premium $19 por usuario/mes | Standard $3 por usuario/mes (desde $15/mes) |
| Top Enterprise | $231 por usuario/año | Ultimate $99 por usuario/mes | Premium $6 por usuario/mes (desde $30/mes) |
| Autoalojado / Autogestionado | Enterprise Server $231 por usuario/año | Para todos los niveles Autoadministrado | Data Center $2300 por 25 usuarios/año |

### Anexo II: Licencias

Actualmente hay alrededor de un centenar de licencias de código abierto en el mercado, y elegir una no es tarea fácil; de hecho, puede convertirse en una tarea crítica que comprometa todo el proyecto. Dado que un análisis profundo del proceso de licenciamiento está fuera del alcance de este documento, este anexo está diseñado para ofrecer una visión rápida del estado actual en el campo.

### Anexo III: Recursos

- Sitios del proyecto
  - PoliRural - Future Oriented Collaborative Policy Development for Rural Areas and People
  - Digital Innovation Hub – Social Space for Smart Regions
  - PoliRural GitHub Organization
  - WP3 - Final Integration, Release & Licensing
- Sitios principales relacionados con este documento
  - GitHub / GitHub Docs
  - OpenAIRE
  - OpenAIRE in EOSC
  - Zenodo
- Artículos, informes y sitios informativos
  - Research Data Guide 2022 – EUI Library
  - Open Source and Open Data Licenses in the Smart Infrastructure Era: Review and License Selection Frameworks | SpringerLink (artículo con acceso restringido)
  - Metadata quality | Nature collections
  - FAIRsharing.org – Standards, databases y politicas
## Recursos y Políticas

- Open Source Licensing primer for Enterprise AI/ML | [Towards Data Science](https://towardsdatascience.com/open-source-licensing-primer-for-enterprise-ai-ml-1d1f6e2ca06c)
- How to Apply a License to Your Open Source Software Project | [FOSSA](https://fossa.com/blog/how-to-apply-a-license-to-your-open-source-software-project/)
- Disciplinary repositories - [Open Access Directory at Simmons University](http://oad.simmons.edu/oadwiki/Disciplinary_repositories)
- License compatibility | [Wikipedia](https://en.wikipedia.org/wiki/License_compatibility)
- Permissive software license | [Wikipedia](https://en.wikipedia.org/wiki/Permissive_software_license)

## Herramientas

- Choose an open source license | [Choose a License](https://choosealicense.com/) – by GitHub
- [JSON-LD Playground](https://json-ld.org/playground/)
- [JSON Formatter & Validator](https://jsonformatter.curiousconcept.com/) (curiousconcept.com)
- [Citation File Format (CFF)](https://citation-file-format.github.io/) (citation-file-format.github.io)
- [ScienceOpen](https://www.scienceopen.com/) – Un entorno interactivo de descubrimiento

En resumen, este documento presenta una guía para la integración, publicación y licenciamiento de proyectos de software abierto, utilizando GitHub como plataforma de control de versiones. Se incluyen comparaciones de características y planes de las tres soluciones más populares en el área de alojamiento de código y control de versiones (GitHub, GitLab y BitBucket), así como información sobre licencias de código abierto y recursos útiles relacionados con el tema.

