# Diagrama de Componentes de Git

**Sistema de Control de Versiones**
![Local version control diagram](https://git-scm.com/book/en/v2/images/local.png)
*Figure 1. Local version control diagram*

**Sistemas de Control de Versiones Centralizados**
![Centralized version control diagram](https://git-scm.com/book/en/v2/images/centralized.png)
*Figure 2. Centralized version control diagram*

**Sistemas de Control de Versiones Distribuidas**
![Distributed version control diagram](https://git-scm.com/book/en/v2/images/distributed.png)
*Figure 3. Distributed version control diagram*

**Almacenamiento de Datos como Cambios en una Versión Base de Cada Archivo**
![Storing data as changes to a base version of each file](https://git-scm.com/book/en/v2/images/deltas.png)
*Figure 4. Storing data as changes to a base version of each file*

# Los Tres Estados en Git

![Working tree, staging area, and Git directory](https://git-scm.com/book/en/v2/images/areas.png)
*Figure 6. Working tree, staging area, and Git directory*

Git maneja tres estados principales para los archivos durante su ciclo de vida en el sistema de control de versiones. Estos estados determinan cómo Git interactúa con los archivos.

## Estados de los Archivos

1. **Modificado (Modified)**:
   - El archivo ha sido cambiado, pero los cambios aún no se han registrado en la base de datos del proyecto Git.

2. **Preparado (Staged)**:
   - El archivo modificado se ha marcado en su versión actual para que se incluya en la próxima instantánea (commit).

3. **Confirmado (Committed)**:
   - Los datos están almacenados de forma segura en la base de datos local de Git.

## Secciones Principales de un Proyecto Git

Estos estados están asociados con las tres secciones principales de un proyecto Git:

1. **Árbol de trabajo (Working Tree)**:
   - Donde se realizan las modificaciones. Es una vista de un directorio de trabajo y sus archivos y carpetas.

2. **Área de preparación (Staging Area)**:
   - Es un archivo, generalmente contenido en el directorio Git, que almacena información acerca de lo que va a incluirse en la próxima confirmación.

3. **Directorio Git (Git Directory)**:
   - Es donde Git almacena los metadatos y la base de datos de objetos para el proyecto. Es lo que se copia cuando se clona un repositorio de otro equipo.

Estos conceptos son cruciales para entender el flujo de trabajo en Git y cómo los cambios se trasladan desde la creación hasta ser parte del historial confirmado del proyecto.