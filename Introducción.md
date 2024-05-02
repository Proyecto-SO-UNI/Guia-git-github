### Introducción

La colaboración en proyectos de desarrollo de software ha evolucionado significativamente con el advenimiento de plataformas como GitHub. GitHub, basado en el sistema de control de versiones Git, se ha convertido en un pilar fundamental para desarrolladores de todo el mundo, facilitando la colaboración, el seguimiento de cambios y la gestión de proyectos de manera eficiente.

Al adentrarnos en el mundo de GitHub, es esencial comprender el funcionamiento básico de Git, el sistema de control de versiones subyacente. A diferencia de los enfoques tradicionales de desarrollo, donde los archivos suelen residir exclusivamente en las computadoras locales, Git adopta un enfoque distribuido, lo que significa que cada colaborador de un proyecto tiene una copia completa del repositorio en su propia máquina. Esto asegura una mayor independencia y capacidad de trabajo sin conexión a Internet.

Sin embargo, antes de sumergirnos en el mundo de Git y GitHub, es crucial comprender cómo instalar y configurar adecuadamente el software en nuestras computadoras locales. A diferencia de algunas herramientas de control de versiones que ofrecen interfaces gráficas intuitivas, Git se centra en una experiencia de línea de comandos, lo que puede resultar intimidante para algunos usuarios al principio. Pero no te preocupes, en este informe te guiaremos a través del proceso de instalación y te proporcionaremos los conocimientos necesarios para comenzar a utilizar Git y GitHub de manera efectiva.

### Para instalar Git en tu computadora, sigue estos pasos según tu sistema operativo:

#### Windows:
1. **Descarga Git:** Ve al [sitio web oficial de Git](https://git-scm.com/) y haz clic en el enlace de descarga para Windows.
2. **Ejecuta el instalador:** Una vez que se haya descargado el instalador, ábrelo y sigue las instrucciones del asistente de instalación. Puedes aceptar las opciones de instalación predeterminadas o personalizarlas según tus preferencias.
3. **Finaliza la instalación:** Después de completar el proceso de instalación, Git estará instalado en tu computadora. Puedes verificar que la instalación fue exitosa abriendo una ventana de línea de comandos (`cmd`) y escribiendo `git --version`. Deberías ver la versión de Git que se instaló.

#### macOS:
1. **Instalación a través de Xcode Command Line Tools (opción recomendada):** En macOS, Git suele estar disponible a través de las herramientas de línea de comandos de Xcode. Abre la terminal y ejecuta el siguiente comando: xcode-select --install.
2.  **Instalación a través de Homebrew (opción alternativa):** Si prefieres usar Homebrew para instalar Git, puedes ejecutar el siguiente comando en la terminal: brew install git
3.  Homebrew es un gestor de paquetes para macOS que simplifica la instalación de software de código abierto.
3. **Verifica la instalación:** Después de completar la instalación, verifica que Git esté correctamente instalado abriendo la terminal y escribiendo `git --version`. Deberías ver la versión de Git que se instaló.

#### Linux (Ubuntu/Debian):
1. **Instalación a través del administrador de paquetes:** Abre la terminal y ejecuta el siguiente comando para instalar Git en Ubuntu o Debian:
sudo apt update
sudo apt install git
2. **Verifica la instalación:** Después de completar la instalación, verifica que Git esté correctamente instalado abriendo la terminal y escribiendo `git --version`. Deberías ver la versión de Git que se instaló.
 
**Como es la interfaz de git**
Git, como sistema de control de versiones distribuido, se maneja principalmente a través de la línea de comandos. La interfaz de Git en la línea de comandos es poderosa y proporciona acceso a una amplia gama de funciones y comandos para gestionar repositorios de código.

#### Aquí hay una descripción básica de algunos de los comandos más comunes de Git y cómo se utilizan en la interfaz de línea de comandos:

1. **`git init`:** Inicializa un nuevo repositorio Git en un directorio específico.
2. **`git clone`:** Clona un repositorio Git existente desde una ubicación remota (como GitHub) en tu computadora local.
3. **`git add`:** Agrega archivos al área de preparación (staging) para ser incluidos en el próximo commit.
4. **`git commit`:** Crea un nuevo commit que incluye los cambios en los archivos que han sido agregados al área de preparación.
5. **`git push`:** Envía los commits locales a un repositorio remoto, como GitHub.
6. **`git pull`:** Obtiene los cambios desde un repositorio remoto y los fusiona con tu repositorio local.
7. **`git status`:** Muestra el estado actual del repositorio, incluyendo archivos modificados, archivos en el área de preparación y el branch actual.
8. **`git branch`:** Muestra una lista de ramas (branches) en el repositorio y permite crear, eliminar y cambiar entre ramas.
9. **`git checkout`:** Cambia entre ramas o restaura archivos a una versión específica.
10. **`git merge`:** Fusiona cambios de una rama a otra.
    
#### Archivos locales: 

1. **Inicializa un repositorio local:** Si aún no tienes un repositorio Git en tu computadora, puedes crear uno mediante el comando `git init` en la línea de comandos dentro del directorio de tu proyecto.

2. **Agrega archivos al repositorio:** Coloca los archivos que deseas subir al repositorio dentro del directorio de tu proyecto. Luego, utiliza el comando `git add .` para agregar todos los archivos nuevos o modificados al área de preparación.

3. **Realiza un commit:** Después de agregar los archivos al área de preparación, debes realizar un commit para confirmar los cambios. Utiliza el comando `git commit -m "mensaje del commit"` para crear un nuevo commit con un mensaje descriptivo que explique los cambios realizados.

4. **Conecta tu repositorio local con GitHub:** Si aún no has configurado una conexión entre tu repositorio local y un repositorio remoto en GitHub, necesitarás agregar una URL remota para tu repositorio local. Puedes hacerlo utilizando el comando `git remote add origin URL_DEL_REPOSITORIO_GITHUB`.

5. **Sube los cambios a GitHub:** Finalmente, puedes subir los cambios de tu repositorio local a GitHub utilizando el comando `git push -u origin NOMBRE_DE_LA_RAMIFICACION`, donde `NOMBRE_DE_LA_RAMIFICACION` es el nombre de la rama que deseas subir.
