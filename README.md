Curso: Creación de un repositorio con Git

¿Qué aprendí del video?

Aprendí a utilizar Git para administrar las versiones de un proyecto, configurar mi nombre y correo electrónico, inicializar un repositorio local y revisar el estado de los archivos mediante comandos en la terminal de PowerShell.

También aprendí que Git permite identificar los archivos que todavía no se han agregado al control de versiones y preparar los cambios para registrarlos mediante un commit.

Comandos utilizados:
- `git --version`: comprobar que Git estuviera instalado.
- `git config --global user.name "brillos"`: configurar el nombre del usuario.
- `git config --global user.email "gonzalezalvaradobrigitte.2.c@gmail.com"`: configurar el correo electrónico.
- `git config --global -l`: verificar la configuración de Git.
- `cd C:\Users\hp\git\Folder`: acceder a la carpeta del proyecto.
- `git init`: inicializar el repositorio local.
- `git status`: consultar el estado de los archivos.
- `git add .`: preparar los archivos para registrarlos en Git.
- `git commit -m "Primer commit"`: guardar los cambios en el historial del repositorio.


El proyecto contiene:
- `CSS/`: carpeta para los archivos de estilos.
- `JS/`: carpeta para los archivos JavaScript.
- `video.html`: archivo HTML de la página web.
- `README.md`: documento con la descripción de la práctica.

 Dificultades encontradas y soluciones

encontré un mensaje que indicaba que la carpeta actual no era un repositorio de Git. Para resolverlo, volví a ejecutar el comando `git init` en la carpeta del proyecto.

También observé que Git mostraba mis carpetas y archivos como elementos sin seguimiento (*untracked files*). Esto significa que todavía no estaban agregados al control de versiones. Para solucionarlo, utilicé `git add .` y después registré los cambios con `git commit`.
