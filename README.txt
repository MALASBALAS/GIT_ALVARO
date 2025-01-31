Álvaro Balas - Práctica Git
Práctica de gestión de ramas en Git (Realizado desde la terminal).

Perdón por tardar tanto en realizar el trabajo, pero he estado ocupado con proyectos personales. GitHub lo uso a menudo, pero sobre todo para leer código de otras personas. Nunca subo nada, pero me parece muy sencillo su uso desde la terminal.

Comandos usados en la práctica
Inicializar el repositorio
git init
Inicializa un nuevo repositorio Git en la carpeta actual.

Agregar archivos al área de staging
git add .
Añade todos los archivos nuevos o modificados al área de preparación (staging).

Realizar un commit
git commit -m "Actualizar README.txt"
Guarda los cambios en el historial del repositorio con un mensaje descriptivo.

Crear y cambiar de ramas
git checkout -b nombre_rama
Crea una nueva rama y cambia a ella.

Fusionar ramas en main
git checkout main
git merge nombre_rama
Une los cambios de una rama secundaria en la rama principal.

Eliminar un archivo del repositorio y hacer commit
git rm a.txt
git commit -m "Eliminar archivo a.txt"
Elimina un archivo del repositorio y registra el cambio.

Subir cambios al repositorio remoto en GitHub
git push origin main
Envía los cambios locales al repositorio remoto en la rama main.

Clonar un repositorio
git clone https://github.com/usuario/repositorio.git
Descarga un repositorio remoto a la máquina local.

Ver el historial de commits
git log --oneline
Muestra el historial de commits en una lista resumida.
