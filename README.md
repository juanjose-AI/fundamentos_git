# Fundamentos de Git
Primeros comandos de git


### git init
Creacion de repositorio local

### git config --global user.name "Tu Nombre"
Definir el nombre del usuario que va a interactuar con git desde el pc

### git config --global user.email [EMAIL_ADDRESS]"
Definir el correo del usuario que va a interactuar con git desde el pc

### git status
Muestra el estado de los archivos

### git add nombre_archivo
Agrega archivos al stage de un archivo determinado

### git add .
Agrega todos los cambios del stage a pendientes por subir al repositorio

### git commit -m "mensaje"
Agrega archivos pendientes para subir a github

### git log
Muestra el historial de commits

### git log --oneline
Muestra el historial de commits en una sola linea

### git switch nombre_rama
Cambiar de rama

### git checkout -b nombre_rama
Crear una nueva rama y cambiar a ella

### gt restore --staged nombre_archivo
Remover archivos del stage

### git restore nombre_archivo
Restaurar archivos del ultimo commit

### git mv nombre_anterior nombre_nuevo
Renombrar archivos

### git rm nombre_archivo
Eliminar archivos

### git push -u origin nombre_rama
Subir los cambios de los commits pendientes al repositorio remoto

### git branch
Muestra las ramas del proyecto

### git branch -d nombre_rama
Eliminar una rama
