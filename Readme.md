git init
Inicializa un nuevo repositorio en la carpeta actual.

git status
Muestra el estado del repositorio, incluyendo los archivos modificados, no rastreados o listos para commit.

git add <archivo>
Agrega un archivo al área de staging para que se incluya en el próximo commit.

Ejemplo: git add . agrega todos los archivos.

git commit -m "mensaje"
Guarda los cambios en el repositorio con un mensaje descriptivo.

git branch -M main
Renombra la rama actual a main (recomendado por GitHub en lugar de master).

git remote add origin <URL>
Conecta el repositorio local con un repositorio remoto en GitHub.

git push -u origin main
Sube (empuja) los commits al repositorio remoto en la rama main.

git log
Muestra el historial de commits con autor, fecha y mensaje