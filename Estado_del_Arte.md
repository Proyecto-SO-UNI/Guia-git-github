# Guía de Git y GitHub

## Estado del Arte

### Trabajos Relacionados

Tanto **GitHub** como **GitLab** son sistemas de control de versiones que facilitan el trabajo colaborativo entre programadores. A continuación, se presenta una breve historia, diferencias, ventajas y desventajas de estos sistemas y otros relacionados.

- **SCCS (1972)**: El sistema de control de código fuente (*Source Code Control System*) fue el primer sistema de control de versiones de la historia. Desarrollado en los Laboratorios Bell por Marc J. Rochkind.

- **RCS (1982)**: *Revision Control System*, lanzado por Walter Tichy como parte del proyecto GNU. Fue diseñado como una alternativa gratuita a SCCS.

- **CVS (1986)**: *Concurrent Versions System*, desarrollado por Dick Grune. Permitió a los desarrolladores trabajar de manera más independiente al trabajar sobre copias del proyecto.

- **TeamWare (1990)**: Sistema de control de versiones distribuido desarrollado por Sun Microsystems, con características avanzadas para la gestión de versiones.

#### Git

- Inició en 2005 tras la ruptura con BitKeeper, liderado por Linus Torvalds.
- Características destacadas:
  - Velocidad
  - Diseño sencillo
  - Soporte para desarrollo no lineal
  - Completamente distribuido
  - Manejo eficiente de grandes proyectos

### Conceptos Teóricos

#### Control de Versiones

El control de versiones es una disciplina de la ingeniería de software que gestiona los cambios a lo largo del tiempo, esencial en entornos colaborativos.

#### Modelos de Control de Versiones

- **Centralizado**: Como SVN, basado en un único repositorio central.
- **Distribuido**: Como Git, replica el repositorio completo en la máquina de cada colaborador.

#### Conceptos Específicos de Git

- **SHA-1**: Algoritmo usado para asegurar la integridad de los datos del repositorio.
- **Repositorio (Repo)**: Estructura de datos que almacena metadatos para cada archivo y directorio.
- **Git Hook**: Scripts configurables para ejecutar acciones automáticas en respuesta a eventos dentro del ciclo de vida de un repositorio Git.

#### Características de GitHub

- **Pull Request**: Facilita la discusión de cambios propuestos antes de su integración.
- **GitHub Actions**: Plataforma para la automatización de software.
- **GitHub Pages**: Solución para el hospedaje de páginas web desde un repositorio GitHub.

### Otras Herramientas utilizadas para GitGup

- **GitLab**: Plataforma de control de versiones y CI/CD.
- **Bitbucket**: Servicio de hospedaje de proyectos con control de versiones.
- **SourceTree**: Interfaz gráfica para manejar repositorios Git.
- **Jenkins**: Servidor de automatización para integración y entrega continua.
- **Travis CI**: Servicio de integración continua.
- **JIRA**: Herramienta de seguimiento de proyectos y problemas.

### Conclusiones

Git es el gestor de código fuente que domina el panorama desde hace años, ofreciendo varias ventajas sobre otros sistemas, como su rapidez, flexibilidad, integridad de la información, y su naturaleza de código abierto y gratuito.
